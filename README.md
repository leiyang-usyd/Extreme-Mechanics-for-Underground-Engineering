# Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations and mobile-friendly navigation.

## Features

- 🎨 Modern, responsive design
- 📱 Mobile-friendly navigation
- ✨ Smooth animations and transitions
- 📧 Contact form with validation
- 🎯 Portfolio showcase
- 📊 Skills and statistics display
- 🔗 Social media integration

## File Structure

```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Quick Start

1. **Local Development**
   ```bash
   # Open index.html in your browser
   open index.html
   ```

2. **Customize Content**
   - Edit `index.html` to update your personal information
   - Modify `styles.css` to change colors and styling
   - Update `script.js` for custom functionality

## Deployment Options

### 1. GitHub Pages (Free & Easy)

1. **Create a GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click "Settings" → "Pages"
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Your site will be available at `https://yourusername.github.io/your-repo-name`

### 2. Netlify (Free & Fast)

1. **Drag & Drop Method**
   - Go to [netlify.com](https://netlify.com)
   - Sign up/Login
   - Drag your `personal-website` folder to the deploy area
   - Your site will be live instantly

2. **GitHub Integration**
   - Connect your GitHub repository
   - Netlify will auto-deploy on every push

### 3. Vercel (Free & Modern)

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```

### 4. Firebase Hosting (Free)

1. **Install Firebase CLI**
   ```bash
   npm install -g firebase-tools
   ```

2. **Initialize and Deploy**
   ```bash
   firebase login
   firebase init hosting
   firebase deploy
   ```

### 5. Traditional Web Hosting

Upload files to any web hosting service:
- cPanel hosting
- AWS S3 + CloudFront
- DigitalOcean App Platform
- Heroku (with static buildpack)

## Customization Guide

### Update Personal Information

1. **Name and Title**
   ```html
   <!-- In index.html -->
   <title>Your Name - Personal Website</title>
   <div class="nav-logo">
       <a href="#home">Your Name</a>
   </div>
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   ```

2. **Contact Information**
   ```html
   <!-- Update contact details -->
   <p>your.email@example.com</p>
   <p>+1 (555) 123-4567</p>
   <p>San Francisco, CA</p>
   ```

3. **Social Media Links**
   ```html
   <!-- Update social media URLs -->
   <a href="https://github.com/yourusername" class="social-link">
   <a href="https://linkedin.com/in/yourusername" class="social-link">
   ```

### Change Colors

Edit `styles.css` to customize the color scheme:

```css
/* Primary colors */
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --accent-color: #7c3aed;
}
```

### Add Portfolio Projects

1. **Duplicate portfolio item structure**
2. **Update project details**
3. **Add project images** (replace placeholder icons)

### Skills and Technologies

Update the skills section in `index.html`:

```html
<div class="skill-tags">
    <span class="skill-tag">Your Skill 1</span>
    <span class="skill-tag">Your Skill 2</span>
    <!-- Add more skills -->
</div>
```

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Performance Tips

1. **Optimize Images**
   - Use WebP format when possible
   - Compress images before uploading
   - Consider lazy loading for large images

2. **Minimize HTTP Requests**
   - Combine CSS files
   - Use CDN for external libraries

3. **Enable Compression**
   - Enable Gzip compression on your server
   - Use a CDN for faster delivery

## SEO Optimization

1. **Meta Tags**
   ```html
   <meta name="description" content="Your personal website description">
   <meta name="keywords" content="web developer, designer, portfolio">
   ```

2. **Open Graph Tags**
   ```html
   <meta property="og:title" content="Your Name - Personal Website">
   <meta property="og:description" content="Your description">
   <meta property="og:image" content="path/to/your/image.jpg">
   ```

## Troubleshooting

### Common Issues

1. **Images not loading**
   - Check file paths
   - Ensure images are in the correct directory

2. **Contact form not working**
   - The current form shows a demo message
   - For real functionality, integrate with a service like Formspree or Netlify Forms

3. **Mobile menu not working**
   - Check if JavaScript is enabled
   - Verify script.js is properly linked

### Performance Issues

1. **Slow loading**
   - Optimize images
   - Minify CSS/JS files
   - Use a CDN

2. **Layout issues**
   - Test on different screen sizes
   - Check browser developer tools

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help with deployment or customization, feel free to:
- Open an issue on GitHub
- Check the documentation of your chosen hosting platform
- Consult web development communities

---

**Happy coding! 🚀** 