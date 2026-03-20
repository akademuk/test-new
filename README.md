# VELOCITY | Elite Car Rental & Detailing

**VELOCITY** is a high-octane, premium landing page designed for luxury car rentals and detailing services. It features a dark, aggressive aesthetic with carbon fiber textures, neon accents, and high-performance animations.

## 🏎️ Features

- **High-Performance Design:** Dark mode aesthetic with carbon fiber patterns and bold typography (Orbitron & Oswald).
- **Dynamic Theme Switcher:** Users can toggle between multiple color schemes:
  - `Velocity Red` (Default)
  - `Midnight Blue`
  - `Gold Standard`
  - `Toxic Lime`
  - `Miami Magenta`
- **Smooth Experience:** Integrated **Lenis** for buttery smooth scrolling.
- **Interactive Fleet Showcase:** **Swiper.js** powered car slider with 3D transitions.
- **Visual Effects:**
  - Glitch hover effects on text and buttons.
  - Text stroke styling for headers.
  - Custom scrollbars.
- **Responsive Layout:** Fully responsive design built with Tailwind CSS, optimized for mobile and desktop.

## 🛠️ Tech Stack

- **Framework:** HTML5, CSS3 (Variables)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **Fonts:** 
  - `Orbitron` (Headings/Display)
  - `Oswald` (Numbers/Stats)
  - `Inter` (Body text)
- **Icons:** [FontAwesome 6](https://fontawesome.com/)
- **Libraries:**
  - [Swiper.js](https://swiperjs.com/) (Car sliders)
  - [Fancybox](https://fancyapps.com/fancybox/) (Lightboxes)
  - [Lenis](https://lenis.studio/) (Smooth Scrolling)

## 🎨 Customization

### Color Themes
The site uses CSS variables for theming. You can modify the presets in the `<style>` block or the `theme` object in the Tailwind config.

```css
/* Example: Velocity Red */
:root {
    --color-bg: #050505;
    --color-surface: #121212;
    --color-primary: #dc2626; /* Red */
    --color-text: #f3f4f6;
}
```

### Tailwind Configuration
The `tailwind.config` script in the `<head>` defines the custom font families and color mappings to the CSS variables.

## 🚀 Getting Started

1. Open `index.html` in your browser.
2. No build step required (uses CDN libraries).
3. To customize images, replace files in the `assets/` folder or update the `src` attributes in the HTML.

## 📱 Mobile Optimization
The layout includes custom breakpoints (`md: 1100px`, `lg: 1280px`) to ensure optimal viewing on tablets and smaller laptops, specifically tuned for vertical video presentations.
