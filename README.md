
<p align="center">
  <img src="https://i.ibb.co/cKRNwsRN/minecraft-title.png" alt="Project Logo" width="500">
  <h1 align="center">Made by lildanlid</h1>
  <p align="center">
    A free, simple, and open-source JSON API for fetching in-game stock and economy data from popular Roblox games.
    <br />
    <a href="https://stock-apis.vercel.app/"><strong>Visit the Homepage »</strong></a>
    <br />
    <br />
    <a href="https://rvlt.gg/2f9G59bQ">Report a Bug</a>
    ·
    <a href="https://rvlt.gg/2f9G59bQ">Request a Game</a>
  </p>
</p>

<p align="center">
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/stargazers"><img src="https://img.shields.io/github/stars/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/network/members"><img src="https://img.shields.io/github/forks/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="Forks"></a>
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/issues"><img src="https://img.shields.io/github/issues/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="Issues"></a>
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/blob/main/LICENSE"><img src="https://img.shields.io/github/license/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="License"></a>
  <a href="https://github.com/VaryCoolUsername/Plants-Vs-Brainrots-API/commits/main"><img src="https://img.shields.io/github/last-commit/VaryCoolUsername/Grow-A-Garden-API?style=flat-square" alt="Last Commit"></a>
</p>

---

Tired of complex setups or web scraping to get in-game stock data? This API provides simple, free, and semi-reliable JSON endpoints for a few popular Roblox games. It's perfect for developers creating Discord bots, web dashboards, or any other project that needs up-to-date in-game stock information.

## 📖 Table of Contents

- [✨ Features](#-features)
- [💡 A Note on Performance](#-a-note-on-performance)
- [🎮 Supported Games](#-supported-games)
- [🚀 Quick Start](#-quick-start)
- [🗂️ API Endpoints & Response Formats](#️-api-endpoints--response-formats)
- [🤝 How to Contribute](#-how-to-contribute)
- [📜 License](#-license)

## ✨ Features

- **🎮 Multi-Game Support:** A single API for fetching stock data from multiple Roblox games.
- **⚡ Live Data:** Fetches data to provide the most current stock information.
- **🆓 Completely Free:** No API keys, no rate limits, and no cost.
- **🔄 CORS Enabled:** Use it directly from your frontend or backend applications without any hassle.
- **🤝 Open to Contributions:** Easily request new games or contribute new endpoints.
- **JSON Format:** Clean, predictable, and easy-to-parse JSON responses.

## 💡 A Note on Performance

To ensure the data is always up-to-date, this API fetches information live when a request is made. This process can sometimes take a few seconds to complete. Additionally, as a serverless function, the first request after a period of inactivity may experience a "cold start," which adds a little extra delay.

## 🎮 Supported Games

| Game | API Endpoint | Status |
| :--- | :--- | :--- |
| **Grow a Garden** | [`/api/growagarden/stocks`](https://stock-apis.vercel.app/api/growagarden/stocks) | ✅ Online |
| **Plants vs Brainrots** | [`/api/plantsvsbrainrots/stocks`](https://stock-apis.vercel.app/api/plantsvsbrainrots/stocks) | ✅ Online |
| ~~**Blox Fruits**~~ | `~~/api/bloxfruits/stocks~~` | ❌ Temporarily Unavailable |

*Don't see the game you need? [Open an issue](https://rvlt.gg/2f9G59bQ) to request it!*
