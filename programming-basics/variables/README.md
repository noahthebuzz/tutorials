# Variables — Storing Data in Your Program

Variables are one of the very first things you learn in programming. They let you give a name to a value so you can use (and change) it later in your code.

---

## What is a Variable?

Think of a variable as a **labelled box**. You put something inside the box and stick a label on it. Whenever you need that thing again, you just refer to the label.

```python
name = "Alice"   # the box is labelled "name" and contains "Alice"
age  = 25        # the box is labelled "age" and contains 25
```

---

## Prerequisites

- You have Python 3 installed (`python --version` should print `3.x.x`).
- You can run a `.py` file from your terminal: `python my_script.py`.

No prior programming experience is required.

---

## Step 1 — Create a Variable

Type the variable name, an `=` sign, and the value you want to store:

```python
message = "Hello, world!"
```

- The **name** (`message`) can be anything you like — no spaces, and start with a letter or underscore.
- The **value** (`"Hello, world!"`) is whatever you want to store.

---

## Step 2 — Read a Variable

To use the value stored in a variable, just write the name:

```python
print(message)   # prints: Hello, world!
```

---

## Step 3 — Change a Variable

You can overwrite a variable at any time by assigning a new value to it:

```python
score = 0
print(score)   # 0

score = 10
print(score)   # 10
```

---

## Step 4 — Variable Types

Python figures out the *type* of data automatically:

| Value | Type | Example |
|-------|------|---------|
| `"hello"` | Text (string) | `greeting = "hello"` |
| `42` | Whole number (integer) | `count = 42` |
| `3.14` | Decimal number (float) | `pi = 3.14` |
| `True` / `False` | Boolean | `is_valid = True` |

You can check the type with `type()`:

```python
x = 99
print(type(x))   # <class 'int'>
```

---

## Summary

| Concept | Example |
|---------|---------|
| Create a variable | `name = "Alice"` |
| Read a variable | `print(name)` |
| Update a variable | `name = "Bob"` |

Variables are the building blocks of every program — once you're comfortable with them, every other concept becomes much easier to learn.

---

## Next Steps

- Learn about **data types** in more depth.
- Explore **lists** — a variable that holds multiple values.
- Try **if-statements** to make decisions based on variable values.

---

## Real-World Example

See the [`examples/`](./examples/) folder for a short, complete script that uses variables to greet a user.
