# Phenix Tower - 360° Interactive Virtual Tour

A stunning 360-degree interactive virtual tour of Phenix Tower, built with Marzipano.js for an immersive viewing experience.

![Phenix Tower Virtual Tour](https://img.shields.io/badge/Status-Live-brightgreen)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 🌐 Live Demo

**Visit the live site:** [https://abdalkaderdev.github.io/phenix/](https://abdalkaderdev.github.io/phenix/)

## 📋 Features

- **34 Interactive Scenes** - Explore different areas of Phenix Tower
- **360° Panoramic Views** - Full immersive experience with zoom and navigation
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Auto-rotation** - Hands-free viewing with automatic panorama rotation
- **Fullscreen Mode** - Immersive viewing experience
- **Navigation Controls** - Intuitive zoom, pan, and scene navigation
- **Hotspot Navigation** - Click on arrows to move between connected areas

## 🛠️ Technology Stack

- **Marzipano.js** - Professional-grade panorama viewer
- **HTML5/CSS3** - Modern web standards
- **Vanilla JavaScript** - No framework dependencies
- **GitHub Pages** - Free hosting and deployment

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- Git

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Abdalkaderdev/phenix.git
   cd phenix
   ```

2. **Install dependencies** (optional, for development tools)
   ```bash
   npm install
   ```

3. **Start local server**
   ```bash
   npm start
   # or
   npm run dev
   ```

4. **Open in browser**
   - Navigate to `http://localhost:8000`
   - The virtual tour will load automatically

### Manual Setup
If you prefer not to use Node.js, you can simply:
1. Download the files
2. Open `index.html` in a web browser
3. Note: Some browsers may have issues with local file access

## 📁 Project Structure

```
phenix/
├── index.html          # Main application file
├── index.js            # Application logic
├── style.css           # Styling and layout
├── data.js             # Scene configuration and hotspots
├── tiles/              # Panorama image tiles (34 scenes)
│   ├── 0-1/           # Scene 1
│   ├── 1-2/           # Scene 2
│   └── ...            # Additional scenes
├── vendor/             # Third-party libraries
│   ├── marzipano.js   # Panorama viewer library
│   ├── bowser.min.js  # Browser detection
│   └── screenfull.min.js # Fullscreen API
├── img/                # UI icons and assets
└── .github/workflows/  # GitHub Actions deployment
```

## 🎮 How to Use

### Navigation
- **Mouse/Touch**: Click and drag to look around
- **Scroll**: Zoom in and out
- **Numbered buttons**: Jump to specific scenes (1-34)
- **Arrow hotspots**: Click to navigate between connected areas

### Controls
- **Play/Pause**: Toggle auto-rotation
- **Fullscreen**: Enter/exit fullscreen mode
- **Scene List**: Show/hide scene navigation
- **Directional arrows**: Quick view adjustments

## 🔧 Customization

### Adding New Scenes
1. Add panorama images to the `tiles/` directory
2. Update `data.js` with scene configuration
3. Add navigation hotspots between scenes

### Modifying Styles
- Edit `style.css` for visual changes
- Customize colors, fonts, and layout

### Updating Content
- Modify `index.html` for title and metadata
- Update `data.js` for scene information and hotspots

## 🚀 Deployment

This project is automatically deployed to GitHub Pages:

1. **Push changes** to the `main` branch
2. **GitHub Actions** automatically builds and deploys
3. **Site updates** within minutes

### Manual Deployment
```bash
git add .
git commit -m "Update virtual tour"
git push origin main
```

## 📊 Performance

- **Optimized images**: Tiled panorama loading for fast performance
- **Progressive loading**: Images load as needed
- **Caching**: Browser-friendly caching strategies
- **Mobile optimized**: Responsive design for all devices

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## 🙏 Acknowledgments

- **Marzipano.js** - For the excellent panorama viewer library
- **GitHub Pages** - For free hosting and deployment
- **GitHub Actions** - For automated deployment workflow

## 📞 Support

If you have any questions or need help:
- Open an issue on GitHub
- Check the [Marzipano documentation](http://www.marzipano.net/)

---

**Built with ❤️ by Abdalkaderdev** 