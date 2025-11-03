
<p align="center">
  <img src="https://i.ibb.co/cKRNwsRN/minecraft-title.png" alt="Project Logo" width="500">
  <h1 align="center">Made by lildanlid</h1>
  <p align="center">
    A free, simple, and open-source JSON API for fetching in-game stock and economy data from popular Roblox games.
    <br />
    <a href="https://stocktracker-rbx.netlify.app/"><strong>Visit the Homepage »</strong></a>
    <br />
    <br />
    <a href="https://rvlt.gg/2f9G59bQ">Report a Bug</a>
    ·
    <a href="https://rvlt.gg/2f9G59bQ">Request a Game</a>
  </p>
</p>

<p align="center">
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/stargazers"><img src="https://img.shields.io/github/stars/VaryCoolUsername/Plants-Vs-Brainrots-API?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/network/members"><img src="https://img.shields.io/github/forks/VaryCoolUsername/Plants-Vs-Brainrots-API?style=flat-square" alt="Forks"></a>
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/issues"><img src="https://img.shields.io/github/issues/VaryCoolUsername/Plants-Vs-Brainrots-API?style=flat-square" alt="Issues"></a>
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/blob/main/LICENSE"><img src="https://img.shields.io/github/license/VaryCoolUsername/Plants-Vs-Brainrots-API?style=flat-square" alt="License"></a>
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/commits/main"><img src="https://img.shields.io/github/last-commit/VaryCoolUsername/Plants-Vs-Brainrots-API?style=flat-square" alt="Last Commit"></a>
</p>

---

Tired of complex setups or fragile web scraping to get in-game stock data? This API exposes simple, consistent JSON endpoints for several Roblox games. Use it for Discord bots, dashboards, or scripts.

## 📖 Table of Contents

- [✨ Features](#features)  
- [🔑 Key System](#key-system)
- [💡 A Note on Performance](#a-note-on-performance)  
- [🎮 Supported Games](#supported-games)  
- [🚀 Quick Start](#quick-start)  
- [📜 License](#license)
- [🌱 Tracker](#tracker)

---

<a id="features"></a>
## ✨ Features

- **Multi-Game Support** — single API surface for multiple Roblox games.  
- **Live Data** — fetches current in-game stock when requested.  
- **Free** — no cost to use. (See key system for limits.)  
- **CORS Enabled** — usable from frontend or backend.  
- **Open Source** — contributions welcome.  
- **JSON Responses** — predictable, easy to parse.

<a id="key-system"></a>
## 🔑 Key System

This API now requires an API key to protect against mass automated abuse.  
- Get a key: `https://stockapis.onrender.com/getkey`  
- View your key, limits and usage: `https://stockapis.onrender.com/key`  
Keys are bound to your IP and subject to rate limits. Keep your key secret.

<a id="a-note-on-performance"></a>
## 💡 A Note on Performance

The API fetches live data on request. Expect occasional delays.  
Cold starts and upstream game-server delays can add latency. Design your client with retries and caching.

<a id="supported-games"></a>
## 🎮 Supported Games

| Game | API Endpoint | Status |
| :--- | :--- | :---: |
| **Grow a Garden** | [`/api/growagarden/stocks`](https://stockapis.onrender.com/api/growagarden/stocks) | ✅ Online |
| **Plants vs Brainrots** | [`/api/plantsvsbrainrots/stocks`](https://stockapis.onrender.com/api/plantsvsbrainrots/stocks) | ✅ Online |
| ~~**Blox Fruits**~~ | `~~/api/bloxfruits/stocks~~` | ❌ discontinued |

Don't see your game? [Open an issue](https://rvlt.gg/2f9G59bQ) to request it.

<a id="quick-start"></a>
## 🚀 Quick Start

Request example (url):
"https://stockapis.onrender.com/api/growagarden/stocks?key=YOUR_KEY"

<a id="tracker"></a>
## Tracker

[Ive already created a tracker for both games if you would like to use that.
go here to use it.](https://stocktracker-rbx.netlify.app/)


