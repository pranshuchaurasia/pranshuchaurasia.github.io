# JavaScript Directory

This folder is reserved for shared JavaScript files.

## Current Architecture

The website currently uses **inline JavaScript** embedded directly in each HTML file
for simplicity (minimal JS currently used for mobile menu toggle).

## When to Extract JS

Consider extracting to a shared `main.js` if:
- You add more interactive features
- JavaScript becomes difficult to maintain in the HTML files
- You want to enable JS caching across pages

## Usage

```html
<!-- Add before closing </body> tag -->
<script src="assets/js/main.js"></script>
```
