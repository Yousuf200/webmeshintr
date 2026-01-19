# ✨ Gesture Particle Playground

A fun experiment mixing **hand tracking + Three.js particles** to create interactive shapes controlled by your fingers.

```bash
https://yousuf200.github.io/webmeshintr/
```
I built this just for fun—no deep science, just curiosity about how digital gestures can feel "magical" on screen 😄.

---

## 🎮 Features & Interactions

The app tracks your hand via **MediaPipe** and renders thousands of particles in **Three.js**.

* **Index Finger:** Attracts particles to your fingertip.
* **Pinch:** Compresses the particle cloud.
* **Open Hand:** Relaxes the shape back to its original state.

### ⌨️ Keyboard Controls

| Key | Resulting Shape |
| :--- | :--- |
| **H** | Heart ❤️ |
| **B** | Ball ⚽ |
| **S** | Saturn 🪐 |

---

## 🚀 Getting Started

Because the browser requires secure contexts for webcam access, you must run this on a local server (it won't work by just opening the `.html` file directly).

### Option 1: Python
Run this command in your project folder:
```bash
python -m http.server 8000
```
Then open: http://localhost:8000

### Option 2: VS Code
Use the Live Server extension → Click Go Live.

---

### 🧪 Tech Stack
Three.js – High-performance particle rendering.

MediaPipe Hands – Real-time ML gesture tracking.

Vanilla JavaScript – No frameworks, just trial and error.

---

### ⚠️ Notes
Browser: Works best in Chrome.

Hardware: Requires webcam permission.

Environment: Lighting matters! Clearer hand visibility = smoother tracking.

Why I made this: No big goal—I just wanted to move digital particles with my hand and feel like a wizard for 5 minutes. Mission accomplished.

---

### 📜 License
Do whatever you want with it.
