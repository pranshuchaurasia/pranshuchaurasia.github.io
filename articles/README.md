# Articles Section

Blog articles for the portfolio website.

## Structure

```
articles/
├── index.html          # Articles listing (Coming Soon page)
├── [article-slug]/     # Individual article folders (future)
│   ├── index.html      # Article content
│   └── images/         # Article-specific images
└── README.md           # This file
```

## Adding a New Article

1. Create a folder: `articles/your-article-slug/`
2. Create `index.html` using this template:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Copy head from articles/index.html -->
    <link rel="stylesheet" href="../../assets/css/styles.css">
</head>
<body>
    <!-- Navigation, content, footer -->
</body>
</html>
```

3. Add images to `your-article-slug/images/` if needed
4. Update `articles/index.html` to link to the new article

## URL Structure

Articles follow clean URLs:
```
https://pranshuchaurasia.github.io/articles/your-article-slug/
```

## Styling

- Use shared styles from `../assets/css/styles.css`
- Add article-specific styles inline in `<style>` block
