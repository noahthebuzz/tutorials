# 📚 Tutorials

> No matter how clueless you feel, or how much less skilled you think you are compared to other coders, everyone started out as a baby babbling "gugu, gaga". The difference is that some people find it easier to learn and pick things up, or they've simply put in more work and time to master it. **You can do it too!** This is just meant to make it easier.

This repository is a growing collection of **beginner-friendly tutorials** — the most basic, no-frills introduction to each topic. Every tutorial focuses on the essentials so you can get up and running as fast as possible.

---

**Navigate:** [📂 Topics](#-topics) · [🗂️ Repository Structure](#️-repository-structure) · [🤝 Contributing](#-contributing) · [📄 License](#-license)

---

## 📂 Topics

Tutorials are grouped into **categories**. Each category is a folder; each tutorial lives inside a category.

| Category | Tutorial | Description |
|----------|----------|-------------|
| programming-basics | 📖 [Variables](./programming-basics/variables/README.md) | How to store and use data in a program — a complete example tutorial |

> More tutorials coming soon — or **add yours!** See [Contributing](#-contributing) below.

---

## 🗂️ Repository Structure

```
tutorials/
├── README.md                        ← you are here
├── CONTRIBUTING.md                  ← how to add your own tutorial
└── <category>/                      ← group related tutorials together
    └── <tutorial>/                  ← one folder per tutorial
        ├── README.md                ← the tutorial text (always a .md file)
        ├── tags.txt                 ← required: one tag per line
        └── examples/                ← optional: real code snippets
            └── example.py
```

**Real example** (already in this repo):

```
programming-basics/
└── variables/
    ├── README.md
    ├── tags.txt
    └── examples/
        └── hello.py
```

The category name is up to you — just pick something that groups the tutorial naturally. If no existing category fits, create a new one. There are no strict rules; use your best judgment.

---

## 🤝 Contributing

Want to add a tutorial? Awesome! Please read **[CONTRIBUTING.md](./CONTRIBUTING.md)** for the full guide.

Here is the quick version:

1. **Fork** this repository and create a new branch.
2. **Choose (or create) a category folder** (e.g. `softdrinks/`, `web-dev/`, `cooking/`).
3. **Create a tutorial folder** inside it (e.g. `softdrinks/redbull/`).
4. **Write your tutorial** in `<category>/<tutorial>/README.md` — follow the layout shown in [`programming-basics/variables/README.md`](./programming-basics/variables/README.md).
5. *(Optional)* Add real code snippets inside `<category>/<tutorial>/examples/`.
6. **Add a row** to the [Topics](#-topics) table in this `README.md` linking to your new tutorial.
7. Open a **Pull Request** and describe what topic you have added.

Please keep tutorials short, clear, and beginner-friendly — the goal is *the most basic case*, not an exhaustive reference.

---

## 📄 License

This project is open for everyone. Feel free to use, share, and build upon it.
