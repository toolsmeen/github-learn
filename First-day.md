# 🚀 Day 1: Git & GitHub Basics Learning Notes

Today, I learned essential Git commands and the standard workflow for setting up a project and managing code with Git & GitHub.

---

## 🛠️ Initial Project Setup Workflow

### 1. Initialize Git Repository
When starting a new project (e.g., after creating project files or setting up a React / Next.js app), initialize Git in your project folder:

```bash
git init
```

### 2. Stage All Changes
Add all created files and project changes to the staging area:

```bash
git add .
```

### 3. Commit Staged Changes
Save your staged changes with a clear commit message:

```bash
git commit -m "project setup ready"
```

---

## 🌿 Branching Strategy

Perform the initial project setup on the **`main`** branch. 

After the initial setup, **always create a separate branch for every new feature or task** (e.g., Login Page, Homepage, Authentication).

### Creating & Switching to a Feature Branch

```bash
# Create and switch to a new feature branch
git checkout -b feature/login-page

# Alternative using modern git command:
git switch -c feature/login-page
```

---

## 📋 Quick Reference

| Command | Description |
| :--- | :--- |
| `git init` | Initializes a new local Git repository |
| `git add .` | Stages all new and modified files |
| `git commit -m "message"` | Commits staged changes to local repository history |
| `git checkout -b <branch-name>` | Creates and switches to a new branch |

---

> 💡 **Key Takeaway**: Keep the `main` branch stable and develop all new features (Login, Homepage, Auth, etc.) on dedicated feature branches.
