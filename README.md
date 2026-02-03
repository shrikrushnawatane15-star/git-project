````md
# 🚀 Git Commands – Complete Guide (Beginner to Advanced)

This repository contains a **complete collection of Git commands** starting from **profile setup** to **push, pull, branching, undo, stash, and advanced commands**.

Perfect for:
- Beginners learning Git
- Daily developer reference
- Interview preparation

---

## 🔰 1. Git Setup (One Time)

### Check Git installation
```bash
git --version
````

### Set Git username and email

```bash
git config --global user.name "Your Name"
git config --global user.email "yourmail@gmail.com"
```

### Verify configuration

```bash
git config --list
```

### Set default branch

```bash
git config --global init.defaultBranch main
```

---

## 📁 2. Repository Setup

### Create a new repository

```bash
mkdir my-project
cd my-project
git init
```

### Clone existing repository

```bash
git clone https://github.com/username/repository-name.git
```

---

## 📄 3. Basic Git Commands

### Check repository status

```bash
git status
```

### Add files to staging

```bash
git add filename
git add .
```

### Commit changes

```bash
git commit -m "Initial commit"
```

### View commit history

```bash
git log
git log --oneline
```

---

## 🔗 4. Remote Repository (GitHub)

### Add remote origin

```bash
git remote add origin https://github.com/username/repository-name.git
```

### Check remote URL

```bash
git remote -v
```

---

## ⬆️ 5. Push Commands

### First push

```bash
git push -u origin main
```

### Normal push

```bash
git push
```

---

## ⬇️ 6. Pull Commands

### Pull latest changes

```bash
git pull
```

### Pull from specific branch

```bash
git pull origin main
```

---

## 🌿 7. Branch Commands

### List branches

```bash
git branch
```

### Create new branch

```bash
git branch feature-branch
```

### Switch branch

```bash
git checkout feature-branch
```

### Create & switch branch

```bash
git checkout -b feature-branch
```

### Merge branch

```bash
git checkout main
git merge feature-branch
```

---

## ❌ 8. Undo & Reset Commands

### Unstage a file

```bash
git reset filename
```

### Undo last commit (keep changes)

```bash
git reset --soft HEAD~1
```

### Undo last commit (remove changes)

```bash
git reset --hard HEAD~1
```

### Discard file changes

```bash
git checkout -- filename
```

---

## 🧹 9. Git Stash

### Save work temporarily

```bash
git stash
```

### List stashes

```bash
git stash list
```

### Apply stash

```bash
git stash apply
```

### Delete stash

```bash
git stash drop
```

---

## 🔍 10. Compare & Inspect

### View differences

```bash
git diff
```

### View staged differences

```bash
git diff --staged
```

### File history

```bash
git blame filename
```

---

## 🚨 11. Fix Common Issues

### Push rejected error

```bash
git pull --rebase
git push
```

### Change remote URL

```bash
git remote set-url origin NEW_URL
```

---

## 🧠 12. Advanced Git Commands

### Cherry-pick commit

```bash
git cherry-pick commit_hash
```

### Rebase branch

```bash
git rebase main
```

### Remove untracked files

```bash
git clean -f
```

---

## 🧪 13. Daily Git Workflow

```bash
git status
git add .
git commit -m "update feature"
git pull
git push
```

---

## 📌 Best Practices

* Always pull before push
* Use meaningful commit messages
* One feature per branch
* Do not push broken code

---

## 👨‍💻 Author

Your Name
[yourmail@gmail.com](mailto:yourmail@gmail.com)

---

⭐ If you find this repository useful, don’t forget to star it!

```

```
