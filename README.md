# NEON RAID

A modern neon-retro browser tribute to the classic 1982 river shooter. One file, zero dependencies, zero build step — runs anywhere a browser runs.

**Play locally:** just double-click `index.html`.

## Features

Procedurally generated river that narrows as you advance through sectors, with a bridge guarding the end of each one. Enemy helicopters, patrol ships, and (from Sector 2) fast crossing jets. Fuel management — fly over FUEL depots to refuel, or shoot them for points. Classic scoring (ship 30 · helicopter 60 · fuel 80 · jet 100 · bridge 500), persistent Hall of Legends top-10 leaderboard saved in your browser, synthesized retro sound (no audio files), particle explosions, screen shake, and crisp vector graphics that render at your display's native resolution (Retina/4K sharp).

## Controls

| Action | Desktop | Mobile |
|---|---|---|
| Steer | ← → or A D | drag finger left/right |
| Throttle | ↑ ↓ or W S | drag finger up/down |
| Fire | Space or X | hold (autofire) |
| Pause / Mute / Legends | P / M / L | ♪ button |

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `neon-raid`).
2. Push these two files:
   ```bash
   git init
   git add index.html README.md
   git commit -m "NEON RAID v1"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/neon-raid.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / root → Save**.
4. After a minute, the game is live at `https://YOUR_USERNAME.github.io/neon-raid/`.

No build step, no dependencies — GitHub Pages serves `index.html` as-is. High scores are stored per-browser via localStorage.
