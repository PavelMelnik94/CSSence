# CSSence - Advanced CSS/SCSS Snippets

![CSSence Logo](images/icon.png)

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/PavelMelnik94.cssence?color=blue&amp;label=VS%20Code%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=PavelMelnik94.cssence)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/PavelMelnik94.cssence?color=blue)](https://marketplace.visualstudio.com/items?itemName=PavelMelnik94.cssence)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/PavelMelnik94.cssence?color=blue)](https://marketplace.visualstudio.com/items?itemName=PavelMelnik94.cssence)

## Overview

CSSence is a powerful VS Code extension providing a comprehensive collection of CSS/SCSS snippets based on Ant Design system. It includes optimized base configurations, mobile-first responsive design patterns, and iOS-specific fixes.

## Features

### 🎨 Design System Integration

- Complete Ant Design color system
- Consistent spacing scales
- Typography system
- Border radius utilities
- Shadow configurations

### 📱 Mobile Optimization

- iOS-specific fixes
- Touch interaction improvements
- Mobile-first media queries
- Performance optimizations
- Disabled hover states on touch devices

### 🚀 Quick Start Snippets

Sets up complete design system variables.

### 📦 Main Snippets

| Prefix | Description |
|--------|-------------|
| `!init` | 🎯 Complete project initialization with typography, root variables and basic HTML optimizations (Ant Desing based) |
| `s-full-bg` | 🖼️ Full-screen responsive background image |
| `s-center-flex` | 📍 Centering elements using flexbox |
| `s-center-absolute` | 📌 Absolute centering using transform |
| `s-div.background` | 🎨 DIV with background image and scroll fixation |
| `s-media-min` | 📱 Media query min-width (Mobile First) |
| `s-media-max` | 💻 Media query max-width (Desktop First) |
| `s-animation` | ✨ CSS animation template with keyframes |
| `s-theme-toggle` | 🌓 Light/Dark theme toggle functionality |
| `s-aspect-ratio` | 📐 Fixed aspect ratio (16:9) container |
| `s-tooltip` | 💬 Tooltip with smooth animation |
| `s-card-hover` | 🃏 Card with hover effect animation |
| `s-hamburger-menu` | 🍔 Animated hamburger menu button |
| `s-input-floating` | ✍️ Input field with floating label |
| `s-skeleton-loading` | ⌛ Skeleton loading animation |
| `s-scroll-snap` | 📜 Container with scroll snap functionality |
| `s-gradient-text` | 🌈 Text with animated gradient effect |
| `s-custom-scrollbar-minimal` | 📊 Minimal custom scrollbar design |
| `s-grid-container` | 🏗️ Responsive grid container |
| `s-truncate-text` | ✂️ Text truncation with ellipsis |
| `s-glassmorphism` | 🌫️ Frosted glass effect |
| `s-responsive-image` | 🖼️ Responsive image handling |
| `s-smooth-transition` | 🔄 Smooth transition effect |
| `s-custom-checkbox` | ☑️ Custom animated checkbox |
| `s-loading-spinner` | 🔄 Animated loading spinner |

## Usage

1. Open any CSS/SCSS file
2. Type snippet prefix (e.g., `!init`)
3. Press `Tab` or `Enter`

## Supported Languages

- CSS
- SCSS
- CSS Modules
- SCSS Modules

```scss
// Use the provided media query helpers
@media (min-width: var(--breakpoint-md)) {
  // Desktop styles
}
```

### iOS Specific Fixes

```scss
// Automatically included in base-html snippet
@supports (-webkit-touch-callout: none) {
  // iOS specific fixes
}
```

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Support

If you encounter any issues or have suggestions:

- [Create an issue](https://github.com/pavelmelnik94/CSSence/issues)
- [Email support](mailto:recyclesordie94@gmail.com)

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## Author

**Pavel Melnik**

- GitHub: [@PavelMelnik94](https://github.com/PavelMelnik94)

## Acknowledgments

- Inspired by Ant Design System
- Created for modern web development needs
- Optimized for real-world use cases

---

Made with ❤️ by [Pavel Melnik](https://github.com/PavelMelnik94)

*Last Updated: 2025-01-18 02:04:29 UTC*
