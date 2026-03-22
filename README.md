# 🍉 Fruit Drop

A Suika-style fruit merge game built as a Progressive Web App. Drop fruits into the box — when two identical fruits touch, they merge into the next bigger fruit!

## Play

**[Play Online →](https://kevincolten.github.io/fruit-drop/)**

## How to Play

- **Tap/click** to position your fruit, **release** to drop
- When two identical fruits collide, they **merge** into the next fruit in the chain
- Chain: Cherry → Strawberry → Grape → Orange → Lime → Apple → Peach → Coconut → Pineapple → Melon → Watermelon
- The box grows infinitely — keep stacking!
- Build **combos** by triggering chain merges

## Features

- 🎵 Synthesized sound effects (Web Audio API)
- 📱 Responsive — adapts to any screen size mid-game
- 🎮 Physics-based gameplay (Matter.js)
- ✨ Particle effects, screen shake, and combo system
- 📲 Installable as a PWA for offline play
- 🏆 Local high score tracking

## Tech Stack

- Vanilla JavaScript + Canvas 2D
- [Matter.js](https://brm.io/matter-js/) for physics
- [Fredoka](https://fonts.google.com/specimen/Fredoka) font
- Service Worker for offline caching

## Install as PWA

1. Visit the hosted page in Chrome/Safari
2. Click "Add to Home Screen" / install prompt
3. Play offline anytime

## Local Development

Just serve the files with any static server:

```bash
npx serve .
```

## License

MIT
