# 🤝 Contributing a Tutorial

Thank you for wanting to contribute! This guide walks you through everything you need to know to add your own tutorial to this repository.

---

## 📋 Before You Start

- Tutorials should cover **one specific topic** and aim for the **most basic, beginner-friendly** explanation.
- All tutorials **must** be written in a `.md` (Markdown) file.
- Code examples are optional but strongly encouraged.

---

## 🗂️ Folder Structure

Every tutorial lives in its own folder at the root of the repository:

```
your-topic/
├── README.md        ← required: the tutorial text
└── examples/        ← optional: code snippets from real projects
    ├── example1.js
    └── example2.py
```

Use a short, lowercase, hyphenated folder name that clearly describes the topic:

| ✅ Good | ❌ Avoid |
|--------|---------|
| `git-basics` | `GitBasics` |
| `python-lists` | `python_lists_tutorial` |
| `html-forms` | `forms` |

---

## 🪜 Step-by-Step Guide

### 1. Fork & Clone

1. Click **Fork** in the top-right corner of this repository.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/tutorials.git
   cd tutorials
   ```
3. Create a new branch for your tutorial:
   ```bash
   git checkout -b add-my-topic
   ```

### 2. Create Your Tutorial Folder

```bash
mkdir my-topic
```

### 3. Write the Tutorial

Create `my-topic/README.md`. Use the [`example-tutorial/README.md`](./example-tutorial/README.md) as a template — it shows the expected structure:

```
# Topic Title

Short one-sentence description.

---

## What is <Topic>?
...

## Prerequisites
...

## Step 1 — ...
...

## Step 2 — ...
...

## Summary
...

## Next Steps
...
```

### 4. Add Code Examples (Optional)

If you have a real-world code snippet that illustrates the topic, add it inside an `examples/` subfolder:

```bash
mkdir my-topic/examples
# then add your file(s)
```

Name each file clearly: `basic-usage.js`, `full-example.py`, etc.

### 5. Update the README Topics Table

Open the root `README.md` and add a row to the **Topics** table:

```markdown
| 📖 [My Topic](./my-topic/README.md) | One-line description of what this tutorial covers |
```

### 6. Commit & Push

```bash
git add .
git commit -m "Add tutorial: my-topic"
git push origin add-my-topic
```

### 7. Open a Pull Request

Go to the original repository on GitHub and click **New Pull Request**. In the description, briefly explain:

- What topic your tutorial covers.
- Why it is useful for beginners.
- Any code examples you included.

---

## ✅ Quality Checklist

Before submitting, make sure:

- [ ] The tutorial is written in `<topic>/README.md`
- [ ] The language is simple and beginner-friendly
- [ ] The tutorial covers only the basics — no overwhelming detail
- [ ] Code snippets (if any) are in `<topic>/examples/`
- [ ] A row has been added to the Topics table in the root `README.md`
- [ ] The PR description explains the new tutorial

---

## 💬 Questions?

Open an [issue](../../issues) and ask away!
