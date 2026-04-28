# 🤝 Contributing a Tutorial

Thank you for wanting to contribute! This guide walks you through everything you need to know to add your own tutorial to this repository.

---

## 📋 Before You Start

- Tutorials should cover **one specific topic** and aim for the **most basic, beginner-friendly** explanation.
- All tutorials **must** be written in a `.md` (Markdown) file.
- Code examples are optional but strongly encouraged.

---

## 🗂️ Folder Structure

Tutorials are organized in **two levels**:

```
<category>/
└── <tutorial>/
    ├── README.md        ← required: the tutorial text
    ├── tags.txt         ← required: one tag per line (topics / categories)
    └── examples/        ← optional: code snippets from real projects
        ├── example1.js
        └── example2.py
```

**Category** — a broad grouping (e.g. `programming-basics`, `web-dev`, `softdrinks`, `cooking`).  
**Tutorial** — the specific topic inside that category (e.g. `variables`, `html-forms`, `redbull`).

If you are adding a tutorial about **RedBull**, a natural home would be:

```
softdrinks/
└── redbull/
    ├── README.md
    ├── tags.txt
    └── examples/
```

You are free to create a new category if none of the existing ones fit — just pick a name that makes sense.

Use short, lowercase, hyphenated names for both levels:

| ✅ Good | ❌ Avoid |
|--------|---------|
| `programming-basics/variables` | `ProgrammingBasics/Variables` |
| `web-dev/html-forms` | `web_dev/html_forms_tutorial` |
| `softdrinks/redbull` | `Softdrinks/RedBull` |

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
   git checkout -b add-my-tutorial
   ```

### 2. Create Your Category & Tutorial Folders

```bash
mkdir -p my-category/my-tutorial
```

If the category already exists, just create the tutorial folder inside it:

```bash
mkdir programming-basics/loops
```

### 3. Write the Tutorial

Create `my-category/my-tutorial/README.md`. Use [`programming-basics/variables/README.md`](./programming-basics/variables/README.md) as a template — it shows the expected structure:

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

### 4. Add a tags.txt File

Create `my-category/my-tutorial/tags.txt` and list every relevant tag — one per line. Tags help organise tutorials in the wiki and make them discoverable. Think about the category, technology, concepts covered, and any other keywords a reader might search for.

Example for a RedBull tutorial:

```
Softdrinks
Energy Drinks
RedBull
Caffeine
Beverages
```

Be generous — more tags are better than fewer.

### 5. Add Code Examples (Optional)

If you have a real-world code snippet that illustrates the topic, add it inside an `examples/` subfolder:

```bash
mkdir my-category/my-tutorial/examples
# then add your file(s)
```

Name each file clearly: `basic-usage.js`, `full-example.py`, etc.

### 6. Update the README Topics Table

Open the root `README.md` and add a row to the **Topics** table:

```markdown
| my-category | 📖 [My Tutorial](./my-category/my-tutorial/README.md) | One-line description |
```

### 7. Commit & Push

```bash
git add .
git commit -m "Add tutorial: my-category/my-tutorial"
git push origin add-my-tutorial
```

### 8. Open a Pull Request

Go to the original repository on GitHub and click **New Pull Request**. In the description, briefly explain:

- What category and topic your tutorial covers.
- Why it is useful for beginners.
- Any code examples you included.

---

## ✅ Quality Checklist

Before submitting, make sure:

- [ ] The tutorial is written in `<category>/<tutorial>/README.md`
- [ ] A `tags.txt` file is present with at least one tag per line
- [ ] The category name clearly groups the tutorial
- [ ] The language is simple and beginner-friendly
- [ ] The tutorial covers only the basics — no overwhelming detail
- [ ] Code snippets (if any) are in `<category>/<tutorial>/examples/`
- [ ] A row has been added to the Topics table in the root `README.md`
- [ ] The PR description explains the new tutorial

---

## 💬 Questions?

Open an [issue](../../issues) and ask away!
