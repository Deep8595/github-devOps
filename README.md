# Git Commands for DevOps Engineers 🚀

This section covers **Git commands commonly used in DevOps workflows**, including CI/CD pipelines, branching strategies, release management, rollback, and automation.

---

# 📦 Repository Setup (CI/CD Pipelines)

These commands are commonly used in Jenkins, GitHub Actions, GitLab CI, etc.

```bash
git clone <repository-url>
cd <repo-name>
git fetch --all
git pull origin main
```

Reset workspace in CI pipeline

```bash
git fetch origin
git reset --hard origin/main
git clean -fd
```

---

# 🌿 Branching Strategy (DevOps Workflow)

Create feature branch

```bash
git checkout -b feature/login
```

Switch branch

```bash
git checkout develop
```

Merge feature branch

```bash
git merge feature/login
```

Delete branch after merge

```bash
git branch -d feature/login
```

---

# 🔁 Rebase (Clean History Before Merge)

Rebase with main branch

```bash
git rebase main
```

Interactive rebase

```bash
git rebase -i HEAD~5
```

---

# 📦 Release Management (Production Deployment)

Create release tag

```bash
git tag v1.0.0
```

Push tag

```bash
git push origin v1.0.0
```

Push all tags

```bash
git push --tags
```

---

# 🔄 Rollback & Recovery (Production Issues)

Rollback using revert

```bash
git revert <commit-id>
```

Rollback to previous commit

```bash
git reset --hard HEAD~1
```

Rollback to specific version

```bash
git checkout v1.0.0
```

---

# 🔐 Git Commands for DevOps Automation

Get current commit ID

```bash
git rev-parse HEAD
```

Get current branch

```bash
git branch --show-current
```

Get changed files

```bash
git diff --name-only
```

Get last commit message

```bash
git log -1 --pretty=%B
```

---

# 📥 Sync With Remote Repository

Fetch latest changes

```bash
git fetch origin
```

Pull latest code

```bash
git pull origin main
```

Compare branches

```bash
git diff main develop
```

---

# ⚡ Git Commands Used in CI/CD Pipelines

Typical DevOps pipeline workflow

```bash
git clone <repo>
git checkout develop
git pull origin develop
npm install
npm run build
git tag v1.2.0
git push origin v1.2.0
```

---

# 🧠 DevOps Git Workflow

```
Developer → Feature Branch
        ↓
Pull Request (PR)
        ↓
Merge to Develop
        ↓
Merge to Main
        ↓
Create Tag (Release)
        ↓
CI/CD Pipeline Deploy
```

---

# ⭐ Most Important Git Commands for DevOps

```
git clone
git fetch
git pull
git checkout
git merge
git rebase
git tag
git revert
git reset
git clean
git rev-parse
git diff
```
