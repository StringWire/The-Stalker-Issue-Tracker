# 👁️ Custom Entity – The Stalker (Issue Tracker)

Welcome to the official issue tracker for **The Stalker** plugin! 
*Note: This repository is for issue tracking and bug reports only. The source code is closed-source.*

## 🐛 How to Report a Bug
If you've found a bug or have a feature request, please navigate to the **[Issues](../../issues)** tab and create a new issue. Please provide as much detail as possible, including your server version and the plugin version you are running.

---

## 📜 Latest Changelog

### v2.0 Beta (Jun 21, 2026)
*Status: Beta Release | Supported Paper Version: Paper 26.2*

**Added:**
* **Sanity System**: A brand new hidden mechanic that tracks player sanity levels.
  * Sanity slowly drains when standing in darkness or near The Stalker.
  * Low sanity causes screen distortion (Nausea effect).
  * Critical sanity spawns Hallucinations (fake creepers that aggressively charge the player but vanish into smoke when hit).
* **Environment Sabotage**: The Stalker now actively hunts light sources.
  * Automatically breaks torches and lanterns.
  * Extinguishes campfires in a configurable radius as it approaches players.
* **Weeping Angel Difficulty**: Added a new `weeping_angel` difficulty option in `config.yml`.
  * The Stalker moves 3× faster than normal.
  * Instantly freezes whenever a player looks directly at it.
* **Audio Enhancements**: A sinister heartbeat sound that plays whenever The Stalker is within 15 blocks of a player.
* **Special Loot Drops**: Defeating The Stalker on High or Weeping Angel difficulty now rewards a configurable special item. (Default: Night Vision Goggles / Dark Green Leather Helmet).

**Changed:**
* Updated all version strings throughout the plugin and configuration files from 1.6 to 2.0 Beta.
* Expanded the AI state machine in `StalkerEntity` to support the new Weeping Angel movement and freezing behavior.
* Updated the plugin for compatibility with **Paper 26.2**.

---

### v1.6 Update (Apr 29, 2026)

**🧠 AI Improvements**
* Enhanced stalking and chasing behavior.
* Improved difficulty scaling (Easy / Mid / High).

**⚔️ Combat Enhancements**
* Added lightning strike effects.
* Improved jumpscare system.
* Better knockback handling.

**🛡️ Player System**
* Added safe whitelist system.
* Improved player targeting logic.
* Instant despawn when protected.

**🎨 Skin System**
* Added skin caching system.
* Supports PNG skins + MineSkin API.

**⚙️ Improvements & Compatibility**
* Performance optimizations, bug fixes, and stability improvements.
* Support for Paper 1.21.1 – 1.21.11.
* Optional support for Citizens.
