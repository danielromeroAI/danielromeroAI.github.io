# 🚀 QUICK START GUIDE

Follow these 3 simple steps to get your website online in under 10 minutes!

## ✅ Step 1: Customize Your Content (5 minutes)

### 1.1 Add Your Files
- [ ] Add your photo to `assets/profile-photo.jpg`
- [ ] Add your CV to `assets/Daniel_Romero_CV_2025.pdf`

### 1.2 Update Social Links (Open index.html and search for these)
- [ ] Line ~75: Google Scholar URL
- [ ] Line ~76: LinkedIn URL  
- [ ] Line ~77: GitHub URL
- [ ] Line ~478: ResearchGate URL

Replace the placeholder URLs (like `https://scholar.google.com`) with your actual profile URLs.

### 1.3 Test Locally
- [ ] Open `index.html` in your browser to preview
- [ ] Click all links to make sure they work
- [ ] Test dark/light mode toggle

## ✅ Step 2: Deploy to GitHub (3 minutes)

### Option A: Using GitHub Website (Easiest)
1. Go to https://github.com and sign in
2. Click "+" → "New repository"
3. Name it: `yourusername.github.io` (use YOUR actual GitHub username)
4. Make it Public → Create repository
5. Click "uploading an existing file"
6. Drag ALL your files into the upload area
7. Click "Commit changes"

### Option B: Using Git Command Line
```bash
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

## ✅ Step 3: Enable GitHub Pages (1 minute)

1. In your repository, click "Settings"
2. Click "Pages" in the left menu
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 2-3 minutes ⏰

**Done! 🎉** Your site is live at: `https://yourusername.github.io`

---

## 🎨 Quick Customizations

### Change the Color Scheme
Edit `styles.css` lines 8-12:
```css
--primary-color: #1e3a8a;    /* Change this blue */
--secondary-color: #0d9488;   /* Change this teal */
```

### Add a New Publication
Copy this template into the publications section (~line 220 in index.html):
```html
<div class="publication-card">
    <div class="publication-year">2026</div>
    <h4>Your Paper Title Here</h4>
    <p class="publication-authors">Authors</p>
    <p class="publication-journal"><em>Journal Name</em></p>
    <a href="your-doi-link" class="publication-link">
        <i class="fas fa-external-link-alt"></i> View Publication
    </a>
</div>
```

### Update Your Info Later
```bash
# Make changes to your files in VS Code
git add .
git commit -m "Updated publications"
git push
# Site updates automatically in 1-2 minutes!
```

---

## 🆘 Common Issues

**Q: Site not showing after 3 minutes?**
- A: Check repo name is exactly `yourusername.github.io`
- A: Go to Settings → Pages and verify it's enabled

**Q: Photo not displaying?**
- A: Make sure filename is exactly `profile-photo.jpg` (lowercase)
- A: Check it's in the `assets` folder

**Q: Dark mode not working?**
- A: Try a different browser or clear cache
- A: Check browser console for JavaScript errors (F12)

---

## 📞 Need More Help?

Read the full `README.md` for detailed instructions on:
- Adding a custom domain
- Google Analytics integration
- Contact form setup
- Advanced customizations

---

**You've got this! 💪**

Your professional academic website will be live in minutes.
