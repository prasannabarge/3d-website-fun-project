# 🚀 Alex Vance — World-Class 3D Digital Showcase & Portfolio

An ultra-modern, high-performance, single-file 3D WebGL interactive showcase and developer portfolio built with modern web technologies, real-time shaders, and dynamic visual capabilities.

![Version](https://img.shields.io/badge/version-2026.9.0-00f0ff?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-7000ff?style=for-the-badge)
![Build](https://img.shields.io/badge/build-single--file_html-10b981?style=for-the-badge)

---

## ✨ Key Features

- **🌌 Interactive 3D WebGL Canvas Engine**: Real-time background particle starfield with interactive mouse parallax positioning built using Three.js.
- **🎮 3D Canvas Playground (Lab 3D)**: Live controls allowing users to adjust shape geometries (Icosahedron, Torus Knot, Sphere), manipulate rotation speed, adjust particle density, and toggle wireframe rendering mode on the fly.
- **🎨 Dynamic Theme Palette Switcher**: Hot-swappable visual presets powered by CSS custom variables:
  - **Neon Cyber** (`#00f0ff` / `#ff007f`)
  - **Deep Space** (`#a855f7` / `#3b82f6`)
  - **Emerald Glow** (`#10b981` / `#84cc16`)
- **💻 Interactive Command Line Interface (CLI)**: Built-in executable bash-style terminal supporting commands like `help`, `skills`, `projects`, `matrix`, `clear`, and `time`. Includes an authentic Matrix digital rain canvas overlay toggle!
- **🔊 Web Audio API Synthesizer Engine**: Synthesized real-time audio feedback for interactive elements, hover actions, theme updates, and form actions with a quick mute toggle.
- **💎 Glassmorphic UI/UX Design System**: High-gloss frosted panels, responsive grid architectures, dynamic gradient typography, and custom ambient neon glows.
- **📂 Curated Showcase & Capabilities Matrix**: Interactive category filtering for projects, architecture modal detail viewer, and quantitative metric counter animations using GSAP.
- **⚡ Zero Build Setup**: Fully self-contained inside a single `.html` file via lightweight CDN integrations.

---

## 🛠️ Tech Stack & Dependencies

- **HTML5 & CSS3** — Native custom variables & modern layout structure.
- **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first styling framework.
- **[Three.js](https://threejs.org/) (r128)** — 3D WebGL graphics renderer.
- **[GSAP](https://greensock.com/gsap/) & ScrollTrigger** — Fluid scroll-driven layout animations.
- **[Lucide Icons](https://lucide.dev/)** — Modern vector icons.
- **Web Audio API** — Programmatic sound synthesis without external audio files.

---

## 🚀 Quick Start Guide

Since the entire application is architected within a **single, standalone HTML file**, no complex setup, Node.js packages, or build processes are required!

### Option 1: Direct File Execution
1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/3d-portfolio.html.git
   ```
2. Open `index.html` directly in any modern Web Browser (Chrome, Firefox, Edge, Safari, Brave).

### Option 2: Local HTTP Server (Recommended)
To prevent CORS or asset loading restrictions in certain browsers:
```bash
# Using Python 3
python -m http.server 8000

# Or using Node.js npx http-server
npx http-server . -p 8000
```
Navigate to `http://localhost:8000` in your web browser.

---

## 🖥️ Interactive CLI Terminal Commands

Open the **CLI Terminal** section or scroll down to test the following commands:

| Command | Description |
| :--- | :--- |
| `help` | Lists all available console commands |
| `skills` | Displays core frontend, WebGL, and cloud skill breakdown |
| `projects` | Outputs the current list of featured showcase projects |
| `matrix` | Toggles the Matrix digital rain overlay effect across the viewport |
| `clear` | Wipes clean the terminal log terminal view |
| `time` | Displays the current system timestamp in ISO format |

---

## 🎨 Customization & Theme Config

You can easily customize default colors by modifying the `:root` variables in the inline `<style>` section of `index.html`:

```css
:root {
    --color-primary: #00f0ff;
    --color-secondary: #ff007f;
    --color-accent: #7000ff;
    --glow-color: rgba(0, 240, 255, 0.35);
}
```

---

<p center align="center">
  Crafted with ❤️ and WebGL precision by <b>Alex Vance</b>
</p>