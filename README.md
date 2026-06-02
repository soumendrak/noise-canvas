<div align="center">

# Noise Canvas

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/noise-canvas/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <rect x="16" y="24" width="108" height="80" rx="4" fill="#0d0d1a"/>
  <circle cx="40" cy="45" r="15" fill="#ff6b35" opacity="0.4"/>
  <circle cx="70" cy="60" r="20" fill="#ff8c42" opacity="0.3"/>
  <circle cx="100" cy="50" r="12" fill="#d94f1a" opacity="0.35"/>
  <circle cx="55" cy="80" r="18" fill="#ff6b35" opacity="0.25"/>
  <circle cx="90" cy="75" r="14" fill="#ff8c42" opacity="0.2"/>
  <text x="70" y="128" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#8a8a9a">click for fullscreen</text>
</svg>

**Hypnotic real-time Perlin noise visualisation with adjustable parameters.**

**Live:** [https://soumendrak.github.io/noise-canvas/](https://soumendrak.github.io/noise-canvas/)

</div>

---

## Features

- Real-time Perlin noise rendered on canvas at 60fps
- Adjustable frequency, octaves, and speed via sliders
- 4 colour schemes: Fire, Ocean, Aurora, Grayscale
- Click to toggle full-screen screensaver mode (hides UI)
- FPS counter in the corner
- Dark theme with orange accent (#ff6b35)

## How It Works

A value noise function generates pseudo-random gradients at integer lattice points. Fractal Brownian Motion (FBM) layers multiple octaves of noise at decreasing amplitudes and increasing frequencies. The combined value maps to a colour using the selected colour scheme's palette. `requestAnimationFrame` loops at 60fps, with a time offset incrementing each frame to create animation.

## Usage

1. Open `https://soumendrak.github.io/noise-canvas/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/noise-canvas.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
