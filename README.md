# 🐙 Git & GitHub Mastery Roadmap

A structured guide and practice repository for mastering Git version control, GitHub workflows, and collaboration best practices.

---

## 📌 Phase 1: Git Basics & Setup
- [ ] **Configuration**
  - [ ] Set up username and email (`git config --global`)
  - [ ] Generate and link SSH keys to GitHub
- [ ] **Core Commands**
  - [ ] Initialize repository (`git init`)
  - [ ] Clone remote repos (`git clone`)
  - [ ] Stage and commit changes (`git add`, `git commit -m`)
  - [ ] Check repository status and history (`git status`, `git log --oneline`)

---

## 📌 Phase 2: Branching & Merging
- [ ] **Branch Management**
  - [ ] Create and switch branches (`git switch -c` / `git checkout -b`)
  - [ ] List and delete local/remote branches (`git branch -d`)
- [ ] **Combining Code**
  - [ ] Fast-forward and 3-way merges (`git merge`)
  - [ ] Resolve merge conflicts manually
  - [ ] Rebase feature branches (`git rebase`)

---

## 📌 Phase 3: Remote Repositories & GitHub
- [ ] **Remote Operations**
  - [ ] Link remotes (`git remote add origin`)
  - [ ] Push and pull changes (`git push`, `git pull`, `git fetch`)
- [ ] **Collaboration & Code Review**
  - [ ] Create Pull Requests (PRs)
  - [ ] Perform code reviews and address feedback
  - [ ] Fork public repositories and sync upstream changes

---

## 📌 Phase 4: Advanced Git Workflows
- [ ] **Time Travel & Recovery**
  - [ ] Stash uncommitted work (`git stash`, `git stash pop`)
  - [ ] Undo commits (`git reset`, `git revert`)
  - [ ] View action history with `git reflog`
- [ ] **Power Features**
  - [ ] Pick specific commits across branches (`git cherry-pick`)
  - [ ] Track down bugs using `git bisect`
  - [ ] Configure `.gitignore` for clean repositories

---

## 📌 Phase 5: Automation & CI/CD
- [ ] Learn GitHub Actions basics (Workflows, Triggers, Jobs)
- [ ] Set up automated linting/testing on Pull Requests
- [ ] Deploy pages automatically using GitHub Pages

---

## 📝 Practice Commands Reference

| Action | Command |
| :--- | :--- |
| **Check Status** | `git status` |
| **Stage All Changes** | `git add .` |
| **Commit Changes** | `git commit -m "your commit message"` |
| **Push to Remote** | `git push origin main` |
| **Pull Latest** | `git pull origin main` |
