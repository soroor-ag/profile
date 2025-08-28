# Portfolio Website - Soroor Ag

A modern, responsive portfolio website showcasing your professional experience, projects, and skills.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Navigation**: Fixed navigation bar with smooth scrolling
- **Sections**: Home, About, Resume, Experiences, and Contact
- **Projects Showcase**: Dedicated page for displaying your projects
- **Skills Display**: Organized skills and technologies section
- **Social Links**: GitHub, LinkedIn, and email integration
- **Mobile Friendly**: Hamburger menu for mobile devices
- **Animations**: Smooth scroll animations and hover effects

## Files Structure

```
portfolio/
├── index.html          # Main homepage
├── experiences.html    # Projects and experiences page
├── styles.css         # All styling and responsive design
├── script.js          # Interactive functionality
└── README.md          # This file
```

## Quick Start

1. **Download/Clone** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting service

## Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

- **Name**: Replace "Soroor Ag" with your name
- **Title**: Update the hero subtitle
- **Description**: Modify the about section text
- **Skills**: Update the skill tags in the about section

### 2. Resume Section

Update the resume content in `index.html`:

```html
<!-- Education -->
<div class="resume-item">
    <div class="resume-item-header">
        <h4>Your Degree</h4>
        <span class="date">2020 - 2024</span>
    </div>
    <p class="institution">Your University</p>
    <p>Your coursework description</p>
</div>

<!-- Work Experience -->
<div class="resume-item">
    <div class="resume-item-header">
        <h4>Your Job Title</h4>
        <span class="date">2023 - Present</span>
    </div>
    <p class="institution">Your Company</p>
    <ul>
        <li>Your achievement 1</li>
        <li>Your achievement 2</li>
    </ul>
</div>
```

### 3. Projects

Edit the projects in `experiences.html`:

```html
<div class="project-card">
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">
            Your project description
        </p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i>
                View Code
            </a>
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i>
                Live Demo
            </a>
        </div>
    </div>
</div>
```

### 4. Social Links

Update the social links in `index.html`:

```html
<div class="social-links">
    <a href="https://github.com/YOUR_USERNAME" target="_blank" class="social-link">
        <i class="fab fa-github"></i>
        <span>GitHub</span>
    </a>
    <a href="https://linkedin.com/in/YOUR_USERNAME" target="_blank" class="social-link">
        <i class="fab fa-linkedin"></i>
        <span>LinkedIn</span>
    </a>
    <a href="mailto:your.email@example.com" class="social-link">
        <i class="fas fa-envelope"></i>
        <span>Email</span>
    </a>
</div>
```

### 5. Profile Picture

Replace the placeholder icon with your actual profile picture:

1. Add your image to the project folder
2. Replace the profile placeholder in `index.html`:

```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-photo">
</div>
```

3. Add CSS for the profile photo in `styles.css`:

```css
.profile-photo {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid rgba(255, 255, 255, 0.2);
}
```

### 6. Colors and Theme

Customize the color scheme in `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --secondary-color: #fbbf24;    /* Accent yellow color */
    --gradient-start: #667eea;     /* Gradient start */
    --gradient-end: #764ba2;       /* Gradient end */
    --text-dark: #1f2937;          /* Dark text */
    --text-light: #6b7280;         /* Light text */
    --bg-light: #f9fafb;           /* Light background */
}
```

## Deployment Options

### GitHub Pages (Free)

1. Create a new repository on GitHub
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your portfolio folder
3. Get a free subdomain or connect your custom domain

### Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Deploy automatically on every push

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- **Lazy Loading**: Images load only when needed
- **CSS Animations**: Hardware-accelerated animations
- **Optimized Fonts**: Google Fonts with display=swap
- **Minimal JavaScript**: Lightweight and fast
- **Responsive Images**: Optimized for different screen sizes

## SEO Optimization

- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## Accessibility Features

- Keyboard navigation support
- Screen reader friendly
- High contrast ratios
- Focus indicators
- Semantic HTML

## Customization Tips

1. **Keep it Simple**: Don't overcrowd with too many elements
2. **Quality Content**: Focus on showcasing your best work
3. **Regular Updates**: Keep your portfolio current
4. **Test Responsiveness**: Check on different devices
5. **Optimize Images**: Compress images for faster loading

## Support

If you need help customizing your portfolio:

1. Check the HTML comments for guidance
2. Review the CSS classes and structure
3. Test changes in small increments
4. Use browser developer tools for debugging

## License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Happy Coding! 🚀**

Your portfolio is now ready to showcase your skills and projects to the world!
