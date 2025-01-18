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

Sets up complete design system variables.

### 📦 Main Snippets

| Prefix | Description |
|--------|-------------|
| `!init` | 🎯 Полная инициализация проекта с типографикой, root-переменными и базовыми HTML-оптимизациями |
| `s-full-bg` | 🖼️ Полноэкранный респонсивный фоновый рисунок |
| `s-center-flex` | 📍 Центрирование через flexbox |
| `s-center-absolute` | 📌 Абсолютное центрирование через transform |
| `s-div.background` | 🎨 DIV с фоновым изображением и фиксацией при прокрутке |
| `s-media-min` | 📱 Медиа-запрос min-width (Mobile First) |
| `s-media-max` | 💻 Медиа-запрос max-width (Desktop First) |
| `s-animation` | ✨ Шаблон CSS-анимации с keyframes |
| `s-theme-toggle` | 🌓 Переключение светлой/темной темы |
| `s-aspect-ratio` | 📐 Фиксированное соотношение сторон (16:9) |
| `s-tooltip` | 💬 Всплывающая подсказка с плавной анимацией |
| `s-card-hover` | 🃏 Карточка с эффектом при наведении |
| `s-hamburger-menu` | 🍔 Анимированное гамбургер-меню |
| `s-input-floating` | ✍️ Поле ввода с плавающим лейблом |
| `s-skeleton-loading` | ⌛ Скелетон-загрузчик с анимацией |
| `s-scroll-snap` | 📜 Контейнер с привязкой прокрутки |
| `s-gradient-text` | 🌈 Текст с анимированным градиентом |
| `s-custom-scrollbar-minimal` | 📊 Минималистичный скроллбар |
| `s-grid-container` | 🏗️ Адаптивный grid-контейнер |
| `s-truncate-text` | ✂️ Обрезка текста с многоточием |
| `s-glassmorphism` | 🌫️ Эффект матового стекла |
| `s-responsive-image` | 🖼️ Адаптивное изображение |
| `s-smooth-transition` | 🔄 Плавный эффект перехода |
| `s-custom-checkbox` | ☑️ Кастомный чекбокс с анимацией |
| `s-loading-spinner` | 🔄 Анимированный спиннер загрузки |

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
