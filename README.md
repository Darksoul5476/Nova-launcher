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

## 📸 Screenshots

<p align="center">
  <img src="screenshots/home.png" alt="Home" width="400">
  <img src="screenshots/instances.png" alt="Instances" width="400">
</p>

---

## 📥 Download

| Platform | Download | Size |
|----------|----------|------|
| 🪟 **Windows** | [Nova-Launcher-Windows.zip](https://github.com/Darksoul5476/Nova-launcher/releases/latest) | ~337 MB |
| 🐧 **Linux** | [Nova-Launcher-Linux-Fixed.zip](https://github.com/Darksoul5476/Nova-launcher/releases/latest) | ~337 MB |

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
