# Tailwind-css-Landing-page


## 🌐 Live Demo

[https://todestop429.netlify.app/](https://todestop429.netlify.app/)

---


This is a responsive landing page for the ToDesktop product, built with [Tailwind CSS](https://tailwindcss.com/) and vanilla HTML/JS. It demonstrates how to convert a web app into a desktop app, and showcases features, customer stories, and pricing.

## Features

- **Responsive Design:** Works on all screen sizes.
- **Tailwind CSS:** Utility-first CSS for rapid UI development.
- **Animated Company Logos:** Uses IntersectionObserver and scroll events for smooth logo animations.
- **Interactive Navigation:** Mobile-friendly navigation with a hamburger menu.
- **Feature Highlights:** Grid layout for product features.
- **Customer Stories:** Testimonial section with styled cards.
- **FAQs:** Expandable/collapsible FAQ section.
- **Modern UI:** Gradients, rounded corners, and subtle shadows.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd Tailwind
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Build Tailwind CSS:**
   ```sh
   npx tailwindcss -i ./style.css -o ./output.css --watch
   ```
   > This command will watch for changes in your HTML and CSS files and rebuild `output.css` automatically.

4. **Open `index.html` in your browser.**

## Project Structure

```
.
├── assets/           # Images and icons
├── index.html        # Main HTML file
├── style.css         # Tailwind input CSS (with @import "tailwindcss")
├── output.css        # Generated Tailwind CSS
├── script.js         # JavaScript for interactivity
├── package.json      # npm dependencies
└── tailwind.config.js# Tailwind configuration (if present)
```

## Customization

- **Tailwind Config:**  
  If you want to customize Tailwind (colors, fonts, etc.), create or edit `tailwind.config.js`.
- **Content Paths:**  
  Make sure your HTML files are included in the `content` array in `tailwind.config.js` for proper purging.

## Development Tips

- Edit `style.css` to add custom Tailwind layers or base styles.
- Use `npx tailwindcss ... --watch` during development for live CSS updates.
- All assets should be placed in the `assets/` folder and referenced with relative paths.

## Troubleshooting

- **Styles not updating?**  
  Make sure `output.css` is being rebuilt and linked in your HTML.
- **Tailwind classes not working?**  
  Check for typos and ensure your HTML is included in the Tailwind `content` config.
- **Icons not showing?**  
  Ensure Font Awesome CDN is loaded in the `<head>`.

## License

This project is for demonstration and educational purposes.

---

**Made with ❤️
