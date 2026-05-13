# Heseos Carbon Credit Dashboard

Smart Connected & Sustainable Living — Carbon Credit Calculator

## Deploy to Vercel

### Option 1: Drag & Drop (Fastest)
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **"Add New → Project"**
3. Choose **"Deploy from folder"** or drag this folder directly
4. Vercel auto-detects static HTML — click **Deploy**
5. Done ✅ — your site is live in ~30 seconds

### Option 2: GitHub (Recommended for updates)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → **"Add New → Project"**
3. Import your GitHub repo
4. Framework preset: **"Other"** (no framework)
5. Click **Deploy**

### Option 3: Vercel CLI
```bash
npm install -g vercel
vercel login
vercel --prod
```

## Files
- `index.html` — the entire app (self-contained)
- `vercel.json` — Vercel routing config

## Notes
- No backend needed — fully static
- Lead data is stored in browser localStorage
- All dependencies loaded from CDN (Chart.js, html2pdf.js)
- Works on all modern browsers
