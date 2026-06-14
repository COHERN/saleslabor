# Store Labor & Sales Tracker

**Version 1.0 2026**

A quarterly labor management tool for retail stores. Track department-level sales and labor performance with automatic variance calculations.

## Files

- `index.html` — Main landing page & tracker generator
- `summary.html` — Weekly performance report (WTD / PTD)
- `Store_Labor_Tracker_Template.xlsx` — Excel workbook template

## How to Use

### 1. Generate Your Tracker
Visit the main page (`index.html`), enter your store number, quarter, year, and select which departments apply to your store. Download the customized Excel file.

### 2. Enter Forecast Data
Open the downloaded Excel file. Each monthly sheet asks for:
- **Sales** (per department)
- **Labor %** (target labor as % of sales)
- **Avg Hourly Rate** (average wage)

Everything else calculates automatically.

### 3. Update Actuals
As each month progresses, enter actual sales, labor %, and hourly rates. Variance appears instantly showing **GOOD!** or **BAD!** status.

### 4. Track Weekly Performance
Use `summary.html` to enter weekly performance data:
- **WTD Sales** (vs projection)
- **PTD Shrink, Gross, Gain** (vs projection)

Variance calculates with +/- notation. Print to PDF for notes.

## GitHub Pages Setup

1. Create a new GitHub repository (e.g., `store-labor-tracker`)
2. Copy all three files to the repo root:
   - `index.html`
   - `summary.html`
   - `Store_Labor_Tracker_Template.xlsx`
3. In repo Settings → Pages:
   - Source: Deploy from branch
   - Branch: `main` / root (`/`)
4. Your site will be live at `https://yourusername.github.io/store-labor-tracker`

## Features

- **10 departments** (customizable per store)
- **Automatic calculations** for hours, labor $, variance
- **Traffic light status** — GOOD! or BAD! at a glance
- **Quarterly summaries** — all months auto-total
- **Weekly reports** — print-friendly with notes space

## Support

Instructions are built into every Excel sheet. See the INSTRUCTIONS tab for detailed guidance.
