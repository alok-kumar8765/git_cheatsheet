# 🐙 The Ultimate Git Command Reference Sheet

🚀 **Speed Up Your Development Workflow: Essential Commands & Best Practices**

This repository provides a comprehensive and easy-to-reference guide to the most essential Git commands, focusing on practical use cases and best practices.  
Whether you're a beginner learning version control or an experienced developer needing a quick lookup, this cheat sheet enhances your day-to-day workflow.

---


# 📑 Table of Contents

* [🐙 The Ultimate Git Command Reference Sheet](#-the-ultimate-git-command-reference-sheet)
* [📑 Table of Contents](#-table-of-contents)
* [🛡️ Quality Badges](#️-quality-badges)
* [📝 Detailed Git Command Reference](#-detailed-git-command-reference)

  * [🔧 Configuration](#-configuration)
  * [📁 Basic Operations](#-basic-operations)
  * [🌿 Branching & Merging](#-branching--merging)
  * [🛠️ Undoing Changes](#️-undoing-changes)
* [🎓 Learning Resources](#-learning-resources)
* [⭐ Boost Your Repository Quality](#-boost-your-repository-quality)
* [💬 Contributions Welcome](#-contributions-welcome)
* [⭐ Support the Project](#-support-the-project)

---

## 🛡️ Quality Badges

<p align="left">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" alt="status" />
  <img src="https://img.shields.io/badge/Code%20Quality-Excellent-blue" alt="code quality" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="license" />
</p>

---

# 📝 Detailed Git Command Reference

Below is a complete reference covering configuration, basic operations, branching, merging, and undoing changes — each with descriptions, practical use cases, and runnable examples.

---

## 🔧 Configuration

| Command | Description | Use Case | Example |
|--------|-------------|----------|---------|
| `git config --global user.name "Your Name"` | Sets your Git author name globally. | First-time Git setup on new machine. | `git config --global user.name "Alok Kumar"` |
| `git config --global user.email "you@example.com"` | Sets your Git author email globally. | First-time Git setup on new machine. | `git config --global user.email "alok@example.com"` |

---

## 📁 Basic Operations

| Command | Description | Use Case | Example |
|--------|-------------|----------|---------|
| `git init` | Initializes a new Git repository. | Starting a new project. | `git init` |
| `git clone <url>` | Clones a remote repo. | Downloading a project from GitHub/GitLab. | `git clone https://github.com/alok-kumar8765/repo.git` |
| `git status` | Shows working directory status. | See files to stage or commit. | `git status` |
| `git add <file>` / `git add .` | Stages specific files or all changes. | Preparing changes for commit. | `git add index.html` or `git add .` |
| `git commit -m "message"` | Saves staged changes as a commit. | Creating a snapshot of work. | `git commit -m "Feat: Add login form structure"` |
| `git push` | Uploads commits to remote. | Sharing changes with team. | `git push origin main` |
| `git pull` | Fetches + merges remote changes. | Sync work with latest updates. | `git pull origin main` |

---

## 🌿 Branching & Merging

| Command | Description | Use Case | Example |
|--------|-------------|----------|---------|
| `git branch` | Lists branches. | Review available branches. | `git branch` |
| `git branch <name>` | Creates a new branch. | Start new feature. | `git branch new-feature` |
| `git checkout <branch>` | Switches branches. | Change development context. | `git checkout main` |
| `git checkout -b <branch>` | Creates + switches to new branch. | Quick feature branch creation. | `git checkout -b user/profile-page` |
| `git merge <branch>` | Merges branch into current. | Combine feature into main/develop. | `git merge feature-x` |
| `git branch -d <branch>` | Deletes local merged branch. | Cleanup branches after merge. | `git branch -d old-feature` |

---

## 🛠️ Undoing Changes

| Command | Description | Use Case | Example |
|--------|-------------|----------|---------|
| `git diff` | Shows file differences. | Review changes before staging. | `git diff` |
| `git checkout -- <file>` | Discards uncommitted changes. | Revert accidental edits. | `git checkout -- css/style.css` |
| `git reset <file>` | Unstages a file but keeps edits. | Undo `git add`. | `git reset index.html` |
| `git log` | Shows commit history. | View commit messages & authors. | `git log --oneline` |
| `git stash` | Temporarily saves changes. | Switch branches without committing. | `git stash push -m "WIP on feature"` |

---

# 🎓 Learning Resources

### 📚 Official Git Documentation  
- Git Docs: https://git-scm.com/doc  
- Pro Git Book (free): https://git-scm.com/book  
- Git Command Reference: https://git-scm.com/docs  

### 🎥 Recommended Video Tutorials  
- Git & GitHub for Beginners – Crash Course  
- Learn Git Branching (Interactive): https://learngitbranching.js.org/

---

## 💬 Contributions Welcome

Feel free to submit issues, suggest improvements, or open pull requests to expand this cheat sheet!

---

## ⭐ If this project helped you — please star the repo!

## Image

<img src="https://github.com/alok-kumar8765/git_cheatsheet/blob/main/img.png" height="50%" width="50%">