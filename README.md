# 🚀 Team Collaboration GitHub Practice

## 📌 Project Description

This project was created to demonstrate effective team collaboration using GitHub. The main goal is to understand how multiple developers can work on the same project using branches, pull requests, and merges.

A simple Python program is used where each team member contributes by adding or modifying functions in the code.

---

## 👥 Team Members

* Dev1
* Dev2
* Dev3
* Dev4
* Dev5

---

## 🌿 Branching Strategy

The project follows a structured branching model:

* `main` → Final stable version
* `development` → Integration branch
* `dev1`, `dev2`, `dev3`, `dev4`, `dev5` → Individual developer branches

Each developer worked on their own branch and later merged their work into the `development` branch.

---

## 🔁 Workflow Process

1. Repository created by owner
2. Collaborators added
3. Development branch created from main
4. Each developer created their own branch from development
5. Developers:

   * Pulled latest changes
   * Added their code
   * Committed changes
   * Pushed to their branch
6. Pull Requests (PRs) were created to merge into `development`
7. Merge conflicts (if any) were resolved manually
8. Final code merged from `development` to `main`

---

## 💻 Sample Code Structure

```python
def dev1():
    return "Hello from Dev 1"

def dev2():
    return "Hello from Dev 2"

def dev3():
    return "Hello from Dev 3"

def dev4():
    return "Hello from Dev 4"

def dev5():
    return "Hello from Dev 5"


if __name__ == "__main__":
    print(dev1())
    print(dev2())
    print(dev3())
    print(dev4())
    print(dev5())
```

---

## ⚠️ Merge Conflict Handling

To understand real-world scenarios, multiple developers edited the same part of the code, which created merge conflicts. These conflicts were resolved manually before merging.

---

## 🎯 Objective

* Learn GitHub collaboration
* Understand branching strategies
* Practice pull requests and merging
* Handle merge conflicts effectively

---

## ✅ Outcome

All team members successfully contributed to the project using GitHub workflows, demonstrating proper version control practices.

---
