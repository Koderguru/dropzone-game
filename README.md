# 🧟 Drop Zone — Arcade

A voxel zombie-survival arcade game that runs entirely in your browser. You get
dropped onto a block-built battleground crawling with the undead — hold the zone,
survive the waves, and climb the score board. Single player **and** real-time
online multiplayer (no server needed).

> **The entire game is one file: [`game.html`](game.html).** No build step, no
> install, no framework. Open it in a browser and play.

---

## 🎬 Gameplay demo

![Drop Zone gameplay](https://github.com/Koderguru/dropzone-game/raw/main/gameplay-demo.gif)

> The clip above auto-plays on loop right here in the README. Want full quality
> **with sound**? [Watch / download the MP4](https://github.com/Koderguru/dropzone-game/raw/main/gameplay-demo.mp4).

---

## ▶️ How to play

**Option 1 — just open the file**
1. Download or clone this repo.
2. Double-click `game.html` (or right-click → Open With → your browser).
3. That's it. The game is running.

**Option 2 — play online (GitHub Pages)**
The game is live here:
👉 **https://koderguru.github.io/dropzone-game/**

### Controls
- **Move:** WASD / Arrow keys (or the on-screen joystick on mobile)
- **Aim & shoot:** mouse / touch
- **Pause:** the pause button in the HUD

### Multiplayer
The game uses peer-to-peer connections (via [PeerJS](https://peerjs.com/)), so
one player hosts a room and shares a short code — the other player joins with it.
No backend or database required.

---

## 🤔 Why plain HTML — and not Next.js / React?

This project is intentionally built as **one plain `.html` file** with vanilla
HTML, CSS, and JavaScript. That's a deliberate choice, especially helpful if
you're learning:

- **Zero setup.** There's no `npm install`, no bundler, no dev server. You open
  the file and it works — anywhere, on any machine.
- **Easy to read top-to-bottom.** Everything (markup, styles, game logic) lives
  in a single file, so you can see exactly how the whole game fits together
  without jumping across folders, components, and config files.
- **Great for beginners.** Frameworks like Next.js or React are powerful, but
  they add a lot of concepts (JSX, build tools, routing, hydration, the virtual
  DOM…) that get in the way when your goal is to understand *the actual game*.
  Here, what you see is what runs.
- **The browser does the heavy lifting.** The game renders on the HTML5
  `<canvas>` element using the native Canvas 2D API — no game engine.

If you already know React/Next.js, this is a fun reminder of how much you can do
with just the browser. If you're new, this is a clean place to learn how games
and real-time multiplayer actually work under the hood.

### Built with
- HTML5 **`<canvas>`** for all rendering
- Vanilla **JavaScript** for game logic, physics, and the game loop
- Plain **CSS** for the UI / overlays
- **[PeerJS](https://peerjs.com/)** for peer-to-peer multiplayer
- Google Fonts (Bricolage Grotesque + Inter)

---

## 🛠️ Want to tweak it?

Open `game.html` in any text editor. Everything is in there:
- The `<style>` block near the top controls the look.
- The `<script>` block contains the game loop, the zombies, the weapons, the
  scoring, and the multiplayer logic.

Change a number, refresh the browser, see what happens. That's the whole loop.

---

## 💬 Community

Join the Telegram group for updates, chat, and to share scores:

👉 **https://t.me/+VsctHA_OmSVjNGNl**

---

## 📄 License

Free to use and learn from. Have fun and build something cool. 🚀
