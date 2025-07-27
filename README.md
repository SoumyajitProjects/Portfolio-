# Netflix-Style Portfolio Website

A modern, responsive portfolio website inspired by Netflix's UI design. This portfolio showcases your personal information, experience, technologies, projects, and contact details in an elegant dark theme.

## Features

- 🎬 Netflix-inspired dark theme
- 📱 Fully responsive design
- ⚡ Smooth scrolling navigation
- 🎨 Animated elements on scroll
- 💼 Professional timeline layout
- 🛠️ Technology showcase
- 📋 Project gallery with hover effects
- 📧 Contact form
- 🔗 Social media links

## Structure

```
netflix-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # All styling
├── js/
│   └── script.js      # Interactive functionality
├── images/            # Your images (add your own)
├── assets/            # Additional assets
└── README.md          # This file
```

## Customization Guide

### 1. Personal Information

Replace the placeholder content in `index.html`:

- **Line 37**: Update `<h1 class="hero-title">Your Name</h1>`
- **Line 38**: Update `<h2 class="hero-subtitle">Full Stack Developer</h2>`
- **Line 40-42**: Update the hero description
- **Lines 67-70**: Update the "About Me" section
- **Lines 88-91**: Update your statistics (years, projects, technologies)

### 2. Profile Image

- Replace the placeholder image URL in the About section (line 94)
- Add your actual profile photo to the `images/` folder
- Update the `src` attribute: `<img src="images/your-photo.jpg" alt="Your Name">`

### 3. Experience Timeline

Update the experience section (lines 104-170):
- Change company names, job titles, and dates
- Update job descriptions
- Modify the technology tags for each role

### 4. Technologies

Update the technologies section (lines 176-262):
- Add or remove technology categories
- Update technology names and icons
- Icons use Font Awesome classes (e.g., `fab fa-react`)

### 5. Projects

Update the projects section (lines 268-380):
- Replace project titles and descriptions
- Update project images (use your actual project screenshots)
- Change project links to your live demos and GitHub repos
- Update technology tags for each project

### 6. Contact Information

Update contact details (lines 392-413):
- Replace email, phone, and location
- Update social media links
- Add your actual social media profiles

### 7. Colors and Styling

The main colors used are:
- Primary Red: `#e50914` (Netflix red)
- Background: `#141414` (Dark)
- Cards: `#222222` (Medium dark)
- Text: `#ffffff` (White)
- Secondary text: `#cccccc` (Light gray)

To change colors, update the CSS variables in `style.css`.

### 8. Images

Replace placeholder images:
- Hero background: Update the URL in CSS line 85
- Project images: Replace placeholder URLs with your project screenshots
- Profile image: Add your photo to the images folder

### 9. Fonts

The website uses system fonts for better performance:
- Primary: 'Helvetica Neue', Arial, sans-serif

To use custom fonts, add Google Fonts links to the HTML head section.

## Adding Your Content

### Add New Projects

1. Copy a project card div (lines 270-297)
2. Update the image, title, description, and links
3. Add appropriate technology tags

### Add New Technologies

1. Add a new tech-item div in the appropriate category
2. Use Font Awesome icons or custom icons
3. Update the technology name

### Add New Experience

1. Copy a timeline-item div (lines 108-125)
2. Update dates, company, role, and description
3. Add relevant technology tags

## Deployment

### Option 1: GitHub Pages
1. Upload files to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify
1. Drag and drop the folder to Netlify
2. Your site will be live instantly

### Option 3: Vercel
1. Import the project from GitHub
2. Deploy with one click

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Mobile Responsive

The website is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## Performance Tips

1. Optimize images before uploading
2. Use WebP format for better compression
3. Minify CSS and JavaScript for production
4. Use a CDN for better loading speeds

## License

This template is free to use for personal and commercial projects.

## Credits

- Design inspiration: Netflix
- Icons: Font Awesome
- Placeholder images: Unsplash, Placeholder.com

---

**Note**: Remember to replace all placeholder content and images with your actual information and projects!
