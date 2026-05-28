# 🚀 Luomas Website Deployment Guide

## 🔥 One-Click Deployment to GitHub Pages

Follow these **step-by-step instructions** to get your website live!

---

### 📋 Prerequisites

- A GitHub account (free)
- Internet connection
- All website files ready in `d:\luomas\luomas-en\`

---

### 🛠️ Step 1: Create GitHub Account

1. Open your browser and go to: https://github.com
2. Click **Sign up** (top-right corner)
3. Fill in:
   - Username (e.g., `johnsmith`)
   - Email address
   - Password
4. Complete the verification process
5. Verify your email address

---

### 📦 Step 2: Create New Repository

1. After logging in, click the **+** icon in the top-right corner
2. Select **New repository**
3. Fill in the form:
   - **Repository name**: `luomas-website` (exact name recommended)
   - **Description**: `Luomas Power Bank Official Website`
   - **Public/Private**: Select **Public** (required for GitHub Pages)
   - **Initialize with README**: **Uncheck** this option
4. Click **Create repository**

---

### 📤 Step 3: Upload Website Files

1. On your repository page, you'll see "Quick setup"
2. Click the link that says **uploading an existing file**
3. On the upload page:
   - Click **Choose your files** or drag-and-drop files
   - Select all these files from `d:\luomas\luomas-en\`:
     - `index.html`
     - `products.html`
     - `rd.html`
     - `company.html`
     - `service.html`
     - `news.html`
     - `careers.html`
     - `team.html`
4. In the "Commit changes" section:
   - Write a commit message: `Initial website upload`
   - Keep "Commit directly to the main branch" selected
5. Click **Commit changes**

---

### 🌐 Step 4: Enable GitHub Pages

1. Go to your repository homepage
2. Click **Settings** (gear icon, top-right)
3. In the left sidebar, scroll down and click **Pages**
4. Under "Build and deployment":
   - **Source**: Select **Deploy from a branch**
   - **Branch**: Select `main` (default)
   - **Folder**: Select `/ (root)`
5. Click **Save**

---

### ✅ Step 5: Access Your Live Website

1. After saving, wait **1-2 minutes** for deployment
2. Refresh the Pages settings page
3. You'll see a green banner with your URL:
   ```
   Your site is live at https://YOUR_USERNAME.github.io/luomas-website/
   ```

**Example:** If your GitHub username is `techmaster2024`, your URL will be:
```
https://techmaster2024.github.io/luomas-website/
```

---

### 🔗 Final URLs After Deployment

| Page | URL |
|------|-----|
| Homepage | `https://username.github.io/luomas-website/` |
| Products | `https://username.github.io/luomas-website/products.html` |
| R&D | `https://username.github.io/luomas-website/rd.html` |
| Company | `https://username.github.io/luomas-website/company.html` |
| Support | `https://username.github.io/luomas-website/service.html` |
| News | `https://username.github.io/luomas-website/news.html` |
| Careers | `https://username.github.io/luomas-website/careers.html` |
| Team | `https://username.github.io/luomas-website/team.html` |

---

### 🧪 Verify Your Website

After deployment, test these items:

- ✅ All pages load correctly
- ✅ Navigation menu works
- ✅ Mobile menu toggles (on small screens)
- ✅ Images load properly
- ✅ Interactive features work (product filters, FAQ accordion)
- ✅ No broken links

---

### ⚠️ Troubleshooting

**Issue: Site not loading**
- Wait 2-3 minutes and refresh
- Check the **Actions** tab in your repository for build errors
- Ensure you selected the `main` branch and `/ (root)` folder

**Issue: Images not showing**
- Clear browser cache (Ctrl+Shift+Delete)
- Hard refresh the page (Ctrl+F5)

**Issue: CSS styles not applying**
- Verify all HTML files have the Font Awesome CDN link
- Check for typos in file names

---

### 📞 Need Help?

If you encounter any issues during deployment:
1. Double-check all steps above
2. Review GitHub Pages documentation: https://docs.github.com/en/pages
3. Contact your team member Zhang Yiming (QA & Operations)

---

**🎉 Congratulations!** Your website is now live and accessible to everyone!

---

*Last Updated: May 2024*
*Version: 1.0*
