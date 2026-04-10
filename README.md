# 🎵 RhythmBeast

> A rhythm-driven snake game that reacts to your music in real time.

Upload any song and the game comes alive — the snake surges on bass drops, obstacles spawn on the beat, and the entire visual world pulses to your track. Eat apples, build combos, survive power-ups and hazards, and see how long you last.

---

## Features

**Gameplay**
- Beat-sync speed — the snake automatically surges faster on bass drops
- Combo chain with a decay timer — keep eating or your streak breaks within 5 seconds
- Level-up system — every 100 points the snake speeds up mid-game with a banner alert
- Power-up apples — Slow-Mo, Shield, Magnet, and 2× Score multiplier, each with a distinct shape and colour
- Ghost apples — fake apples that look almost real but cost you points and break your combo
- Beat-spawned obstacles — cracked red blocks appear every few beats and must be avoided
- Shield absorbs one hit from self-collision or an obstacle before breaking
- Magnet pulls nearby apples toward the snake head

**Visuals**
- Glowing snake trail behind the head
- Apple pop-in animation when new apples spawn
- Spinning shapes on power-up apples
- Screen shake on death and obstacle hits
- Beat flash overlay on every detected bass hit
- Floating score pop-ups on every eat
- Milestone and level-up banners across the canvas
- Subtle grid overlay on the play area
- Full-screen 3D isometric visualizer below the game with adjustable responsiveness

**Progression**
- 6 unlockable snake skins — Rainbow, Neon, Fire, Ice, Galaxy, Void
- Skins unlock permanently in your browser based on all-time high score
- High scores saved per song per difficulty
- Song library — recently played tracks saved for one-click reload

**End Screen**
- Full stats breakdown — best combo, apples eaten, power-ups collected, level reached, time survived
- Detailed pause screen shows live stats mid-game

**Modes**
- Normal — survive as long as possible
- Timed Challenge — race to the highest score before the song ends, with a combo bonus added at the end

---

## How to Play

1. Download or clone the repo
2. Double-click `RhythmBeast.html` — no install, no server needed
3. Upload any MP3, WAV, OGG, or FLAC file — or paste a direct audio URL
4. Pick a difficulty and skin, then hit Start

**Controls:** Arrow keys or WASD to move · ESC to pause · SPACE to start

---

## Building a Desktop EXE (Windows)

The game runs as a standalone HTML file, but if you want a proper native app:

1. Install [Node.js](https://nodejs.org) (LTS version)
2. Run `BUILD.bat`
3. Your EXE appears at `dist/RhythmBeast.exe`

Built with [Electron](https://www.electronjs.org) — the same technology Discord and VS Code use.

---

## Tech Stack

- Vanilla JavaScript — no frameworks, no build step
- Web Audio API for real-time beat detection and frequency analysis
- Canvas 2D for all rendering
- Electron for the optional desktop build

---

## Difficulties

| Difficulty | Snake Speed | Score Multiplier | Ghost Rate |
|---|---|---|---|
| Easy | Slow | ×1.0 | Rare |
| Medium | Normal | ×1.5 | Occasional |
| Hard | Fast | ×2.0 | Common |
| Insane 💀 | Very fast | ×3.0 | Frequent |

---

## Power-ups

| Apple | Effect | Duration |
|---|---|---|
| 🔵 Blue diamond | Slow-Mo — halves snake speed | 8 seconds |
| 🟠 Orange hexagon | Shield — absorbs one fatal hit | Until used |
| 🟣 Purple diamond | Magnet — pulls apples toward you | 7 seconds |
| ⭐ Gold star | 2× Score — doubles all points earned | 9 seconds |
| 👻 Grey circle | Ghost — fake apple, costs points and breaks combo | — |

---

## Skins

| Skin | Unlock At |
|---|---|
| 🌈 Rainbow | Default |
| 💜 Neon | 50 pts |
| 🔥 Fire | 150 pts |
| ❄️ Ice | 350 pts |
| 🌌 Galaxy | 700 pts |
| 🕳️ Void | 1200 pts |

---

Made with 🎵 — works with any audio file you own.
