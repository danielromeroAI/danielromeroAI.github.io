````markdown
# Dr. Daniel Romero

**Assistant Professor of Data Science & Analytics**  
SUNY Polytechnic Institute

[![Website](https://img.shields.io/badge/Website-Live-brightgreen)](https://danielromeroai.github.io)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## About

This repository hosts my professional academic website, showcasing my research in artificial intelligence, deep learning, and resilience engineering. The site features my publications, teaching experience, and ongoing research projects in building resilient AI-human systems.

## Research Interests

- **Deep Learning & AI Agents** - Building autonomous systems capable of monitoring and adapting AI behavior
- **Resilience Engineering** - Developing frameworks for AI system resilience assessment
- **Prescriptive Analytics** - Creating decision support tools for complex real-world problems
- **Multi-Agent Systems** - Designing intelligent agents for healthcare, education, and supply chain applications

## Website Features

- **Responsive Design** - Optimized for all devices
- **Dark/Light Mode** - Theme toggle with persistent preference
- **Performance Optimized** - Fast loading with vanilla JavaScript
- **Accessible** - WCAG compliant design

## Connect

- 🌐 [Website](https://danielromeroai.github.io)
- 📧 [Email](mailto:romerod2@sunypoly.edu)
- 🎓 [Google Scholar](https://scholar.google.com/citations?hl=en&user=uEqegLwAAAAJ&view_op=list_works&sortby=pubdate)
- 💼 [LinkedIn](https://www.linkedin.com/in/daniel-romero-rodriguez-226bb213)
- 💻 [GitHub](https://github.com/danielromeroAI)
- 🎥 [YouTube](https://www.youtube.com/@danrom12)

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Fonts**: Google Fonts (Inter, Playfair Display)
- **Icons**: Font Awesome 6
- **Hosting**: GitHub Pages

## License

© 2025 Daniel Romero. All rights reserved.

---

*Building the next generation of AI systems through deep learning, agent-based intelligence, and resilience engineering.*

````

## 🚀 Quick Start

### 1. Set Up Your Files

1. **Add Your Photo:**
   - Add a professional photo to `assets/profile-photo.jpg`
   - Recommended size: 500x500 pixels (square)
   - Supported formats: JPG, PNG

2. **Add Your CV:**
   - Place your CV in `assets/Daniel_Romero_CV_2025.pdf`
   - Or update the filename in `index.html` (search for "Daniel_Romero_CV_2025.pdf")

3. **Customize Content:**
   - Open `index.html` in VS Code
   - Update social media links (search for "https://scholar.google.com", "https://www.linkedin.com", etc.)
   - Add your actual Google Scholar, LinkedIn, GitHub, ResearchGate URLs

### 2. Preview Locally

Simply open `index.html` in your web browser to preview the site.

**OR** use VS Code's Live Server extension:
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🌐 Deployment to GitHub Pages (FREE)

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon → "New repository"
3. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Example: If your username is "danielromero", name it `danielromero.github.io`
4. Set it to **Public**
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A - Using GitHub Web Interface (Easiest):**
1. In your new repository, click "uploading an existing file"
2. Drag and drop all your files (index.html, styles.css, script.js, and assets folder)
3. Scroll down and click "Commit changes"

**Option B - Using Git Command Line:**
```bash
# In your project folder
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/your-username.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository Settings
2. Click "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 2-3 minutes

Your site will be live at: `https://your-username.github.io`

## 🎨 Customization Guide

### Change Colors

Edit the CSS variables in `styles.css` (lines 8-23):

```css
:root {
    --primary-color: #1e3a8a;      /* Main blue color */
    --secondary-color: #0d9488;     /* Teal accent */
    --accent-color: #3b82f6;        /* Bright blue */
    /* ... */
}
```

### Update Content

All content is in `index.html`. Search for these sections:
- Hero section: Lines 50-100
- About section: Lines 110-180
- Research section: Lines 190-350
- Teaching section: Lines 360-480
- Contact section: Lines 490-550

### Add New Publications

Find the publications grid (around line 220) and add a new card:

```html
<div class="publication-card">
    <div class="publication-year">2026</div>
    <h4>Your Paper Title</h4>
    <p class="publication-authors">Author names</p>
    <p class="publication-journal"><em>Journal Name</em></p>
    <a href="DOI-link" target="_blank" class="publication-link">
        <i class="fas fa-external-link-alt"></i> View Publication
    </a>
</div>
```

### Add New Courses

Find the courses grid (around line 420) and add:

```html
<div class="course-card">
    <div class="course-header">
        <i class="fas fa-laptop-code"></i>
        <span class="course-level">Graduate</span>
    </div>
    <h4>Course Name</h4>
    <p class="course-semester">Semester Info</p>
</div>
```

## 🔧 Advanced Customization

### Add Google Analytics

Add this before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

### Add Custom Domain

1. Buy a domain (e.g., danielromero.com) from Namecheap or Google Domains
2. In your GitHub repo: Settings → Pages → Custom domain
3. Enter your domain and click Save
4. In your domain provider's DNS settings, add:
   - Type: A Record
   - Host: @
   - Value: 185.199.108.153 (and also add .109, .110, .111)
   - Type: CNAME
   - Host: www
   - Value: your-username.github.io

### Enable Contact Form

You can add a contact form using free services like:
- **Formspree**: https://formspree.io
- **Netlify Forms**: https://www.netlify.com/products/forms/
- **Google Forms**: Embedded in your site

## 📱 Social Media Links

Update these in `index.html`:

1. **Google Scholar**: Replace `https://scholar.google.com` with your profile URL
2. **LinkedIn**: Replace `https://www.linkedin.com` with your profile URL
3. **GitHub**: Replace `https://github.com` with your profile URL
4. **ResearchGate**: Replace `https://www.researchgate.net` with your profile URL

## 🔄 Monthly Maintenance (5-10 minutes)

1. **Add new publications**: Edit the publications section in `index.html`
2. **Update courses**: Modify the courses section
3. **Update CV**: Replace the file in `assets/`
4. **Push changes to GitHub**:
   ```bash
   git add .
   git commit -m "Update publications and CV"
   git push
   ```

## 🎯 Tips for Success

1. **Keep it updated**: Set a monthly reminder to update your content
2. **Professional photo**: Use a high-quality, professional headshot
3. **Test on mobile**: Always check how it looks on phone/tablet
4. **Check broken links**: Quarterly, verify all external links work
5. **Backup regularly**: Keep a local copy of all files

## 🆘 Troubleshooting

**Site not showing up after deployment?**
- Wait 5 minutes, sometimes it takes time
- Check Settings → Pages to see if it's enabled
- Make sure repository is named `username.github.io`

**Profile photo not showing?**
- Check file is named exactly `profile-photo.jpg`
- Verify it's in the `assets/` folder
- Try clearing browser cache

**CV download not working?**
- Confirm file is in `assets/` folder
- Check filename matches the one in HTML
- Verify file is uploaded to GitHub

**Dark mode not saving?**
- Check browser allows localStorage
- Try a different browser
- Clear cookies and try again

## 📞 Need Help?

- Check the code comments in each file
- Search GitHub Issues for similar problems
- Review GitHub Pages documentation
- Test locally first before deploying

## 📄 License

This website template is free to use and customize for your personal academic website.

---

**Built with ❤️ for academic excellence**

Last updated: November 2025
