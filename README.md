# Welcome to Git and GitHub at ChaiCode Cohort! 🚀

Git and GitHub are the backbone of collaborative development at ChaiCode. This guide will help you get started with these essential tools and become a confident contributor to our projects.

---

## 🗍 Table of Contents
1. [Introduction](#introduction)
2. [Basics of Git and GitHub](#basics-of-git-and-github)
3. [Installation and Setup](#installation-and-setup)
4. [Cloning the Repository](#cloning-the-repository)
5. [Basic Git Commands](#basic-git-commands)
6. [Commit Message Rules](#commit-message-rules)
7. [Branching Workflow](#branching-workflow)
8. [Pull Requests](#pull-requests)
9. [Best Practices](#best-practices)

---

## 🌱 Introduction

At ChaiCode Cohort, we use **Git** for version control and **GitHub** for collaboration. These tools enable our developers to track code changes, work together efficiently, and maintain high-quality code.

Whether you’re a Git newbie or have some experience, this guide will walk you through everything you need to know to get started.

---

## 🌿 Basics of Git and GitHub

### What is Git?
Git is a distributed version control system that tracks changes in your codebase. It’s widely used for managing source code and enables multiple developers to collaborate on the same project.

### What is GitHub?
GitHub is a cloud-based platform that hosts Git repositories. It provides tools for:
- Code review and collaboration.
- Issue tracking.
- Continuous integration and deployment.

---

## 🔧 Installation and Setup

### Step 1: Install Git

#### Windows
1. Download Git for Windows: [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Run the installer and follow the setup wizard.

#### macOS
1. Download Git for macOS: [https://git-scm.com/download/mac](https://git-scm.com/download/mac)
2. Install using Homebrew:
   ```bash
   brew install git
   ```

#### Linux
1. Install Git using your package manager:
   ```bash
   sudo apt update && sudo apt install git
   ```

### Step 2: Configure Git

Run the following commands in your terminal:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 3: Create a GitHub Account
1. Go to [https://github.com/](https://github.com/).
2. Click **Sign Up** and follow the instructions.

---

## 🔠 Cloning the Repository

1. Copy the repository URL from GitHub.
2. Run the following command in your terminal:
   ```bash
   git clone https://github.com/ChaiCode/example-repo.git
   ```
3. Navigate to the cloned repository folder:
   ```bash
   cd example-repo
   ```

---

## 🔢 Basic Git Commands

| Command               | Description                                |
|-----------------------|--------------------------------------------|
| `git status`          | Check the status of your working directory. |
| `git add <file>`      | Stage changes for the next commit.         |
| `git commit -m "msg"` | Save changes with a message.               |
| `git push`            | Push changes to the remote repository.     |
| `git pull`            | Fetch and merge changes from the remote repository. |
| `git log`             | View commit history.                      |

### Example:
```bash
# Check status
$ git status

# Stage changes
$ git add index.html

# Commit changes
$ git commit -m "feat: Add home page layout"

# Push changes
$ git push origin main

# Pull changes
$ git pull origin main

# View commit history
$ git log
```

---

## 🔖 Commit Message Rules

- Use the present tense (e.g., "Add feature" not "Added feature").
- Capitalize the first letter of the message.
- Keep the message under 50 characters.
- Use prefixes for categorization:
  - `feat:` for new features.
  - `fix:` for bug fixes.
  - `docs:` for documentation changes.
  - `chore:` for maintenance tasks.

### Example Messages:
```bash
feat: Add tea selection feature
fix: Resolve login issue for tea enthusiasts
docs: Update README with chai varieties
chore: Update dependencies for security patches
```

---

## 🔃 Branching Workflow

### Branching Strategy
We use the following branches:
- `main`: Production-ready code.
- `development`: Ongoing development.
- `feature/<name>`: Specific features.

### Creating and Switching Branches
```bash
git branch feature/tea-menu
git checkout feature/tea-menu
```

### Merging Branches
1. Switch to the target branch (e.g., `development`):
   ```bash
   git checkout development
   ```
2. Merge the feature branch:
   ```bash
   git merge feature/tea-menu
   ```

---

## 🔀 Pull Requests (PR)

1. Push your branch to GitHub:
   ```bash
   git push origin feature/tea-menu
   ```
2. Go to the GitHub repository and click **New Pull Request**.
3. Add a meaningful description and request a review.

![Pull Request Screenshot](screenshots/pull-request.png)

---

## 🏆 Best Practices

- Commit changes frequently with descriptive messages.
- Pull updates regularly to avoid conflicts.
- Review your code before pushing it.

---

**Congratulations!** You’re now ready to contribute to ChaiCode projects like a pro. If you have any questions, feel free to ask your mentor!


