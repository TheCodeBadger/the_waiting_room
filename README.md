# The Waiting Room

> *You were told to wait. You should have left.*

A first-person **liminal-horror** walking simulator that runs entirely in your browser — no downloads, no installs, no plugins. Step into a quiet, wrong-feeling medical facility and find your way out... if there is one.

![The Waiting Room — Title Image](Images/The%20Waiting%20Room.png)

---


## About

You play as **Adam Cole**, alone in a place that should be familiar but isn't. *The Waiting Room* is built around atmosphere and **environmental storytelling** — the building tells you what happened here, if you're paying attention. Explore, piece it together, and reach one of several possible endings. Some things are easy to find. Others are waiting for those who look a little closer.

This started as a personal project to push what's possible in a single, self-contained web page — and turned into something with a lot more under the surface.

## Features

- 👣 **First-person exploration** with real-time 3D rendering
- 🏚️ **Atmospheric, environmental storytelling** — no hand-holding
- 🔀 **Multiple endings** depending on the choices you make
- 🔎 **A hidden narrative thread** for the curious
- 🔊 **Fully synthesized audio** — every sound generated in-browser, no audio files
- 📦 **Self-contained** — the entire game, including the 3D engine, ships in one HTML file

## Controls

| Input | Action |
|-------|--------|
| `W` `A` `S` `D` | Move |
| Mouse | Look around |
| `Esc` | Pause / release cursor |

> Click the game window once to lock the mouse and begin.

## Running locally

Because the game is a single self-contained file, you can usually just **double-click the HTML file** to play it.

If you've added external assets (such as the 3D model files), browsers block those from loading over `file://` for security reasons. In that case, serve the folder with a tiny local web server:

```bash
# Python 3
python -m http.server 8000
```

Then open **http://localhost:8000** in your browser.

## Built with

- **HTML5 · CSS3 · JavaScript**
- **[Three.js](https://threejs.org/)** — real-time 3D, bundled inline so the game stays a single file
- **Blender** — environment and asset work
- **Meshy.ai** + **Mixamo** — character model and rigging (*The Doctor*)

## Roadmap


- [ ] Fix issues with sound
- [ ] Integrate *The Doctor* (distance-based silhouette → full-colour rendering)
- [ ] Polish room layouts and lighting
- [ ] Additional environmental detail and lore
- [ ] Performance pass for lower-end machines

## Credits

Created by **Code Badger** — [Code Badger](https://www.codebadger.co.uk).

Engine: [Three.js](https://threejs.org/). Character tools: [Meshy.ai](https://www.meshy.ai/), [Mixamo](https://www.mixamo.com/).

## License

© 2026 Code Badger. All rights reserved.

---

*Built from the ground up.* 🦡
