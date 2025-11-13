# Business Name Generator

A sleek, modern web application that generates creative business names with a single click. Features a beautiful glassmorphism design, dark mode support, and clipboard functionality.

## ✨ Features

- **Instant Generation**: Generate unique business names with a single click
- **Copy to Clipboard**: Easily copy generated names for immediate use
- **Dark Mode**: Toggle between light and dark themes with persistent preferences
- **Glassmorphism Design**: Modern, eye-catching UI with frosted glass effects
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Polished transitions and hover effects for enhanced UX

## 🚀 Demo

Simply open the `index.html` file in your browser to see the application in action.

## 📋 How It Works

1. Click the "Generate Your Business Name" button
2. A random business name appears combining three word categories
3. Click the copy icon to save the name to your clipboard
4. Click "Regenerate" to start over with a new name

## 🎨 Design Highlights

- **Color Schemes**: 
  - Light mode: Blue gradient background with sky-blue accents
  - Dark mode: Dark gradient with cyan and red accents
- **Glass Effect**: Backdrop blur with semi-transparent containers
- **Interactive Elements**: Hover states and smooth transitions throughout
- **Icon Library**: Font Awesome 7.0.1 for scalable vector icons

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom properties (CSS variables), Flexbox, Grid, and advanced animations
- **Vanilla JavaScript**: No frameworks or dependencies
- **Font Awesome**: Icon library for UI elements
- **LocalStorage API**: Theme preference persistence
- **Clipboard API**: Copy-to-clipboard functionality

## 📁 Project Structure

```
business-name-generator/
│
├── index.html          # Main HTML file (contains all code)
└── README.md          # Project documentation
```

## 💻 Installation

1. **Clone or Download**
   ```bash
   git clone https://github.com/yourusername/business-name-generator.git
   ```

2. **Open in Browser**
   ```bash
   cd business-name-generator
   open index.html
   ```

   Or simply double-click the `index.html` file.

## 🎯 Usage

### Basic Usage
```html
<!-- Simply open index.html in any modern browser -->
```

### Customization

To customize the word pools for business name generation, modify the `generateBusinessName()` function:

```javascript
function generateBusinessName() {
    // Customize these arrays with your own words
    const firstWords = ["Crazy", "Amazing", "Fire"];
    const secondWords = ["Engine", "Food", "Garments"];
    const thirdWords = ["Bros", "Limited", "Hub"];
    
    // Generation logic...
}
```

### Theme Customization

Modify CSS custom properties in the `:root` selector for light mode:

```css
:root {
    --primary: #1e3a8a;      /* Primary color */
    --secondary: #60a5fa;    /* Secondary color */
    --accent: #fcd34d;       /* Accent color */
    --bg-gradient: linear-gradient(135deg, #a1c4fd, #c2e9fb);
}
```

And in `.toogle-theme` for dark mode.

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📱 Responsive Breakpoints

- **Desktop**: > 500px
- **Mobile**: ≤ 500px

## 🔧 Future Enhancements

- [ ] Add more word categories for greater variety
- [ ] Include industry-specific name generation
- [ ] Save favorite names to a list
- [ ] Export names to a file
- [ ] Add name availability checking (domain/social media)
- [ ] Multi-language support
- [ ] Advanced filtering options


## 👨‍💻 Author

**Abdur Rahman Adil**

- GitHub: [@SyntaxAdil ](https://github.com/SyntaxAdil )
- Email: abdurrahmanadil005@gmail.com
## 🙏 Acknowledgments

- Font Awesome for the icon library
- Inspiration from modern web design trends
- The open-source community

## 📞 Support

If you have any questions or run into issues, please open an issue on GitHub or contact the author directly.

---

⭐ **Star this repository if you find it helpful!**