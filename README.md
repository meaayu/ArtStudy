# ArtStudy 🎨

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

ArtStudy s a cinematic interactive designed for artists to study light, form, and anatomy in a distraction-free, high-fidelity environment. 

Experience a professional-grade drawing workspace right in your browser, featuring real-time 3D models, gesture drawing sessions, and a precision-engineered brush engine.

## ✨ Modules

### ✍️ Drawing Session (NEW)
A dedicated environment for speed-drawing and rhythm practice.
*   **Stabilized Brush Engine**: High-fidelity quadratic curve interpolation with velocity-responsive tapering for professional stroke quality.
*   **Timed Sessions**: Rapid iteration cycles (30s to 300s) to train economy of line.
*   **Wacom/Tablet Support**: Fully compatible with stylus pressure (Stroke Width & Opacity).
*   **History System**: Robust Undo/Redo with offscreen canvas buffering for flicker-free resizing.
*   **Floating Reference Window**: Customizable reference placement that stays out of your drawing path.

### 🗿 Head Study
Interactive anatomical analysis using high-fidelity 3D assets.
*   **Reference Models**: Switch between Loomis, Asaro Planes, and Skull structures.
*   **Cinematic Rendering**: Precise shadow projection for planar study.
*   **Integrated Draw Mode**: Capture anatomical notes directly over the model.

### 📐 Form Study
Geometric analysis for understanding structural light.
*   **Material Lab**: Real-time adjustment of Metalness and Roughness for complex shading study.
*   **Depth Viz**: Technical "INF.0" depth visualization for perspective analysis.
*   **Interactive Lighting**: Manipulate global light sources in a 3D environment.

## ⌨️ Keyboard Shortcuts

### 🎨 Drawing Session Controls
| Key | Action |
| :--- | :--- |
| `Space` | Pause/Resume Timer |
| `S` | Skip to next reference |
| `B` / `E` | Switch between Brush and Eraser |
| `[` / `]` | Adjust Brush Size |
| `{` / `}` | Adjust Brush Opacity |
| `C` | Toggle Zen Canvas (White / Dark) |
| `D` | Instant Export (PNG) |
| `Ctrl + Z` | Undo |
| `Ctrl + Shift + Z` | Redo |
| `Esc` | Terminate Session / Home |

### 🛠️ Universal Navigation
| Key | Action |
| :--- | :--- |
| `1` | Switch to Form Study |
| `2` | Switch to Head Study |
| `3` | Switch to Drawing Session |

## 🛠️ Technology Stack

*   **Core**: React 18+ + TypeScript
*   **3D Engine**: Three.js + @react-three/fiber
*   **Animation**: Motion (motion/react)
*   **Icons**: Lucide React
*   **Canvas**: High-performance HTML5 2D Context with offscreen stabilization

---
*Created for the modern draftsman seeking precision and flow.*
