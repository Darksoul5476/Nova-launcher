<p align="center">
  <img src="src/renderer/icon.png" alt="Nova Launcher" width="128" height="128">
</p>

<h1 align="center">Nova Launcher</h1>

<p align="center">
  <strong>A modern, feature-rich Minecraft launcher with full mod support.</strong>
</p>

<p align="center">
  <a href="https://github.com/Darksoul5476/Nova-launcher/releases/latest">
    <img src="https://img.shields.io/github/v/release/Darksoul5476/Nova-launcher?color=blue&label=Latest%20Release" alt="Latest Release">
  </a>
  <a href="https://github.com/Darksoul5476/Nova-launcher/releases">
    <img src="https://img.shields.io/github/downloads/Darksoul5476/Nova-launcher/total?color=green&label=Total%20Downloads" alt="Total Downloads">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue" alt="Platforms">
  <img src="https://img.shields.io/badge/License-Proprietary-red" alt="License">
</p>

---

## ✨ Features

| Category | Features |
|----------|----------|
| 🎮 **Instances** | Create multiple isolated Minecraft profiles with different versions and mods |
| 🔧 **Mod Support** | Supports **Vanilla**, **Fabric**, **Forge**, and **Quilt** |
| 🌐 **Mod Browser** | Built-in browser for **Modrinth** and **CurseForge** |
| 📦 **Modpacks** | Export and import modpacks with one click |
| 🔐 **Auth** | Secure login with **Microsoft accounts** |
| 💾 **Auto Java** | Automatically downloads the correct Java version |
| 🖥️ **System Tray** | Hide to tray or quit with a custom dialog |
| 🎨 **Custom Icons** | Custom system tray and taskbar icons |
---

## 📥 Download

| Platform | Download | Size |
|----------|----------|------|
| 🪟 **Windows** | [Nova-Launcher-Windows.zip]((https://github.com/Darksoul5476/Nova-launcher/releases/tag/v.1.0.2)) | ~337 MB |
| 🐧 **Linux** | [Nova-Launcher-Linux-Fixed.zip]((https://github.com/Darksoul5476/Nova-launcher/releases/tag/v1.0.2-linux)) | ~337 MB |

---

## 🚀 Quick Start

### Windows
1. Download the Windows zip
2. Extract anywhere
3. Run `Nova Launcher.exe`

### Linux
```bash
cd ~/Downloads
unzip Nova-Launcher-Linux-Fixed.zip -d NovaLauncher
cd NovaLauncher/NovaLauncherLinux
sudo apt install -y libnss3 libnspr4 libgtk-3-0t64 libasound2t64
chmod -R 755 ~/Downloads/NovaLauncher
echo '#!/bin/bash\ncd "$(dirname "$0")"\n./"Nova Launcher" --no-sandbox' > start.sh && chmod +x start.sh
./start.sh
