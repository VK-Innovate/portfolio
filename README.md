# VK Portfolio — Deployment Guide

## Files
- `index.html` — Main portfolio page
- `style.css`  — All styles
- `script.js`  — Animations & interactions
- `vercel.json` — Vercel config

---

## Deploy to Vercel (Free, takes 2 minutes)

### Option A — Drag & Drop (Easiest)
1. Go to https://vercel.com → Sign up with GitHub
2. Click **"Add New Project"**
3. Drag the entire portfolio folder onto the Vercel upload area
4. Click **Deploy**
5. Your site is live at `https://your-name.vercel.app`

### Option B — GitHub (Recommended, auto-deploys on push)
1. Create a new repo on GitHub: `vk-portfolio` (public)
2. Push these 4 files to it:
   ```
   git init
   git add .
   git commit -m "initial portfolio"
   git remote add origin https://github.com/VK-Innovate/vk-portfolio.git
   git push -u origin main
   ```
3. Go to https://vercel.com → **"Add New Project"** → Import from GitHub
4. Select `vk-portfolio` → Deploy
5. Any future `git push` auto-deploys ✅

### Custom Domain (Optional)
- In Vercel dashboard → Settings → Domains
- Add your domain, follow DNS instructions

---

## Update Resume Link
Once deployed, you'll get a URL like `https://varun-portfolio.vercel.app`
Add it to:
- Your LaTeX resume header
- Your LinkedIn profile
- Your GitHub profile README
