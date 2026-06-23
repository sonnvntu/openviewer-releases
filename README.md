<div align="center">

<img src="assets/openviewer_256.png" alt="OpenViewer Logo" width="128" height="128">

# OpenViewer

**Remote Access and AI-Powered Vision**

[English](README.md) | [Tiếng Việt](README_vi.md)

[![License](https://img.shields.io/badge/license-Proprietary-blue.svg)](#)
[![Platform](https://img.shields.io/badge/platform-Windows%20|%20Linux%20|%20macOS%20|%20Android%20|%20iOS-brightgreen.svg)](#download)
[![GitHub Release](https://img.shields.io/github/v/release/sonnvntu/openviewer-releases?include_prereleases&label=latest)](https://github.com/sonnvntu/openviewer-releases/releases/latest)

</div>

---

## ✨ About

**OpenViewer** is an AI-powered platform that brings together remote access, camera monitoring, and intelligent automation.

### Key Features

- 🖥️ **Remote Access** — View and control any computer from anywhere
  - Low-latency, high-FPS screen streaming.
  - Multi-monitor navigation and management.
  - High-performance screen & audio capture via DXGI (Windows), ScreenCaptureKit (macOS), and X11/Wayland/PipeWire (Linux).
  - High-performance, secure file transfer.
- 📹 **AI-Powered Vision** — Transform cameras into intelligent sensors.
  - Support CPU and GPU acceleration via Vulkan.
  - Deploy custom AI models trained for your specific use cases.
  - Detect people, fire, vehicles, and other critical events.
  - Enhance confidence with multi-stage Detection and Classification pipelines.
  - Create visual AI workflows: Detection → Classification → Rule → Alert.
  - Trigger real-time notifications and automated responses.
- 🔒 **End-to-End Encrypted** — P2P connection with DTLS encryption
- 📱 **Cross-Platform** — Windows, Linux, macOS, Android, iOS
- 🌐 **No Port Forwarding** — Works behind NAT with STUN/TURN relay
- 🔔 **Push Notifications** — AI event alerts delivered to your phone

---

## 🚀 Quick Start

Get started with **OpenViewer** in three simple steps:

### 1. Download OpenViewer
Download the latest client or host installer for your platform from the [GitHub Releases](https://github.com/sonnvntu/openviewer-releases/releases/latest) page.
* Available for Windows, Linux, macOS, Android, and iOS.

### 2. Run and Setup
* **On the Host computer**: Run the OpenViewer Host application to enable remote access and start configuring AI-Powered Vision features.
* **On the Client device**: Open the OpenViewer app (Desktop or Mobile) to connect.

### 3. Connect & Control
* Log in with your account or use the generated connection ID to establish a secure P2P remote session.
* Configure your cameras and start deploying AI models directly from the dashboard.

---

## 📦 Installation Guide

### 🪟 Windows
1. Download the `openviewer-windows-x64.zip` or `.exe` from [Releases](https://github.com/sonnvntu/openviewer-releases/releases/latest).
2. Extract the ZIP file (if downloaded) or run the installer `.exe`.
3. Open `OpenViewer.exe` to start.

### 🐧 Linux
1. Download the `openviewer-linux-x64.AppImage` (or `OpenViewer-v1.0.1-linux-amd64.deb` package).
2. For **AppImage**:
   * Right-click the file, go to **Properties** -> **Permissions** -> check **Allow executing file as program**.
   * Or run the following command in your terminal:
     ```bash
     chmod +x openviewer-linux-x64.AppImage
     ./openviewer-linux-x64.AppImage
     ```
3. For **DEB** (Debian/Ubuntu):
   ```bash
   # Install
   sudo apt install ./OpenViewer-v1.0.1-linux-amd64.deb

   # Reinstall
   sudo apt install --reinstall ./OpenViewer-v1.0.1-linux-amd64.deb
   ```

### 🍎 macOS
1. Download the `openviewer-macos-x64.dmg` (or arm64 for Apple Silicon).
2. Double-click the `.dmg` file and drag **OpenViewer** to your **Applications** folder.
3. If you get a "Developer cannot be verified" warning:
   * Go to **System Settings** > **Privacy & Security**.
   * Scroll down and click **Open Anyway**.

### 🤖 Android (APK)
1. Download the `openviewer-android.apk` file on your device.
2. Open the downloaded file. If prompted, enable **"Install from Unknown Sources"** in settings.
3. Tap **Install** and open the app.

---

## 📸 Screenshots

### 💻 Desktop App
<div align="center">
  <img src="assets/desktop_dashboard.png" alt="Desktop Dashboard & Notifications" width="99%">
</div>
<div align="center" style="margin-top: 10px;">
  <img src="assets/desktop_ai_live.png" alt="Desktop AI Live Stream" width="49%">
  <img src="assets/desktop_ai_events.png" alt="AI Events History" width="49%">
</div>
<div align="center" style="margin-top: 10px;">
  <img src="assets/desktop_remote_win.png" alt="Remote Windows Session" width="49%">
  <img src="assets/desktop_remote_linux.png" alt="Remote Linux Session" width="49%">
</div>

### 📱 Mobile App
<div align="center">
  <img src="assets/mobile_remote_connections.jpg" alt="Mobile Remote Connections" width="32%">
  <img src="assets/mobile_remote.jpg" alt="Mobile Remote Control" width="32%">
  <img src="assets/mobile_camera_live.jpg" alt="Mobile Camera Live Stream" width="32%">
</div>
<div align="center" style="margin-top: 10px;">
  <img src="assets/mobile_ai_alerts.jpg" alt="Mobile AI Alerts List" width="32%">
  <img src="assets/mobile_ai_alert_local.jpg" alt="Mobile AI Alert Details" width="32%">
  <img src="assets/mobile_push_notifications.jpg" alt="Mobile Push Notifications" width="32%">
</div>

---

</div>
