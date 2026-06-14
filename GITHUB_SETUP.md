# Upload to GitHub Pages — Quick Setup

## Files to Upload (All in Root `/`)

```
.gitignore
README.md
index.html
summary.html
Store_Labor_Tracker_Template.xlsx
```

## Step-by-Step

### 1. Create GitHub Repo
- Go to github.com → New repository
- Name: `store-labor-tracker` (or your preference)
- Description: "Store Labor & Sales Tracker"
- Public (so GitHub Pages can host it)
- **Do NOT** initialize with README (you already have one)
- Click Create Repository

### 2. Upload Files
Option A (Web UI — easiest):
- Click "Add file" → "Upload files"
- Drag all 5 files into the upload area
- Commit message: "Initial commit: v1.0"
- Click Commit changes

Option B (Command Line):
```bash
git clone https://github.com/yourusername/store-labor-tracker.git
cd store-labor-tracker
# Copy the 5 files here
git add .
git commit -m "Initial commit: v1.0"
git push origin main
```

### 3. Enable GitHub Pages
- Go to repo Settings → Pages
- Source: "Deploy from a branch"
- Branch: `main` / root (`/`)
- Save
- Wait 1-2 minutes for the site to build

### 4. Access Your Site
Your tracker is now live at:
```
https://yourusername.github.io/store-labor-tracker
```

## What Each File Does

| File | Purpose |
|------|---------|
| `index.html` | Landing page with tracker generator |
| `summary.html` | Weekly performance report |
| `Store_Labor_Tracker_Template.xlsx` | Excel workbook (downloaded from index.html) |
| `README.md` | GitHub repo description |
| `.gitignore` | Ignore unnecessary files |

## Share With Your Team

Once live, share the link:
```
https://yourusername.github.io/store-labor-tracker
```

Everyone can:
- Download the Excel template (customized per store/quarter)
- Fill it with their labor data
- Use the weekly report page to track KPIs

## Updates & Changes

To update in the future:
1. Edit the files locally
2. `git add .`
3. `git commit -m "Description of changes"`
4. `git push origin main`
5. GitHub Pages updates automatically (1-2 min)

---

**That's it.** Your tracker is now live and shareable.
