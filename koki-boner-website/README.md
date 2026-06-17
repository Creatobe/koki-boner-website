# 🏝️ Koki Boner Villa & Resto Bar - Website Project

**A Premium Luxury Hospitality Website for Rodrigues Island, Mauritius**

---

## 📋 PROJECT OVERVIEW

This is a professional, fully responsive single-page website for **Koki Boner Villa & Resto Bar**, a beachfront luxury resort on Rodrigues Island, Mauritius.

### Key Features:
- ✅ **Pure HTML5, CSS3, Flexbox** - No JavaScript, frameworks, or libraries
- ✅ **Fully Responsive** - Desktop, tablet, mobile optimized
- ✅ **Advanced CSS Animations** - Smooth transitions and effects
- ✅ **Premium Design** - Luxury hospitality aesthetic
- ✅ **Semantic HTML** - Clean, professional code structure
- ✅ **Professional Styling** - Organized, customizable CSS

---

## 📁 PROJECT STRUCTURE

```
koki-boner-website/
├── index.html                    # Main HTML file
├── css/
│   └── style.css                # Complete CSS stylesheet
├── images/                       # Image folder (placeholder)
│   ├── hero-beach.jpg
│   ├── villa-overview.jpg
│   ├── beach-villa.jpg
│   ├── ocean-view-room.jpg
│   ├── private-escape.jpg
│   ├── restaurant-dining.jpg
│   ├── seafood.jpg
│   ├── cocktails.jpg
│   ├── island-dishes.jpg
│   ├── gallery-beach-1.jpg
│   ├── gallery-villa-1.jpg
│   ├── gallery-pool.jpg
│   ├── gallery-restaurant.jpg
│   ├── gallery-food.jpg
│   ├── gallery-beach-2.jpg
│   ├── gallery-sunset.jpg
│   └── gallery-room.jpg
└── README.md                    # This file
```

---



## 🖼️ IMAGE REPLACEMENT GUIDE

The website uses placeholder image paths. Replace them with actual images:

### 1. **Hero Section** (`images/hero-beach.jpg`)
- **Recommended Size:** 1920x1080px or larger
- **Content:** Stunning beachfront sunset or beach villa view
- **Location:** HTML Line ~85 (`.hero-background`)

### 2. **About Section** (`images/villa-overview.jpg`)
- **Recommended Size:** 800x600px
- **Content:** Full villa overview or exterior
- **Location:** HTML Line ~162

### 3. **Room Cards** (3 images)
- `images/beach-villa.jpg` - Beachfront villa room (HTML Line ~212)
- `images/ocean-view-room.jpg` - Ocean view bedroom (HTML Line ~237)
- `images/private-escape.jpg` - Luxury suite (HTML Line ~262)
- **Size:** 600x400px each
- **Content:** Interior room photography

### 4. **Restaurant Section** (`images/restaurant-dining.jpg`)
- **Recommended Size:** 1920x1080px
- **Content:** Restaurant interior with sunset view
- **Location:** HTML Line ~293

### 5. **Food Cards** (3 images)
- `images/seafood.jpg` - Fresh seafood dishes (HTML Line ~308)
- `images/cocktails.jpg` - Tropical cocktails (HTML Line ~319)
- `images/island-dishes.jpg` - Local island cuisine (HTML Line ~330)
- **Size:** 600x400px each

### 6. **Gallery Section** (8 images)
- `images/gallery-beach-1.jpg` through `gallery-room.jpg`
- **Recommended Size:** 400x400px each (square)
- **Content:** Mix of beach, villa, food, sunset photos
- **Location:** HTML Lines ~347-361

---

## 🎨 DESIGN SPECIFICATIONS

### Color Palette

```css
Ocean Blue:          #0a4d68
Ocean Light:         #088395
Ocean Lighter:       #05bfdb
Sand Beige:          #f4e4c1
Sand Dark:           #d4a574
White:               #ffffff
Beige Background:    #faf8f3
Palm Green:          #2d5016
Gold Accent:         #d4af37
```

### Typography

- **Display Font:** Playfair Display (elegant serif)
- **Body Font:** Lato (modern sans-serif)
- Both imported from Google Fonts (free)

### Responsive Breakpoints

- **Desktop:** 1200px+ width
- **Tablet:** 768px - 1199px
- **Mobile:** 480px - 767px
- **Small Mobile:** Below 480px

---

## ✨ FEATURES & ANIMATIONS

### CSS Animations Included

1. **fadeIn** - Smooth opacity transition
2. **slideUp** - Bottom to top entrance
3. **slideDown** - Top to bottom entrance
4. **floating** - Gentle Y-axis bobbing
5. **zoom** - Scale growth
6. **pulse** - Opacity pulsing
7. **glow** - Box shadow glow effect
8. **shimmer** - Background position shift

### Micro-Interactions

- ✓ Navigation links with underline hover effect
- ✓ Buttons scale and lift on hover
- ✓ Cards translate up with shadow enhancement
- ✓ Images zoom on hover
- ✓ Smooth color transitions
- ✓ Scroll-triggered fade-ins
- ✓ Floating scroll indicator

### Section Features

| Section | Features |
|---------|----------|
| **Navigation** | Sticky header, transparent to solid transition |
| **Hero** | Full-screen image, overlay, animated text, scroll indicator |
| **About** | Two-column layout, hover image zoom, feature boxes |
| **Villa** | Card grid, image overlays, amenity lists |
| **Restaurant** | Featured hero, food cards, info boxes |
| **Experiences** | 6 card grid with icons, staggered animations |
| **Gallery** | Responsive image grid with zoom hover |
| **Testimonials** | 3 review cards with ratings |
| **Contact** | 4 info cards, booking CTA, gradient background |
| **Footer** | Multi-column layout, social links |

---


## 📱 RESPONSIVE DESIGN BREAKDOWN

### Desktop (1200px+)
- Full navigation menu
- Multi-column layouts
- Large typography
- Full animations

### Tablet (768px - 1199px)
- Adjusted font sizes
- 2-column grids become single/dual
- Optimized spacing
- Touch-friendly buttons

### Mobile (480px - 767px)
- Single column layouts
- Smaller typography
- Reduced spacing
- Full-width buttons
- Vertical navigation

### Small Mobile (Below 480px)
- Minimal spacing
- Compact buttons
- 1rem base font size
- Simplified layouts

---

## 🔍 CODE QUALITY & BEST PRACTICES

### HTML Structure
- ✅ Semantic HTML5 tags (header, nav, section, footer)
- ✅ Descriptive class and ID names
- ✅ Proper heading hierarchy (h1, h2, h3, h4)
- ✅ Accessibility considerations
- ✅ Clean comments throughout

### CSS Organization
1. CSS Variables & Root Styles
2. Reset & General Styles
3. Animations
4. Button Styles
5. Component Styles (Header, Hero, etc.)
6. Responsive Design
7. Utility Classes

### Performance Optimizations
- CSS custom properties for maintainability
- Hardware-accelerated animations (transform, opacity)
- Optimized media queries
- Minimal file size

---

## 📝 CONTENT CUSTOMIZATION

### Change Company Details

**Phone Number** - HTML line ~451:
```html
<a href="tel:+23059123456">+230 5912 3456</a>
```

**Email Address** - HTML line ~459:
```html
<a href="mailto:info@kokiboner.mu">info@kokiboner.mu</a>
```

**Location** - HTML line ~467:
```html
<p>Rodrigues Island</p>
```

**Opening Hours** - HTML line ~475:
```html
<p>Restaurant: 12:00 - 23:00</p>
```

### Change Room Prices

Each room card has price overlay (Lines ~213, ~238, ~263):
```html
<div class="room-overlay">
    <p>From €250/night</p>
</div>
```

### Change Social Media Links

Footer social links (Lines ~553-557):
```html
<a href="#" class="social-link" title="Instagram">📷</a>
```

---


## 📚 RESOURCES & REFERENCES

- **Google Fonts:** https://fonts.google.com
- **CSS Animations:** https://developer.mozilla.org/en-US/docs/Web/CSS/animation
- **Flexbox Guide:** https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- **Responsive Design:** https://web.dev/responsive-web-design-basics/

---

## 📄 FILE INFORMATION

| File | Size | Purpose |
|------|------|---------|
| index.html | ~25 KB | Main website structure |
| css/style.css | ~45 KB | Complete styling & animations |
| images/ | Variable | Image assets |

---

## ✉️ DEPLOYMENT NOTES

To deploy this website:

1. **Upload to Web Host**
   - FTP or file manager
   - Include index.html, css/, images/ folders

2. **Domain Setup**
   - Point domain to hosting
   - Update contact info in website

3. **SEO Basics**
   - Meta description (line 8)
   - Title tag (line 9)
   - Keywords (line 7)

4. **Email Links**
   - Update email addresses (Line ~459, ~581)
   - Test all contact links

---


---

## 🎯 NEXT STEPS & ENHANCEMENTS

### Optional JavaScript Enhancements 
- Form submission handling
- Image gallery lightbox
- Smooth scroll behavior
- Mobile menu toggle

### Additional Features
- Blog section
- Booking calendar integration
- Real-time reviews
- Weather widget

---

**Enjoy your luxury hospitality website! 🏝️✨**

For questions about customization, refer to the sections above or contact your development team.
