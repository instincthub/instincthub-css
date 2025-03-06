# InstinctHub CSS

A clean, minimal CSS library for modern web projects.

## Installation

### npm
```bash
npm install instincthub-css
```

### yarn
```bash
yarn add instincthub-css
```

## Usage

### Import in JavaScript/CSS
```javascript
// In a JavaScript file
import 'instincthub-css';

// In a CSS file
@import 'instincthub-css';
```

### Link in HTML
```html
<link rel="stylesheet" href="node_modules/instincthub-css/dist/instincthub.css">
```

## Available Classes

- `.container` - Responsive container
- `.btn` - Button styling
- `.grid` - 12-column grid system

## Variables

The library uses CSS custom properties (variables) that you can override:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
  --background-color: #your-color;
  --spacing-unit: your-value;
}
```

## License

MIT
