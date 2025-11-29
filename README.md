# 🔄 Unit Converter

A fast, lightweight, and beautiful unit converter with dark mode support. Zero dependencies, instant conversions, and optimized for both desktop and mobile devices.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- **6 Conversion Categories**
  - 📏 Length (meters, kilometers, miles, feet, inches, etc.)
  - ⚖️ Weight (kilograms, grams, pounds, ounces, etc.)
  - 🌡️ Temperature (Celsius, Fahrenheit, Kelvin)
  - 🧪 Volume (liters, gallons, cups, fluid ounces, etc.)
  - 📐 Area (square meters, acres, hectares, etc.)
  - 🚀 Speed (m/s, km/h, mph, knots, etc.)

- **User Experience**
  - ⚡ Real-time conversion as you type
  - 🔄 Quick swap button to reverse units
  - 🌓 Dark mode with persistent preferences
  - 📱 Fully responsive mobile-first design
  - 🎨 Beautiful gradient UI with smooth animations

- **Technical**
  - 🚫 Zero dependencies
  - 📦 Single HTML file (< 10KB)
  - ⚡ Instant load time
  - 💾 LocalStorage for dark mode preference
  - 📢 Ad-ready with placeholder divs

## 📸 Screenshots

### Light Mode
![](#) <!-- Add screenshot -->

### Dark Mode
![](#) <!-- Add screenshot -->

## 🛠️ Installation

### Option 1: Direct Download
1. Download `index.html`
2. Open in any modern web browser
3. That's it! No build process needed.

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/unit-converter.git
cd unit-converter
```

Then open `index.html` in your browser.

### Option 3: GitHub Pages
Fork this repository and enable GitHub Pages in settings to get your own hosted version.

## 💻 Usage

1. **Select Category**: Choose from Length, Weight, Temperature, Volume, Area, or Speed
2. **Enter Value**: Type any number in the input field
3. **Select Units**: Choose the units you want to convert from and to
4. **View Result**: Conversion happens instantly as you type
5. **Swap Units**: Click the swap button (⇅) to reverse the conversion
6. **Toggle Dark Mode**: Click the moon/sun icon in the top right

## 🎨 Customization

### Changing Colors

Edit the CSS gradient in the `<style>` section:

```css
/* Light mode background */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Dark mode background */
background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
```

### Adding More Units

Add units to the `conversions` object in JavaScript:

```javascript
conversions.length.units.push('Your Unit');
conversions.length.toBase['Your Unit'] = conversionFactor;
```

### Integrating Ads

Replace the placeholder divs with your ad code:

```html
<div class="ad-container ad-top">
    <!-- Your ad code here -->
</div>
```

## 🧮 Conversion Formula

The converter uses a base unit system:

1. Convert input to base unit: `baseValue = inputValue × toBaseMultiplier`
2. Convert base unit to target: `outputValue = baseValue ÷ toBaseMultiplier`

**Temperature** uses custom conversion functions due to non-linear scaling.

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contributions
- [ ] Add more conversion categories (time, energy, pressure, etc.)
- [ ] Implement conversion history
- [ ] Add keyboard shortcuts
- [ ] Create unit favorites system
- [ ] Add share/copy result button
- [ ] Implement multi-language support
- [ ] Add unit search functionality

## 📝 License

This project is open

---

⭐ If you found this helpful, consider giving it a star!

**Made with ❤️ and vanilla JavaScript**