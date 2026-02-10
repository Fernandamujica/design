# Publish the roadmap – checklist

Do these in order. Replace **YOUR-USERNAME** and **REPO-NAME** with your GitHub username and the repo name you choose (e.g. `design-roadmap-h126`).

---

## 1. Create the repo on GitHub

- [ ] Open **https://github.com/new**
- [ ] **Repository name:** e.g. `design-roadmap-h126`
- [ ] **Public**
- [ ] **Do not** check “Add a README file”
- [ ] Click **Create repository**

---

## 2. Push your folder from Terminal

- [ ] Open **Terminal**
- [ ] Run (use your real username and repo name):

```bash
cd ~/Downloads/CO_CSAT_Analysis_Site
git add -A
git status
git commit -m "Publish roadmap"
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git
git branch -M main
git push -u origin main
```

- [ ] If it asks to log in: use your GitHub username and a **Personal Access Token** as the password (GitHub → Settings → Developer settings → Personal access tokens → Generate new token).

**If you already added this folder to a repo before**, use this instead of the `remote add` line:

```bash
git remote set-url origin https://github.com/YOUR-USERNAME/REPO-NAME.git
git push -u origin main
```

(If your branch is `master` instead of `main`, use `git push -u origin master` and in step 3 choose **master**.)

---

## 3. Turn on GitHub Pages

- [ ] In your repo on GitHub, open **Settings**
- [ ] In the left sidebar, click **Pages**
- [ ] Under **Source**: **Deploy from a branch**
- [ ] **Branch:** `main` (or `master`) → **Folder:** `/ (root)**
- [ ] Click **Save**

---

## 4. Get your link

- [ ] Wait 1–2 minutes
- [ ] Your link: **https://YOUR-USERNAME.github.io/REPO-NAME/**
- [ ] Share that link; it opens the roadmap.

---

**Example:**  
Username `fmujica`, repo `design-roadmap-h126`  
→ **https://fmujica.github.io/design-roadmap-h126/**
