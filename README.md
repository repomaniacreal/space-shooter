# 🚀 Neon Space Shooter

A fast-paced single-file HTML5 space shooter with neon visuals. Drag your ship, dodge enemy fire, and blast through escalating waves — including a boss every 5th wave!

## How to Play

- **Drag your finger** (or mouse) to move the ship — fire is **automatic**, so focus on dodging!
- Destroy enemy ships to score points and build **kill streaks** (5+ kills triggers a RAMPAGE bonus banner)
- Grab falling **power-ups** to upgrade your weapons
- Survive as many waves as you can — a new boss arrives every 5 waves
- You have 3 hearts ❤️; game over when they're gone

## Power-ups

| Icon | Effect |
|---|---|
| 🔵 Double | Double shot (12s) |
| 🟠 Spread | Spread shot (12s) |
| 🟡 Wide | Wide bullets (12s) |
| 🔴 Laser | Piercing laser (12s) |
| 🟣 Rapid | Rapid fire (8s) |
| 🟢 Shield | One-hit shield (10s) |
| ❤️ Heal | +1 HP |

## Controls

| Input | Action |
|---|---|
| Drag / mouse move (hold) | Move ship |
| Arrow keys / WASD | Move ship |

## Features

- Neon-glow canvas art: nebula background, parallax starfield, screen shake
- 4 enemy types (scout, fighter, tank, boss) with distinct movement and attack patterns
- Kill-streak RAMPAGE banners and wave announcements
- 7 power-up types with on-screen timers
- Boss HP bar and mini HP bars on damaged enemies
- Synthesized sound effects via Web Audio API (no audio files)
- Persistent best score (localStorage)

## Run It

Just open `index.html` in any modern browser — no build step, no dependencies, no server required. Works with both mouse and touch.

## Tech

- Single HTML file, vanilla JavaScript + Canvas 2D
- Web Audio API for all sound effects
