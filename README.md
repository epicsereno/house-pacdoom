# HOUSE PACDOOM

**Simple Pac-Man style meets Doom inside a house**

A playable browser arcade game: navigate a house floorplan maze, collect all the pellets, and shoot the chasing demons.

## Features
- Top-down house maze (rooms + hallways)
- Collect pellets (Pac-Man core)
- Shoot demons with cooldown (Doom flavor)
- Power pellets for temporary invincibility
- Dark atmospheric canvas rendering
- Score + lives + local high score
- Keyboard controls + responsive

## Controls
- **WASD** or **Arrow Keys**: Move
- **Space**: Shoot in facing direction
- Goal: Clear all pellets without losing all lives

## Run locally
```bash
git clone https://github.com/epicsereno/house-pacdoom.git
cd house-pacdoom
npm install
npm run dev
```

Open the local URL (usually http://localhost:5173).

## Build for production / GH Pages
```bash
npm run build
```
The `dist/` folder is ready. For GitHub Pages, enable it in repo settings (source: gh-pages branch or use the included workflow).

## Tech
Vite + React + TypeScript + Tailwind CSS + HTML5 Canvas

Made as a fun mashup of classic arcade and FPS vibes, set entirely inside a house.
