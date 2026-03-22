# 3D Matrix Multiplication

Interactive 3D visualization of matrix multiplication in the browser using Three.js.

![Three.js](https://img.shields.io/badge/Three.js-0.164-blue)
## Features

- **3D Animation** — Matrix A (blue), Matrix B (purple), and Result C (green) as floating cubes in 3D space
- **Step-by-step Computation** — shows for each element C[i][j] which row and column are being multiplied
- **Particles & Beams** — glowing connection lines and flying particles visualize the data flow
- **Orbit Camera** — freely rotatable camera via mouse (drag, scroll, right-click)
- **Configurable Matrices** — dimensions up to 5x5, all values freely editable
- **Speed Control** — smoothly adjust animation speed
- **Zero Dependencies** — single HTML file, Three.js loaded via CDN

## Quick Start

```bash
# Start a local server
python3 -m http.server 8080

# Open browser
open http://localhost:8080
```

Alternatively, open `index.html` directly in a modern browser (requires Import Maps support).

## Usage

1. Set **dimensions** (Matrix A: M x N, Matrix B: N x P)
2. **Enter values** or click **Zufall** (Random)
3. Click **Berechnen** (Compute) — the animation shows the multiplication step by step
4. **Rotate camera** with mouse, adjust **speed** with the slider
5. Click **Zuruecksetzen** (Reset) to start over

## Tech

- [Three.js](https://threejs.org/) — 3D rendering with WebGL
- Vanilla JavaScript (ES Modules)
- No build tools required

