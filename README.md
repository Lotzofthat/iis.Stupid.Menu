````markdown
<p align="center">
  <a href="#"><img src="Resources/GitHub/icon.png" width="120px"></a><br>
  <a href="#"><img src="Resources/GitHub/title.png" height="60px"></a><br><br>
  <a href="https://github.com/iiDk-the-actual/iis.Stupid.Menu/releases">
    <img src="https://img.shields.io/github/v/release/iiDk-the-actual/iis.Stupid.Menu?label=Version&style=for-the-badge">
  </a>
  <a href="https://github.com/iiDk-the-actual/iis.Stupid.Menu/releases/latest">
    <img src="https://img.shields.io/github/downloads/iiDk-the-actual/iis.Stupid.Menu/latest/iis_Stupid_Menu.dll?style=for-the-badge">
  </a>
  <a href="https://discord.gg/iidk">
    <img src="https://img.shields.io/discord/1170093288557129748?label=Discord&style=for-the-badge&color=blueviolet">
  </a>
</p>

---

# 🦧 ii’s Stupid Menu

> **“Why settle for boring when you can have *stupidly good*?”**

**ii’s Stupid Menu** is a feature-packed, open-source **mod menu for Gorilla Tag** built by [**iiDk**](https://github.com/iiDk-the-actual).  
It’s designed to be *fast, customizable, and developer-friendly*, while keeping modding open and free for everyone.

---

## 📚 Table of Contents
- [✨ Features](#-features)
- [💡 Why Open Source](#-why-open-source)
- [🧰 Requirements](#-requirements)
- [📥 Installation](#-installation)
- [🧱 Building from Source](#-building-from-source)
- [🎛️ System Compatibility](#️-system-compatibility)
- [🔒 Data & Telemetry](#-data--telemetry)
- [🗣️ Contact](#️-contact)
- [❤️ Support](#️-support)
- [📜 License](#-license)

---

## ✨ Features
- 🧩 1000+ Mods and Utilities
- 🧠 Built-in AI Assistant (via Pollinations)
- ⚙️ Developer Tools, Debugging & Live Reload
- 🎨 Customizable UI Themes
- 🔊 Text-to-Speech & Audio Feedback
- 📡 Real-Time Friend System
- 🚀 Plugin-Based Architecture
- 🔓 100% Open Source, GPL-3.0 Licensed

---

## 💡 Why Open Source
Modding should be **about creativity and collaboration**, not paywalls or gatekeeping.  
By staying open-source, this project allows everyone to:
- Learn how menus and mods are made
- Contribute and experiment freely
- Improve the Gorilla Tag modding ecosystem
- Keep the spirit of modding alive — **free, open, and educational**

> 🗣️ No DRM. No obfuscation. No nonsense. Just good code.

---

## 🧰 Requirements
| Tool | Minimum Version | Purpose |
|------|------------------|----------|
| 🧱 Gorilla Tag | Latest | Base game |
| ⚙️ BepInEx | 6.x | Plugin loader |
| 💻 .NET SDK | 8.0+ | Build system |
| 🪟 / 🐧 / 🍎 | — | Supported OS (see below) |

---

## 📥 Installation
**Simple setup — takes less than a minute:**

1. Download the latest release [**here**](https://github.com/iiDk-the-actual/iis.Stupid.Menu/releases/latest)
2. Drop `iis_Stupid_Menu.dll` into your **Gorilla Tag → BepInEx → plugins** folder
3. Launch the game.  
✅ You’re done.

> ⚠️ If the menu doesn’t appear, make sure BepInEx is installed and working correctly.

---

## 🧱 Building from Source

### 🪟 Windows
```bash
git clone https://github.com/iiDk-the-actual/iis.Stupid.Menu.git
cd iis.Stupid.Menu

# Update build path
notepad Directory.Build.props  # set <GamePath> to your Gorilla Tag directory

# Build with Visual Studio or .NET
Ctrl + Shift + B
````

✅ The DLL will automatically copy to your Gorilla Tag plugins folder.

---

### 🐧 Linux

```bash
git clone https://github.com/iiDk-the-actual/iis.Stupid.Menu.git
cd iis.Stupid.Menu

# Edit build path
nano Directory.Build.props  # set <GamePath> to your GT directory

# Install .NET if missing
sudo apt install dotnet-sdk-8.0

# Build project
dotnet build
```

✅ No manual references required — builds cleanly on Linux.

---

## 🎛️ System Compatibility

| OS                | Menu | Fonts | Images | Sounds | Videos |
| ----------------- | :--: | :---: | :----: | :----: | :----: |
| 🪟 **Windows 10** |   ✅  |   ✅   |    ✅   |    ✅   |    ✅   |
| 🪟 **Windows 11** |   ✅  |   ✅   |    ✅   |    ✅   |    ✅   |
| 🍎 **macOS**      |   ✅  |   ✅   |    ✅   |    ✅   |    ❌   |
| 🐧 **Linux**      |   ✅  |   ❌   |    ✅   |    ✅   |    ❌   |

---

## 🔒 Data & Telemetry

This project values **transparency**.
Some features send data to external services for legitimate functionality:

| Service                                                          | Purpose                           |
| ---------------------------------------------------------------- | --------------------------------- |
| 🌐 [iidk.online](https://github.com/iiDk-the-actual/iidk.online) | Telemetry, admin tools, TTS       |
| 🤖 [text.pollinations.ai](https://text.pollinations.ai)          | AI Assistant                      |
| 🔗 `wss://iidk.online`                                           | Friend system, live communication |

> Connections are feature-based only — nothing runs without user consent.
> No tracking, analytics, or personal data collection. Ever.

---

## 🗣️ Contact

Questions, suggestions, or contributions?

* 🌍 Website: [https://iidk.dev](https://iidk.dev)
* 💬 Discord: [Join Here](https://discord.gg/iidk)
* 🧱 Contribute: [GitHub → Contributing Guide](https://github.com/iiDk-the-actual/iis.Stupid.Menu/?tab=contributing-ov-file)

---

## ❤️ Support

If you enjoy the project and want to help keep it alive:

| Platform | Link                                                                                                                                                | Address                                      |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| Bitcoin  | [![BTC](https://img.shields.io/badge/Bitcoin-Donate-yellow?style=for-the-badge\&logo=bitcoin)](bitcoin:bc1qtmrqtq4ag720tvux64ff3rjp632jy2d447p3nx)  | `bc1qtmrqtq4ag720tvux64ff3rjp632jy2d447p3nx` |
| Ethereum | [![ETH](https://img.shields.io/badge/Ethereum-Donate-blue?style=for-the-badge\&logo=ethereum)](ethereum:0xa1A78771422F602d9Ded0E8373d5A3D77E146877) | `0xa1A78771422F602d9Ded0E8373d5A3D77E146877` |
| Litecoin | [![LTC](https://img.shields.io/badge/Litecoin-Donate-lightgrey?style=for-the-badge\&logo=litecoin)](litecoin:LaoNB7KADaGGb5ik8RhEBhAFdhM9pu5se5)    | `LaoNB7KADaGGb5ik8RhEBhAFdhM9pu5se5`         |
| XRP      | [![XRP](https://img.shields.io/badge/XRP-Donate-23292F?style=for-the-badge\&logo=xrp)](xrp:rpLLN1Gse5zFnVxwQkMvh6jvKKtPrAjvLV)                      | `rpLLN1Gse5zFnVxwQkMvh6jvKKtPrAjvLV`         |
| Patreon  | [![Patreon](https://img.shields.io/badge/Patreon-iiDk-orange?style=for-the-badge\&logo=patreon)](https://www.patreon.com/iiDk)                      | [iiDk](https://www.patreon.com/iiDk)         |
| CashApp  | [![CashApp](https://img.shields.io/badge/CashApp-$iiWasHere-green?style=for-the-badge\&logo=cashapp)](https://cash.app/$iiWasHere)                  | [$iiWasHere](https://cash.app/$iiWasHere)    |

---

## 📜 License

**GNU General Public License v3.0**

```
Copyright (C) 2025 Goldentrophy Software
https://github.com/iiDk-the-actual/iis.Stupid.Menu

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details.
```

> 🦍 Not affiliated with Gorilla Tag or Another Axiom LLC.
> Portions © 2025 Another Axiom LLC.
> Icons by [Icons8](https://icons8.com)

---

<p align="center">
  <img src="Resources/GitHub/byebye.gif" width="400px">
</p>
```
