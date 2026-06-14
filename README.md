# Block Survival

A Minecraft-flavored, third-person wave-survival shooter that runs entirely in the browser.
Built with [Three.js](https://threejs.org/) in a single `index.html` file — no build step.

## Play

Open `index.html` in a browser (or visit the GitHub Pages link if enabled).

> It must be served over `http(s)` (the page uses an ES-module import map + CDN). Locally:
> ```bash
> python3 -m http.server 8000
> # then open http://localhost:8000
> ```

## Controls

**Keyboard**
- **Arrow keys** — Move
- **A / D** — Turn the view left / right
- **S** — Shoot (hold for automatic guns)
- **R** — Reload
- **B** — Open the upgrade shop
- **1–5** — Switch between owned weapons
- Mouse (optional): drag to look, press to shoot

**iPad / touch** — on-screen sticks (move + look), a **FIRE** button, **RELOAD**, and a **SHOP** button.

## Gameplay

- Survive endless waves of mobs: **zombies, skeletons (ranged), creepers (explode), spiders (fast swarm), endermen (teleport), and slimes (split when killed)**.
- Killing mobs earns 🪙 **tokens** (chance-based drops; special mobs always drop and are worth more).
- Press **B** to spend tokens on better guns (Pistol → SMG → Rifle → Shotgun → Diamond Cannon) and stat upgrades (max HP, damage, reload speed, move speed).

Made for the family. 🟩
