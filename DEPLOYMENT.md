# GitHub Pages Deployment Guide

## Quick Start

### 1. Repository Setup

Your repository must be named: `[your-username].github.io`

For example: `diannnatan.github.io`

### 2. Push Code to GitHub

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Portfolio website"

# Add remote (replace with your username)
git remote add origin https://github.com/[your-username]/[your-username].github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

### 4. Wait & Verify

- Wait 1-2 minutes for deployment
- Visit: `https://[your-username].github.io`
- Check all pages load correctly

## Important Notes

- ✅ Repository must be **public** (for free GitHub Pages)
- ✅ Repository name must match `[username].github.io`
- ✅ All files are in the root directory (no need for `docs/` folder)
- ✅ No build process needed - static HTML works directly

## File Structure

```
.
├── index.html
├── experience.html
├── projects.html
├── publications.html
├── cv.html
├── contact.html
├── project-*.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   ├── CV_Xiao.pdf
│   └── images/
│       └── profile.png
├── _config.yml
└── README.md
```

## Troubleshooting

**Site not loading?**
- Check repository name matches `[username].github.io`
- Verify repository is public
- Check GitHub Pages settings
- Wait a few more minutes for deployment

**404 errors?**
- Ensure all HTML files are in root directory
- Check file names match links in navigation
- Verify file extensions are `.html` (not `.htm`)

**Images not showing?**
- Check image paths are relative (e.g., `assets/images/profile.png`)
- Verify images are committed to repository
- Check file names match exactly (case-sensitive)

## Updates

After making changes:

```bash
git add .
git commit -m "Update website content"
git push origin main
```

Changes will be live in 1-2 minutes.
