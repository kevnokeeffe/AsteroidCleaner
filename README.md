# 🌑 AsteroidCleaner

🧹 Automatically removes excess untracked asteroids and comets from the game.

## 🔍 Overview

**AsteroidCleaner** is a lightweight plugin for Kerbal Space Program that regularly scans for untracked space objects and cleans up extras beyond your defined limits. It's designed to reduce game clutter, save performance, and keep your solar system clean.

## ✨ Features

- Removes untracked **asteroids** beyond a set number (default: 3)
- Removes untracked **comets** beyond a set number (default: 2)
- Safe for use in all scenes (including tracking station)
- Skips tracked objects to preserve player discoveries

## ⚙️ Configuration

Currently hardcoded:
- Max Asteroids: `3`
- Max Comets: `2`
- Cleanup interval: `10 seconds`

Config file support can be added in future versions.

## 📦 Dependencies

- ✅ Kopernicus — required
- 🔄 Compatible with other object-spawning mods
- ⚠️ Game must be run with Kopernicus installed for this mod to function properly

## 🧩 Works Well With

**[AsteroidSpawnLimiter](https://github.com/kevnokeeffe/AsteroidSpawnLimiter)** –  
Use this mod alongside *AsteroidCleaner* to fully control space object clutter.  
While *AsteroidSpawnLimiter* controls how often new asteroids and comets are spawned, *AsteroidCleaner* ensures that excess untracked objects are regularly cleaned up.  
Together, they help keep your save stable and performant over long playthroughs.

## 🔧 Installation

1. Download the latest release from the [GitHub Releases page](https://github.com/kevnokeeffe/AsteroidSpawnLimiter/releases/tag/v1.0.0).
2. Extract the ZIP file.
3. Copy the `GameData/AsteroidSpawnLimiter/` folder into your KSP `GameData/` directory.

## 🚀 Compatibility

- ✅ Tested with **KSP 1.12.5**
- Should work with most other mods

## 🧑‍💻 Author

- **KevO**

## 📄 License

[MIT License](./License.md)

## 🔗 Links

- 📦 [Download Latest Release](https://github.com/kevnokeeffe/AsteroidCometCleaner/releases)

