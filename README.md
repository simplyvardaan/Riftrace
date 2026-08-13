<div align="center">

#  RIFTRACE

### Real-time multiplayer 3D racing, straight in your browser.

Race with friends through electric tracks, chase the perfect lap, and drift into the leaderboard — no downloads, no installs, just a party code.

[![Play Now](https://img.shields.io/badge/▶_PLAY_NOW-riftrace.io-ff3860?style=for-the-badge)](https://riftrace.io)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Made with Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)](https://webrtc.org/)

</div>

---

## 🚦 Table of Contents

- [Features](#-features)
- [Quick Start](#-quick-start)
- [Controls](#-controls)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [License](#-license)

---

## ✨ Features

| | |
|---|---|
| 🌐 **Multiplayer Racing** | Real-time races over peer-to-peer WebRTC connections |
| 🧲 **Physics-Based Driving** | Speed-dependent steering, suspension, and collision detection |
| 🗺️ **Multiple Tracks** | Unique layouts, obstacles, and lines to master |
| 🚩 **Checkpoint System** | Race through gates to track your lap time |
| 🏆 **Leaderboard** | Compete for the best times and climb the rankings |
| 🔑 **Party System** | Create or join a race instantly with a shareable code |
| 📱 **Mobile Support** | Full touch controls, tuned for desktop and mobile alike |
| 🎨 **Car Customization** | Pick your car color and stand out on the grid |

---

## 🚀 Quick Start

### Host a race

1. Open [riftrace.io](https://riftrace.io)
2. Enter your name
3. Choose your car color
4. Click **Create Party**
5. Share the generated party code with friends
6. Pick a track from the dropdown
7. Click **Start Race** once everyone's in

### Join a race

1. Open [riftrace.io](https://riftrace.io)
2. Enter your name
3. Choose your car color
4. Enter the party code from your host
5. Click **Join Party**
6. Wait for the host to hit start 🏁

---

## 🎮 Controls

<table>
<tr>
<td valign="top" width="50%">

**🖥️ Desktop**

| Key | Action |
|:---:|---|
| `W` | Accelerate |
| `S` | Brake / Reverse |
| `A` | Turn left |
| `D` | Turn right |
| `R` | Reset to last checkpoint |

</td>
<td valign="top" width="50%">

**📱 Mobile**

| Input | Action |
|---|---|
| Virtual Joystick | Steer |
| Joystick Up | Accelerate |
| Joystick Down | Brake / Reverse |
| Joystick Left/Right | Turn |

</td>
</tr>
</table>

---

## 🧰 Tech Stack

<div align="center">

![Three.js](https://img.shields.io/badge/Three.js-3D_Rendering-black?style=flat-square&logo=three.js&logoColor=white)
![Ammo.js](https://img.shields.io/badge/Ammo.js-Physics_Engine-orange?style=flat-square)
![PeerJS](https://img.shields.io/badge/PeerJS-WebRTC_P2P-4A90D9?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-Core-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=flat-square&logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/Python-Backend-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-Matchmaking-092E20?style=flat-square&logo=django&logoColor=white)

</div>

| Layer | Technology | Purpose |
|---|---|---|
| 🎥 Rendering | **Three.js** | 3D scene rendering |
| ⚙️ Physics | **Ammo.js** | WebAssembly port of Bullet Physics for realistic driving |
| 🔗 Networking | **PeerJS** | WebRTC peer-to-peer race connections |
| 🖼️ Frontend | **JavaScript / HTML5 / CSS3** | Core client experience |
| 🗄️ Backend | **Python / Django** | Matchmaking and party code management |

---

## 📁 Project Structure

```
Riftrace/
├── frontend/    # Client — Three.js scene, physics, UI, controls
└── backend/     # Server — Django matchmaking & party management
```

---

## 📜 License

Released under the **MIT License**. See [LICENSE](LICENSE) for details.

<div align="center">

**[🏁 Start racing at riftrace.io →](https://riftrace.io)**

</div>
