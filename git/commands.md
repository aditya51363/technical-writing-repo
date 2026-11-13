# Git Commands Reference

A quick reference to 20 important Git commands commonly used for version control and repository management.

## 1. Configuration

| Command | Description |
|---|---|
| `git config --global user.name "Name"` | Set Git username |
| `git config --global user.email "email"` | Set Git email |
| `git config --list` | View Git configuration |

## 2. Repository Setup

| Command | Description |
|---|---|
| `git init` | Initialize a new repository |
| `git clone URL` | Clone an existing repository |
| `git status` | Check the current repository status |

## 3. Staging and Committing

| Command | Description |
|---|---|
| `git add .` | Stage all changes in the current directory |
| `git add filename` | Stage a specific file |
| `git commit -m "message"` | Commit staged changes |
| `git log --oneline` | View compact commit history |
| `git diff` | View unstaged changes |

## 4. Branch Management

| Command | Description |
|---|---|
| `git branch` | List local branches |
| `git branch branch-name` | Create a new branch |
| `git switch branch-name` | Switch to another branch |
| `git switch -c branch-name` | Create and switch to a new branch |
| `git merge branch-name` | Merge another branch into the current branch |

## 5. Remote Repository Operations

| Command | Description |
|---|---|
| `git remote -v` | View remote repository URLs |
| `git remote add origin URL` | Connect a remote repository |
| `git push` | Upload commits to a remote repository |
| `git pull` | Fetch and integrate remote changes |

---

## Basic Git Workflow

```bash
git status
git add .
git commit -m "Updated project"
git push
```

*These commands cover the basic operations required for everyday Git usage and GitHub repository management.*

---

*Technical Writing Coursework | 2026*