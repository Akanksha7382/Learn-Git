# Branching & Merging Strategy

## 🌿 What is a Branch?

A branch is a separate line of development in Git. It allows you to work on features without affecting the main code.

---

## 📌 Why Use Branches?

* Work on features independently
* Avoid breaking main code
* Enable team collaboration
* Easy bug fixing

---

## 🔹 Types of Branches

### 1. Main Branch

* Usually called `main` or `master`
* Contains stable production code

### 2. Feature Branch

* Used to develop new features
* Example: `feature/login-system`

### 3. Bugfix Branch

* Used to fix bugs
* Example: `bugfix/navbar-error`

---

## 📌 Common Branch Commands

### 🔹 Create a Branch

```bash
git branch feature-name
```

### 🔹 Switch Branch

```bash
git checkout feature-name
```

OR (modern way)

```bash
git switch feature-name
```

### 🔹 Create + Switch

```bash
git checkout -b feature-name
```

---

## 🔀 What is Merging?

Merging means combining changes from one branch into another.

---

## 📌 Merge Example

```bash
git checkout main
git merge feature-name
```

---

## ⚠️ Merge Conflicts

### What is Conflict?

When Git cannot automatically merge changes.

### How to Resolve?

1. Open conflicted file
2. Edit manually
3. Remove conflict markers
4. Add and commit again


---

## 🚀 Basic Team Workflow

1. Create branch from main
2. Work on feature
3. Commit changes
4. Push branch
5. Create Pull Request
6. Review & Merge

