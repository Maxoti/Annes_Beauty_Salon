# Annes Mobile Beauty Salon Website

A modern, responsive static website for a mobile beauty salon business in Nairobi, Kenya.

## Overview

This is a single-page website designed for Annes Mobile Beauty Salon, showcasing professional beauty services delivered directly to clients' homes across Nairobi. The website features a clean, elegant design with a pink and purple color scheme that reflects the beauty industry aesthetic.

## Features

###  Design
- Modern gradient color scheme (pink #e91e63 and purple #9c27b0)
- Fully responsive design that works on desktop, tablet, and mobile devices
- Smooth scrolling navigation
- Interactive hover effects and animations
- Mobile-friendly hamburger menu

###  Sections
1. **Header/Navigation** - Sticky navigation bar with smooth scroll links
2. **Hero Section** - Eye-catching landing section with call-to-action button
3. **Services** - Grid display of main service categories with pricing
4. **Gallery** - Portfolio showcase with images and pricing buttons
5. **About Us** - Information about the salon and its values
6. **Coverage Areas** - List of areas served in Nairobi
7. **Contact/Footer** - Contact information and WhatsApp integration

###  WhatsApp Integration
- Floating WhatsApp button for easy client communication
- Pre-filled message template for booking appointments
- Direct link: `https://wa.me/254790394977`

## File Structure

```
annes-beauty-salon/
│
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # Project documentation
└── images/             # Image directory
    ├── Butterfly-locs.jpeg
    ├── dreadlocks.jpeg
    ├── Ghanaians.png
    ├── knotless.jpeg
    ├── makeba.jpeg
    ├── Micro-mini-twist.jpeg
    ├── school-lines.jpeg
    ├── sister-loc.jpeg
    ├── Stitch-lines.jpeg
    ├── twist_braids.jpeg
    └── twist.jpeg
```

## Services Offered

### Main Categories
- **Braiding & Weaving** - Starting from KES 700
- **Blow Drying Services** - Starting from KES 200
- **Hair Styling** - Starting from KES 250

### Gallery Styles with Pricing
- Butterfly Locs - From KES 2,500
- Dreadlocks - From KES 3,000
- Ghanaian Braids - From KES 2,000
- Knotless Braids - From KES 2,800
- Makeba - From KES 1,800
- Micro Mini Twist - From KES 2,200
- School Lines - From KES 1,500
- Sister Locs - From KES 3,500
- Stitch Lines - From KES 2,000
- Twist Braids - From KES 1,800
- Twist - From KES 1,600

## Coverage Areas

The salon provides mobile services in the following Nairobi areas:
- Githurai
- Kasarani
- Kariobangi
- Lavington
- South B
- Umoja
- South C
- Ngong

## Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (Vanilla)** - Interactive features and smooth scrolling
- **SVG** - WhatsApp icon graphic

## Setup Instructions

1. **Clone or Download** the project files
2. **Ensure proper file structure** - Place all images in the `images/` folder
3. **Open `index.html`** in a web browser
4. No build process or dependencies required - it's a static site!

## Customization

### Updating Contact Information
Edit these lines in `index.html`:
```html
<!-- WhatsApp number -->
<a href="https://wa.me/254790394977?text=Hi! I'd like to book an appointment">

<!-- Phone number -->
<span>+254 790 394977</span>

<!-- Email -->
<span>anne125otienoes@gmail.com</span>
```

### Changing Colors
Modify the CSS variables in the `:root` section:
```css
:root {
    --primary: #e91e63;      /* Main pink color */
    --secondary: #9c27b0;    /* Purple accent */
    --dark: #1a1a1a;         /* Dark text */
    --light: #f8f9fa;        /* Light background */
    --gold: #ffd700;         /* CTA button color */
}
```

### Adding/Removing Gallery Items
Add new gallery items following this structure:
```html
<div class="gallery-item">
    <img src="images/your-image.jpeg" alt="Style Name">
    <div class="gallery-caption">Style Name</div>
    <button class="price-btn">From KES X,XXX</button>
</div>
```

### Updating Prices
Simply edit the text content in the service cards and price buttons throughout the HTML.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Lightweight design with no external dependencies
- Optimized CSS with minimal redundancy
- Fast loading times
- Mobile-optimized images recommended (compressed JPEGs/PNGs)

## Future Enhancements

Potential improvements for future versions:
- Image optimization and lazy loading
- Booking form integration
- Testimonials section
- Before/after image galleries
- Blog section for hair care tips
- Multi-language support (English/Swahili)

## Contact

**Annes Mobile Beauty Salon**
-  Phone: +254 790 394977
-  Email: anne125otienoes@gmail.com
- Location: Mobile Services - Nairobi, Kenya
-  WhatsApp: Available via floating button

## License

© 2024 Annes Beauty Salon. All rights reserved.

---

**Built with care for mobile beauty professionals in Nairobi**