# Publish this site to get a shareable link

Choose one of these options. After publishing, you can share:

- **Roadmap (H1/26):** `https://YOUR-SITE-URL/Roadmap_Interactive_View.html`
- **Colombia CSAT:** `https://YOUR-SITE-URL/` or `https://YOUR-SITE-URL/index.html`

---

## Option 1: Netlify Drop (no account, ~1 min)

1. Go to **https://app.netlify.com/drop**
2. Drag the **CO_CSAT_Analysis_Site** folder onto the page.
3. Netlify will give you a link like `https://random-name-123.netlify.app`.
4. Share:
   - Roadmap: `https://random-name-123.netlify.app/Roadmap_Interactive_View.html`
   - Home: `https://random-name-123.netlify.app/`

(You can sign in to Netlify later to change the site name or add a custom domain.)

---

## Option 2: Surge (free, from terminal)

1. Open Terminal and run:
   ```bash
   cd ~/Downloads/CO_CSAT_Analysis_Site
   npx surge .
   ```
2. When prompted, enter your email and (first time) create a password at surge.sh.
3. Surge will print a URL like `https://something.surge.sh`.
4. Share:
   - Roadmap: `https://something.surge.sh/Roadmap_Interactive_View.html`
   - Home: `https://something.surge.sh/`

To use a custom subdomain (e.g. `roadmap-h126.surge.sh`):
```bash
npx surge . roadmap-h126.surge.sh
```

---

## Option 3: GitHub Pages (free, good if you use GitHub)

1. Create a new repository on GitHub (e.g. `design-roadmap-h126`).
2. Upload the contents of **CO_CSAT_Analysis_Site** to the repo (not the folder itself—all the files inside it).
3. In the repo: **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** (or **master**) → **Save**.
4. After a minute, your site will be at:
   - `https://YOUR-USERNAME.github.io/design-roadmap-h126/`
   - Roadmap: `https://YOUR-USERNAME.github.io/design-roadmap-h126/Roadmap_Interactive_View.html`

---

## Make the roadmap the default page (optional)

If you want the **root URL** to open the roadmap instead of the Colombia CSAT page:

- **Netlify:** Add a file `netlify.toml` in the folder with:
  ```toml
  [[redirects]]
    from = "/"
    to = "/Roadmap_Interactive_View.html"
    status = 200
  ```
- **Surge:** Before running `surge`, rename `index.html` to something else (e.g. `Colombia_CSAT.html`) and rename `Roadmap_Interactive_View.html` to `index.html`. Then the root URL will show the roadmap.
