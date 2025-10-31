## GIT AND GUTHUB BASICS

## 1️⃣ VS Code me changes ka flow

1. Aap **`app1.py`** ya koi bhi file edit karte ho.
2. Ye changes **local repository (aapke laptop)** me hoti hain.
3. **Abhi tak GitHub pe ye changes nahi gaye**.

---

## 2️⃣ Push ka role

* Jab aap **ready ho** aur chahte ho ki aapke changes **GitHub repo me chale jaye**, tab **push** karte ho.
* VS Code me push karne ke liye:-s

  1. **Source Control tab (Ctrl+Shift+G)** kholna
  2. Changes stage karo → `+` icon ya `Stage All`
  3. Commit message likho → `✔ Commit`
  4. Push → `… → Push`

**Effect:** Local changes → GitHub (remote repo)

---

## 3️⃣ Pull ka role

* Agar aap **VS Code me kaam start kar rahe ho** aur Ansh ne GitHub pe changes kiye hain, tab **pull** karna zaruri hai.
* Pull se:

  1. Ansh ke updates aapke local repo me aa jate hain
  2. Aapka VS Code workspace updated hota hai

**Effect:** GitHub (remote repo) → Local changes

---

## 4️⃣ Summary

| Action   | Direction      | VS Code me                                          |
| -------- | -------------- | --------------------------------------------------- |
| **Pull** | Remote → Local | Latest GitHub updates aapke laptop me aa jaate hain |
| **Push** | Local → Remote | Aapke changes GitHub pe chala jata hai              |

> **Important:** Har din kaam start karne se pehle **pull** karo, kaam finish karne ke baad **push** karo.

---

💡 **Analogy:**

* VS Code = aapka desk
* GitHub = office main master file
* Pull = office se latest file desk pe lana
* Push = desk ka kaam office file me bhejna


# **VS Code + Git Workflow for Beginners (Visual Guide)**

```
┌─────────────┐       pull       ┌───────────────┐
│ GitHub Repo │  <---------->  │ Local Repo    │
│ (Remote)    │                │ (VS Code)     │
└─────────────┘                └───────────────┘
        ↑                              ↑
        │ push                         │ edit files
        │                              │ save changes
        │                              │
        └------------------------------┘
               commit & stage
```

---

## **Step-by-Step Workflow in VS Code**

### 1️⃣ Start Working

```bash
git pull origin main
```

* Latest changes GitHub se local repo me aayenge
* Hamesha **kaam start karne se pehle pull karo**

---

### 2️⃣ Edit Files in VS Code

* Open VS Code → edit files (`app1.py`, `nlpengine.py`, etc)
* Save changes

---

### 3️⃣ Stage & Commit Changes

```bash
git add .
git commit -m "Describe what you changed"
```

* `git add .` → saare changes staging area me jaate hain
* `git commit` → local repo me snapshot save hota hai

---

### 4️⃣ Push Changes to GitHub

```bash
git push origin main
```

* Local commits GitHub pe chala jata hai
* Collaborators ke liye update available ho jata hai

---

### 5️⃣ Pull Regularly

* Agar collaborator ne changes push kiye hain, pull karo:

```bash
git pull origin main
```

* Conflicts aaye → manually resolve karo, phir commit & push

---

### 6️⃣ Tips for Beginners in VS Code

1. **Source Control Tab (Ctrl+Shift+G)** use karo → Easy staging, commit, push
2. **.gitignore** file create karo → ignore sensitive files (venv/, .env, uploads/)
3. **Commit message** short aur meaningful rakho
4. Har din kaam shuru karne se pehle **pull**, kaam finish karne ke baad **push**

---

### ✅ Quick Git Commands Cheat Sheet

| Command                | Purpose                          |
| ---------------------- | -------------------------------- |
| `git init`             | Start git in your project folder |
| `git status`           | Check current changes            |
| `git add .`            | Stage all changes                |
| `git commit -m "msg"`  | Commit staged changes            |
| `git pull origin main` | Get latest changes from GitHub   |
| `git push origin main` | Send local commits to GitHub     |
| `git log`              | Show commit history              |



## 1️⃣ VS Code me changes ka flow

1. Aap **`app1.py`** ya koi bhi file edit karte ho.
2. Ye changes **local repository (aapke laptop)** me hoti hain.
3. **Abhi tak GitHub pe ye changes nahi gaye**.

---

## 2️⃣ Push ka role

* Jab aap **ready ho** aur chahte ho ki aapke changes **GitHub repo me chale jaye**, tab **push** karte ho.
* VS Code me push karne ke liye:

  1. **Source Control tab (Ctrl+Shift+G)** kholna
  2. Changes stage karo → `+` icon ya `Stage All`
  3. Commit message likho → `✔ Commit`
  4. Push → `… → Push`

**Effect:** Local changes → GitHub (remote repo)

---

## 3️⃣ Pull ka role

* Agar aap **VS Code me kaam start kar rahe ho** aur Ansh ne GitHub pe changes kiye hain, tab **pull** karna zaruri hai.
* Pull se:

  1. Ansh ke updates aapke local repo me aa jate hain
  2. Aapka VS Code workspace updated hota hai

**Effect:** GitHub (remote repo) → Local changes

---

## 4️⃣ Summary

| Action   | Direction      | VS Code me                                          |
| -------- | -------------- | --------------------------------------------------- |
| **Pull** | Remote → Local | Latest GitHub updates aapke laptop me aa jaate hain |
| **Push** | Local → Remote | Aapke changes GitHub pe chala jata hai              |

> **Important:** Har din kaam start karne se pehle **pull** karo, kaam finish karne ke baad **push** karo.

---

💡 **Analogy:**

* VS Code = aapka desk
* GitHub = office main master file
* Pull = office se latest file desk pe lana
* Push = desk ka kaam office file me bhejna






