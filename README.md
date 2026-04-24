# VR Solar System

An interactive **3D Solar System simulation** built with **HTML, JavaScript, and Three.js**.
This project renders the Sun, planets, Saturn’s rings, and a dynamic star field in a browser with smooth animations and VR-style mouse camera controls.

---

## Features

* 🌞 Realistic Sun at the center of the scene
* 🪐 Orbiting planets:

  * Mercury
  * Venus
  * Earth
  * Mars
  * Jupiter
  * Saturn
* 💍 Saturn ring system
* ✨ Procedural star background
* 🎮 Mouse-look camera controls
* 🖱️ Pointer lock support for immersive movement
* 📱 Responsive fullscreen canvas
* ⚡ Lightweight and runs directly in browser

---

## Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript
* **3D Engine:** Three.js (r128)
* **Rendering:** WebGL

---

## How to Run

### Option 1: Open Directly

1. Download the project file.
2. Open the `.html` file in Chrome / Edge / Firefox.

### Option 2: Use Live Server

Recommended for best performance:

```bash
# If using VS Code
Install Live Server extension
Right click file → Open with Live Server
```

---

## Controls

* **Move Mouse** → Look around the solar system
* **Click Screen** → Enable pointer lock mode
* **Resize Window** → Scene auto-adjusts

---

## Project Structure

```text
VR-Solar-System/
└── index.html
```

---

## How It Works

### Scene Setup

Creates:

* `THREE.Scene()`
* Perspective camera
* WebGL renderer

### Lighting

* Ambient light
* Point light at the Sun

### Planets

Each planet is created using:

* Sphere geometry
* Pivot object for orbit rotation

### Animation Loop

Uses `requestAnimationFrame()` to:

* Rotate planetary pivots
* Render each frame smoothly

---

## Browser Requirements

* WebGL enabled
* Modern browser:

  * Chrome
  * Edge
  * Firefox

---

## Future Improvements

* 🌍 Planet textures
* 🌙 Moon orbiting Earth
* ☄️ Asteroids / comets
* 📱 Mobile touch controls
* 🥽 WebXR / VR headset support
* 🔊 Space sound effects
* 📊 Planet info labels

---

## Educational Value

Great beginner project for learning:

* 3D graphics
* WebGL concepts
* Three.js basics
* Camera movement
* Animation loops

---

## Author

Built as an interactive browser-based space simulation project.

---

## License

MIT License
