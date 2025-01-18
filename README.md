# CSSence - Advanced CSS/SCSS Snippets

![CSSence Logo](images/icon.png)

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/PavelMelnik.cssence.svg?color=blue&amp;label=VS%20Code%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=PavelMelnik.cssence)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/PavelMelnik.cssence.svg?color=blue)](https://marketplace.visualstudio.com/items?itemName=PavelMelnik.cssence)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/PavelMelnik.cssence.svg?color=blue)](https://marketplace.visualstudio.com/items?itemName=PavelMelnik.cssence)

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

#### Base HTML/Body Setup

```scss
base-html⇥
```

Outputs optimized HTML and Body configurations with mobile fixes.

#### Root Variables

```scss
root-full⇥
```

Sets up complete design system variables.

### 📦 Main Snippets

| Prefix | Description |
|--------|-------------|
| `base-html` | Optimized HTML/Body base configuration |
| `root-full` | Complete root variables setup |

## Installation

1. Open VS Code
2. Press `Ctrl+P` / `Cmd+P`
3. Type: `ext install PavelMelnik.cssence`
4. Press Enter

## Usage

1. Open any CSS/SCSS file
2. Type snippet prefix (e.g., `root-full`)
3. Press `Tab` or `Enter`

## Supported Languages

- CSS
- SCSS
- CSS Modules
- SCSS Modules

## Examples

### Setting up root variables

```scss
root-full⇥

:root {
  /*Colors */
  --color-primary: #1890ff;
  --color-success: #52c41a;
  /* ... more variables*/
}
```

### Optimized base configuration

```scss
base-html⇥

html {
  /*Mobile optimizations */
  -webkit-text-size-adjust: 100%;
  /* ... more optimizations*/
}
```

## Best Practices

### Mobile-First Development

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

## Roadmap

- [ ] Additional component snippets
- [ ] Dark mode utilities
- [ ] Animation presets
- [ ] Custom themes support
- [ ] RTL support

## Support

If you encounter any issues or have suggestions:

- [Create an issue](https://github.com/pavelmelnik94/CSSence/issues)
- [Email support](mailto:info@dinujaya.me)

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
