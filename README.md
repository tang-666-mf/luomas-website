# ROMOSS Power Bank Official Website

## 🌐 Project Overview

This is the official English website for ROMOSS Power Bank, a leading global provider of high-quality mobile charging solutions.

### Website Features

- ✅ **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- ✅ **Modern UI/UX** - Clean, professional design with smooth animations
- ✅ **Interactive Features** - Product filtering, FAQ accordion, mobile navigation
- ✅ **SEO Optimized** - Proper meta tags and semantic HTML structure
- ✅ **Fast Loading** - Optimized images and minimal dependencies

---

## 📂 Website Structure

```
romoss-en/
├── index.html          # Homepage - Brand showcase and core features
├── products.html       # Our Products - Full product catalog with filtering
├── rd.html             # R&D - Technology innovation and patents
├── company.html        # Company Profile - History, values, and global presence
├── service.html        # After-sale Service - Support, FAQ, and service centers
├── news.html           # News & Events - Latest news and upcoming events
├── careers.html        # Join Us - Job openings and company culture
└── team.html           # Our Team - 6 core team members and responsibilities
```

---

## 🚀 Local Access Guide

### Method 1: Direct File Opening (Easiest)

1. Navigate to the website folder:
   ```
   d:\luomas\romoss-en\
   ```

2. Double-click `index.html` to open it in your default browser

3. Navigate between pages using the menu links

**Pros:** No setup required, works immediately  
**Cons:** Some interactive features may have limitations

---

### Method 2: Python HTTP Server (Recommended)

1. Open PowerShell or Command Prompt

2. Navigate to the website folder:
   ```powershell
   cd d:\luomas\romoss-en
   ```

3. Start the local server:
   ```powershell
   python -m http.server 8000
   ```

4. Open your browser and visit:
   ```
   http://localhost:8000
   ```

5. To stop the server, press `Ctrl + C`

**Pros:** Full functionality, simulates real server environment  
**Cons:** Requires Python installed

---

### Method 3: VS Code Live Server

1. Install the "Live Server" extension in VS Code

2. Right-click on `index.html`

3. Select "Open with Live Server"

4. The website will open automatically at:
   ```
   http://127.0.0.1:5500/index.html
   ```

**Pros:** Auto-reload on file changes, easy to use  
**Cons:** Requires VS Code and extension

---

## 🌍 GitHub Pages Deployment (Free Public URL)

### Step 1: Create GitHub Account

1. Visit [https://github.com](https://github.com)
2. Click "Sign up" and create a free account
3. Verify your email address

---

### Step 2: Create New Repository

1. Click the **+** icon in the top-right corner
2. Select **"New repository"**
3. Fill in the repository details:
   - **Repository name**: `romoss-website` (or any name you prefer)
   - **Description**: `ROMOSS Power Bank Official Website`
   - **Public/Private**: Select **Public** (required for GitHub Pages)
   - **Initialize with README**: Uncheck this box
4. Click **"Create repository"**

---

### Step 3: Upload Website Files

#### Option A: Using GitHub Web Interface (Easier)

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop all HTML files from `d:\luomas\romoss-en\`:
   - `index.html`
   - `products.html`
   - `rd.html`
   - `company.html`
   - `service.html`
   - `news.html`
   - `careers.html`
   - `team.html`
3. Add a commit message: `Initial website upload`
4. Click **"Commit changes"**

#### Option B: Using Git Command Line (Advanced)

1. Open PowerShell in the website folder:
   ```powershell
   cd d:\luomas\romoss-en
   ```

2. Initialize Git repository:
   ```powershell
   git init
   ```

3. Add all files:
   ```powershell
   git add .
   ```

4. Commit changes:
   ```powershell
   git commit -m "Initial website upload"
   ```

5. Add remote repository (replace with your URL):
   ```powershell
   git remote add origin https://github.com/YOUR_USERNAME/romoss-website.git
   ```

6. Push to GitHub:
   ```powershell
   git branch -M main
   git push -u origin main
   ```

---

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (gear icon in the top-right)
3. In the left sidebar, click **Pages**
4. Under **Build and deployment**, click **Source**
5. Select **Deploy from a branch**
6. Select **main** branch and **/(root)** folder
7. Click **Save**

---

### Step 5: Access Your Website

1. Wait 1-2 minutes for deployment to complete
2. Your website will be available at:
   ```
   https://YOUR_USERNAME.github.io/romoss-website/
   ```

**Example:** If your GitHub username is `johnsmith`, your URL will be:
```
https://johnsmith.github.io/romoss-website/
```

3. You can now share this URL with anyone!

---

## 📱 Testing Your Website

### Desktop Testing

- Test on Chrome, Firefox, Safari, and Edge
- Check all pages load correctly
- Verify navigation links work
- Test interactive features (product filters, FAQ, etc.)

### Mobile Testing

1. Open browser DevTools (F12)
2. Click the device toolbar icon (or press Ctrl+Shift+M)
3. Test different device sizes:
   - iPhone 12/13/14
   - Samsung Galaxy
   - iPad
   - Desktop

### Responsive Testing Checklist

- ✅ Navigation menu works on mobile
- ✅ Images resize correctly
- ✅ Text is readable on small screens
- ✅ Buttons are easily tappable
- ✅ No horizontal scrolling

---

## 🎨 Customization Guide

### Changing Brand Colors

Find and replace these color codes in all HTML files:

- **Primary Blue**: `#3b82f6`
- **Secondary Cyan**: `#06b6d4`
- **Dark Background**: `#0f172a`
- **Light Background**: `#f8fafc`

### Updating Team Information

Edit `team.html` to update team member details:

```html
<div class="team-card">
    <div class="avatar">INITIALS</div>
    <h3>Full Name</h3>
    <div class="role">Job Title</div>
    <p>Description of responsibilities</p>
</div>
```

### Modifying Product Information

Edit `products.html` to update product details:

```html
<div class="product-card" data-category="category">
    <img src="image-url" alt="Product Name">
    <div class="product-info">
        <span class="badge">Category</span>
        <h3>Product Name</h3>
        <p>Product description</p>
        <div class="specs">
            <!-- Product specifications -->
        </div>
        <div class="product-price">$XX.XX</div>
    </div>
</div>
```

---

## 🔧 Troubleshooting

### Issue: Images not loading

**Solution:** Ensure you have an internet connection. Images are loaded from Unsplash CDN.

### Issue: Styles not applying

**Solution:** Clear your browser cache (Ctrl+Shift+Delete) and reload the page.

### Issue: GitHub Pages not updating

**Solution:**
1. Check the Actions tab in your GitHub repository
2. Wait for the deployment to complete (usually 1-2 minutes)
3. Clear your browser cache
4. Hard refresh the page (Ctrl+F5)

### Issue: Mobile menu not working

**Solution:** Ensure JavaScript is enabled in your browser settings.

---

## 📞 Support

For questions or issues:
- Email: support@romoss.com
- Phone: +1-800-ROMOSS
- Live Chat: www.romoss.com/chat

---

## 📄 License

© 2024 ROMOSS Technology Co., Ltd. All rights reserved.

---

## 🎓 Academic Use

This website was created as a course project for web development coursework. It demonstrates:
- Responsive web design principles
- Modern HTML5 and CSS3 techniques
- User experience best practices
- International web standards

**Course:** Web Development Fundamentals  
**Instructor:** [Instructor Name]  
**Semester:** Spring 2024  
**Grade:** [Pending]

---

**Last Updated:** January 2024  
**Version:** 1.0.0