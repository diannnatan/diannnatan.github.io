# Diana's Portfolio Website

A professional, responsive portfolio website showcasing research experience, projects, and publications. Built with HTML, CSS, and JavaScript, optimized for GitHub Pages.

## 🌐 Live Website

Visit the live website at: [diannnatan.github.io](https://diannnatan.github.io)

## ✨ Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Fast Loading**: Optimized for performance
- **SEO Optimized**: Proper meta tags and structured data
- **Contact Form**: Functional contact form with validation
- **Print-friendly CV**: Optimized print styles for CV page

## 📁 Project Structure

```
diana-website/
├── index.html              # Homepage
├── experience.html         # Experience timeline
├── projects.html           # Projects showcase
├── project-*.html          # Individual project pages
├── publications.html       # Academic publications
├── cv.html                 # Curriculum vitae
├── contact.html            # Contact form and information
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── script.js           # JavaScript functionality
├── assets/
│   ├── CV_Xiao.pdf         # CV PDF
│   └── images/
│       └── profile.png      # Profile picture
├── _config.yml             # GitHub Pages configuration
└── README.md               # This file
```

## 🚀 Deploying to GitHub Pages

### Step 1: Create/Prepare Your Repository

1. **If you haven't created the repository yet:**
   - Go to GitHub and create a new repository
   - Name it `[your-username].github.io` (e.g., `diannnatan.github.io`)
   - Make it public (required for free GitHub Pages)

2. **If the repository already exists:**
   - Make sure it's named correctly: `[your-username].github.io`
   - Ensure it's set to public

### Step 2: Push Your Code to GitHub

1. **Initialize git (if not already done):**
   ```bash
   git init
   ```

2. **Add all files:**
   ```bash
   git add .
   ```

3. **Commit your changes:**
   ```bash
   git commit -m "Initial commit: Portfolio website"
   ```

4. **Add remote repository:**
   ```bash
   git remote add origin https://github.com/[your-username]/[your-username].github.io.git
   ```

5. **Push to GitHub:**
   ```bash
   git branch -M main
   git push -u origin main
   ```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Click **Save**

### Step 4: Wait for Deployment

- GitHub Pages will automatically build and deploy your site
- It usually takes 1-2 minutes
- You'll see a green checkmark when it's ready
- Your site will be available at: `https://[your-username].github.io`

### Step 5: Verify Your Site

1. Visit `https://[your-username].github.io`
2. Check all pages load correctly
3. Test navigation and links
4. Verify images and PDFs load properly

## 🔧 Customization

### Update Personal Information

- **Homepage** (`index.html`): Update hero section and about section
- **Experience** (`experience.html`): Update timeline entries
- **Projects** (`projects.html`): Add your research projects
- **CV** (`cv.html`): Update curriculum vitae
- **Contact** (`contact.html`): Update contact information

### Update Configuration

Edit `_config.yml` to update:
- Site title and description
- Author information
- Social media links
- SEO settings

### Update Assets

- Replace `assets/images/profile.png` with your profile picture
- Replace `assets/CV_Xiao.pdf` with your CV PDF
- Update CV download link in `cv.html` if filename changes

## 📱 Responsive Design

The website is built with a mobile-first approach:
- **Mobile**: < 768px
- **Tablet**: 768px - 968px
- **Desktop**: > 968px

## 🔍 SEO & Performance

- Meta tags and descriptions on all pages
- Semantic HTML structure
- Optimized images
- Fast loading times
- Accessible design

## 📝 Notes

- The contact form currently shows a success message but doesn't send emails. To enable email functionality, you'll need to integrate with a service like Formspree, Netlify Forms, or a custom backend.
- All pages are static HTML, so no server-side processing is required.
- The site works perfectly with GitHub Pages' free hosting.

## 📄 License

This project is open source and available under the MIT License.

---

**Built with ❤️ for showcasing academic work**
