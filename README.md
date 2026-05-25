# 3D Beast Battle: Neon Raid 👾⚡

A fast-paced, high-fidelity 3D first-person shooter set in a neon cyberpunk grid arena. Battle procedural mechanical beasts, collect credits, and upgrade your weaponry in real-time.

---

## 🚀 Key Features

* **Cyber-Mech Quadruped Beasts**: Encounter terrifying mechanical spiders featuring hierarchical walking limb physics, glowing eyes, horns, armored plates, back-mounted plasma cannons, and pulsing energy cores.
* **Futuristic Arsenal**:
  * ⚡ **Pulse Rifle**: High-frequency automatic energy weapon.
  * 🔥 **Ion Blaster**: Heavy shock impact energy emitter.
  * 🔭 **Sniper Rifle**: High-precision, high-velocity railgun that delivers devastating damage.
* **Tactical Sniper Scope**: Equip the Sniper Rifle and **hold Right-Click** to engage a tactical HUD scope featuring:
  * 20° Field of View zoom.
  * Cyan reticle with grid scanlines.
  * **Active Raycast Distance Tracking**: Real-time laser telemetry displaying the exact distance in meters to target blocks or enemies.
* **Retro-Synth Audio**: Interactive sound effects synthesized dynamically in-browser using the Web Audio API (no external audio assets required).
* **In-Game Upgrade Terminal**: Press `ESC` during combat to access the terminal, repair core integrity, or purchase new weapons.
* **Procedural Cyberspace**: Each sector is procedurally generated with light-emissive walls, a reflecting grid floor, and cyberpunk volumetric fog.

---

## 🎮 How to Play

### Controls
| Key | Action |
| --- | --- |
| **W, A, S, D** | Move Engine (Walk) |
| **SPACE** | Thrust Jump |
| **Q** | Cycle Arms (Switch Weapons) |
| **L-CLICK** | Fire Laser / Emitter |
| **R-CLICK (Hold)** | Zoom Sniper Scope (Sniper Rifle only) |
| **ESC** | Pause link / Access Upgrade Terminal |

### Gameplay Loop
1. Click **Initialize System** to start the neural link.
2. Eliminate all mechanical beasts to purge the sector.
3. Access the **Upgrade Terminal** between rounds or during pause. Spend your credits to repair your core or purchase weapon upgrades.
4. Re-lock the screen to deploy to the next, harder sector.

---

## 🛠️ Technology Stack
* **Framework**: Vanilla HTML5, CSS3, JavaScript (ES6 Modules)
* **Graphics**: Three.js (WebGL 3D Rendering)
* **Controls**: Three.js PointerLockControls
* **Audio**: HTML5 Web Audio API Synth

---
## 🌐 Deploy to GitHub Pages (Play Online)
To share this game online for free:
1. Create a repository on GitHub and push your files.
2. In the repository **Settings**, click on **Pages** in the sidebar.
3. Under **Build and deployment**, set the branch to `main` (`/root` folder) and click **Save**.
4. Your game will be live at `https://<YOUR-USERNAME>.github.io/<YOUR-REPO-NAME>/`!
