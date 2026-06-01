<h1 align="center">Nova Launcher</h1>

<p align="center">
  <strong>A modern, feature-rich Minecraft launcher supporting both Java & Bedrock editions with built-in mod browsing, skin management, and more.</strong>
</p>

<p align="center">
  <a href="https://github.com/Darksoul5476/Nova-launcher/releases/latest">
    <img src="https://img.shields.io/github/v/release/Darksoul5476/Nova-launcher?color=7c5cbf&label=Latest%20Release&style=flat-square" alt="Latest Release">
  </a>
  <a href="https://github.com/Darksoul5476/Nova-launcher/releases">
    <img src="https://img.shields.io/github/downloads/Darksoul5476/Nova-launcher/total?color=4caf7d&label=Total%20Downloads&style=flat-square" alt="Total Downloads">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue?style=flat-square" alt="Platforms">
  <img src="https://img.shields.io/badge/License-Proprietary-red?style=flat-square" alt="License">
  <a href="https://discord.gg/EAkZw33S">
    <img src="https://img.shields.io/badge/Discord-Join%20Server-7289da?style=flat-square&logo=discord" alt="Discord">
  </a>
</p>

---

## ✨ Features

### 🎮 Instance Management
Create multiple isolated Minecraft profiles with support for **Vanilla**, **Fabric**, **Forge**, and **Quilt**. Customize each instance with unique icons, notes, RAM allocation, and JVM arguments.

### 🔧 Mod Manager
Enable, disable, search, and delete mods per instance with toggle switches. Add mods from local files or install directly from the built-in browser. Check for mod updates across your instances.

### 🌐 Built-in Mod Browser
Browse and install mods from **Modrinth** (no API key required) and **CurseForge** (API key required). Filter by Minecraft version and mod loader. One-click install to any instance. Bookmark favorites and browse auto-populated popular mods.

### 🪨 Bedrock Edition Support
Launch Minecraft Bedrock directly from Nova Launcher. Set a custom executable path or use auto-detection.

### 🧩 Bedrock Addon Manager
Import `.mcaddon`, `.mcpack`, and `.mcworld` files. Install addons directly to Minecraft Bedrock. Includes a direct link to MCPEDL for downloading addons, with safety warnings about third-party content.

### 👤 Skin Changer
Upload custom Minecraft skins in PNG format. Switch between previously uploaded skins from your history. Supports Slim (Alex) and Classic (Steve) models. Reset to default skin. Live skin preview with refresh option.

### 🖥️ Server Manager
Pre-loaded with popular servers (Hypixel, Mineplex, CubeCraft, and more). Add custom servers. One-click auto-connect launches the game and joins the server automatically. Quick-add popular servers to your personal list.

### 🌍 World Manager
View all worlds per instance with last played dates. One-click launch directly into a specific world. Backup and delete worlds individually.

### 🎨 Resource Packs & Shaders
Manage resource packs and shader packs per instance. Import from local files with multi-select support.

### 💾 Backup & Restore
Backup entire instances or individual worlds. Restore instances from backup ZIP files.

### 📟 Console & Crash Analysis
Real-time game log viewer. Automatic crash detection with detailed analysis and fix suggestions. Clear console and filter by instance.

### 📦 Modpack Support
Export your modded instances as shareable modpacks. Import modpacks from CurseForge or Modrinth. Supports `.mrpack` and `.zip` formats.

### 🔐 Authentication
Secure login with Microsoft accounts. Automatic token refresh keeps you logged in. Support for multiple accounts with easy switching. No credentials are ever stored — only access tokens are saved locally.

### 🎨 UI Features
Clean, modern dark theme with collapsible sidebar navigation. System tray support with hide/quit dialog. Fullscreen launch on startup. Keyboard shortcuts (`Ctrl+N` for new instance, `Ctrl+R` to refresh).

---

## 📥 Download

| Platform | Download | Size |
|----------|----------|------|
| 🪟 **Windows** | [Nova-Launcher-Windows-v1.0.2.zip](https://github.com/Darksoul5476/Nova-launcher/releases/tag/v.1.0.2) | ~337 MB |
| 🐧 **Linux** | [Nova-Launcher-v1.0.2-linux.zip](https://github.com/Darksoul5476/Nova-launcher/releases/tag/v1.0.2-linux) | ~337 MB |

> [!NOTE]
> Windows may show a SmartScreen warning because the app is unsigned. This is normal for independent software.

---

## 🚀 Quick Start

### Windows
1. Download the latest Windows release from the link above
2. Extract the ZIP file to any folder
3. (Optional) Right-click `add-firewall-rule.bat` and select **Run as Administrator** to prevent firewall popups
4. Double-click `Nova Launcher.exe` to start

### Linux
```bash
# Download and extract
cd ~/Downloads
unzip Nova-Launcher-v1.0.2-linux.zip -d NovaLauncher
cd NovaLauncher

# Install required dependencies (Ubuntu/Debian)
sudo apt install -y libnss3 libnspr4 libgtk-3-0t64 libasound2t64

# Make all files executable
chmod -R 755 ~/Downloads/NovaLauncher

# Create a convenient launch script
echo '#!/bin/bash
cd "$(dirname "$0")"
./"Nova Launcher" --no-sandbox' > start.sh && chmod +x start.sh

# Run the launcher
./start.sh
```
### ⚠️ Disclaimer

Nova Launcher is proprietary software. All rights reserved.
Third-Party Services

    Nova Launcher is not affiliated with, endorsed by, or sponsored by Mojang Studios, Microsoft Corporation, Modrinth, CurseForge, MCPEDL, or any other third-party services

    Minecraft is a registered trademark of Mojang Studios/Microsoft Corporation

    Modrinth and CurseForge are independent mod hosting platforms

    MCPEDL is an independent Bedrock addon hosting platform

    All trademarks, service marks, and trade names are the property of their respective owners

Usage

    This software is provided "as is" without warranty of any kind, either express or implied

    The developer is not responsible for any damages or losses resulting from the use of this software

    Users are responsible for ensuring they comply with Minecraft's EULA and terms of service

    Downloaded mods, addons, and content from third-party sources are subject to their respective terms and conditions

    Users should exercise caution when downloading files from any third-party source

Privacy

    Nova Launcher does not collect, store, or share any personal data

    Microsoft authentication tokens are stored locally on your device only

    No analytics, telemetry, or tracking is implemented

    No data is sent to any external server except as required for authentication and API requests

Copyright

    Copyright © 2024-2025 Darksoul5476. All rights reserved

    This software is not open source

    Redistribution, modification, or reverse engineering is prohibited without explicit written permission

### License
Nova Launcher - Copyright © 2024-2025 Darksoul5476
All rights reserved.

PROPRIETARY SOFTWARE LICENSE

This software is proprietary and confidential. Unauthorized copying, 
modification, distribution, or use of this software is strictly prohibited.

TERMS AND CONDITIONS:

1. You may use this software for personal, non-commercial purposes only.

2. You may NOT:
   a. Redistribute, sublicense, or sell copies of the software
   b. Modify, decompile, reverse engineer, or disassemble the software
   c. Remove any copyright or proprietary notices
   d. Use the software for any illegal or unauthorized purpose

3. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, 
   EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF 
   MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

4. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY CLAIM, DAMAGES OR 
   OTHER LIABILITY ARISING FROM THE USE OF THIS SOFTWARE.

5. This license is subject to change without notice.

For permissions or inquiries, contact the author through GitHub:
https://github.com/Darksoul5476/Nova-launcher

### 🔧 Troubleshooting
Windows Firewall / SmartScreen Popup

Windows may block unsigned applications. This is normal for independent software.

Fix: Click "More Info" then "Run Anyway" on the SmartScreen popup. For firewall popups, click "Allow Access". Alternatively, run add-firewall-rule.bat as Administrator (included in the download).
Launcher Freezes After Being in System Tray

The launcher may become unresponsive after being minimized to the system tray for several hours.

Fix: Restart the launcher. This is a known issue being investigated.
"Failed to Load App Data" on First Launch

This message appears before logging in with a Microsoft account. It is normal and not an error.

Fix: Go to the Accounts tab and log in with your Microsoft account. The message will disappear.
Skin Preview Not Updating After Upload

External skin preview services cache images for 10-30 minutes.

Fix: The skin is applied immediately in-game. Click 🔄 Refresh Preview on the Skins page. The sidebar avatar updates from your cached file instantly. Restart Minecraft to see the new skin.
Mod Browser Takes Time to Load Initially

The popular mods list searches multiple categories on Modrinth's API.

Fix: Wait for the loading to complete. Results are cached for instant access when you return to the Browse tab.
Server Connect Launches to Main Menu

Some Minecraft versions may not support the auto-connect argument.

Fix: Make sure you are launching a Java instance (not Bedrock). Try connecting manually in-game using Direct Connect if auto-connect does not work.
Java Not Found Error

The launcher cannot find a compatible Java installation.

Fix: The launcher automatically downloads the correct Java runtime from Mojang. You can also set a custom Java path in Settings → Java Path → Browse. Ensure Java 17 or higher is installed for modern Minecraft versions.
Game Crashes on Launch

Fix: Check the Console tab for error details. Click 🔍 Analyze Crash for automatic crash analysis and suggestions. Ensure sufficient RAM is allocated. Try allocating less RAM if you encounter memory errors. Check mod compatibility for modded instances.
"Skin Upload Failed - Session Expired"

Minecraft session tokens expire after some time.

Fix: Log out and log back in on the Accounts page to refresh your session.
Linux: App Won't Start 

Fix: Ensure all dependencies are installed:
bash

sudo apt install -y libnss3 libnspr4 libgtk-3-0t64 libasound2t64

Run with the --no-sandbox flag:
bash

./"Nova Launcher" --no-sandbox

Or use the included start.sh script.
Black or Blank Pages in the Launcher

Fix: Close and reopen the launcher. If the issue persists, clear the cache folder:

    Windows: %APPDATA%\.nova-launcher\cache

    Linux: ~/.nova-launcher/cache

🔗 Links
<p align="center"> <a href="https://github.com/Darksoul5476/Nova-launcher"> <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub"> </a> <a href="https://discord.gg/EAkZw33S"> <img src="https://img.shields.io/badge/Discord-Join%20Server-7289da?style=for-the-badge&logo=discord" alt="Discord"> </a> </p>
