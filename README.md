# SpaceCoutureByNupur

A sleek, responsive website for SpaceCoutureByNupur - a boutique interior design and Vastu consultancy in Delhi, founded by Nupur Bahri.

## Features

### Design & User Experience
- **Elegant & Minimalist Design**: Clean, luxury aesthetic with soft neutral tones
- **Responsive Layout**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: CSS transitions and JavaScript-powered interactions
- **Loading Screen**: Professional loading animation
- **Parallax Effects**: Subtle parallax scrolling for enhanced visual appeal

### Typography & Colors
- **Font Combination**: Playfair Display (serif) + Inter (sans-serif)
- **Color Palette**: Soft neutral tones with #8b7355 as primary accent
- **Accessibility**: High contrast ratios and readable font sizes

### Sections
1. **Home/Hero**: Full-width hero with compelling messaging
2. **About**: Introduction to Nupur Bahri with stats and highlights
3. **Services**: Four main service categories with detailed descriptions
4. **Portfolio**: Filterable project showcase with hover effects
5. **Testimonials**: Sliding testimonial carousel with client reviews
6. **Process**: Step-by-step design process explanation
7. **Recognitions**: Awards, certifications, and achievements
8. **Instagram Feed**: Social media integration (simulated)
9. **Contact**: Comprehensive contact form with validation

### Technical Features
- **SEO Optimized**: Meta tags, structured data, semantic HTML
- **Performance**: Lazy loading, image optimization, minified assets
- **Accessibility**: WCAG compliant, keyboard navigation, screen reader support
- **Progressive Web App**: Service worker for offline functionality
- **Form Validation**: Client-side validation with error handling
- **Mobile-First**: Responsive design starting from mobile breakpoints

## File Structure

```
spacecouturebynupur/
├── index.html          # Main HTML file
├── styles.css          # Complete CSS styling
├── script.js           # JavaScript functionality
├── sw.js              # Service Worker for PWA
├── README.md          # Project documentation
└── .vscode/           # VS Code settings
    └── settings.json
```

## Setup Instructions

1. **Clone or Download**: Get the project files to your local machine
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **Local Server** (Recommended): Use a local server for best experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
4. **Access**: Navigate to `http://localhost:8000` in your browser

## Browser Support

- **Modern Browsers**: Chrome 60+, Firefox 60+, Safari 12+, Edge 79+
- **Mobile Browsers**: iOS Safari 12+, Chrome Mobile 60+
- **Features**: CSS Grid, Flexbox, ES6+, Intersection Observer API

## Customization

### Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #8b7355;
    --secondary-color: #6d5a44;
    --text-color: #2c2c2c;
    --background-color: #fefefe;
    --accent-color: #faf9f7;
}
```

### Content
- Update text content directly in `index.html`
- Replace placeholder images with actual project photos
- Modify contact information and social media links

### Styling
- All styles are in `styles.css` with clear section comments
- Responsive breakpoints: 1024px, 768px, 480px
- CSS Grid and Flexbox for layouts

## Performance Optimizations

- **Image Optimization**: WebP format support, lazy loading
- **Font Loading**: Preconnect to Google Fonts, font-display: swap
- **CSS**: Minified and optimized for critical rendering path
- **JavaScript**: Efficient event handling with throttling/debouncing
- **Caching**: Service Worker for offline functionality

## SEO Features

- **Meta Tags**: Complete Open Graph and Twitter Card meta tags
- **Structured Data**: JSON-LD schema markup (can be added)
- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Alt Text**: Descriptive alt attributes for all images
- **Sitemap**: XML sitemap can be generated for search engines

## Contact Form

The contact form includes:
- **Validation**: Client-side validation with error messages
- **Required Fields**: Name, email, phone, service type, message
- **Optional Fields**: Location, budget range, newsletter subscription
- **Accessibility**: Proper labels and ARIA attributes
- **Feedback**: Success/error notifications

**Note**: The form currently simulates submission. To make it functional, integrate with:
- Backend API (Node.js, PHP, Python)
- Form services (Formspree, Netlify Forms, EmailJS)
- Email services (SendGrid, Mailgun)

## Instagram Integration

Currently uses placeholder images. To integrate real Instagram feed:
1. Set up Instagram Basic Display API
2. Get access token and user ID
3. Replace the `initializeInstagramFeed()` function in `script.js`
4. Update image sources with actual Instagram post data

## Deployment

### Static Hosting (Recommended)
- **Netlify**: Drag and drop deployment with form handling
- **Vercel**: Git-based deployment with automatic builds
- **GitHub Pages**: Free hosting for static sites
- **Firebase Hosting**: Google's hosting platform

### Traditional Hosting
- Upload all files to your web server's public directory
- Ensure proper MIME types are configured
- Enable GZIP compression for better performance

## Analytics & Tracking

The website includes tracking functions for:
- Button clicks and interactions
- Form submissions
- Navigation usage
- Portfolio views

To enable analytics:
1. Add Google Analytics 4 tracking code to `index.html`
2. Update the `trackEvent()` function in `script.js`
3. Configure conversion goals in your analytics dashboard

## Maintenance

### Regular Updates
- Update dependencies (Font Awesome, Google Fonts)
- Refresh portfolio images and content
- Monitor and fix any broken links
- Update testimonials and recognitions

### Performance Monitoring
- Use Google PageSpeed Insights
- Monitor Core Web Vitals
- Check mobile usability
- Test across different browsers and devices

## Support

For technical support or customization requests:
- Review the code comments for guidance
- Check browser console for any errors
- Ensure all files are properly uploaded
- Verify image paths and external resources

## License

This project is created for SpaceCoutureByNupur. All rights reserved.

---

**Built with ❤️ for SpaceCoutureByNupur**
*Creating harmonious spaces that inspire and elevate your lifestyle*