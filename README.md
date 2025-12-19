# PikiStyles - Premium Fashion Boutique Template

![PikiStyles Banner](images/banner-image3.jpg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Credits](#credits)
- [Contact](#contact)
- [License](#license)

## Overview

**PikiStyles** is a modern, responsive HTML template designed for online fashion boutiques and e-commerce stores. It features a stunning 3D product slider, smooth animations, and an elegant design that showcases clothing and footwear collections in style.

### Key Highlights

- **Fully Responsive**: Optimized for all devices from mobile phones to desktops
- **3D Carousel Slider**: Eye-catching 3D rotating product display
- **Modern UI/UX**: Clean, professional design with smooth animations
- **E-Commerce Ready**: Product cards, cart, quick view, and checkout modals
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Lightweight**: Fast loading times with optimized assets

## Features

### Visual Features

- **3D Product Slider** - Rotating carousel with vintage smoky background
- **Product Quick View** - Modal popup for quick product previews
- **Shopping Cart** - Fully functional cart interface with quantity controls
- **Image Lightbox** - Chocolat lightbox for product image galleries
- **Parallax Effects** - Jarallax-powered parallax scrolling
- **Smooth Animations** - CSS transitions and hover effects

### Functional Features

- **Responsive Navigation** - Mobile-friendly offcanvas menu
- **Search Functionality** - Integrated search box with smooth toggle
- **Product Collections** - Separate sections for Men's and Women's fashion
- **Discount Coupons** - Promotional banner section
- **User Authentication** - Login/Register modal forms
- **Newsletter Signup** - Email subscription form
- **Product Filtering** - Organized product categorization

### Technical Features

- **Bootstrap 5** - Modern CSS framework
- **jQuery** - JavaScript library for interactions
- **Swiper.js** - Touch slider for product carousels
- **Custom CSS Variables** - Easy theming and customization
- **SVG Icons** - Scalable vector icons for better quality
- **Preloader** - Loading animation for better UX

## Technologies Used

### Core Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES5)** - Interactive functionality

### Libraries & Frameworks

| Library | Version | Purpose |
|---------|---------|---------|
| Bootstrap | 5.x | Responsive CSS framework |
| jQuery | 1.11.0 | DOM manipulation and events |
| Swiper.js | Latest | Product carousels and sliders |
| Jarallax | Latest | Parallax scrolling effects |
| Chocolat.js | Latest | Lightbox image galleries |

### Fonts

- **Inter** - Primary font for body text and headings
- **Playfair Display** - Decorative font for special headings
- **Source Sans Pro** - Alternative display font

All fonts are loaded from Google Fonts CDN.

## Project Structure

```
pikistyles-botique/
│
├── index.html                 # Main HTML file
├── style.css                  # Main stylesheet
├── LICENSE                    # License file
├── README.md                  # This documentation
│
├── css/
│   ├── vendor.css             # Third-party library styles
│   ├── 3d-slider.css          # 3D carousel slider styles
│   └── ajax-loader.gif        # Loading spinner animation
│
├── js/
│   ├── jquery-1.11.0.min.js   # jQuery library
│   ├── plugins.js             # Compiled third-party plugins
│   └── script.js              # Custom JavaScript functionality
│
└── images/
    ├── main-logo.png          # Site logo
    ├── banner-image3.jpg      # Hero banner image
    │
    ├── clothes/               # Clothing product images
    │   ├── dress-1.jpg
    │   ├── dress-2.jpg
    │   ├── men-1.jpg
    │   ├── shirt-1.jpg
    │   └── ...
    │
    ├── chocolat/              # Lightbox control icons
    │   ├── close.png
    │   ├── left.png
    │   ├── right.png
    │   └── ...
    │
    ├── card-item*.jpg         # Product card images
    ├── collection-item*.jpg   # Collection showcase images
    ├── post-item*.jpg         # Blog post images
    └── ...
```

## Installation

### Quick Start

1. **Download or Clone** the repository:
   ```bash
   git clone https://github.com/PhilipCodexKe/pikistyles-botique.git
   ```

2. **Navigate** to the project directory:
   ```bash
   cd pikistyles-botique
   ```

3. **Open** `index.html` in your browser:
   - Double-click the file, or
   - Use a local development server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using PHP
     php -S localhost:8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

4. **Visit** `http://localhost:8000` in your browser

### Requirements

- **Modern Web Browser** - Chrome, Firefox, Safari, or Edge (latest versions)
- **Local Web Server** (optional but recommended for development)
- **Text Editor** - VS Code, Sublime Text, or any code editor for customization

## Usage

### Basic Setup

The template is ready to use out of the box. Simply open `index.html` in a browser to see the fully functional template.

### Navigation Structure

The main navigation includes:
- **Home** - Landing page with product slider
- **Men** - Men's fashion collection
- **Women** - Women's fashion collection
- **Pages** - About, Shop, Blog, Single Product, etc.
- **Shop** - Main shopping page
- **Sale** - Sale items

### Key Sections

#### 1. Hero Section (3D Slider)
```html
<section class="slider-3d-section" id="intro">
  <!-- 3D rotating product carousel -->
</section>
```

#### 2. Discount Coupon
```html
<section class="discount-coupon py-2 my-2 py-md-5 my-md-5">
  <!-- Newsletter signup with 10% discount -->
</section>
```

#### 3. Collections
```html
<section id="collection-products" class="py-2 my-2 py-md-5 my-md-5">
  <!-- Men's and Women's featured collections -->
</section>
```

#### 4. Latest Products
```html
<section id="latest-products" class="product-store">
  <!-- Grid of latest products -->
</section>
```

## Customization

### Colors

The template uses CSS custom properties for easy theming. Edit the `:root` variables in `style.css`:

```css
:root {
  --accent-color: #333;
  --black-color: #000;
  --dark-color: #111;
  --light-color: #fff;
  --bs-primary: #ce071e;        /* Primary brand color */
  --bs-primary-dark: #8d0414;   /* Darker shade */
}
```

### Fonts

To change fonts, update the Google Fonts import in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
```

Then update the font variables in `style.css`:

```css
:root {
  --body-font: "Inter", sans-serif;
  --heading-font: "Inter", sans-serif;
}
```

### Logo

Replace `images/main-logo.png` with your own logo. Recommended dimensions: **100x40px** (transparent background).

### Product Images

Replace images in the following directories:
- `images/clothes/` - Clothing product images
- `images/card-item*.jpg` - Homepage product cards
- `images/collection-item*.jpg` - Collection sections

**Recommended image sizes:**
- Product cards: **400x500px**
- Large collection images: **800x600px**
- Banner images: **1920x800px**

### 3D Slider Configuration

Edit the slider quantity in `index.html`:

```html
<div class="slider-3d" style="--quantity: 6">
  <!-- Add or remove slider items -->
  <div class="slider-3d-item" style="--position: 1">
    <img src="images/card-item1.jpg" alt="Product">
  </div>
  <!-- Increase --quantity value as you add more items -->
</div>
```

### Contact Information

Update contact details in the footer section of `index.html`:

```html
<div class="footer-contact-text">
  <span>Your Store Name, City - Country.</span>
  <span>Call us: +123 456 7890</span>
  <span><a href="mailto:your@email.com">your@email.com</a></span>
</div>
```

## Browser Support

The template is tested and works perfectly on:

- Google Chrome - Latest 
- Mozilla Firefox - Latest 
- Safari - Latest 
- Microsoft Edge - Latest  
- Opera - Latest 
- Mobile Browsers - iOS Safari, Chrome Mobile 

**Note:** Internet Explorer is not supported.

## Responsive Breakpoints

The template uses Bootstrap 5 breakpoints:

- **Mobile**: < 576px
- **Tablet**: 576px - 991px
- **Desktop**: 992px - 1199px
- **Large Desktop**: ≥ 1200px

## JavaScript Functions

### Main Functions in `script.js`

```javascript
// Initialize product quantity controls
initProductQty()

// Initialize parallax effects
initJarallax()

// Initialize lightbox gallery
initChocolat()

// Animate text effects
initTextFx()

// Search box toggle
$(".search-item").click()

// Swiper slider initialization
new Swiper(".main-swiper", {...})
```

## Animations & Effects

### Hover Effects

- **hvr-sweep-to-right** - Button sweep animation
- **zoom-effect** - Image zoom on hover
- **text-hover** - Underline animation for links

### CSS Animations

- **3D Slider Auto-rotation** - 20s continuous rotation
- **Preloader** - Fade out on page load
- **Parallax Scrolling** - Background image parallax

## Performance Optimization

### Best Practices Implemented

1. **Image Optimization**
   - Compress all images before upload
   - Use appropriate image formats (JPEG for photos, PNG for graphics)
   - Implement lazy loading for below-fold images

2. **CSS Optimization**
   - Minified vendor CSS
   - CSS custom properties for theming
   - Mobile-first responsive design

3. **JavaScript Optimization**
   - Minified jQuery library
   - Combined plugin files
   - Event delegation for better performance

4. **Loading Optimization**
   - Preloader for seamless transitions
   - Async loading of non-critical resources
   - CDN for Google Fonts

## Troubleshooting

### Common Issues

**Q: 3D Slider not rotating**
- Check if JavaScript is enabled
- Ensure all CSS files are loaded
- Clear browser cache

**Q: Images not displaying**
- Verify image paths are correct
- Check file extensions (case-sensitive on some servers)
- Ensure images exist in the `images/` directory

**Q: Modal not opening**
- Check Bootstrap JavaScript is loaded
- Verify data-bs-toggle attributes
- Check browser console for errors

**Q: Responsive design issues**
- Clear browser cache
- Test in incognito/private mode
- Verify viewport meta tag is present

## Contact

**PikiStyles Online Store**

- Location: Nairobi, Kenya
- Phone: +254 794 554 194
- Email: [philipwafula97@gmail.com](mailto:philipwafula97@gmail.com)
- GitHub: [@PhilipCodexKe](https://github.com/PhilipCodexKe)

## Credits

### Third-Party Resources

- **Bootstrap** - [getbootstrap.com](https://getbootstrap.com)
- **jQuery** - [jquery.com](https://jquery.com)
- **Swiper.js** - [swiperjs.com](https://swiperjs.com)
- **Jarallax** - [github.com/nk-o/jarallax](https://github.com/nk-o/jarallax)
- **Chocolat.js** - [github.com/nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat)
- **Google Fonts** - [fonts.google.com](https://fonts.google.com)

### Design Inspiration

Template designed and developed by **TemplatesJungle** with customizations by PikiStyles.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Future Enhancements

Planned features for upcoming releases:

- Dark mode toggle
- Multi-language support
- Product filtering and sorting
- Wishlist functionality
- Customer reviews and ratings
- Integration with payment gateways
- Backend integration (Node.js/PHP)
- Admin panel for product management
- Real-time inventory tracking
- Social media integration

---

## Changelog

### Version 1.0.0 (Current)
- Initial release
- 3D product slider implementation
- Responsive design for all devices
- E-commerce modals (cart, login, quick view)
- Product grid layouts
- Newsletter integration
- Footer with multiple sections

---

**Made with love by PikiStyles Team**

*Last Updated: December 2025*
