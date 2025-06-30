# Professional Nanny Resume Website

A modern, responsive one-page website template designed for nannies to showcase their professional experience and skills.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Scrolling Navigation**: Click navigation links to smoothly scroll to sections
- **Modern UI**: Clean, professional design with animations and hover effects
- **Contact Form**: Built-in contact form for potential clients
- **Mobile-Friendly**: Hamburger menu for mobile navigation
- **SEO Ready**: Proper HTML structure and meta tags

## Sections

1. **Section 1 (Home)**: Introduction and call-to-action buttons
2. **Section 2 (About)**: Personal information, skills, and statistics
3. **Section 3 (Experience)**: Education, certifications, and work experience
4. **Section 4 (Contact)**: Contact information and contact form

## Customization Guide

### 1. Personal Information
Edit the following in `index.html`:
- Replace "Your Name" with your actual name
- Update the home title and subtitle
- Modify the about section content
- Update statistics (years of experience, families served, etc.)

### 2. Contact Information
In the contact section, update:
- Email address
- Phone number
- Location (City, State)
- Social media links

### 3. Experience & Qualifications
Update the experience cards with:
- Your actual education details
- Real certifications
- Previous work experience
- Skills and qualifications

### 4. Profile Picture
Replace the placeholder icon in the home section:
```html
<!-- Replace this -->
<div class="profile-placeholder">
    <i class="fas fa-user-circle"></i>
</div>

<!-- With your actual image -->
<div class="home-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-image">
</div>
```

### 5. Colors and Styling
The website uses a purple/indigo color scheme. To change colors, edit the CSS variables in `styles.css`:
- Primary color: `#4f46e5`
- Secondary color: `#3730a3`
- Background colors: `#f8fafc`

## Deployment Options

### Option 1: GitHub Pages (Recommended)
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. You can connect your GitHub repository for automatic deployments

### Option 3: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

### Option 4: Traditional Web Hosting
Upload all files to your web hosting provider's public_html directory.

## File Structure
```
your-nanny-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance
- Optimized for fast loading
- Minimal external dependencies
- Responsive images
- Efficient CSS and JavaScript

## Customization Tips

1. **Add Your Photo**: Replace the placeholder with your professional photo
2. **Update Content**: Make all content personal and specific to your experience
3. **Add References**: Consider adding a testimonials section
4. **Include Certificates**: Add images of your certifications
5. **Custom Domain**: Purchase a custom domain for a more professional look

## Support
This template is designed to be easy to customize. If you need help with deployment or customization, refer to the documentation of your chosen hosting platform.

## License
This template is free to use for personal and commercial projects. 