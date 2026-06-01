
<h1 align="center">Nova Launcher</h1>

<p align="center">
  <strong>A modern, feature-rich Minecraft launcher for both Java & Bedrock editions.</strong>
</p>

<p align="center">
  <a href="https://github.com/Darksoul5476/Nova-launcher/releases/latest">
    <img src="https://img.shields.io/github/v/release/Darksoul5476/Nova-launcher?color=7c5cbf&label=Latest&style=flat-square" alt="Latest Release">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue?style=flat-square" alt="Platforms">
  <img src="https://img.shields.io/badge/License-Proprietary-red?style=flat-square" alt="License">
  <a href="https://discord.gg/WhDS7YEp5q">
    <img src="https://img.shields.io/badge/Discord-Join%20Server-7289da?style=flat-square&logo=discord" alt="Discord">
  </a>
</p>

---

## What is Nova Launcher?

Nova Launcher is a custom Minecraft launcher that lets you create and manage multiple Minecraft instances with different versions, mod loaders, and settings. It supports both **Java Edition** (Vanilla, Fabric, Forge, Quilt) and **Bedrock Edition**, all from one place.

Built with a clean dark theme, it includes a built-in mod browser, skin changer, server auto-connect, addon manager, and more. No account credentials are ever stored - only secure Microsoft authentication tokens are saved locally.

---

## Why Nova Launcher?

- **One launcher for everything** - Java & Bedrock in the same app
- **Built-in mod browser** - Search Modrinth and install mods without leaving the launcher
- **Skin changer** - Upload and switch between skins instantly
- **Server auto-connect** - Click a server and jump straight in
- **World quick launch** - Launch directly into any saved world
- **Free and private** - No data collection, no ads, no tracking
- **Windows & Linux** - Available on both platforms

---

## 📥 Installation

### Windows

1. Download `Nova Launcher Setup 1.0.2.exe` from the [latest release](https://github.com/Darksoul5476/Nova-launcher/releases/latest)
2. Run the installer
3. If Windows SmartScreen shows a warning, click **"More info"** → **"Run anyway"**
4. Launch Nova Launcher from the Desktop shortcut or Start Menu

### Linux

1. Download `Nova-Launcher-v1.0.2-Linux.zip` from the [latest release](https://github.com/Darksoul5476/Nova-launcher/releases/latest)
2. Extract the zip file
3. Install dependencies (Ubuntu/Debian):
```bash
sudo apt install -y libnss3 libnspr4 libgtk-3-0t64 libasound2t64
```
4: Make the launcher executable and run:
```bash
chmod +x "Nova Launcher"
./"Nova Launcher" --no-sandbox
```
5: Or create a launch script for easier use:
```bash
echo '#!/bin/bash
cd "$(dirname "$0")"
./"Nova Launcher" --no-sandbox' > start.sh && chmod +x start.sh
./start.sh
```
⚠️ Disclaimer

Nova Launcher is not affiliated with Mojang, Microsoft, Modrinth, CurseForge, or MCPEDL. Minecraft is a registered trademark of Mojang/Microsoft. This software is proprietary and does not collect any personal data.

🔗 Links
<p align="center"> <a href="https://github.com/Darksoul5476/Nova-launcher"> <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub"> </a> <a href="https://discord.gg/WhDS7YEp5q"> <img src="https://img.shields.io/badge/Discord-Join%20Server-7289da?style=for-the-badge&logo=discord" alt="Discord"> </a> </p>
