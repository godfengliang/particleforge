# ParticleForge — GPU Particle System Editor

Real-time GPU-accelerated particle system editor in your browser. Create stunning VFX with force fields, color gradients, and 12 presets — all running on WebGL shaders.

**Live Demo:** [particleforge-gpu.surge.sh](https://particleforge-gpu.surge.sh/)

## Features

- **50,000+ particles** — CPU simulation with GPU point-sprite rendering
- **12 presets** — Fireworks, Galaxy, Rain, Snow, Explosion, Tornado, Fountain, Fireflies, Matrix, Nebula, Sparkler, Portal
- **5 emitter shapes** — Point, Sphere, Cone, Ring, Disk
- **Force field system** — Gravity, wind, vortex, turbulence
- **Color gradients** — 3-stop gradient (start/mid/end) with color picker
- **Blend modes** — Additive and alpha blending
- **Trail effect** — Configurable motion trails
- **Orbit camera** — Drag to rotate, scroll to zoom, right-drag to pan
- **Touch support** — Mobile-friendly with pinch-to-zoom
- **Screenshot export** — Download as PNG
- **Real-time stats** — Particle count, FPS, draw time

## Tech

- WebGL point sprites for GPU-accelerated rendering
- Float textures for particle data upload (OES_texture_float)
- CPU-side Verlet-style simulation with drag
- Custom perspective and lookAt matrix math
- Single HTML file, zero dependencies

## License

MIT
