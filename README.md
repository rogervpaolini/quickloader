# Quick Loader - Website Files

## Overview

This is a complete, standalone website for Quick Loader featuring the PrimeWeb Works black and white minimalist theme. The site includes thin line dividers, elegant serif typography, floating navigation with underline hover animations, and smooth scroll effects. It is fully responsive across all devices and uses 100% of the provided article content.

## File Structure

```
quick-loader-website/
├── index.html              # Home page with complete article
├── about.html              # About page
├── contact.html            # Contact page with form
├── privacy-policy.html     # Privacy policy page
├── style.css               # All styling (PrimeWeb Works design)
├── script.js               # JavaScript for interactivity
└── README.md               # This file
```

## Features

- **PrimeWeb Works Minimalist Theme**: Black and white monochrome design with elegant simplicity
- **Thin Line Dividers**: Subtle 1px borders separating sections and content areas
- **Elegant Serif Typography**: Playfair Display for headlines, Lora for body text
- **Floating Navigation**: Fixed position sidebar with underline hover animations
- **Smooth Scroll Effects**: Navigation links smoothly scroll to sections
- **100% Article Content**: Complete furniture preparation guide with all 19 sections
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Contact Form**: Fully functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Print Friendly**: Optimized for printing

## Pages Included

1. **index.html** - Home page with comprehensive article on furniture preparation for moving (100% of article content)
2. **about.html** - Information about Quick Loader mission, expertise, and services
3. **contact.html** - Contact form and multiple contact methods
4. **privacy-policy.html** - Privacy policy and data handling information

## How to Deploy

### Option 1: Direct Upload to Web Host
1. Upload all files to your web hosting provider's root directory
2. Ensure the folder structure is preserved
3. No build process or server configuration needed

### Option 2: GitHub Pages
1. Create a new GitHub repository
2. Upload all files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 3: Netlify
1. Connect your GitHub repository to Netlify
2. Netlify will automatically detect and deploy your site
3. Or drag and drop the folder directly into Netlify

### Option 4: Vercel
1. Import your GitHub repository to Vercel
2. Vercel will automatically deploy your site
3. Custom domain support available

### Option 5: Local Testing
1. Open `index.html` in any modern web browser
2. All links and functionality will work locally
3. Use a local server for best results (e.g., Python: `python -m http.server 8000`)

## Customization

### Change Colors
Edit the CSS variables at the top of `style.css`:
```css
:root {
    --black: #000000;
    --white: #FFFFFF;
    --light-gray: #F8F8F8;
    /* ... other colors ... */
}
```

### Change Fonts
Google Fonts are loaded in the HTML files. To change fonts:
1. Update the `<link>` tag in each HTML file
2. Update the `--font-*` variables in `style.css`

### Update Content
- Edit the article text in `index.html`
- Update page content in `about.html`, `contact.html`, `privacy-policy.html`
- All changes are immediately reflected when you refresh the page

### Add New Pages
1. Create a new `.html` file
2. Copy the structure from an existing page
3. Update the navigation links in all pages to include the new page

## Navigation Features

- **Floating Navigation**: Fixed position sidebar with minimalist styling
- **Underline Hover Animations**: Navigation links animate with elegant underlines
- **Active Indicators**: Navigation links highlight when their section is in view
- **Smooth Scroll**: Clicking navigation links smoothly scrolls to sections
- **Responsive Design**: Navigation adapts to smaller screens

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies (except Google Fonts)
- Lightweight CSS and JavaScript
- Fast load times
- Optimized for Core Web Vitals

## SEO

- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Mobile-friendly design
- Fast page load times

## Article Content

The website features a complete 19-section article on furniture preparation for moving:
1. Assessing Furniture Before Packing
2. Cleaning Furniture Before Moving
3. Measuring Furniture and Doorways
4. Disassembling Large Furniture
5. Securing Moving Parts
6. Protecting Wooden Furniture
7. Safeguarding Glass Components
8. Protecting Upholstered Furniture
9. Caring for Leather Furniture
10. Preparing Mattresses for Transport
11. Removing Fragile Accessories
12. Using Quality Protective Materials
13. Labelling Furniture Components
14. Planning Safe Lifting Techniques
15. Loading Furniture Carefully
16. Protecting Furniture from Weather
17. Inspecting Furniture After Delivery
18. Establishing Furniture in Its New Location
19. Preventing Future Wear After the Move

Plus an introduction and conclusion section.

## Support

For questions or issues with the website, contact:
- Email: hello@quickloader.ca
- Phone: +1 (416) 555-1234

## Legal

© 2026 Quick Loader. All rights reserved.

---

**Last Updated**: April 2026
**Version**: 1.0
**Theme**: PrimeWeb Works Black and White Minimalist
**Article Coverage**: 100% of provided content
