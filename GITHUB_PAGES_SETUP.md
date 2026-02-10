# Publish on GitHub Pages (roadmap only)

## 1. Create a new repo on GitHub

1. Go to **https://github.com/new**
2. **Repository name:** e.g. `design-roadmap-h126`
3. **Public**, leave "Add a README" **unchecked**
4. Click **Create repository**

## 2. Push this folder

In Terminal (replace `YOUR-USERNAME` and `REPO-NAME`):

```bash
cd ~/Downloads/CO_CSAT_Analysis_Site
git add -A
git commit -m "Roadmap only: remove Colombia CSAT, index = roadmap"
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git
git branch -M main
git push -u origin main
```

(If you already had a remote from before: `git remote set-url origin https://github.com/YOUR-USERNAME/REPO-NAME.git` then push.)

## 3. Enable Pages

**Settings → Pages** → Source: **Deploy from a branch** → Branch: **main**, folder: **/ (root)** → Save.

## 4. Share

After 1–2 minutes your link is:

**`https://YOUR-USERNAME.github.io/REPO-NAME/`**

That’s the roadmap. No other pages.
