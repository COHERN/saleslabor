# Deploy to GitHub Pages

## Step 1: Create Repository

- Go to github.com
- Click **+** → **New repository**
- Name: `store-labor-tracker`
- **Make it PUBLIC**
- Don't initialize with README (you already have one)
- Click **Create**

## Step 2: Upload Files

**Option A: Web Upload (Easiest)**
1. Click **Add file** → **Upload files**
2. Drag these files into the box:
   - `index.html`
   - `tracking.html`
   - `period.html`
   - `README.md`
   - `.gitignore`
   - `GITHUB_SETUP.md`
3. Commit message: `Initial commit`
4. Click **Commit changes**

**Option B: Command Line**
```bash
git clone https://github.com/yourusername/store-labor-tracker.git
cd store-labor-tracker
# Copy the 6 files here
git add .
git commit -m "Initial commit"
git push origin main
```

## Step 3: Enable GitHub Pages

1. Go to repo **Settings**
2. Left sidebar → **Pages**
3. **Source**: Deploy from a branch
4. **Branch**: `main` / root folder `/`
5. Click **Save**
6. Wait 1-2 minutes

## Step 4: Access Your Site

Your tracker is live at:
```
https://yourusername.github.io/store-labor-tracker
```

Share this link with your team.

## Updates

To update later:
1. Edit files locally
2. `git add .`
3. `git commit -m "Update"`
4. `git push origin main`
5. GitHub Pages updates automatically (1-2 min)

---

**That's it. Your tracker is now live.**
