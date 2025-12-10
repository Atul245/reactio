# 🌟 Kinetic Gesture Particles - Ultimate Edition

![Project Status](https://img.shields.io/badge/Status-Active-brightgreen) ![Tech](https://img.shields.io/badge/Three.js-WebGL-black) ![AI](https://img.shields.io/badge/MediaPipe-Computer%20Vision-blue)

A mesmerizing, interactive 3D particle system controlled entirely by hand gestures. This project fuses **Computer Vision** (MediaPipe) with **High-Performance 3D Graphics** (Three.js) to create a "Minority Report" style interface where you can sculpt, explode, and morph digital matter in real-time.

---

## ✨ Features

* **⚡ Real-time Hand Tracking:** Detects single and dual hands with high precision.
* **🌌 3D Particle Physics:** Simulates 8,000+ particles with inertia, friction, and velocity.
* **💡 Neon Post-Processing:** Integrated Bloom/Glow effects for a cyberpunk aesthetic.
* **🧲 Physics Interaction:** Includes gravity wells (Black Hole), repulsion fields, and elastic scaling.
* **🔤 Text-to-Particle:** Type any name or word to generate it instantly in 3D space.
* **🎨 Dynamic Colors:** Cycle through neon palettes using gestures.

---

## 🎮 Gesture Control Guide

Control the simulation using your webcam. Ensure your hand is visible and well-lit.

### 1️⃣ Single Hand Controls
| Gesture | Icon | Action | Description |
| :--- | :---: | :--- | :--- |
| **Open Hand** | 🖐️ | **Rotate View** | Move your hand around to rotate the 3D camera angle. |
| **Tilt Wrist** | ↪️ | **Spin (360°)** | Tilt your hand left or right (like turning a doorknob) to spin the object. |
| **Rock Sign** | 🤘 | **Next Shape** | Extend Index + Pinky fingers. Switches to the next geometric shape. |
| **Peace Sign** | ✌️ | **Swap Color** | Show a "V" sign. Cycles through neon color palettes. |
| **Fist** | ✊ | **Black Hole** | Close your hand tight. Creates a gravity well that sucks all particles in. |

### 2️⃣ Dual Hand Controls
| Gesture | Icon | Action | Description |
| :--- | :---: | :--- | :--- |
| **Stretch** | ↔️ | **Rubber Band** | Move hands apart to stretch the shape; bring them close to compress it. |
| **Clap** | 🙌 | **Sonic Blast** | Bring hands together fast. Causes a chaotic particle explosion. |

---

## 🛠️ Technology Stack

* **[Three.js](https://threejs.org/):** WebGL rendering engine for the 3D scene.
* **[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html):** Machine learning pipeline for hand tracking.
* **[Three.js Post-Processing](https://github.com/mrdoob/three.js/tree/master/examples/jsm/postprocessing):** UnrealBloomPass for the glow effect.
* **Tailwind CSS:** For the glassmorphism UI overlay.
* **Lucide Icons:** For the UI iconography.

---

## 🚀 How to Run Locally

Because this project uses the user's camera, browsers typically require it to be served over `localhost` or `HTTPS` (not just opening the file directly).

### Method: VS Code (Recommended)
1.  Install the **"Live Server"** extension in VS Code.
2.  Right-click `index.html` and select **"Open with Live Server"**.

---

## ⚙️ Customization

You can tweak the physics and visuals in `script.js`:

* **Particle Count:** Change `this.count = 8000;` (Higher = more detail, Lower = faster performance).
* **Bloom Strength:** Adjust `bloomPass.strength = 1.8;` for more or less glow.
* **Colors:** Modify the `this.colorList` array to add your own themes.

---

## 📜 License

This project is open-source. Feel free to use it for portfolios, learning, or experiments.

**Built with ❤️ using Three.js & MediaPipe.**