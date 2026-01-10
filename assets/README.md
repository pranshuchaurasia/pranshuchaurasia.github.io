# Assets Directory

This folder contains all static assets for the portfolio website.

## Structure

```
assets/
├── css/                # Stylesheets
│   └── styles.css      # Shared styles for all pages
├── images/             # Image assets
│   ├── profile.jpg     # Profile photo
│   └── articles/       # Article-specific images
├── js/                 # JavaScript files (minimal, currently inline)
└── README.md           # This file
```

## CSS Architecture

The website uses a **modular CSS approach**:

- **`css/styles.css`** – Shared base styles used across all pages
  - CSS variables (design tokens)
  - Navigation, buttons, typography
  - Background effects, animations
  - Responsive breakpoints

- **Inline `<style>` blocks** – Page-specific styles in each HTML file

### Linking the Shared CSS

```html
<!-- From root (index.html) -->
<link rel="stylesheet" href="assets/css/styles.css">

<!-- From articles folder -->
<link rel="stylesheet" href="../assets/css/styles.css">
```

## Image Guidelines

- **Profile images**: Use optimized JPG/WebP, recommended size 400x400px
- **Article images**: Place in `images/articles/[article-slug]/` folder
- **Optimization**: Use tools like ImageOptim or Squoosh before uploading
