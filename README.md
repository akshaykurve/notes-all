
# 🚀 Comprehensive Git Commands Cheat Sheet

This document provides a categorized list of all major Git commands, including their descriptions and usage.

---

## 🔧 Configuration Commands

| Command | Description |
|--------|-------------|
| `git config --global user.name "Name"` | Set username globally |
| `git config --global user.email "email@example.com"` | Set email globally |
| `git config --list` | List all Git configurations |
| `git config -e` | Edit config file |
| `git help <command>` | Get help for a command |

---

## 📁 Repository Commands

| Command | Description |
|--------|-------------|
| `git init` | Initialize a new Git repository |
| `git clone <url>` | Clone a repository |
| `git remote add origin <url>` | Add a remote repository |
| `git remote -v` | Show remote URLs |
| `git remote remove <name>` | Remove a remote |

---

## 📌 Staging and Committing

| Command | Description |
|--------|-------------|
| `git status` | Show working directory status |
| `git add <file>` | Stage a file |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Commit staged changes |
| `git commit -a -m "message"` | Stage and commit tracked files |
| `git reset <file>` | Unstage a file |
| `git reset` | Unstage all |
| `git reset --hard` | Discard all changes |

---

## 🔄 Branching & Merging

| Command | Description |
|--------|-------------|
| `git branch` | List branches |
| `git branch <name>` | Create a new branch |
| `git checkout <branch>` | Switch to branch |
| `git checkout -b <name>` | Create and switch to new branch |
| `git merge <branch>` | Merge branch into current |
| `git branch -d <name>` | Delete branch |
| `git branch -m <old> <new>` | Rename branch |

---

## 🔃 Push and Pull

| Command | Description |
|--------|-------------|
| `git fetch` | Download changes from remote |
| `git pull` | Fetch and merge from remote |
| `git pull origin <branch>` | Pull specific branch |
| `git push` | Push to remote repository |
| `git push origin <branch>` | Push specific branch |
| `git push -u origin <branch>` | Set upstream and push |

---

## 🔁 Rebasing & Cherry Picking

| Command | Description |
|--------|-------------|
| `git rebase <branch>` | Reapply commits on top of another base |
| `git cherry-pick <commit>` | Apply specific commit to current branch |

---

## 🧹 Undo & Cleanup

| Command | Description |
|--------|-------------|
| `git revert <commit>` | Revert a commit (safe) |
| `git reset --soft HEAD~1` | Undo last commit, keep changes staged |
| `git reset --mixed HEAD~1` | Undo last commit, unstage changes |
| `git reset --hard HEAD~1` | Undo last commit and discard changes |
| `git clean -fd` | Delete untracked files/directories |

---

## 📜 Viewing History & Logs

| Command | Description |
|--------|-------------|
| `git log` | View commit history |
| `git log --oneline` | Condensed log |
| `git log --graph` | Visual commit history |
| `git show <commit>` | Show details of a commit |
| `git diff` | Show unstaged changes |
| `git diff --staged` | Show staged changes |
| `git blame <file>` | Show who made each line change |

---

## 🗃️ Tagging

| Command | Description |
|--------|-------------|
| `git tag` | List tags |
| `git tag <name>` | Create a tag |
| `git tag -d <name>` | Delete a tag |
| `git push origin <tag>` | Push a tag to remote |

---

## 📦 Stashing

| Command | Description |
|--------|-------------|
| `git stash` | Save uncommitted changes |
| `git stash list` | Show saved stashes |
| `git stash apply` | Reapply last stash |
| `git stash pop` | Reapply and remove stash |
| `git stash drop` | Delete a stash |

---

## 🧪 Submodules

| Command | Description |
|--------|-------------|
| `git submodule add <url>` | Add a submodule |
| `git submodule update --init` | Initialize submodules |
| `git submodule foreach <command>` | Run command in each submodule |

---

## 🧠 Miscellaneous

| Command | Description |
|--------|-------------|
| `git archive` | Create a tar/zip of repo |
| `git grep <text>` | Search in repo |
| `git bisect` | Find bug using binary search |
| `git reflog` | View reference log (history of HEAD) |

---
