# 🐇 Bhop Simulator 3D

[![Java 11+](https://img.shields.io/badge/Java-11%2B-orange.svg)](https://www.oracle.com/java/)
[![OpenGL 3.3](https://img.shields.io/badge/OpenGL-3.3-blue.svg)](https://www.opengl.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Open-source 3D Bhop / Wallhop simulator with Source-engine physics written in Java + LWJGL 3.

🌐 **Website:** [Live Demo / Landing Page](https://YOUR_USERNAME.github.io/BhopGame/)

---

## 🚀 Features

- 🎯 **Source-like Physics:** Air acceleration, strafe speed-up, ground friction.
- 🧱 **Roblox Wallhop:** Touch walls in air, flick camera and jump to climb vertically.
- 🌀 **Portal Hub:** Lobby with 3D portal arches leading to Obby levels and Sandbox.
- ⏱️ **Speedrun Timers:** Easy / Medium / Hard courses with green start pads and red kill lasers.
- 🪑 **Interactions:** Gamer chair with 3D floating `[E]` prompt and sitting animations.
- 🎥 **Camera Modes:** First person with crosshair, `F5` 3rd person, `Shift+F5` Roblox-style Debug HUD.

---

## 🎮 Controls

| Key | Action |
| --- | --- |
| **W, A, S, D** | Move / Strafe |
| **Mouse** | Camera Look |
| **Space** | Jump / Autohop / Wallhop |
| **E** | Sit / Stand on Chair |
| **F5** | Toggle 3rd Person View |
| **Shift + F5** | Toggle FPS / MS / Pos Debug Overlay |
| **Esc** | Release / Lock Cursor |

---

## 🛠️ Build & Run

### Requirements
- **JDK 11** or higher
- **Maven 3.8+**

### Launch from source
```bash
mvn clean compile
mvn exec:java
