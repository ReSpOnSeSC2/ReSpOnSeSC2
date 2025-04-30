# Personal Portfolio Website

A responsive portfolio website showcasing personal web projects and social media profiles. This single-page website is designed to highlight your professional work and online presence in a clean, modern interface.

## 📋 Overview

This portfolio includes:
- Professional websites showcase (TriuneHealth and SaveLodge)
- Social media profiles (TikTok, Twitch, and YouTube)
- Responsive design that works on mobile, tablet, and desktop devices
- Clean, modern UI with hover animations

## 🗂️ Repository Structure

```
username.github.io/
├── index.html              # Main website HTML
├── README.md               # This documentation file
├── images/                 # Image assets directory
│   ├── triunehealth.jpg    # Screenshot of TriuneHealth website
│   └── savelodge.jpg       # Screenshot of SaveLodge website
└── .gitignore              # Optional: Git ignore file
```

## 🛠️ Technical Details

- **HTML5**: Semantic markup for better accessibility and SEO
- **CSS3**: Modern styling with flexbox and CSS grid for layouts
- **Font Awesome**: Icon library for social media icons
- **Responsive Design**: Media queries ensure the site looks good on all devices
- **No JavaScript**: Simple design that works without JavaScript dependencies
- **GitHub Pages**: Hosting platform with continuous deployment

## 🚀 Setup and Deployment

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```

2. Open `index.html` in your browser to preview the site

3. Make desired changes to the HTML and test locally before committing

### Getting Website Screenshots

1. Visit your websites (triunehealth.io and savelodge.com)
2. Take screenshots:
   - **Windows**: Use Snipping Tool or press `Win+Shift+S`
   - **macOS**: Press `Cmd+Shift+4` or use Screenshot app
   - **Browser Extensions**: Use extensions like "Full Page Screenshot" for complete page captures
3. Crop and resize images to 1200×600px (2:1 ratio) for consistency
4. Save as JPG or PNG format with descriptive filenames

### GitHub Pages Deployment

1. Create a repository named `yourusername.github.io` (replace with your GitHub username)
2. Push your code to the repository:
   ```bash
   git add .
   git commit -m "Initial portfolio website"
   git push origin main
   ```
3. Enable GitHub Pages in repository settings:
   - Go to Settings > Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Save
4. Your site will be available at `https://yourusername.github.io` after a few minutes

## 🔧 Customization Guide

### Changing Content

Edit `index.html` to modify:

- **Header section**: Update your name, title, and tagline
- **Projects section**: Modify website descriptions and links
- **Social Media section**: Update usernames and links
- **Footer**: Update copyright information and year

### Styling Modifications

The CSS is embedded in the `<style>` section of `index.html`. Key variables:

```css
:root {
    --primary: #2563eb;    /* Primary blue color */
    --dark: #111827;       /* Dark background color */
    --light: #f3f4f6;      /* Light background color */
    --accent: #7c3aed;     /* Purple accent color */
}
```

Modify these variables to change the color scheme throughout the site.

### Adding New Projects

To add a new project, copy and paste this template into the `projects-grid` section:

```html
<div class="project-card">
    <img src="images/project-name.jpg" alt="Project Name" class="project-img">
    <div class="project-content">
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">Description of your project.</p>
        <a href="https://www.example.com" target="_blank" class="project-link">Visit Website</a>
    </div>
</div>
```

### Adding New Social Profiles

To add a new social profile, copy and paste this template into the `social-grid` section:

```html
<div class="social-card">
    <div class="social-icon">
        <i class="fab fa-[platform-name]"></i>
    </div>
    <h3 class="social-name">Platform Name</h3>
    <p class="social-username">@username</p>
    <a href="https://www.platform.com/username" target="_blank" class="social-link">Follow Me</a>
</div>
```

Replace `[platform-name]` with the appropriate Font Awesome icon name.

## 📱 Maintenance

1. **Regular Updates**: Keep project information and screenshots current
2. **Image Optimization**: Compress images before uploading to improve load times
3. **Link Checking**: Periodically verify all links are working correctly
4. **Browser Testing**: Test in multiple browsers to ensure compatibility

## 📄 License

This project is available for personal use. You may modify and adapt it for your own portfolio.

## 🔗 Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [HTML5 Validator](https://validator.w3.org/)
- [CSS3 Validator](https://jigsaw.w3.org/css-validator/)
