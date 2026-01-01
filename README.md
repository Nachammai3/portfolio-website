# Professional Portfolio Website

A responsive, static personal portfolio website built with HTML5 and CSS3.

## Features
- **Neon Theme**: Modern dark/light blue gradient aesthetics.
- **Responsive Design**: Mobile-first approach using Flexbox and Grid.
- **Project Slider**: Pure CSS scrolling marquee for project highlights.
- **PWA Ready**: Includes `manifest.json` and offline fallback.
- **No External Libraries**: 100% dependency-free.

## Project Structure
```
portfolio-website/
├── index.html          # Main application file
├── css/
│   └── style.css       # All styles and animations
├── assets/
│   ├── images/         # Place your project images here
│   └── icons/          # PWA icons go here
├── manifest.json       # Web App Manifest
├── offline.html        # Offline fallback page
└── README.md           # This file
```

## How to Run
1. Unzip the downloaded file.
2. Open `index.html` in any modern web browser.
3. (Optional) To view as a PWA, serve the folder using a local server (e.g., Live Server in VS Code).

## Customization
- **Colors**: Edit the `:root` variables in `css/style.css`.
- **Content**: Update the HTML text in `index.html`.
- **Images**: Add your images to `assets/images` and update `src` attributes in `index.html`.
