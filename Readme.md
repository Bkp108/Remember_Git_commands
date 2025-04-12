# 🚀 Git & GitHub Basic Commands Cheat Sheet

## 🔧 1. Initial Setup (One-Time)
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

---

## 🆕 2. Create New Repository (Local + GitHub)

### 📂 Local Project Folder
```bash
mkdir my-project
cd my-project
```

### 🔄 Initialize Git
```bash
git init
```

---

## 📄 3. Add & Commit Changes

### ➕ Add all files
```bash
git add .
```

### 📝 Commit with message
```bash
git commit -m "your message"
```

---

## ☁️ 4. Connect to GitHub

### 🛰️ Add GitHub Remote
```bash
git remote add origin https://github.com/your-username/your-repo.git
```

### 📤 Push to GitHub
```bash
git push -u origin main
```

---

## 🔁 5. Daily Workflow

### 1. Check file status
```bash
git status
```

### 2. Add changes
```bash
git add filename.txt
# OR
git add .
```

### 3. Commit changes
```bash
git commit -m "Updated something"
```

### 4. Push to GitHub
```bash
git push
```

---

## 📥 6. Cloning a Repo

```bash
git clone https://github.com/username/repo-name.git
```

---

## 🌳 7. Branching

### Create new branch
```bash
git branch new-feature
```

### Switch branch
```bash
git checkout new-feature
```

### Create & switch
```bash
git checkout -b new-feature
```

---

## 🔄 8. Pull Latest Changes

```bash
git pull
```

---

## 🔗 9. Git Remote Check

```bash
git remote -v
```

---

## 💥 10. Remove Git Cache (if needed)

```bash
git rm -r --cached .
```

---


## ✅ 11. Check Commit History

```bash
git log
```

---
