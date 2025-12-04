# Portfolio — Make site live

This repo contains a static portfolio site. The main HTML file is `potfolio.html` (note: filename has a typo). To make the site live you can push this repo to GitHub and enable GitHub Pages, or deploy to Netlify / Vercel / Render.

Quick steps (recommended: GitHub Pages):

1. Initialize git (if not already) and commit

```powershell
cd C:\Users\rahul\portfolio
git init
git add .
git commit -m "Initial portfolio commit"
```

2. Create a repo on GitHub (use the website) and add remote, then push:

```powershell
git remote add origin https://github.com/<your-username>/portfolio.git
git branch -M main
git push -u origin main
```

3. Enable GitHub Pages:
- Open the repo on GitHub → Settings → Pages
- Under "Source" select branch `main` and folder `/ (root)` and save
- The site will be available at `https://<your-username>.github.io/portfolio/` within a minute or two

Alternative: Netlify (drag-and-drop or CLI)

- Drag-and-drop the repo's folder (or `index.html`) at https://app.netlify.com/drop
- Or install the Netlify CLI and deploy:

```powershell
npm i -g netlify-cli
netlify login
netlify deploy --dir=.
```

Notes
- I added `index.html` which redirects to `potfolio.html` so the site root works immediately. If you prefer direct root content, rename `potfolio.html` to `index.html`.
- If you want a custom domain, configure it in the hosting provider and update DNS as instructed by the provider.

If you want, I can:
- create a real `index.html` (copy contents of `potfolio.html`) so no redirect is needed
- create a remote repo and push (you will need to provide a GitHub token or complete authentication locally)
- deploy to Netlify/Vercel if you provide access/authorize the CLI

Tell me how you'd like to proceed and I will continue.
# Portfolio

This repository contains the portfolio website files (HTML, CSS, JS).
