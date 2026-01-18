# Draw With Flowers – WebGL Canvas

![Draw With Flowers Screenshot](flower.png)

An interactive WebGL sketch where you **draw with procedural flowers** using a custom GLSL fragment shader and Three.js.  
Click anywhere on the canvas to grow a new flower, and use the “clean the screen” button to reset the canvas. [web:60][web:74]

---

## 🌐 Live Demo

👉 **Try it in your browser:**  
(https://andrew-fernando-15.github.io/click-to-grow-flower/index.html)

_Update the URL after you enable GitHub Pages for this repo._ [web:106]

---

## ✨ Highlights

- Click or tap anywhere to grow **randomized flowers with stems** on a full‑screen canvas. [web:74]  
- Procedural shapes driven entirely by a **GLSL fragment shader** (no image textures). [web:60]  
- Uses a **feedback render target** so previous flowers stay on the screen until cleared. [web:71]  
- Simple **“clean the screen”** control to wipe the canvas and start fresh. [web:72]

---

## 🧩 Tech Stack

- **HTML5** – canvas and basic layout  
- **CSS3** – fullscreen layout and minimal styling  
- **Vanilla JavaScript** – input handling and render loop  
- **Three.js** – WebGL renderer, shaders, and render targets [web:123]

No frameworks or UI libraries – everything is hand‑coded to focus on shaders and core WebGL concepts.

---

## ▶️ Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/andrew-fernando-15/click-to-grow-flowers.git
   cd click-to-grow-flowers
