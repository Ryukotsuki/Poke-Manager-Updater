<p align="center">
  <img src="https://github.com/Ryukotsuki/Poke-Manager-Updater/assets/50199421/2fafe453-cbe3-49ff-8ff2-caebeec90e26" alt="Poke Manager Updater logo" width="520" />
</p>

<h1 align="center">Poke Manager Updater</h1>

<p align="center">
  A lightweight Windows updater for downloading and applying the latest Poke Manager release with live progress, speed, and version feedback.
</p>

<p align="center">
  <a href="https://github.com/Ryukotsuki/Poke-Manager-Updater/releases"><img src="https://img.shields.io/github/v/release/Ryukotsuki/Poke-Manager-Updater?style=for-the-badge&label=Latest%20Release" alt="Latest release"></a>
  <a href="https://github.com/Ryukotsuki/Poke-Manager-Updater/releases"><img src="https://img.shields.io/github/downloads/Ryukotsuki/Poke-Manager-Updater/total?style=for-the-badge" alt="Downloads"></a>
  <a href="https://github.com/Ryukotsuki/Poke-Manager-Updater/stargazers"><img src="https://img.shields.io/github/stars/Ryukotsuki/Poke-Manager-Updater.svg?style=for-the-badge" alt="Stars"></a>
  <a href="https://github.com/Ryukotsuki/Poke-Manager-Updater/issues"><img src="https://img.shields.io/github/issues/Ryukotsuki/Poke-Manager-Updater.svg?style=for-the-badge" alt="Issues"></a>
</p>

---

## ✨ Features

- 🔄 **Automatic Poke Manager Updates**  
  Checks the latest release from `Ryukotsuki/Poke-Manager` and downloads the newest available build.

- 📦 **Direct Replacement Workflow**  
  Downloads the latest `PokeManager.exe` and applies it in-place.

- 🛑 **Safe App Closure**  
  Attempts to close running `PokeManager.exe` instances before replacing the file.

- 📊 **Live Progress Tracking**  
  Shows graphical progress while the update is downloading.

- ⚡ **Download Speed Metrics**  
  Displays downloaded MB, total MB, and real-time MB/s speed.

- 🏷️ **Version Feedback**  
  Shows which version is currently being downloaded.

- 🚀 **Automatic Relaunch**  
  Restarts Poke Manager after the update finishes.

- 🎨 **Compact Desktop UI**  
  Uses a small frameless PySide6 interface with the PokeMMO-style branding used across the manager tools.

---

## 📸 Preview

<p align="center">
  <img alt="Poke Manager Updater screenshot" src="https://github.com/user-attachments/assets/3db74558-d4fb-4a11-81e9-059748fa74f6" />
</p>

---

## 🚀 Getting Started

### ⬇️ Download

Download the latest updater release from the [Releases page](https://github.com/Ryukotsuki/Poke-Manager-Updater/releases).

---

## 🧭 How It Works

Poke Manager Updater checks:

```text
https://api.github.com/repos/Ryukotsuki/Poke-Manager/releases/latest
```

When a newer release is found, the updater downloads the first release asset and saves it as:

```text
PokeManager.exe
```

It also uses `PokeUpdater Version.txt` to track updater version information:

```text
Latest Version: 2.9.7
Current Version: 2.9.7
```

## 💖 Support

If Poke Manager Updater helps you, a star on GitHub goes a long way.

- ⭐ Star the repository
- 🐛 Report bugs through [Issues](https://github.com/Ryukotsuki/Poke-Manager-Updater/issues)
- 💡 Suggest improvements or new features
- 💸 [Donate via PayPal](https://paypal.me/Ryukotsuki?country.x=US&locale.x=en_US)

### 💬 Community

Have questions, feedback, or want to share your setup? Join the Discord:

<p align="center">
  <a href="https://discord.gg/HdfjKbPNc9">
    <img src="https://github.com/user-attachments/assets/09fb5822-5e82-431b-b9cc-bbd4111ba48b" alt="Join Discord" />
  </a>
</p>

---

## 📜 Disclaimer

Poke Manager Updater is an independent fan-made utility. It is not affiliated with, endorsed by, or officially connected to [PokeMMO](https://pokemmo.com/) or its developers.

---

<p align="center">
  Built to keep Poke Manager updated with less fuss. ✨
</p>
