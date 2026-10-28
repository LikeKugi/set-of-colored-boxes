# Set of Colored Boxes

A Free Code Camp CSS lab project demonstrating different CSS color formats through a responsive grid of colored boxes.

## 🎨 Project Overview

This project showcases five different ways to define colors in CSS:

| Box | Color Format | Value | Color Preview |
|-----|-------------|-------|---------------|
| **Color 1** | **Hexadecimal** | `#2563eb` | <span style="display:inline-block;width:20px;height:20px;background:#2563eb;border-radius:3px;vertical-align:middle;margin-right:8px;"></span>Blue |
| **Color 2** | **RGB** | `rgb(34, 197, 94)` | <span style="display:inline-block;width:20px;height:20px;background:rgb(34,197,94);border-radius:3px;vertical-align:middle;margin-right:8px;"></span>Green |
| **Color 3** | **Predefined (Word)** | `steelblue` | <span style="display:inline-block;width:20px;height:20px;background:steelblue;border-radius:3px;vertical-align:middle;margin-right:8px;"></span>Steel Blue |
| **Color 4** | **HSL** | `hsl(25, 95%, 53%)` | <span style="display:inline-block;width:20px;height:20px;background:hsl(25,95%,53%);border-radius:3px;vertical-align:middle;margin-right:8px;"></span>Orange |
| **Color 5** | **Hexadecimal** | `#dc2626` | <span style="display:inline-block;width:20px;height:20px;background:#dc2626;border-radius:3px;vertical-align:middle;margin-right:8px;"></span>Red |

## 📁 Project Structure

```
set-of-colored-boxes/
├── index.html    # Main HTML structure
├── styles.css    # CSS styles with all color definitions
├── package.json  # Project configuration
└── README.md     # This file
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Running the Project

1. Clone or download this repository
2. Open `index.html` in your web browser

Or serve it locally with a simple HTTP server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have npx)
npx serve

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## ✨ Features

- **Responsive Design**: Grid layout adapts to different screen sizes
- **Hover Effects**: Boxes lift up with enhanced shadow on hover
- **Clean Code**: Well-organized CSS with comments explaining each color format
- **Accessibility**: Semantic HTML structure

## 🎯 Learning Objectives

This project demonstrates the following CSS color formats:

1. **Hexadecimal** (`#RRGGBB`) - Most common web color format
2. **RGB** (`rgb(r, g, b)`) - Red, Green, Blue values (0-255)
3. **Named Colors** - Predefined CSS color keywords (140+ available)
4. **HSL** (`hsl(h, s%, l%)`) - Hue, Saturation, Lightness
5. **Any valid color format** - The fifth box shows you can use any format

## 📱 Responsive Breakpoints

- **Desktop**: 5 columns (max-width: 800px)
- **Tablet** (≤480px): 2 columns
- **Mobile** (≤320px): 1 column

## 📚 References

- [MDN Web Docs - CSS Colors](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
- [MDN Web Docs - Named Colors](https://developer.mozilla.org/en-US/docs/Web/CSS/named-color)
- [Free Code Camp - Responsive Web Design Certification](https://www.freecodecamp.org/learn/2022/responsive-web-design/)

## 📄 License

This project is part of the Free Code Camp curriculum. Feel free to use it for learning purposes.

---

*Built with ❤️ as part of the Free Code Camp Responsive Web Design curriculum*
