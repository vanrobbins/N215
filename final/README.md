# Fine Arts Gallery Website

A modern, responsive art gallery website showcasing contemporary and classical artworks with dedicated sections for gallery viewing, event information, and visitor contact.

## Features

- 🎨 Modern art gallery design with professional aesthetics
- 📱 Fully responsive across all devices (mobile, tablet, desktop)
- �️ Interactive gallery grid with artwork detail pages
- 📅 Events section with individual event detail pages
- � Contact form with image overlay design
- 🎯 Smooth navigation and hover effects
- 🔧 Built with modular SASS architecture

## Live Demo

[View Live Gallery](https://in-info-web4.luddy.indianapolis.iu.edu/~vanrobbi/final/)

## Technologies Used

- **HTML5** - Semantic markup and accessibility
- **SASS/SCSS** - Modular CSS preprocessing
- **CSS3** - Modern styling with Flexbox and Grid
- **Responsive Design** - Mobile-first approach

## Project Structure

```
final/
├── index.html                 # Homepage with featured works
├── about.html                 # About the gallery
├── gallery.html               # Gallery grid overview
├── events.html                # Events listing
├── contact.html               # Contact form
├── gallery/                   # Individual artwork pages
│   ├── sculpt.html
│   ├── abstract.html
│   ├── collage.html
│   └── impressionist.html
├── events/                    # Individual event pages
│   ├── age-of-art.html
│   ├── art-show.html
│   ├── color-theory.html
│   └── express-yourself.html
├── scss/                      # SASS source files
│   ├── style.scss            # Main import file
│   ├── variables.scss        # Color palette & design tokens
│   ├── structure.scss        # Base styles
│   ├── nav.scss              # Navigation styles
│   ├── foot.scss             # Footer styles
│   ├── home.scss             # Homepage specific
│   ├── about.scss            # About page specific
│   ├── gallery.scss          # Gallery styles
│   ├── events.scss           # Events styles
│   ├── contact.scss          # Contact form styles
│   └── responsive.scss       # Media queries
├── css/
│   └── style.css             # Compiled CSS
├── img/                      # Image assets
│   ├── hero images
│   ├── gallery artworks
│   ├── event images
│   └── social icons
└── README.md
```

## Pages Overview

### Homepage (`index.html`)

- Hero section with gallery branding
- Featured artwork showcase
- Introduction to the gallery

### About (`about.html`)

- Gallery history and mission
- Hero image with overlay
- Professional layout

### Gallery (`gallery.html`)

- Grid layout showcasing 4 main artworks
- Interactive hover effects
- Links to individual artwork pages

### Individual Artwork Pages (`gallery/*.html`)

- **Sculpt** - Contemporary sculpture showcase
- **Abstract** - Modern abstract paintings
- **Collage** - Mixed media collage works
- **Impressionist** - Classical impressionist pieces

### Events (`events.html`)

- Upcoming gallery events
- Event cards with hover interactions
- Links to detailed event pages

### Individual Event Pages (`events/*.html`)

- **Age of Art** - Historical art exhibition
- **Art Show** - Contemporary artist showcase
- **Color Theory** - Educational workshop
- **Express Yourself** - Interactive art experience

### Contact (`contact.html`)

- Professional contact form
- Image with orange overlay
- Responsive two-column layout

## Color Palette

The gallery uses a professional art-focused color scheme:

```scss
// Primary Colors
$white: #fff;
$black: #000;
$orange: #fc5000; // Primary accent color
$blue: #00879e; // Secondary accent color

// Overlays
$orange-overlay: rgba(#e9830d, 0.4);
$blue-overlay: rgba($blue, 0.35);
```

## Responsive Breakpoints

```scss
$mobile: 480px; // Mobile devices
$tablet: 768px; // Tablets
$desktop: 1024px; // Desktop
$wide: 1200px; // Wide screens
```

## SASS Architecture

The project follows a modular SASS structure for maintainability:

- **`variables.scss`** - Color palette, breakpoints, and design tokens
- **`structure.scss`** - Base styles, resets, and global elements
- **`nav.scss`** - Navigation bar styling
- **`foot.scss`** - Footer and social media links
- **`home.scss`** - Homepage specific styles
- **`about.scss`** - About page layout
- **`gallery.scss`** - Gallery grid and artwork page styles
- **`events.scss`** - Events listing and detail pages
- **`contact.scss`** - Contact form and image styling
- **`responsive.scss`** - All media queries and responsive design

## Key Features

### Gallery Grid

- CSS Grid layout with custom template areas
- Responsive design that adapts to screen size
- Hover effects with scaling and shadow

### Navigation

- Consistent across all pages
- Active page highlighting
- Mobile-responsive with stacked layout

### Image Overlays

- Orange and blue gradient overlays
- Professional photography presentation
- Consistent with brand colors

### Form Design

- Two-column layout (image + form)
- Responsive stacking on mobile
- Professional styling with hover effects

### Event System

- Clickable event cards
- Individual detail pages
- Back navigation to main events page

