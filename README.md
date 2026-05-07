# ConceptForge 🌀

**An immersive, interactive concept visualizer controlled by your Logitech R400 presenter remote.**

Not another slide deck — a living 3D universe of ideas you can navigate from across the room.

## Features

- 🕹️ **Full R400 support** – Forward/Back, Play, Black screen buttons mapped to navigation, auto-tour, and immersion mode
- 🌌 **Beautiful 3D cosmic visualization** powered by Three.js
- ✨ Smooth camera flights between concepts
- 📊 Live sidebar with rich details + connections
- 🎬 Auto-Tour mode (perfect for presentations)
- ✏️ In-app JSON editor to customize concepts instantly
- 🎉 Special effects on key actions
- 🔒 Works completely offline after first load (single HTML file)

## How to use with your Logitech R400

1. Plug in the R400 USB receiver
2. Open `index.html` (or visit the GitHub Pages link below)
3. Go fullscreen (F11 or button)
4. Use the remote:
   - **Forward (>)** → Next concept / Advance tour
   - **Back (<)** → Previous concept
   - **Play** → Toggle Auto-Tour or Dive deeper
   - **Black screen (.)** → Immersion mode (hide UI, boost visuals)

Works great with projectors and large screens!

## Quick Start

```bash
git clone https://github.com/js22gz/GrokMe.git
cd GrokMe
open index.html   # or double-click
```

Or visit the live demo (enable GitHub Pages in repo settings if not already):
**https://js22gz.github.io/GrokMe/**

## Customize

Click the **⚙️ Edit Concepts** button in the app to paste your own JSON array of concepts. Changes are live!

Each concept object:
```json
{
  "id": 1,
  "name": "Your Concept",
  "desc": "Short powerful description...",
  "insight": "Key takeaway or analogy",
  "connections": [2, 3],
  "color": "#00f9ff"
}
```

## Tech Stack
- Pure HTML + Tailwind CSS (CDN)
- Three.js r134 (CDN)
- Vanilla JS (no build tools)
- Fully self-contained

## Roadmap / Ideas
- Add sound design (Web Audio)
- More visual modes (2D graph, particle field)
- Export to video / PDF tour
- Multi-user sync

Built with ❤️ by Grok + Jonatan

---

*Perfect for workshops, keynotes, teaching complex topics, or just exploring ideas hands-free.*