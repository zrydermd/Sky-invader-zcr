# Sky Invaders 🛸

A polished, mobile-first Space Invaders game in a single self-contained `index.html` — no build step, no dependencies.

**Play it:** https://zrydermd.github.io/Sky-invader-zcr/

## Controls

- **Mobile:** swipe/drag anywhere to steer your ship — it auto-fires
- **Desktop:** arrow keys to move, space to fire faster

## Features

- Canvas rendering with glowing ships, pixel-art aliens, particles, and screen shake
- Score + high score persisted in `localStorage`
- Waves get faster as you clear them (and as the swarm thins out)
- Start screen, game-over screen with restart
- Scroll/zoom locked while playing for a clean fullscreen feel

## Deployment

Deployed automatically to GitHub Pages by `.github/workflows/deploy.yml` on every push to `main`.
