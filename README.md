# ScreenDrawIyagi(스크린드라이야기) v1.9.0

![ScreenDrawing](screendrawing.png)

A **screen annotation and drawing overlay tool** for Windows and Linux.

Draw lines, shapes, text, and emoji stamps directly on top of your running screen — no screenshot needed.
Perfect for presentations, lectures, screen sharing, and visual reviews.

---

## ✨ Features

### Drawing Tools
* **Pen** — freehand drawing
* **Line / Arrow** — draw straight lines and directional arrows
* **Rectangle / Ellipse** — draw shapes (with optional fill mode)
* **Text** — type directly on screen (font and size configurable)
* **Emoji Stamp** — pick an emoji and stamp it anywhere on screen
* **Eraser** — erase parts of your drawing
* **Highlighter** — semi-transparent highlight overlay

### Color & Style
* **Color picker** — choose any pen color
* **Stroke width** — adjust line thickness from 1 to 120px
* **Fill mode** — toggle filled rectangles and ellipses
* **Highlighter mode** — highlight existing screen content with transparency

### Emoji Picker
* **9 categories** — Expressions / Hands & Body / Hearts / Animals / Food / Activities / Travel / Objects / Symbols
* **Stamp mode** — click anywhere to stamp the selected emoji in a 3D ink style
* **Text insert** — insert emoji directly into text input while typing

### Convenience
* **Undo** — step back to the previous state
* **Snapshot** — save the current drawing as an image file
* **Clear all** — reset the canvas
* **Floating toolbar** — drag the toolbar anywhere on screen
* **Settings persistence** — last used color, width, font, and tool are saved automatically

---

## 🎮 Keyboard Shortcuts

| Key | Action |
|---|---|
| ESC / Q | Quit the app |
| Ctrl + Z | Undo |
| S | Save snapshot |
| Delete / C | Clear canvas |

---

## ⬇ Download

### Windows
Install from the Microsoft Store.
(Store link coming soon)

### Linux
Download the binary from GitHub Releases.

```bash
chmod +x ScreenDrawIyagi
./ScreenDrawIyagi
```

---

## 🐧 Linux Setup

Qt6 platform plugins are required.

```bash
sudo apt install libqt6widgets6 libqt6-xcb-private-plugins
```

Emoji font (if not already installed):

```bash
sudo apt install fonts-noto-color-emoji
```

On Wayland, the app runs automatically via XWayland.

---

## 🖥 Supported Platforms

* Windows 10 / 11
* Linux (GNOME Wayland / X11)

---

## 👤 Author

IYAGI INC
Email: [iyagicom@gmail.com](mailto:iyagicom@gmail.com)
GitHub: https://github.com/iyagicom

---

## 📜 License

Copyright (c) 2026 IYAGI INC. All rights reserved.

This software is provided as **executable files only**. Source code is not publicly available.

You may use this software for personal and non-commercial purposes.
Redistribution, modification, or reverse engineering is prohibited without explicit written permission from the author.
