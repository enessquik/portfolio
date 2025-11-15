# Portfolio - Enes Dinç

A modern, minimalist portfolio website showcasing my work, skills, and experience as a Full Stack Developer.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on mobile, tablet, and desktop devices
- **Modern UI/UX**: Clean, minimalist design with generous white space and bold typography
- **Smooth Animations**: Subtle fade-in animations, hover effects, and micro-interactions
- **Fixed Navigation**: Sticky navigation bar with smooth scroll behavior and active link highlighting
- **Project Showcase**: Grid layout for projects with hover effects and detailed information
- **Skills Display**: Organized skill categories with interactive hover effects
- **Contact Section**: Multiple contact methods and social media links
- **Performance Optimized**: Debounced scroll events and optimized animations for smooth performance

## 🎨 Design Principles

This portfolio follows modern design principles inspired by minimalist web design:

- **Minimalism**: Clean and uncluttered interface with focus on content
- **White Space**: Generous spacing for better readability and visual hierarchy
- **Typography**: Bold, modern sans-serif fonts for clear communication
- **Color Scheme**: Simple black, white, and accent color (indigo blue) palette
- **Micro-interactions**: Subtle animations that enhance user experience without being distracting

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive features and animations
├── README.md           # Project documentation
└── LICENSE            # MIT License
```

## 🚀 Getting Started

### Prerequisites

No special prerequisites are needed! This is a static website built with vanilla HTML, CSS, and JavaScript.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/enessquik/portfolio.git
   ```

2. Navigate to the project directory:
   ```bash
   cd portfolio
   ```

3. Open `index.html` in your browser:
   - **Option 1**: Double-click on `index.html`
   - **Option 2**: Right-click and choose "Open with" your preferred browser
   - **Option 3**: Use a local development server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```
   - Then open `http://localhost:8000` in your browser

## 🛠️ Customization

### Update Personal Information

1. **Hero Section** (`index.html`, line ~26):
   - Update your name and title
   - Modify the description text

2. **About Section** (`index.html`, line ~48):
   - Replace the bio text with your own story
   - Update the statistics (years of experience, projects, clients)

3. **Projects** (`index.html`, line ~79):
   - Replace project placeholders with your actual projects
   - Update project titles, descriptions, and tags
   - Add links to live demos or GitHub repositories

4. **Skills** (`index.html`, line ~193):
   - Modify the skill categories and items to match your expertise
   - Add or remove skills as needed

5. **Contact Information** (`index.html`, line ~256):
   - Update email address and phone number
   - Replace social media links with your profiles

### Customize Colors

Edit the CSS variables in `styles.css` (line ~2):

```css
:root {
    --primary-color: #000000;      /* Main text color */
    --secondary-color: #ffffff;    /* Background color */
    --accent-color: #6366f1;       /* Accent/highlight color */
    --text-color: #333333;         /* Body text */
    --text-light: #666666;         /* Secondary text */
}
```

### Modify Fonts

Change the font family in `styles.css` (line ~11):

```css
:root {
    --font-primary: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, ...;
}
```

Or add custom fonts via Google Fonts in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
```

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 481px - 768px
- **Desktop**: > 768px

## ✨ Key Features Explained

### Smooth Scrolling
The navigation menu implements smooth scrolling to different sections of the page with offset adjustment for the fixed navbar.

### Fade-in Animations
Elements with the `.fade-in` class will animate into view as you scroll down the page using the Intersection Observer API.

### Mobile Menu
A hamburger menu appears on mobile devices for better navigation on smaller screens.

### Parallax Effect
The hero section has a subtle parallax effect on desktop devices for added visual interest.

### Counter Animation
Statistics in the About section animate from 0 to their target value when scrolled into view.

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Enes Dinç**
- GitHub: [@enessquik](https://github.com/enessquik)
- Email: contact@enesdinc.com

## 🙏 Acknowledgments

- Design inspiration from modern minimalist portfolios
- Icons from inline SVG
- Smooth animations using CSS transitions and Intersection Observer API

## 📞 Support

If you have any questions or need help customizing the portfolio, feel free to:
- Open an issue on GitHub
- Contact me via email
- Connect with me on social media

---

Made with ❤️ by Enes Dinç