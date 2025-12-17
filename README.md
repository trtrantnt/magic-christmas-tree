# 🎄 Christmas Magic - Interactive Hand Gesture Web App

An interactive Christmas-themed web application that responds to hand gestures using MediaPipe and Three.js. Create magical Christmas moments with your hands! ✨

![Christmas Magic](https://img.shields.io/badge/Christmas-Magic-red?style=for-the-badge&logo=christmas)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## ✨ Features

- 🎄 **Tree Formation** - Beautiful 3D Christmas tree with golden particles, red lights, and gift boxes
- 🎁 **Explosion Effect** - Hand gestures trigger particle explosion with photo carousel
- 📸 **Photo Gallery** - 5 interactive photos that orbit and can be viewed in detail
- ❤️ **Love Message** - Special heart shape formation with "I LOVE YOU" message
- 🎵 **Background Music** - Festive audio that plays during the experience
- 🖐️ **Real-time Hand Tracking** - Using MediaPipe Hands for gesture recognition

## 🎮 Hand Gestures

| Gesture | Action |
|---------|--------|
| 🖐️ **Open Hand** | Explode particles & show photo carousel |
| 👌 **Pinch** (thumb + index) | Focus on selected photo |
| ✊ **Fist** | Return to Christmas tree formation |
| 🫶 **Two Hands Heart** | Show heart shape with love message |

## 🚀 Quick Start

### Running Locally

1. **Clone the repository**
```bash
git clone https://github.com/trtrantnt/christmas-magic.git
cd christmas-magic
```

2. **Start a local server**
```bash
# Using Python
python -m http.server 8000

# Or using Node.js
npx http-server -p 8000
```

3. **Open in browser**
```
http://localhost:8000
```

4. **Grant camera permission** when prompted and enjoy! 🎄

### Hosting on GitHub Pages

This project is configured to work with GitHub Pages automatically:

1. Push your code to GitHub
2. Go to **Settings** → **Pages**
3. Set **Source** to `Deploy from a branch`
4. Select **Branch**: `main`, **Folder**: `/ (root)`
5. Click **Save**
6. Wait 2-5 minutes for deployment

## 🛠️ Technologies Used

- **Three.js** (r128) - 3D graphics and particle systems
- **MediaPipe Hands** - Real-time hand tracking
- **Vanilla JavaScript** - No frameworks needed
- **Canvas API** - Procedural textures
- **HTML5 & CSS3** - UI and styling

## 📁 Project Structure

```
christmas-magic/
├── assets/
│   ├── images/             # Photo gallery
│   │   ├── image1.jpeg
│   │   ├── image2.jpeg
│   │   ├── image3.jpeg
│   │   ├── image4.jpeg
│   │   └── image5.jpeg
│   └── audio/
│       └── audio.mp3       # Background music
├── index.html              # Main application
└── README.md               # Documentation
```

## 🎨 Features Breakdown

### Particle Systems
- **2000 Gold Particles** - Form the main tree structure
- **300 Red Lights** - Blinking Christmas lights
- **150 Gift Boxes** - Red gift box particles

### Visual Effects
- Dynamic particle morphing (tree ↔ sphere ↔ heart)
- Smooth transitions with lerp interpolation
- Additive blending for glowing effects
- Real-time size and color animations
- Fog effect for depth perception

### Performance Optimizations
- Frame skipping (processes every 3rd frame)
- Efficient geometry updates
- Proper Three.js disposal
- Optimized texture generation

## 📝 License

MIT License - Feel free to use this project for your own Christmas celebrations!

## 👨‍💻 Author

Made with ❤️ for Christmas celebrations!

---

## 🌐 Live Demo

**🎄 Experience the magic here:** [https://trtrantnt.github.io/magic-christmas-tree/](https://trtrantnt.github.io/magic-christmas-tree/)

*Note: Requires a device with a working webcam and modern browser (Chrome, Edge, Firefox recommended)*