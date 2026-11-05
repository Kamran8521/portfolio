# Kamran Jouhar — Portfolio

A static one-page portfolio (plain HTML/CSS/JS, no build step).

**Live:** https://kamran-portfolio-mu.vercel.app. Every push to `main` deploys automatically via Vercel.

## Edit content
All text lives in the `CONFIG` object near the bottom of `index.html`:
name, email, socials, projects, skills, services, about text and stats.
Project screenshots go in `images/` and are referenced with `image: "images/file.jpg"`.

## Deploy (GitHub + Vercel)
1. Create an empty repo on GitHub, e.g. `portfolio`.
2. In this folder:
   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```
3. On vercel.com → **Add New → Project** → import the repo.
   Framework preset: **Other**. Leave build command and output directory empty → **Deploy**.
4. Every `git push` after that redeploys automatically.
5. Optional: Vercel → Project → Settings → Domains to add a custom domain.
