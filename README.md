# Why The Flying Face

**Why The Flying Face** is a chaotic, personality-driven Flappy Bird clone where the player uploads a photo, the game detects the face, crops it into a circular sprite, and sends it flying through a gauntlet of pipes, hazards, powerups, and shifting biomes.

Developed by **Bilal Tariq — Sentientsaur on Itch.io**.

## About The Game

Why The Flying Face turns a familiar arcade format into something more personal, expressive, and ridiculous in the best way. Instead of controlling a generic bird, players fly as a detected face from their own uploaded image. The game automatically crops the face region, removes the surrounding photo context, and uses it as the playable character.

The experience starts simple, then escalates through five distinct biomes with changing visuals, obstacles, physics, and pacing. Each biome introduces a new layer of pressure while keeping the core loop fast, readable, and replayable: flap, dodge, collect, survive, and chase a higher score.

## Features

- **Face-based player sprite** using uploaded photos and automatic face detection.
- **Circular cropped face rendering** with no bird body, wings, or beak.
- **Classic Flappy-style controls** with spacebar, tap, or click.
- **Five biome progression system:**
  - Valley
  - Desert
  - Glacier
  - Lava
  - Space
- **Unique biome obstacles**, including cacti, icicles, fireballs, and asteroids.
- **Dynamic biome transitions** with on-screen announcements.
- **Powerup system** with obstacle shields and pipe shields.
- **Visual powerup effects**, countdown timers, glow animations, and collection feedback.
- **Leaderboard system** using localStorage for persistent top scores.
- **Developer mode** with secret cheat controls and separate marked scores.
- **Custom looping background music** using `token_hunt.mp3`.
- **Web Audio sound effects** for flaps, scoring, shields, and game-over impact.
- **Self-contained browser game** built around a single HTML file with local assets.

## How To Play

1. Open `whytheflyingface.html` in a browser, or play directly at https://sentientsaur.itch.io/why-the-flying-face
2. Upload a photo, or choose **Play With Default Face**.
3. Press **Space**, tap, or click to flap.
4. Fly through pipe gaps to score points.
5. Collect glowing powerups:
   - Blue Shield protects from biome obstacles.
   - Green Bubble protects from pipes.
6. Survive as long as possible while the game advances through harder biomes.
7. After game over, enter your name to save your score to the leaderboard.

## Technologies Used

- **HTML5** for structure and single-file game packaging.
- **CSS3** for responsive UI, overlays, buttons, and visual styling.
- **JavaScript** for game logic, physics, collision detection, scoring, biomes, powerups, and leaderboard behavior.
- **HTML5 Canvas** for real-time rendering and animation.
- **face-api.js** for browser-based face detection.
- **TinyFaceDetector model** for detecting and cropping faces from uploaded photos.
- **Web Audio API** for arcade-style sound effects.
- **HTML Audio** for looping background music.
- **localStorage** for persistent scoreboards.

---

**Why The Flying Face**  
Developed by **Bilal Tariq — Sentientsaur on Itch.io**
## 🎮 Play The Game

*Play on Itch.io:* https://sentientsaur.itch.io/why-the-flying-face
