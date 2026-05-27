# PillowTax Website

A "coming soon" landing page for PillowTax — Finance Made Comfortable.

## 🚀 Deploy to GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com/new](https://github.com/new)
2. Name it `pillowtax` (or any name you like)
3. Set visibility to **Public**
4. Click **Create repository**

### Step 2 — Upload the files

**Option A — GitHub web interface (easiest):**
1. In your new repo, click **Add file → Upload files**
2. Drag and drop all files from this folder:
   - `index.html`
   - `mascot.png`
   - `pillowmascot.png`
3. Click **Commit changes**

**Option B — Git command line:**
```bash
cd pillowtax-site
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pillowtax.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: `main`, folder: `/ (root)`
4. Click **Save**

### Step 4 — Your site is live! 🎉

After ~1–2 minutes your site will be at:
```
https://YOUR_USERNAME.github.io/pillowtax/
```

---

## 📁 File Structure

```
pillowtax-site/
├── index.html        ← Main website
├── mascot.png        ← Logo (nav + footer)
├── pillowmascot.png  ← Hero mascot illustration
└── README.md
```

## 🎨 Brand Colors

| Color  | Hex       |
|--------|-----------|
| Yellow | `#FFEE00` |
| Green  | `#1A6B3C` |
| Black  | `#0a0a0a` |
