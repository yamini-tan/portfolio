# Yamini Tantuway — Portfolio

Personal portfolio site. AI & ML engineering student · Bengaluru.

Dark (northern lights) + day theme, built as a single static page — no build step required.

## Structure

```
portfolio/
├── index.html        # the whole site
├── support.js        # runtime (loads React from CDN)
├── assets/           # portrait + hobby photos
└── uploads/          # resume PDF (Download CV button)
```

## Run locally

Just open `index.html` in a browser, or:

```bash
npx serve .
```

## Deploy to Vercel

**Option 1 — GitHub (recommended)**
1. Create a new GitHub repo and push this folder:
   ```bash
   git init
   git add .
   git commit -m "portfolio"
   git branch -M main
   git remote add origin https://github.com/yamini-tan/portfolio.git
   git push -u origin main
   ```
2. Go to [vercel.com/new](https://vercel.com/new), import the repo.
3. Framework preset: **Other**. No build command, output directory: root. Deploy.

**Option 2 — no GitHub**
```bash
npm i -g vercel
vercel
```

Every push to `main` auto-redeploys.
