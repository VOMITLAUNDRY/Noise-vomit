# 🎵 Noise Vomit - Interactive Soundboard

An audience-interactive soundboard application designed for live performances, installations, and events. Project a QR code for your audience to scan and let them trigger sounds from their phones in real-time!

## ✨ Features

- **Audience Participation**: Share a QR code that audience members can scan to access the soundboard
- **Random Sound Playback**: Play random sounds with a single tap or spacebar
- **Individual Sound Control**: Browse and play specific sounds from the grid
- **Volume Control**: Adjust playback volume with persistent settings
- **Keyboard Shortcuts**: Space for random play, Escape to stop
- **Mobile-Friendly**: Responsive design optimized for both desktop and mobile devices
- **Dark Theme**: Cyberpunk-inspired neon green aesthetic

## 🚀 Quick Start

### For GitHub Pages (Recommended)

1. Fork or clone this repository
2. Add your audio files to the `sounds/` directory
3. Edit the `sounds` array in `index.html` to list your audio files
4. Enable GitHub Pages in your repository settings (Settings → Pages → Deploy from branch `main`)
5. Access your soundboard at `https://yourusername.github.io/Noise-vomit/`

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/VOMITLAUNDRY/Noise-vomit.git
   cd Noise-vomit
   ```

2. Add your sound files to the `sounds/` directory

3. Open `index.html` in a web browser, or serve with a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if http-server is installed)
   npx http-server
   ```

4. Visit `http://localhost:8000` in your browser

## 📁 Project Structure

```
Noise-vomit/
├── index.html          # Main application file
├── sounds/             # Directory for your audio files
│   ├── 01-beep.mp3
│   ├── 02-noise.mp3
│   └── ...
├── README.md           # This file
└── LICENSE             # License information
```

## 🎨 Customization

### Adding Sounds

1. Place your audio files (MP3, WAV, OGG) in the `sounds/` directory
2. Edit the `sounds` array in `index.html` (around line 139):

```javascript
const sounds = [
  "sounds/01-beep.mp3",
  "sounds/02-noise.mp3",
  "sounds/03-thump.mp3",
  // Add your files here
];
```

### Styling

The application uses CSS custom properties for easy theme customization. Edit the `:root` section in `index.html`:

```css
:root {
  --bg: #000;           /* Background color */
  --neon: #0f0;         /* Primary accent color */
  --muted: #6b6b6b;     /* Muted text color */
  --panel: rgba(255,255,255,0.03); /* Panel background */
}
```

## 🎯 Use Cases

- **Live Music Performances**: Let the audience participate in your show
- **Interactive Art Installations**: Create immersive audio experiences
- **Theatre Productions**: Audience-driven sound effects
- **Workshops & Presentations**: Engage participants with interactive audio
- **Parties & Events**: Collaborative DJ experiences

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript**: No build tools or dependencies required
- **Responsive Design**: Works on desktop, tablet, and mobile
- **QR Code Generation**: Automatic QR code via qrserver.com API
- **LocalStorage**: Saves volume preferences
- **Deck Shuffling**: Prevents sound repetition in random mode

## 📱 Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

Note: Some browsers require user interaction before playing audio (autoplay policy).

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Share your implementations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- QR code generation powered by [QR Server API](https://goqr.me/api/)
- Inspired by interactive performance art and audience participation

## 📧 Contact

Created by [@VOMITLAUNDRY](https://github.com/VOMITLAUNDRY)

---

**Have fun making noise!** 🎉