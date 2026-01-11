# CSS Directory

Shared stylesheets for the portfolio website.

## Files

| File | Description |
|------|-------------|
| `styles.css` | Shared base styles with light/dark mode support |

## styles.css Structure

The shared stylesheet is organized into documented sections:

1. **CSS Variables** – Design tokens with dark (default) and light theme variants
2. **Theme Toggle** – Styling for the light/dark mode toggle button
3. **Reset & Base** – Box-sizing, html/body defaults
4. **Typography** – Font families, gradient text
5. **Layout** – Container, section padding
6. **Background Effects** – Grid pattern, glow orbs (theme-aware opacity)
7. **Navigation** – Fixed nav with theme-aware background
8. **Buttons & Links** – Primary, secondary, back-link
9. **Cards & Components** – Section headers, cards
10. **Badges & Tags** – Status badges, skill tags
11. **Animations** – Keyframes for effects
12. **Responsive** – Mobile breakpoints

## Light/Dark Mode

The theme is controlled via `data-theme` attribute on `<html>`:
- **Dark mode (default)**: No attribute or empty value
- **Light mode**: `data-theme="light"`

```css
/* Dark theme variables in :root */
:root {
    --bg-primary: #0a0a0f;
    /* ... */
}

/* Light theme overrides */
[data-theme="light"] {
    --bg-primary: #faf9f7;
    /* ... */
}
```

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
