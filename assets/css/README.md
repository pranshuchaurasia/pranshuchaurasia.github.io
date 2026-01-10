# CSS Directory

Shared stylesheets for the portfolio website.

## Files

| File | Description |
|------|-------------|
| `styles.css` | Shared base styles for all pages |

## styles.css Structure

The shared stylesheet is organized into documented sections:

1. **CSS Variables** – Design tokens (colors, gradients)
2. **Reset & Base** – Box-sizing, html/body defaults
3. **Typography** – Font families, gradient text
4. **Layout** – Container, section padding
5. **Background Effects** – Grid pattern, glow orbs
6. **Navigation** – Fixed nav, mobile menu
7. **Buttons & Links** – Primary, secondary, back-link
8. **Cards & Components** – Section headers, cards
9. **Badges & Tags** – Status badges, skill tags
10. **Animations** – Keyframes for effects
11. **Responsive** – Mobile breakpoints

## Usage

```html
<!-- From root (index.html) -->
<link rel="stylesheet" href="assets/css/styles.css">

<!-- From subfolders (articles/index.html) -->
<link rel="stylesheet" href="../assets/css/styles.css">
```

## Adding New Styles

- **Shared styles** → Add to `styles.css` in the appropriate section
- **Page-specific styles** → Keep inline in the HTML file
