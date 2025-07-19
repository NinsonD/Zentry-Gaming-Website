# Zentry Gaming Website

An interactive, modern, and visually rich website for Zentry Gaming, built with React, Vite, and Tailwind CSS.

## Features

- Animated Navigation Bar with floating and scroll effects
- Custom Audio Player with animated indicator
- Hero Section with animated titles and video backgrounds
- About, Gallery, and Contact Sections with unique layouts and custom fonts
- Responsive Design for all devices
- Custom CSS Animations and advanced Tailwind usage
- Optimized Assets (images, videos, fonts)

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [GSAP](https://greensock.com/gsap/) (for animations)
- [react-use](https://github.com/streamich/react-use) (for scroll hooks)

## Getting Started

1. **Clone the repository:**

   ```sh
   git clone https://github.com/NinsonD/Zentry-Gaming-Website.git
   cd Zentry-Gaming-Website
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Start the development server:**

   ```sh
   npm run dev
   ```

   The site will be available at `http://localhost:5173` (or as shown in your terminal).

4. **Build for production:**
   ```sh
   npm run build
   ```

## Project Structure

- `src/` — Main source code (components, styles)
- `public/` — Static assets (images, fonts, audio, videos)
- `index.html` — Main HTML entry
- `tailwind.config.js` — Tailwind CSS configuration
- `vite.config.js` — Vite configuration

## Customization

- **Fonts:** Custom fonts are loaded from `/public/fonts` and configured in `index.css`.
- **Audio:** The navigation bar includes an audio loop (`/public/audio/loop.mp3`).
- **Images & Videos:** All assets are in `/public/img` and `/public/videos`.

## Credits

- UI/UX Design & Development: [Ninson D](https://github.com/NinsonD)
- [GSAP](https://greensock.com/gsap/) for advanced animations
- [Uiverse.io](https://uiverse.io/) for some CSS loader inspiration

## License

This project is for educational and portfolio purposes. For commercial use, please contact the author.
