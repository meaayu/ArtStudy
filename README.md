<div align="center">
  <img src="logo.svg" width="120" alt="ArtStudy Atelier Logo" />
  <h1>ArtStudy Atelier</h1>
  <p><i>A cinematic interactive digital atelier for high-fidelity light, form, and anatomy study.</i></p>

  [![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
  [![Three.js](https://img.shields.io/badge/Three.js-R160-black?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
</div>

---

## 🏛️ The Philosophy

**ArtStudy** is designed as a distraction-free, high-performance workspace for the modern draftsman. Inspired by traditional ateliers and cinematic rendering, it bridges the gap between digital convenience and classical anatomical study. Every module is engineered for **flow**, providing the tools necessary for precision without the clutter of traditional creative software.

## 🎨 Professional Modules

### 🗿 Anatomy Study (`HeadStudy`)
Master the human portrait through interactive anatomical analysis.
- **Reference Spectrum**: Seamlessly toggle between **Loomis Head**, **Asaro Planes**, and **Skull** structures.
- **Direct Overlay**: Capture anatomical insights with an integrated digital drawing layer directly atop 3D subjects.
- **Planar Clarity**: Analyze light fall-off and shadow termination on precisely rendered surfaces.

### 📐 Form Study (`FormStudy`)
Universal geometric analysis for understanding structural light and perspective.
- **Material Laboratory**: Manipulate **Roughness** and **Metalness** in real-time to study complex material optics.
- **Optic Control**: Switch between **Perspective** (cinematic depth) and **Orthographic** (blueprint precision) projections.
- **Depth Viz**: Technical "INF.0" visualization for advanced foreshortening analysis.
- **Lighting Control**: Dynamic global light manipulation for rapid shading studies.

### ✍️ Drawing Session (`GestureStudy`)
A high-performance environment for speed-drawing and rhythmic practice.
- **Stabilized Brush Engine**: Advanced quadratic curve interpolation with velocity-responsive tapering for natural stroke quality.
- **Floating Reference System**: A draggable, resizable reference window that optimizes your ergonomic workspace.
- **Timed Iteration**: Cycle through rapid gesture sessions (30s to 5m) to train economy of line.
- **Zen Mode**: Toggle between High-Contrast White and Deep Charcoal canvases via simple keyboard shortcuts.

---

## ⌨️ Universal Control Scheme

### 🛠️ Global Navigation
| Key | Action |
| :--- | :--- |
| `1` | Switch to **Form Study** |
| `2` | Switch to **Head Study** |
| `3` | Switch to **Drawing Session** |
| `Esc` | Return to Atelier Entrance / Exit Study |

### 🖋️ Creative Controls
| Key | Action |
| :--- | :--- |
| `B` / `E` | Toggle **Brush** / **Eraser** |
| `[` / `]` | Adjust Brush **Size** |
| `{` / `}` | Adjust Brush **Opacity** |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `D` | Instant Export (PNG) |
| `C` | Toggle Canvas Contrast (**White** / **Dark**) |

---

## 🛠️ Technical Fabric

- **Framework**: React 19 + TypeScript
- **3D Engine**: Three.js + React Three Fiber
- **Vector Dynamics**: Custom HTML5 Canvas engine with offscreen stabilization and DPR-aware scaling.
- **Motion**: Motion (formerly Framer Motion) for cinematic UI transitions.
- **Styling**: Tailwind CSS 4.0 with customized "Atelier" design tokens.

---

<div align="center">
  <p><i>Created for the artist who values precision, flow, and the pursuit of mastery.</i></p>
  <p>© 2026 ArtStudy Atelier</p>
</div>
