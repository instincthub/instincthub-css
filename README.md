# InstinctHub CSS

A lightweight, responsive CSS library designed for modern web applications. InstinctHub CSS provides a clean foundation with thoughtfully crafted components and utilities for rapid development.

![npm version](https://img.shields.io/npm/v/instincthub-css)
![license](https://img.shields.io/npm/l/instincthub-css)
![downloads](https://img.shields.io/npm/dm/instincthub-css)

## Features

- 🎨 Clean, minimal design system
- 📱 Responsive grid layout
- 🧩 Ready-to-use components
- 🔄 Customizable with CSS variables
- 🚀 Lightweight with no dependencies
- 🌐 Cross-browser compatible

## Installation

### npm
```bash
npm install instincthub-css
```

### yarn
```bash
yarn add instincthub-css
```

### pnpm
```bash
pnpm add instincthub-css
```

## Usage

### In JavaScript Applications

#### Import in JavaScript/TypeScript
```javascript
// In your main JS/TS file
import 'instincthub-css';
```

#### Import in CSS/SCSS
```css
/* In your CSS file */
@import 'instincthub-css';
```

#### Import Specific Path
```javascript
import 'instincthub-css/dist/instincthub.css';
```

### In HTML

```html
<!-- Using a local copy -->
<link rel="stylesheet" href="node_modules/instincthub-css/dist/instincthub.css">

<!-- Using CDN (unpkg) -->
<link rel="stylesheet" href="https://unpkg.com/instincthub-css@1.0.0/dist/instincthub.css">

<!-- Using CDN (jsDelivr) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/instincthub-css@1.0.0/dist/instincthub.css">
```

## Components & Utilities

### Layout

#### Container
```html
<div class="container">
  <!-- Your content here -->
</div>
```

### Elements

#### Buttons
```html
<button class="default-btn">Default Button</button>
<button class="primary-btn">Primary Button</button>
<button class="important-btn">Important Button</button>
<button class="danger-btn">Danger Button</button>
<button class="outlined-btn">Outlined Button</button>
```

## Customization

InstinctHub CSS uses CSS custom properties (variables) for easy customization:

```css
:root {
  --DarkCyan: #00838f;
  --TurkishRose: #bc658d;
  --Gunmetal: #2c333a;
  --ViridianGreen: #009ba2;
  --White: #ffffff;
  --Danger: #ea5f5e;
  --FadeGlass: #ffffffe6;

  --Rhythm: #69779b;
  --CaribbeanGreen: #00c5a2;
  --OldLavender: #756c83;
  --AmericanPurple: #432160;
  --ChineseBlue: #415b90;
  --DarkSlateGray: #314a52;
  --MaximumRedPurple: #a03c78;
  --DarkLavender: #6f539b;
  --MetallicBlue: #3c5186;
  --TiffanyBlue: #0fabbc;
  --PoliceBlue: #394a6d;
  --Corn: #fbeb5b;
  --LimeGreen: #4be133;
  --OldRose: #394a6d;
  --Magnolia: #f4f3fe;
  --ChineseSilver: #cccccc;
  --LavenderGray: #c5c0db;
  --Main-Gradient: linear-gradient(79.85deg, #009ba2 -20.87%, #bc658d 87.74%);
  --Dark-Gradient: linear-gradient(
    90deg,
    rgba(0, 0, 0, 1) 0%,
    rgba(33, 33, 33, 1) 35%,
    rgba(79, 79, 79, 1) 100%
  );
  --blue: rgb(26, 57, 87);
  --white: rgb(236, 236, 236);
  --DeepGreen-CyanTurquoise: #206d62;
  --Nunito: "Nunito", sans-serif;
  --Gray: #f4f4f4;
  --filter: none;
  --Montserat: "Montserrat", sans-serif;
  --shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  --overlay: rgba(44, 51, 58, 0.2);
  --lightShadow: 0px 1px 8px rgba(0, 0, 0, 0.2);
  --borderDefault: 1px solid rgba(44, 51, 58, 0.2);
  --nesgBlue: #083e9e;
  --nesgBlueOpacity: #083f9e9c;
  --main-color: #f857a6;
  --second-color: #ff5858;
  --OpacityBackground: #7d7c7c20;
}
```

## Browser Support

InstinctHub CSS supports all modern browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Development

```bash
# Clone the repository
git clone https://github.com/instincthub/instincthub-css.git

# Navigate to the directory
cd instincthub-css

# Install dependencies
npm install

# Build the package
npm run build
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Noah Olatoye

## Acknowledgments

- Inspired by modern CSS frameworks and design systems
- Developed with love at InstinctHub

---

Made with ❤️ by the InstinctHub team