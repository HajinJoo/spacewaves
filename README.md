# 🚀 Space Waves

A retro neon side-scrolling space arcade game built with HTML5 Canvas and pure JavaScript — no dependencies required!

## 🎮 How to Play

Pilot your spaceship through increasingly dangerous waves of obstacles. Dodge asteroids, energy gates, and space debris for as long as you can!

### Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| Move Up | `↑` Arrow or `W` | Tap top half of screen |
| Move Down | `↓` Arrow or `S` | Tap bottom half of screen |
| Start / Restart | `Space` | Tap anywhere |

### Scoring

- **+points/second** — survive longer to score more
- **+5 NEAR MISS** — bonus points for threading the gap close to an obstacle

### Difficulty Waves

| Wave | Unlock Time | Obstacles |
|------|-------------|-----------|
| Wave 1: Asteroid Field | 0s | Asteroids |
| Wave 2: Energy Storm | ~20s | Asteroids + Energy Gates |
| Wave 3: Debris Cloud | ~40s | All types, faster |
| Wave 4: Chaos | ~63s | All types, even faster |
| Wave 5: Singularity | ~90s | Maximum chaos |

## 🚀 How to Run

Just open `index.html` in any modern browser — no server, no build step, no dependencies!

```bash
# Option 1: Double-click index.html in your file explorer

# Option 2: Use a simple local server
npx serve .
# or
python3 -m http.server 8080
```

## 🌐 Deploy to GitHub Pages

1. Go to your repository **Settings → Pages**
2. Under **Source**, select `main` branch and `/ (root)` folder
3. Click **Save**
4. Your game will be live at `https://<your-username>.github.io/spacewaves/`

## ✨ Features

- **Retro neon/synthwave** visual style with glowing effects
- **Parallax starfield** with 3 depth layers and nebula backdrop
- **Wave-pattern obstacles** — asteroids, energy gates, and debris on sinusoidal paths
- **Particle effects** — engine trail, explosion on death, floating score text
- **Screen shake** on near-misses and death for game feel
- **High score** saved to `localStorage`
- **Sound effects** via Web Audio API (synth engine noise, near-miss chime, explosion)
- **Responsive** — works on desktop and mobile browsers
- **Single file** — everything in one `index.html`

## 🛠️ Tech

- HTML5 Canvas 2D rendering
- 60fps via `requestAnimationFrame`
- Web Audio API for procedural sound effects
- `localStorage` for high score persistence
- Zero external dependencies