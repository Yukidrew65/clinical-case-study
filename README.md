# Clinical Intake & Symptom Triage Copilot — Case Study Brief

A single-page site for the UX case study brief. No build step, no dependencies — just one `index.html`.

## Deploy to Netlify

### Option A — Git (recommended)
1. Push this folder to a GitHub repo:
   ```bash
   git init
   git add .
   git commit -m "Add case study brief site"
   git branch -M main
   git remote add origin https://github.com/<you>/<repo>.git
   git push -u origin main
   ```
2. In Netlify: **Add new site → Import an existing project → GitHub**, pick the repo.
3. Leave build command blank and publish directory as `.` (root). Deploy.

### Option B — Drag & drop
Drag this folder onto the Netlify dashboard. Done.

## Local preview
Just open `index.html` in a browser, or run:
```bash
python3 -m http.server 8000
```
then visit `http://localhost:8000`.

## Notes
- Fonts (Fraunces + Spline Sans) load from Google Fonts.
- Fully responsive; no JS required.
