# Cybersecurity Professional Portfolio

A modern, professional portfolio website designed for cybersecurity professionals, red teamers, and penetration testers. Features a dark theme with green accent colors, terminal-style elements, and smooth animations.

## 🚀 Features

- **Modern Dark Theme** - Professional dark color scheme perfect for cybersecurity professionals
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Elements** - Smooth scrolling, animations, and hover effects
- **Terminal Aesthetic** - Terminal-style components that resonate with security professionals
- **GitHub Pages Ready** - Optimized for easy deployment on GitHub Pages

## 📋 Sections

1. **Hero Section** - Eye-catching introduction with terminal animation
2. **About** - Personal information and expertise areas
3. **Skills** - Technical skills, tools, and certifications
4. **Projects** - Showcase of your security projects and research
5. **Contact** - Social links and contact information

## 🛠️ Customization

### Personal Information

1. **Name and Title** - Edit the hero section in `index.html`:
   ```html
   <span class="name">Your Name</span>
   <span class="title">Red Teamer & Penetration Tester</span>
   ```

2. **About Section** - Update the about text in `index.html` to reflect your experience

3. **Skills** - Modify the skills section to match your expertise:
   - Update skill percentages
   - Add/remove tools and technologies
   - Update certifications

4. **Projects** - Replace the example projects with your own:
   - Update project titles and descriptions
   - Add your GitHub repository links
   - Update project tags

5. **Contact Information** - Update contact links:
   ```html
   <a href="mailto:your.email@example.com">...</a>
   <a href="https://linkedin.com/in/yourprofile">...</a>
   <a href="https://github.com/yourusername">...</a>
   <a href="https://twitter.com/yourusername">...</a>
   ```

6. **Profile Photo** - Replace the placeholder SVG in the about section with your actual photo:
   ```html
   <div class="image-placeholder">
       <img src="path/to/your/photo.jpg" alt="Your Name">
   </div>
   ```

### Color Scheme

You can customize colors in `styles.css` by modifying CSS variables:
```css
:root {
    --accent-green: #00ff41;
    --accent-red: #ff0040;
    --accent-blue: #00d4ff;
    /* ... */
}
```

## 📦 Hosting on GitHub Pages

### Method 1: Using GitHub Web Interface (Easiest)

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon in the top right, then "New repository"
   - Name it `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - Make it public
   - Click "Create repository"

2. **Upload Your Files**
   - In your new repository, click "uploading an existing file"
   - Drag and drop all your portfolio files (index.html, styles.css, script.js)
   - Add a commit message like "Initial portfolio upload"
   - Click "Commit changes"

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
   - Wait a few minutes for GitHub to build your site

4. **Access Your Site**
   - Your portfolio will be available at: `https://yourusername.github.io`

### Method 2: Using Git Command Line

1. **Initialize Git Repository**
   ```bash
   cd /home/osboxes/Videos/portifolio
   git init
   ```

2. **Add All Files**
   ```bash
   git add .
   ```

3. **Create Initial Commit**
   ```bash
   git commit -m "Initial portfolio commit"
   ```

4. **Add GitHub Remote**
   ```bash
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   ```
   (Replace `yourusername` with your actual GitHub username)

5. **Push to GitHub**
   ```bash
   git branch -M main
   git push -u origin main
   ```

6. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Settings → Pages
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

### Method 3: Using Custom Domain (Optional)

If you have a custom domain:

1. **Add CNAME File**
   - Create a file named `CNAME` (no extension) in your repository root
   - Add your domain name inside: `yourdomain.com`

2. **Configure DNS**
   - Add a CNAME record in your DNS settings pointing to `yourusername.github.io`

3. **Update GitHub Settings**
   - In repository Settings → Pages, add your custom domain

## 🔧 Troubleshooting

### Site Not Loading
- Wait 5-10 minutes after enabling GitHub Pages (first deployment takes time)
- Check repository settings to ensure Pages is enabled
- Verify you're using the correct URL format: `username.github.io`

### Styles Not Loading
- Ensure all file paths are correct (case-sensitive on Linux)
- Check that `styles.css` is in the same directory as `index.html`
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)

### Images Not Showing
- Use relative paths for images: `images/photo.jpg`
- Ensure image files are committed to the repository
- Check file names are correct (case-sensitive)

## 📝 File Structure

```
portifolio/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Design Features

- **Terminal Aesthetic**: Terminal-style components with green text
- **Grid Background**: Animated grid overlay in hero section
- **Smooth Animations**: Scroll-triggered animations and transitions
- **Responsive Navigation**: Mobile-friendly hamburger menu
- **Skill Progress Bars**: Animated progress bars for skills
- **Project Cards**: Hover effects on project cards
- **Dark Theme**: Professional dark color scheme

## 📄 License

This portfolio template is free to use and modify for personal or commercial projects.

## 🤝 Contributing

Feel free to fork this repository and customize it for your own portfolio!

## 📧 Support

If you encounter any issues or have questions about hosting on GitHub Pages, refer to the [GitHub Pages Documentation](https://docs.github.com/en/pages).

---

**Note**: Remember to update all placeholder content (name, email, social links, projects) with your actual information before deploying!

