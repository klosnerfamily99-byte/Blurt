# BLURT

A browser-based battle royale — drop into a Hunger-Games-style arena with 99 bots, pick one of 5 skins, and watch the red storm close in. Last one standing wins.

## Play it
Just open `index.html` in any modern browser (desktop or mobile Safari/Chrome). No build step, no installs.

## Host it free on GitHub Pages
1. Create a new GitHub repo (e.g. `blurt`).
2. Upload `index.html` to the repo root.
3. Go to **Settings → Pages**, set source to the `main` branch / root folder.
4. Wait a minute, then visit `https://<your-username>.github.io/<repo-name>/` — works on iPhone Safari, just like a regular website.

## Controls
**Desktop:** WASD to move, mouse to look (click to lock pointer), left-click to fire.
**iPhone/mobile:** left-side joystick to move, right-side drag to look, FIRE button to shoot.

## Skins
- **Recruit** – balanced, no bonus
- **Wraith** – faster, smaller hitbox
- **Brute** – more HP, hits harder, slower
- **Medic** – regenerates HP over time
- **Marksman** – long range, big damage, slower fire rate

## Notes
This is a simplified, single-file Three.js game (no external build tools) so it's easy to drop straight into GitHub Pages. Everything — map, storm, bots, AI, skins — lives in `index.html`.
