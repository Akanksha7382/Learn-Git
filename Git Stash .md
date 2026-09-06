# Git Stash - Temporary Save for Work in Progress

## 📌 What is Git Stash?

`git stash` is used to temporarily save your uncommitted changes without committing them.  
It helps when you want to switch branches or work on something urgent without losing your current progress.

---

## 🚀 Why use Git Stash?

- Switch branches without committing half-done work
- Keep your working directory clean
- Come back later and continue work

---

## 🧠 Basic Commands

### 1. Stash current changes
```bash
git stash
```

2. Stash with message
```
git stash save "work in progress on login feature"
```

3. List all stashes
```
git stash list
```

4. Apply last stash
```
git stash apply
```

5. Apply and remove stash
```
git stash pop
```

6. Drop a specific stash
```
git stash drop stash@{0}
```

7. Clear all stashes
```
git stash clear
```
---

Later:
```
git stash pop
```
## Real-life example

- You're on feature/login.
```
git status
```
```
Modified: Login.js
Modified: App.js
```

- Save your work:
```
git stash
```

- Switch to another branch:
```
git checkout main
```

- Pull the latest code:
```
git pull
```

- Go back to your branch:
```
git checkout feature/login
```

- Restore your work:
```
git stash apply
```
Now your changes are back, and you can continue where you left off.


