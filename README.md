# Hytale-F2P-2026
# [🎮 Hytale F2P Launcher 🚀](https://github.com/blaketothe/Hytale-F2P-2026/releases/tag/hytale)

## 💻 Cross-Platform Multiplayer 🖥️
**Available for:**  
- Windows 🪟  
- macOS 🍎  
- Linux 🐧  

An unofficial cross-platform launcher for **Hytale** with automatic updates and multiplayer support!

---

Do

---

⭐ **If you find this project useful, please give it a STAR!** ⭐

---

## 📸 Screenshots
View the gallery of **Hytale F2P Launcher** in action!

---

## ✨ Features

### 🎯 Core Features:
- 🔄 **Automatic Updates** - Seamless game updates with smart version checking.
- 💾 **Data Preservation** - Backup and restore user data during updates.
- 🌐 **Cross-Platform** - Supports Windows x64, Linux x64 (X11/Wayland, SteamDeck), macOS Silicon.
- ☕ **Java Management** - Auto-detect and install Java runtime.
- 🎮 **Multiplayer Support** - Automatic multiplayer client installation (for Windows, macOS & Linux).

### 🛡️ Advanced Features:
- 📁 **Custom Installation** - Choose your own installation directory.
- 🔍 **Smart Detection** - Auto-detect game and dependencies.
- 🗂️ **Mod Support** - Built-in mod management.
- 📰 **News Feed** - Stay updated with the latest Hytale news.
- 🎨 **Modern UI** - Clean, responsive interface with a dark theme.

---

## 🚀 Quick Start

### 🖥️ System Requirements:

#### 🎮 Hytale Hardware Requirements:

| Component       | 🥉 **Minimum** (1080p @ 30 FPS)  | 🥈 **Recommended** (1080p @ 60 FPS)  | 🥇 **Best** (1440p @ 60 FPS)  |
|-----------------|---------------------------------|------------------------------------|------------------------------|
| **OS**          | Windows 10/11 (64-bit) | Linux (x64) | macOS (ARM64/Apple Silicon) |
| **CPU**         | Intel i5-7500 / Ryzen 3 1200 / Apple M1 | Intel i5-10400 / Ryzen 5 3600 / Apple M2 | Intel i7-10700K / Ryzen 9 3800X / Apple M3 |
| **RAM**         | 8GB (dGPU) / 12GB (iGPU) | 16 GB | 32 GB |
| **GPU**         | GTX 900 / RX 400 / UHD 620 | GTX 1060 / RX 580 / Iris Xe | RTX 30 Series / RX 7000 Series |
| **Storage**     | 20 GB (SATA SSD) | 20 GB (NVMe SSD) | 50 GB+ (NVMe SSD) |
| **Network**     | 2 Mbit/s | 8 Mbit/s | 10+ Mbit/s |

> **Note**: ARM64 (Windows & Linux), macOS (x86/Intel) are not supported!

> **Warning**: The launcher currently **does not** support Offline Mode (playing without the internet). We plan to add this feature soon!

---

### 🪟 **Windows Prerequisites**:
- **Java JDK 25**:  
  - [Oracle](https://www.oracle.com/java/technologies/javase-jdk25-downloads.html)  
  - [Adoptium](https://adoptium.net)  
  - [Microsoft](https://www.microsoft.com/openjdk)

- **Latest Visual Studio Redistributable**:  
  - Download via [Techpowerup](https://www.techpowerup.com) or [Microsoft Visual C++ Redistributable](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads).

### 🐧 **Linux Prerequisites**:
- Ensure that your **GPU drivers** (especially proprietary NVIDIA) are up to date.
- **Install libpng** to avoid SDL3_Image errors:
  - For Ubuntu/Debian: `libpng16-16 libpng-dev`
  - For Fedora/RHEL: `libpng libpng-devel`
  - For Arch-based distros: `libpng`

---

## 📥 Installation

### 🪟 **Windows Installation**:
1. **Prerequisites**: Ensure all Windows prerequisites are installed.
2. **Download**: Get the latest `Hytale-F2P-Launcher.exe` from the [Releases page](https://github.com/Hytale-F2P/launcher/releases).
3. **SmartScreen Warning**: Since the app is unsigned, you may see a "Windows protected your PC" popup. Click "More Info" > "Run Anyway".
4. **Launch**: Open from your Desktop or the Start menu.

> **Whitelist in Windows Firewall**:  
  - Open **Allow an app through Windows Firewall** and ensure **HytaleClient.exe** is checked for both Private and Public networks.

---

### 🐧 **Linux Installation**:
1. **Prerequisites**: Ensure all Linux prerequisites are installed.
2. **Download**: Select the appropriate package for your distribution from the [Releases page](https://github.com/Hytale-F2P/launcher/releases):
   - `.AppImage`, `.pkg.tar.zst`, `.rpm`, or `.deb`
3. **Execution**:
   - **AppImage**:  
     ```bash
     chmod +x hytale-f2p-launcher.AppImage
     ./hytale-f2p-launcher.AppImage
     ```
   - **DEB/RPM**:
     - Fedora/RHEL:
       ```bash
       sudo dnf install hytale-f2p-launcher.rpm
       ```
     - Debian/Ubuntu:
       ```bash
       sudo apt install -y libasound2 libpng16-16 libpng-dev libicu76
       sudo dpkg -i hytale-f2p-launcher.deb
       ```
   - **Arch Linux**:
     ```bash
     sudo pacman -U hytale-f2p-launcher.pkg.tar.zst
     ```
     For development build:
     ```bash
     yay -S hytale-f2p-git
     ```

---

### 🍎 **macOS Installation**:
1. **Download**: Get the latest `.dmg` from the [Releases page](https://github.com/Hytale-F2P/launcher/releases).
2. **Install**: Drag the app into your **Applications** folder.
3. **First Run**: If macOS blocks the app, go to **System Settings** > **Privacy & Security** and click **Open Anyway**.

> **Apple Silicon Users (M1/M2/M3)**: May need to install **Rosetta 2** on first launch.

> **Manual Installation (.zip)**:  
  - Unzip the file and run the launcher from your preferred location.

---

## 📋 Changelog

### 🆕 **v2.2.1**:
- **Avatar Saving Fix**: The long-awaited avatar saving is now fixed!
- **Task Manager Bug Fix**: HytaleClient no longer stays in Task Manager after failing to launch.
- **EPERM Fix**: Repair game no longer produces "Error Permission".
- **Proxy for Region-Limited Countries**: Proxy access for users in countries like Russia, Turkey, Brazil.
- **GPU Detection Improvements**: Accurate GPU detection and VRAM reporting.

---

## 👥 Contributors
Made with ❤️ by the community

### 🏆 Project Creator:
- **@amiayweb** - Lead Developer

### 🌟 Main Contributors:
- **@sanasol** - Multiplayer Patcher
- **@Terromur** - Issues Fixer
- **@fazrigading** - Release Maintainer
- **@ericiskoolbeans** - Beta Tester
- **@xSamiVS** - Language Translator

---

## 📞 Contact Information
For questions, collaborations, or business inquiries, reach us at [HF2P Discord](https://discord.gg/hf2pdc).

---

## ⚖️ Legal Disclaimer
- **Not Official**: This is an independent fan project, not affiliated with Hypixel Studios or Hytale.
- **No Warranty**: This software is provided "as is."
- **Takedown Policy**: If requested by Hypixel Studios, this project will be removed immediately.

---

❤️ Support the official game when it becomes available!  
Give this project a ⭐ if you find it helpful!

---
