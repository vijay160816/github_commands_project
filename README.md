# Demonstrating Project with git commands
A handy reference for common Git commands, organized by workflow stage.

---

## 🔧 Setup
- Configure username:  
  `git config --global user.name "Your Name"`
- Configure email:  
  `git config --global user.email "you@example.com"`
- Check settings:  
  `git config --list`

---

## 📂 Starting a Repository
- Initialize new repo:  
  `git init`
- Clone existing repo:  
  `git clone <url>`

---

## 📌 Staging Changes
- Add file:  
  `git add <file>`
- Add all changes:  
  `git add .`
- Unstage file:  
  `git reset <file>`
- Check status:  
  `git status`

---

## 💾 Committing
- Commit with message:  
  `git commit -m "message"`
- Commit all tracked changes:  
  `git commit -am "message"`
- View commit history:  
  `git log`

---

## 🌿 Branching
- Create new branch:  
  `git branch <name>`  
  or  
  `git checkout -b <name>`
- Switch branch:  
  `git checkout <name>`  
  or  
  `git switch <name>`
- List branches:  
  `git branch`
- Delete branch:  
  `git branch -d <name>`

---

## 🔄 Remote Repositories
- Add remote:  
  `git remote add origin <url>`
- Push branch:  
  `git push origin <branch>`
- Pull changes:  
  `git pull`
- Fetch updates:  
  `git fetch`

---

## ⏪ Undoing Changes
- Discard local changes:  
  `git checkout -- <file>`
- Reset to last commit:  
  `git reset --hard HEAD`
- Revert commit:  
  `git revert <commit>`

---

## 📊 Inspection
- Show commit details:  
  `git show <commit>`
- Compare changes:  
  `git diff`
- Compare staged vs. last commit:  
  `git diff --cached`

---

## 📝 Notes
This  sheet is meant for quick reference. For deeper explanations, check the [Git documentation](https://git-scm.com/doc).
