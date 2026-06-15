# Store Performance Tracker

**Version 1.0 2026**

Real-time department performance tracking. No Excel. No complexity.

## What It Does

- **Weekly Tracking** — WTD sales, shrink, gross, gain by department
- **Period Tracking** — PTD or QTD performance, YoY sales comparison
- **Auto-Saves** — Data persists in your browser
- **Department-Level** — Track each department separately
- **Sales ID** — Corporate loves it
- **PDF Export** — Print or save as PDF anytime

## Files

- `index.html` — Landing page (README)
- `tracking.html` — Weekly performance tracker
- `period.html` — Period (PTD/QTD) tracker with YoY
- `README.md` — This file
- `.gitignore` — Git ignore rules
- `GITHUB_SETUP.md` — Deploy instructions

## How to Use

1. **Go to landing page** (`index.html`)
2. **Pick a tracker** (Weekly or Period)
3. **Select department** from dropdown
4. **Enter Sales ID, projections, actuals**
5. **Variance auto-calculates** as +/- only
6. **Print/PDF** when ready
7. **Switch departments** to see different data

## Variance Format

All variance shown as +/- only:
- `+$1,234` — gained that much
- `-$1,234` — lost that much
- `+0.25 pts` — above target
- `-0.25 pts` — below target

Green = Good. Red = Bad.

## GitHub Pages Setup

1. Create GitHub repo (`store-labor-tracker`)
2. Upload all files
3. Settings → Pages → Deploy from `main` branch, root folder
4. Site goes live in 1-2 minutes

See `GITHUB_SETUP.md` for detailed steps.

## Data Storage

- Saves to browser `localStorage`
- **Each department has separate history**
- **Clear browser data = loses history**
- No server uploads needed

## Support

Everything is self-contained in the HTML. No dependencies. Works offline.
