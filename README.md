# 🧰 Git Command Reference

> A concise cheat sheet for everyday Git workflows — from setup to collaboration.

---

## ⚙️ Initial Setup

Configure your identity before making any commits.

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

---

## 🚀 Starting a Project

| Command | Description |
|---|---|
| `git init` | Initialize a new Git repository in the current directory |
| `git clone <repo-url>` | Copy an existing remote repository to your local machine |

---

## 📁 Staging & Committing

```bash
git status                  # Show the current state of the working directory
git add <file>              # Stage a specific file for the next commit
git commit -m "message"     # Save staged changes with a descriptive message
```

---

## 🔍 Inspecting Changes

| Command | Description |
|---|---|
| `git log` | Display the full commit history |
| `git diff` | Compare changes between commits, branches, or the working directory |
| `git status` | Show staged, unstaged, and untracked files |

---

## 🌿 Branching & Merging

```bash
git branch                  # List all local branches
git branch <name>           # Create a new branch
git checkout <branch>       # Switch to an existing branch
git merge <branch>          # Merge a branch into the current one
git rebase <branch>         # Reapply commits on top of another branch
```

> 💡 **Tip:** Use `git checkout -b <name>` to create and switch to a new branch in one step.

---

## 🔄 Working with Remotes

```bash
git remote -v               # Show linked remote repositories
git push origin <branch>    # Upload local commits to the remote
git pull origin <branch>    # Fetch and merge changes from the remote
```

---

## 🧹 Undoing & Cleaning

| Command | Description |
|---|---|
| `git reset <file>` | Unstage a file without losing its changes |
| `git rm <file>` | Remove a file from the repo and staging area |
| `git stash` | Temporarily save uncommitted changes for later |

---

## 🏷️ Tagging

```bash
git tag <name>              # Mark a specific commit (e.g., for a release)
```

> 💡 **Tip:** Use annotated tags for releases: `git tag -a v1.0.0 -m "First release"`

---

## 🗺️ Quick Reference Summary

| Category | Commands |
|---|---|
| **Setup** | `config` |
| **Start** | `init`, `clone` |
| **Track** | `status`, `add`, `rm`, `reset` |
| **Save** | `commit`, `stash` |
| **Inspect** | `log`, `diff` |
| **Branch** | `branch`, `checkout`, `merge`, `rebase` |
| **Remote** | `remote`, `push`, `pull` |
| **Release** | `tag` |

---
## 📡 Connection Guide
See [Connection-Builder.md](Connection-Builder.md) for full Git remote setup instructions.
---

*Generated with ❤️ — Happy committing!*
