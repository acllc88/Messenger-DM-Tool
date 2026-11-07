# Messenger DM Tool — Landing Page

Static landing page for the Messenger DM Tool Chrome extension.

## Files
- `index.html` — main page
- `terms.html` — Terms of Service & Refund Policy (Stripe & PayPal, no-refund)
- `How-to-Install-Messenger-DM-Tool.pdf` — Client installation guide (step-by-step)
- `demo.mp4` — product demo video
- `shot1.png`, `shot2.png` — product screenshots
- `steps/step-01.jpg` … `step-08.jpg` — walkthrough frames from the video
- `og-image.jpg` — Open Graph / social preview image (1200×630)
- `favicon.png`, `logo.png`, `apple-touch-icon.png` — brand icons
- `vercel.json` — Vercel configuration

## Deploy to Vercel
1. Push this folder to a GitHub repository.
2. Go to https://vercel.com → New Project → Import the repo.
3. Framework Preset: **Other** (static). Root directory: this folder. No build command needed.
4. Deploy.

Or via CLI:
```bash
npm i -g vercel
cd "FB-Messenger-DM-Landing"
vercel
```

## Before publishing
- Replace the placeholder domain `https://messengerdmtool.com/` in `index.html` (canonical, og:url, twitter) with your real deployed URL.
- Update the buy link if needed (currently `https://payhip.com/b/OQcTg`).

## Local preview
```bash
python3 -m http.server 8000
# open http://localhost:8000
```