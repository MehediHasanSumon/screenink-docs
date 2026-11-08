<p align="center">
  <img src="assets/icons/screenink.svg" alt="ScreenInk Logo" width="112" height="112" />
</p>

<h1 align="center">ScreenInk Documentation & Downloads</h1>

<p align="center">
  <strong>Commercial-grade, memory-safe, ultra-low-latency live screen annotation software.</strong><br>
  Built with modern <strong>C++20</strong> and <strong>Qt 6</strong> for presenters, educators, streamers, and engineers.
</p>

<p align="center">
  <a href="#-cross-platform-downloads"><img src="https://img.shields.io/badge/Release-v1.0.0-blue.svg?style=flat-square" alt="Version 1.0.0" /></a>
  <a href="#-cross-platform-downloads"><img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20macOS-green.svg?style=flat-square" alt="Supported Platforms" /></a>
  <img src="https://img.shields.io/badge/Standard-C%2B%2B20-orange.svg?style=flat-square" alt="C++20" />
  <img src="https://img.shields.io/badge/Framework-Qt%206-41CD52.svg?style=flat-square" alt="Qt 6" />
  <img src="https://img.shields.io/badge/License-Proprietary-red.svg?style=flat-square" alt="License" />
</p>

---

## 📖 Table of Contents
- [📥 Cross-Platform Downloads](#-cross-platform-downloads)
- [🚀 Quick Installation](#-quick-installation)
  - [Linux (Ubuntu / Debian / Mint)](#1-linux-ubuntu--debian--mint)
  - [Linux (Fedora / RHEL / openSUSE)](#2-linux-fedora--rhel--opensuse)
  - [Linux (Universal AppImage)](#3-linux-universal-appimage)
  - [Microsoft Windows (10 & 11)](#4-microsoft-windows-10--11)
  - [Apple macOS (Apple Silicon & Intel)](#5-apple-macos-apple-silicon--intel)
- [✨ Core Features](#-core-features)
- [⌨️ Global Shortcuts Cheatsheet](#️-global-shortcuts-cheatsheet)
- [💻 Command-Line Interface (CLI)](#-command-line-interface-cli)
- [🛡️ Architecture & Security](#️-architecture--security)
- [👨‍💻 Developer & Contact](#-developer--contact)

---

## 📥 Cross-Platform Downloads

Download official production builds of **ScreenInk v1.0.0** for your operating system:

| Operating System | Architecture | Package Format | Recommended For | Direct Download Link | Package Size | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🐧 **Linux** | `x86_64` (amd64) | **`.deb`** | Ubuntu 20.04+, Debian 11+, Linux Mint | [📥 **Download .deb**](https://github.com/MehediHasanSumon/screenink-docs/releases/download/v1.0.0/ScreenInk-1.0.0-Linux.deb) | `344 KB` | 🟢 Stable |
| 🐧 **Linux** | `x86_64` (amd64) | **`.AppImage`** | All Linux Distros (No install required) | [📥 **Download .AppImage**](https://github.com/MehediHasanSumon/screenink-docs/releases/download/v1.0.0/ScreenInk-1.0.0-x86_64.AppImage) | `~25.2 MB` | 🟢 Stable |
| 🐧 **Linux** | `x86_64` (amd64) | **`.rpm`** | Fedora 38+, RHEL, CentOS Stream, openSUSE | [📥 **Download .rpm**](https://github.com/MehediHasanSumon/screenink-docs/releases/download/v1.0.0/ScreenInk-1.0.0-Linux.rpm) | `~8.6 MB` | 🟢 Stable |
| 🪟 **Windows** | `x64` (64-bit) | **`.exe` (Setup)** | Windows 10 & Windows 11 (Standard Setup) | [📥 **Download Setup .exe**](https://github.com/MehediHasanSumon/screenink-docs/releases/download/v1.0.0/ScreenInk-1.0.0-Setup.exe) | `~14.8 MB` | 🟢 Stable |
| 🪟 **Windows** | `x64` (64-bit) | **`.zip` (Portable)** | Windows 10 & Windows 11 (Run without Admin) | [📥 **Download Portable .zip**](https://github.com/MehediHasanSumon/screenink-docs/releases/download/v1.0.0/ScreenInk-1.0.0-win64-portable.zip) | `~15.2 MB` | 🟢 Stable |
| 🍏 **macOS** | `Apple Silicon` (M1–M4) | **`.dmg`** | macOS 12 Monterey – macOS 15 Sequoia (ARM64) | [📥 **Download .dmg (ARM64)**](https://github.com/MehediHasanSumon/screenink-docs/releases/download/v1.0.0/ScreenInk-1.0.0-arm64.dmg) | `~18.5 MB` | 🟢 Stable |
| 🍏 **macOS** | `Intel` (x86_64) | **`.dmg`** | macOS 12 Monterey – macOS 15 Sequoia (Intel) | [📥 **Download .dmg (Intel)**](https://github.com/MehediHasanSumon/screenink-docs/releases/download/v1.0.0/ScreenInk-1.0.0-x86_64.dmg) | `~19.1 MB` | 🟢 Stable |

---

## 🚀 Quick Installation

### 1. Linux (Ubuntu / Debian / Mint)
Download the `.deb` package and install it via terminal:
```bash
sudo dpkg -i ScreenInk-1.0.0-Linux.deb
sudo apt install -f   # Resolve any optional dependencies
```

### 2. Linux (Fedora / RHEL / openSUSE)
Install the `.rpm` package:
```bash
sudo dnf install ScreenInk-1.0.0-Linux.rpm
# or on openSUSE:
sudo zypper install ScreenInk-1.0.0-Linux.rpm
```

### 3. Linux (Universal AppImage)
Make it executable and launch directly:
```bash
chmod +x ScreenInk-1.0.0-x86_64.AppImage
./ScreenInk-1.0.0-x86_64.AppImage
```

### 4. Microsoft Windows (10 & 11)
- **Standard Installer**: Double-click `ScreenInk-1.0.0-Setup.exe` and follow the wizard. ScreenInk will add a Start Menu entry, desktop shortcut, and system tray icon.
- **Portable Version**: Extract `ScreenInk-1.0.0-win64-portable.zip` anywhere and launch `screenink.exe`.

### 5. Apple macOS (Apple Silicon & Intel)
1. Open the downloaded `ScreenInk-1.0.0-arm64.dmg` (or Intel `.dmg`).
2. Drag the `ScreenInk.app` icon into your `Applications` folder.
3. On first run, grant **Accessibility** permissions under *System Settings -> Privacy & Security -> Accessibility* so global drawing hotkeys can be captured.

---

## ✨ Core Features

- **100% Fullscreen Panel Coverage**: Draws directly across system panels, docks, and multi-monitor boundaries without dead zones or gray bars.
- **Instant Dual-Mode Toggle**:
  - `Sketch Mode`: Full transparent drawing canvas directly on top of your live desktop.
  - `Interact Mode`: True mouse click-through to underlying IDEs, browser tabs, and applications without hiding existing drawings.
- **Swept-Capsule Geometric Eraser**: High-precision eraser that cuts and trims polylines and curves smoothly without lag.
- **19 Geometric Shapes**: Lines, arrows, double-headed arrows, rectangles, rounded boxes, circles/ellipses, stars, hearts, speech bubbles, coordinate axes, and number callouts.
- **Photoshop-Style Flyouts**: Compact, non-intrusive floating toolbar with expandable color swatches, opacity controls, and custom color picker.
- **Whiteboard Canvases**: 1-click switching between transparent desktop, pure white canvas, dark chalkboard, and 28px dot grid.
- **Multi-Monitor Isolation**: Independent undo/redo history stacks and DPI coordinate mapping per monitor.
- **Screen Sharing Ready**: Deliberately compatible with Zoom, Google Meet, Microsoft Teams, OBS Studio, and Discord.

---

## ⌨️ Global Shortcuts Cheatsheet

| Action | Primary Shortcut | Alternative Shortcut | Mode Availability |
| :--- | :--- | :--- | :--- |
| **Toggle Sketch / Interact Mode** | `F1` | `Ctrl + Shift + D` | Global (Always) |
| **Clear All Annotations** | `Delete` | `Ctrl + Shift + X` | Sketch Mode |
| **Undo Last Stroke** | `Ctrl + Z` | `Ctrl + Z` | Sketch Mode |
| **Redo Last Stroke** | `Ctrl + Y` | `Ctrl + Shift + Z` | Sketch Mode |
| **Pen Tool** | `P` | `P` | Sketch Mode |
| **Highlighter** | `H` | `H` | Sketch Mode |
| **Text Tool** | `T` | `T` | Sketch Mode |
| **Eraser Tool** | `E` | `E` | Sketch Mode |
| **Laser Pointer** | `X` | `X` | Sketch Mode |
| **Spotlight Tool** | `S` | `S` | Sketch Mode |
| **Rectangle Shape** | `R` | `R` | Sketch Mode |
| **Ellipse / Circle** | `O` | `O` | Sketch Mode |
| **Straight Line** | `L` | `L` | Sketch Mode |
| **Arrow Tool** | `A` | `A` | Sketch Mode |
| **Cycle Colors** | `C` / `Shift + C` | `C` | Sketch Mode |
| **Whiteboard Canvas Cycle** | `W` | `W` | Sketch Mode |
| **Freeze / Resume Screen** | `F` | `F` | Sketch Mode |
| **Save Screenshot (PNG)** | `Ctrl + S` | `Ctrl + S` | Sketch Mode |
| **Copy to Clipboard** | `Ctrl + C` | `Ctrl + C` | Sketch Mode |
| **Hide / Show Floating Toolbar** | `Tab` | `Tab` | Sketch Mode |

---

## 💻 Command-Line Interface (CLI)

ScreenInk provides comprehensive CLI parameters for scripting, stream decks, and automation:

```bash
screenink [options]
```

| Flag | Description |
| :--- | :--- |
| `-h`, `--help` | Displays command-line options and usage guide |
| `-v`, `--version` | Displays current version and branding info |
| `--sketch` | Starts ScreenInk directly in Sketch (draw) mode |
| `--interact` | Starts ScreenInk directly in Interact (click-through) mode |
| `--safe-mode` | Starts in safe recovery mode with default factory settings |
| `--reset-settings`| Resets corrupted or non-standard configuration to defaults |
| `--profile <name>`| Loads a specific profile (`Teaching`, `Coding`, `Streaming`) |

---

## 🛡️ Architecture & Security

- **Pure C++20 Core**: Mathematical algorithms, stroke geometry, and history stacks operate without GUI dependencies and have 100% automated test coverage.
- **Memory Safety**: Clean AddressSanitizer (ASan) and UndefinedBehaviorSanitizer (UBSan) verification with zero leaks.
- **Privacy First**: Zero telemetry, zero external network calls, and zero tracking. All settings and annotations remain strictly on your local device.

---

## 👨‍💻 Developer & Contact

- **Author**: **Md Mehedi Hasan**
- **Role**: Full Stack & Systems Developer
- **Location**: Dhaka, Bangladesh
- **Email**: `mehedihassan2992001@gmail.com`
- **Website & Portfolio**: [https://mehedih.me/](https://mehedih.me/)
- **GitHub**: [@MehediHasanSumon](https://github.com/MehediHasanSumon)

<p align="center">
  <sub>© 2026 Md Mehedi Hasan. All rights reserved.</sub>
</p>
