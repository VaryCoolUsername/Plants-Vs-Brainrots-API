
<p align="center">
  <img src="https://i.ibb.co/cKRNwsRN/minecraft-title.png" alt="Project Logo" width="500">
  <h1 align="center">Made by lildanlid</h1>
  <p align="center">
<p>
    A free, simple, open-source JSON API for fetching in-game stock and economy data from popular Roblox games.
    <br />
    <br /><br />
    <a href="https://rvlt.gg/2f9G59bQ">Report a Bug</a>
    ·
    <a href="https://rvlt.gg/2f9G59bQ">Request a Game</a>
  </p>


  <p>
    <a href="https://github.com/VaryCoolUsername/Grow-A-Garden-API/stargazers"><img src="https://img.shields.io/github/stars/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="Stars"></a>
    <a href="https://github.com/VaryCoolUsername/Grow-A-Garden-API/network/members"><img src="https://img.shields.io/github/forks/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="Forks"></a>
    <a href="https://github.com/VaryCoolUsername/Grow-A-Garden-API/issues"><img src="https://img.shields.io/github/issues/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="Issues"></a>
    <a href="https://github.com/VaryCoolUsername/Grow-A-Garden-API/blob/main/Licence.md"><img src="https://img.shields.io/github/license/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="License"></a>
    <a href="https://github.com/VaryCoolUsername/Grow-A-Garden-API/commits/main"><img src="https://img.shields.io/github/last-commit/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="Last Commit"></a>
  </p>
</div>

---

Tired of complex setups or fragile web scraping to get in-game stock data? This API exposes simple, consistent JSON endpoints for several Roblox games. Use it for Discord bots, dashboards, or scripts.

## 📖 Table of Contents

- [✨ Features](#features)  
- [🔑 Key System](#key-system)
- [💡 A Note on Performance](#a-note-on-performance)  
- [🎮 Supported Games](#supported-games)  
- [📜 License](https://github.com/VaryCoolUsername/Grow-A-Garden-API/blob/main/Licence.md)
- [🔗 Links](#important-links)

---

<a id="features"></a>
## ✨ Features

- **Multi-Game Support** — single API surface for multiple Roblox games.  
- **Live Data** — fetches current in-game stock when requested.  
- **Free** — no cost to use. (See key system for limits.)  
- **CORS Enabled** — usable from frontend or backend.  
- **JSON Responses** — predictable, easy to parse.

<a id="key-system"></a>
## 🔑 Key System

This API now requires an API key to protect against mass automated abuse.  
- Get a key: To get a key you will have to vist the dashboard 
- View your key, limits and usage: ^^^
Keys are bound to your google account and subject to rate limits. Keep your key secret.

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

<a id="important-links"></a>
### Important Links

* Docs: [https://stockapis.onrender.com/docs](https://stockapis.onrender.com/docs)
* Terms: [https://stockapis.onrender.com/TOS](https://stockapis.onrender.com/TOS)
* Privacy: [https://stockapis.onrender.com/PP](https://stockapis.onrender.com/PP)
* Dashboard: [https://stockapis.onrender.com/dash](https://stockapis.onrender.com/dash)

Updates: [https://rvlt.gg/JfyPFbp4](https://rvlt.gg/JfyPFbp4)


