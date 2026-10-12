# AI Power OS

A single-file, browser-based **AI operating system interface** — a futuristic OS desktop that runs directly in the browser with **no build step, no dependencies, and no server**.

Just open `index.html` and you're in.

---

## ✨ What it is

AI Power OS is a self-contained HTML file that boots into a sci-fi desktop environment. It includes a startup sequence, a window manager, a dock, and four working "apps" — all driven by a natural-language command bar.

## 🚀 How to open it

**Option 1 — Local (fastest):**
1. Download or clone this repo.
2. Double-click `index.html` (or drag it into any modern browser).

**Option 2 — Clone:**
```bash
git clone https://github.com/palakpeshwani69428-del/ai-power-os.git
cd ai-power-os
# then open index.html in your browser
```

**Option 3 — Host it:** drop `index.html` on any static host (GitHub Pages, Netlify, Vercel, S3) — it's one file.

> Works in Chrome, Edge, Firefox, and Safari. No internet connection required after loading.

---

## 🧩 Features

### Boot / startup screen
- Glowing hexagonal **neural core** with rotating rings
- Animated grid backdrop
- Typewriter AI greeting from **ARIA**
- Live init log (`[ OK ]` lines) and a progress bar
- **Enter System** button to launch the desktop

### Desktop shell
- Top status bar with live **Neural** and **Memory** meters, link status, and a clock
- Grid wallpaper with ambient glow
- Desktop app icons
- Floating **dock** with hover tooltips and running-app indicators

### Window manager
- Draggable, focusable, minimizable, closable windows
- Sci-fi chrome with glow-on-focus
- Auto-cascading placement for new windows

### Core apps
| App | What it does |
|-----|--------------|
| **AI Assistant** | Chat panel with a rule-based ARIA that answers status / help / notes / tasks queries |
| **System Monitor** | Three animated SVG gauges (CPU / Memory / Neural Load), a canvas throughput sparkline, and uptime / latency / temp readouts |
| **Notes** | Create, edit, save, and delete notes (in-session) |
| **Agents & Tasks** | Add / complete / delete tasks plus a live agent-swarm status list |

### Command bar
Type natural-language commands that actually drive the UI:

| Command | Action |
|---------|--------|
| `open monitor` | Opens the System Monitor (also `open chat`, `open notes`, `open tasks`) |
| `close all` | Closes every open window |
| `note: buy GPU` | Captures a note instantly |
| `task: ship demo` | Queues a task |
| `status` | Opens the monitor and reports live diagnostics |
| `clear` | Clears the chat history |
| `help` | Shows the command reference |

Anything unrecognized falls through to the AI chat. Press **Ctrl/Cmd + K** to focus the command bar.

---

## 🎨 Aesthetic

Dark cyan-on-black HUD, glowing accents, animated grid, smooth window and toast animations, and a responsive layout for smaller screens.

## 🛠️ Tech

- **Pure HTML + CSS + vanilla JavaScript** — one file, zero dependencies
- No frameworks, no bundler, no npm install

## 📄 License

Free to use, modify, and share.
