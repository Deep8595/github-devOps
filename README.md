Git and Github for DevOps

---

# 🟢 1. Beginner Git Commands

These are the **most important basic commands**

### Initialize Repository

```bash
git init
```

### Clone Repository

```bash
git clone <repo-url>
```

### Check Status

```bash
git status
```

### Add Files

```bash
git add file.txt
git add .
```

### Commit Changes

```bash
git commit -m "message"
```

### Show Commit History

```bash
git log
git log --oneline
```

### Push Code

```bash
git push origin main
```

### Pull Code

```bash
git pull origin main
```

### Check Branch

```bash
git branch
```

---

# 🟡 2. Intermediate Git Commands

### Create Branch

```bash
git branch feature
```

### Switch Branch

```bash
git checkout feature
```

or new method

```bash
git switch feature
```

### Create + Switch Branch

```bash
git checkout -b feature
```

### Merge Branch

```bash
git merge feature
```

### Delete Branch

```bash
git branch -d feature
```

### Show Differences

```bash
git diff
```

### View Remote

```bash
git remote -v
```

### Add Remote

```bash
git remote add origin <url>
```

---

# 🟠 3. Branching & Undo Commands (Very Important)

### Undo Last Commit

```bash
git reset --soft HEAD~1
```

### Hard Reset

```bash
git reset --hard HEAD~1
```

### Restore File

```bash
git restore file.txt
```

### Unstage File

```bash
git restore --staged file.txt
```

### Revert Commit

```bash
git revert <commit-id>
```

---

# 🔵 4. Stash Commands (Save Work Temporarily)

### Stash Changes

```bash
git stash
```

### Stash List

```bash
git stash list
```

### Apply Stash

```bash
git stash apply
```

### Pop Stash

```bash
git stash pop
```

---

# 🟣 5. Advanced Git Commands

### Rebase

```bash
git rebase main
```

### Interactive Rebase

```bash
git rebase -i HEAD~3
```

### Cherry Pick

```bash
git cherry-pick <commit-id>
```

### Tagging

```bash
git tag v1.0
git push origin v1.0
```

### Show Specific Commit

```bash
git show <commit-id>
```

### Amend Commit

```bash
git commit --amend -m "new message"
```

---

# 🔴 6. Professional / Power User Commands

### Fetch Without Merge

```bash
git fetch
```

### Compare Branches

```bash
git diff main feature
```

### Clean Untracked Files

```bash
git clean -f
```

### Blame (who wrote code)

```bash
git blame file.txt
```

### Short Log

```bash
git shortlog
```

### Graph View

```bash
git log --graph --oneline --all
```

---

# ⭐ Most Important Commands (Interview Must Know)

These 15 are **must learn**

```
git init
git clone
git add
git commit
git push
git pull
git status
git log
git branch
git checkout
git merge
git rebase
git stash
git reset
git revert
```

---

