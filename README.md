# Intergalactic Neon

A complete vertical shoot 'em up space game built entirely using **HTML5 Canvas API** and **Web Audio API**. Zero external dependencies, single file architecture, and highly optimized for both mobile (touch) and desktop platforms.

## Features
- **Aesthetic Cyberpunk Visuals**: Beautiful glowing retro effects, radial gradient drifting nebulae, and 3 parallax starfield layers.
- **Procedural Synthesizer Soundtrack**: Real-time ambient audio pad generated dynamically using oscillator and convolver nodes (A minor chords), matching arcade SFX for hits, lasers, and explosions.
- **Original Vector Ships**: Custom, dynamically drawn vector ship designs for player and three types of enemies.
- **Dynamic Wave System**: Grid, V, and sine-wave staggered formations with progressive scaling difficulty.
- **Mobile First Touch & Desktop Controls**: Responsive screen scaling with support for touch-drag, mouse, and keyboard movement.

## Play Locally
You can open `index.html` directly in any web browser, or serve it using a lightweight HTTP server:
```bash
npx serve .
# or
python -m http.server 8000
```

## Deployment
This game is fully compatible with static hosting solutions such as **GitHub Pages**. Simply enable GitHub Pages in your repository settings pointing to the `main` branch.
