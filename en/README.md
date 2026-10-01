<p align="center">
  <a href="https://quran.ksu.edu.sa/ayat/">
    <img src="../ayat.png" alt="Ayat Logo" width="220" />
  </a>
</p>

<h1 align="center">Ayat (Electronic Quran) - Linux AppImage</h1>

<p align="center">
  <b>A portable AppImage edition of the Ayat Windows (x64) application, ready to run directly across all 64-bit Linux distributions without prior installation or manual Wine setup.</b>
</p>

<p align="center">
  <b>🇬🇧 English Version</b> | <a href="../ar/README.md"><b>🇸🇦 النسخة العربية</b></a>
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download-AppImage_x86__64-007ACC?style=for-the-badge&logo=appimage&logoColor=white" alt="Download AppImage"></a>
  <a href="#-system-requirements--linux-distributions"><img src="https://img.shields.io/badge/Architecture-x86__64-107C41?style=for-the-badge" alt="Architecture x86_64"></a>
  <a href="https://quran.ksu.edu.sa/ayat/"><img src="https://img.shields.io/badge/KSU-Electronic_Quran-green?style=for-the-badge" alt="King Saud University"></a>
  <img src="https://img.shields.io/badge/Wine_Bundled-v11.18-purple?style=for-the-badge&logo=wine" alt="Wine Bundled">
</p>

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [Why AppImage?](#-why-appimage)
- [Pre-bundled Package Contents](#-pre-bundled-package-contents)
- [Key Features](#-key-features)
- [Download & Execution](#-download--execution)
- [System Requirements & Linux Distributions](#-system-requirements--linux-distributions)
- [Application Menu Integration (Optional)](#-application-menu-integration-optional)
- [Technical Details & Data Storage](#-technical-details--data-storage)
- [Troubleshooting](#-troubleshooting)
- [Disclaimer & Rights](#-disclaimer--rights)

---

## 🕋 About the Project

**Ayat (آيات)** is the interactive software simulator for the Holy Quran, developed by the **Electronic Quran Project at King Saud University (KSU)**. It is one of the most comprehensive and renowned Quranic desktop applications, providing a digital copy of Madina Mushaf alongside interactive features such as audio recitations, interpretations (Tafseer), multi-language translations, and memorization testing tools.

This repository provides an **unofficial AppImage packaging of the Windows x64 version**, making it seamless to execute on Linux distributions out of the box.

---

## 🚀 Why AppImage?

- **Fully Portable:** A single executable file that runs instantly on any Linux distro without complex setup.
- **Dependency Independence:** Bundles the required runtime environment and compatible Wine layer, remaining unaffected by host system updates.
- **No Root Required:** Runs smoothly as a standard user without requiring `sudo` privileges.
- **Offline Ready Out-of-the-Box:** Includes all Quran pages, interpretations (Tafseer), and translations directly within the AppImage file without requiring online content downloads.
- **Clean System Integration:** All application states, recitations, and settings are saved neatly in the user's home directory without modifying root filesystem files.

---

## 📦 Pre-bundled Package Contents

This AppImage release is **fully self-contained and pre-bundled**, embedding all essential Quranic resources directly into the executable package:

- 📖 **High-Resolution Quran Pages:** Complete pages of the Madina Mushaf in authentic Uthmani script are bundled for instant offline viewing.
- 📚 **Standard Quranic Interpretations (Tafseer):** Includes major Tafseer books (such as Al-Sa'di, Ibn Kathir, Al-Qurtubi, Al-Tabari, Al-Jalalayn, Al-Baghawi, etc.) available offline immediately.
- 🌐 **Multi-language Translations:** Core translations of the Quranic meanings across multiple languages are pre-installed within the package.
- 🎧 **Audio Recitations:** Additional recitations can be fetched on demand according to user preference, and are automatically cached locally in the user's directory.

---

## ✨ Key Features

- 📜 **Madina Mushaf Page Layout:** High-resolution rendering of the Holy Quran pages in authentic Uthmani script.
- 🎙️ **Audio Recitations:** Listen to world-renowned Qaris with verse repetition capabilities to assist in memorization.
- 📚 **Tafseer & Quranic Sciences:** Includes famous interpretations (Ibn Kathir, Al-Sa'di, Al-Qurtubi, Al-Tabari, Al-Jalalayn, Al-Baghawi, and more).
- 🌐 **Global Translations:** Meanings translated into over 20 languages worldwide.
- 🔎 **Smart Search:** Fast and precise searching across the Quranic text with or without diacritics (Tashkeel).
- 📝 **Memorization Testing:** Verse/passage repetition mode with text-hiding capabilities for testing.

---

## 📥 Download & Execution

### Step 1: Download the AppImage
Navigate to the **[Releases](https://github.com/HBI-Developer/ayat-appimage/releases)** page of this repository and download the latest AppImage file:
`Ayat-1.4-x86_64.AppImage`

### Step 2: Make It Executable
Open your terminal in the directory where the file was downloaded and grant execution permission:

```bash
chmod +x Ayat-1.4-x86_64.AppImage
```

> **Alternatively via GUI:** Right-click the downloaded file ⬅️ Select **Properties** ⬅️ Go to **Permissions** tab ⬅️ Check **Allow executing file as program**.

### Step 3: Run the Application
Double-click the file in your file manager, or run it via terminal:

```bash
./Ayat-1.4-x86_64.AppImage
```

---

## 💻 System Requirements & Linux Distributions

### Minimum System Specs & Libraries:
- **Processor:** 64-bit (`x86_64`) compatible CPU.
- **RAM:** 2 GB minimum.
- **System Libraries:** Requires `glibc 2.27` or newer, and `libfuse2` package for AppImage mounting.

### 🐧 Minimum Supported Linux Distribution Versions

| Distribution | Minimum Supported Version | Recommended Versions |
| :--- | :---: | :---: |
| **Ubuntu** | **18.04 LTS** or newer | 20.04 LTS / 22.04 LTS / 24.04 LTS |
| **Debian** | **Debian 10 (Buster)** or newer | Debian 11 (Bullseye) / Debian 12 (Bookworm) |
| **Linux Mint** | **19.x (Tara)** or newer | 20.x / 21.x / 22.x |
| **Fedora** | **Fedora 30** or newer | Fedora 38 / 39 / 40 |
| **Arch Linux / Manjaro** | **Rolling Release (Up-to-date)** | Latest system updates |
| **Pop!_OS** | **20.04 LTS** or newer | 22.04 LTS |
| **openSUSE** | **Leap 15.2** or newer | Leap 15.5+ / Tumbleweed |
| **RHEL / AlmaLinux / Rocky** | **8.0** or newer | 8.x / 9.x |

---

## 🎨 Application Menu Integration (Optional)

To integrate Ayat into your system application launcher menu with its official icon:

You can use [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) to integrate any AppImage automatically with a single click.

**Or create a manual `.desktop` entry (`ayat.desktop`):**

1. Place the AppImage file in your preferred applications folder (e.g., `~/Applications/`).
2. Create a file at `~/.local/share/applications/ayat.desktop` with the following contents:

```ini
[Desktop Entry]
Name=Ayat - Electronic Quran
Comment=Electronic Quran Application by King Saud University
Exec=/path/to/Ayat-1.4-x86_64.AppImage
Icon=ayat
Terminal=false
Type=Application
Categories=Education;Religion;Utility;
```
*(Replace `/path/to/` with the actual path to your downloaded AppImage file).*

---

## 🛠️ Technical Details & Data Storage

- **Execution Engine:** Uses an Adobe AIR runtime engine running inside an isolated Wine sub-prefix, self-contained within the AppImage executable.
- **Font Handling:** Configured to dynamically load proprietary fonts (such as `Georgia`, `Times`, `Verdana`, and `Arial`) if present on the host Linux environment for superior typography rendering, using suitable fallbacks otherwise.
- **Embedded Dataset:** The AppImage comes fully pre-loaded with complete Quran pages, standard Tafseers, and core translations for offline readiness.
- **User Data & Configuration Directory:**
  Upon first launch, a lightweight runtime prefix is initialized at:
  `~/.local/share/ayat-appimage/`
- **Downloaded Recitations & Tafseer Data:**
  All downloaded audio files and translations are retained inside the user's data directory, preserving downloaded content across AppImage updates or relocations.

---

## ❓ Troubleshooting

### 1. File fails to run on double-click (Ubuntu 22.04+ / Debian 12)
This is typically caused by missing FUSE 2 library support. Install `libfuse2` using your package manager:

- **Ubuntu / Debian / Mint:**
  ```bash
  sudo apt install libfuse2
  ```
- **Fedora:**
  ```bash
  sudo dnf install fuse-libs
  ```
- **Arch Linux / Manjaro:**
  ```bash
  sudo pacman -S fuse2
  ```

### 2. Resetting Application Data
If you encounter runtime errors or wish to start fresh as if launching for the first time, remove the user data directory:

```bash
rm -rf ~/.local/share/ayat-appimage
```

---

## 📜 Disclaimer & Rights

- **Ayat (آيات):** Is an open project serving the Holy Quran, developed by **King Saud University (KSU)**, Kingdom of Saudi Arabia. All intellectual property, Quranic texts, images, and audio recitations belong to King Saud University.
- **This Repository:** Is an unofficial community project solely aimed at packaging and distributing Ayat as a portable AppImage for Linux users worldwide.
