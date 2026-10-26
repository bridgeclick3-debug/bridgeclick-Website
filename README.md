# ClickBridge Corporate Website

A professional, modern, and fully responsive corporate website for ClickBridge - an IT & Digital Solutions company.

## Features

- **Premium Design**: Dark navy/blue theme with electric blue and cyan accents
- **Fully Responsive**: Mobile-first design that works on all devices
- **Smooth Animations**: Subtle entrance animations and hover effects
- **Sticky Navigation**: Professional navigation that stays accessible while scrolling
- **Contact Form**: Functional contact form with validation
- **Portfolio Section**: Filterable portfolio with category selection
- **SEO Optimized**: Proper meta tags, semantic HTML, and accessibility features
- **Modern Typography**: Clean Inter font family for professional appearance

## Website Structure

1. **Header/Navigation** - Sticky navigation with smooth scrolling
2. **Hero Section** - Powerful headline with technology visual
3. **About Section** - Company introduction with highlights
4. **Services Section** - 9 service cards with detailed descriptions
5. **Process Section** - 4-step transformation process
6. **Industries Section** - 8 industry categories served
7. **Why Choose Us** - 11 trust-building points
8. **Portfolio Section** - Filterable project showcase
9. **Capabilities Section** - Technology capabilities overview
10. **CTA Section** - Strong call-to-action
11. **Contact Section** - Contact form and information
12. **Footer** - Comprehensive footer with links

## Services Offered

1. Social Media Management
2. Website Development
3. Software & Custom Applications
4. Digital Marketing
5. Graphic Design & Branding
6. WhatsApp Business Setup
7. AI & Business Automation
8. IT Support & Maintenance
9. Cybersecurity & Red Teaming

## Industries Served

- Schools & Colleges
- Hospitals & Clinics
- Restaurants & Hotels
- Shops & Local Businesses
- Startups
- Real Estate
- NGOs
- Growing Businesses

## Customization

### Update Contact Information

Replace the placeholder contact details in `index.html`:

- `[PHONE NUMBER]` - Add your phone number
- `[WHATSAPP NUMBER]` - Add your WhatsApp number
- `[EMAIL ADDRESS]` - Add your email address
- `[BUSINESS LOCATION]` - Add your business address
- Social media links in the footer and contact section

### Update Portfolio Projects

Replace the placeholder portfolio cards in `index.html` with actual project details:

```html
<div class="portfolio-card" data-category="websites">
    <div class="portfolio-image">
        <img src="project-image.jpg" alt="Project Name">
    </div>
    <div class="portfolio-info">
        <h3>Project Name</h3>
        <p class="portfolio-industry">Industry</p>
        <p class="portfolio-services">Services provided</p>
        <button class="btn btn-outline">View Project</button>
    </div>
</div>
```

### Update Color Scheme

Modify the CSS variables in `styles.css`:

```css
:root {
    --primary-dark: #0a1628;
    --primary-navy: #1a2d4a;
    --accent-blue: #3b82f6;
    --accent-cyan: #06b6d4;
    --accent-gold: #fbbf24;
    /* ... more variables */
}
```

### Contact Form Integration

The contact form currently shows an alert on submission. To integrate with a backend:

1. Replace the form submission handler in `script.js`
2. Use services like Formspree, Netlify Forms, or your own backend
3. Example with Formspree:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
    <!-- form fields -->
</form>
```

## Deployment

### Static Hosting

The website can be deployed to any static hosting service:

- **Netlify**: Drag and drop the folder or connect to Git
- **Vercel**: Connect to Git repository
- **GitHub Pages**: Push to GitHub and enable Pages
- **AWS S3**: Upload files to S3 bucket with static website hosting

### Local Development

1. Open `index.html` in a web browser
2. Or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## File Structure

```
clickbridge-website/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized CSS with CSS variables
- Minimal JavaScript for essential functionality
- No external dependencies for core functionality
- Font loading optimization with Google Fonts
- Smooth scrolling with native CSS

## Security Notes

- Contact form includes client-side validation
- Cybersecurity services are presented ethically
- Penetration testing is clearly marked as authorized only
- No sensitive information is hardcoded

## SEO

The website includes:

- Proper meta title and description
- Semantic HTML structure (H1, H2, H3)
- Open Graph metadata for social sharing
- Mobile-friendly responsive design
- Fast loading times
- Accessible navigation

## License

This website is custom-built for ClickBridge. All rights reserved.

## Support

For questions or support regarding this website, please contact ClickBridge through the contact information provided on the website.

---

**Built with professionalism and attention to detail for ClickBridge**