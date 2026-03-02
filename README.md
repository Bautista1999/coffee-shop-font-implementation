# Coffee Shop Project - Lato Font Implementation

This project implements the Lato font for coffee shop branding as specified in the design requirements.

## Font Implementation Details

- **Font Family**: Lato (self-hosted)
- **Weights Implemented**: 300, 400, 700, 900
- **Format**: WOFF2 (web-optimized)
- **Loading Strategy**: font-display: swap for performance

## File Structure

```
├── fonts/
│   ├── lato-v25-latin-300.woff2
│   ├── lato-v25-latin-regular.woff2
│   ├── lato-v25-latin-700.woff2
│   └── lato-v25-latin-900.woff2
├── index.html
├── styles.css
└── README.md
```

## Typography Usage

- **Logo (H1)**: Lato Black (900) - Strong brand presence
- **Navigation**: Lato Bold (700) - Clear readability
- **Body Text**: Lato Regular (400) - Optimal readability
- **Buttons**: Lato Bold (700) - Emphasis and actionability

## Features

- Responsive typography using CSS clamp()
- Font loading optimization with font-display: swap
- Cross-browser compatibility with fallback fonts
- Modern web font format (WOFF2) for performance

## Testing

To view the implementation:
1. Serve the project directory with any local server
2. Open index.html in a browser
3. Verify Lato font rendering on all elements

The font should render clearly with proper weights applied to maintain the intended visual hierarchy and brand consistency.