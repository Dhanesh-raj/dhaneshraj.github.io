# Fonts Directory

This directory contains custom font files for the GitHub profile project.

## Recommended Fonts:
- **Primary Font**: Segoe UI (system font, no file needed)
- **Display Font**: Custom serif or sans-serif for headings
- **Code Font**: Monospace font for code snippets

## Supported Formats:
- WOFF2 (recommended for modern browsers)
- WOFF (fallback for older browsers)
- TTF (fallback for very old browsers)

## Usage in CSS:
```css
@font-face {
    font-family: 'CustomFont';
    src: url('../assets/fonts/custom-font.woff2') format('woff2'),
         url('../assets/fonts/custom-font.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
```

## Font Loading Best Practices:
- Use `font-display: swap` for better performance
- Preload critical fonts in HTML head
- Provide fallback fonts in CSS
