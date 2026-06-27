# ZeroTrace Companion — Desktop App

<img width="2250" height="1121" alt="ZeroTrace Companion desktop app" src="https://github.com/user-attachments/assets/bccb7ce9-1b3d-4e3a-975f-c0542ae001da" />

<p align="center">
  <a href="https://github.com/ZeroTracePW/desktop/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/ZeroTracePW/desktop?label=download&style=for-the-badge"></a>
  <img alt="Platforms" src="https://img.shields.io/badge/windows%20%C2%B7%20macOS%20%C2%B7%20linux-supported-555?style=for-the-badge">
  <img alt="Privacy" src="https://img.shields.io/badge/no%20accounts%20%C2%B7%20no%20logs-100%25%20local-4f46e5?style=for-the-badge">
</p>

The official desktop companion for **ZeroTrace BLELogger**. Plug in over USB, configure your device, pull captures, and manage firmware — entirely on your own machine. No account, no cloud, no telemetry.

> **➡️ [Download the latest version](https://github.com/ZeroTracePW/desktop/releases/latest)**

---

## ⚠️ Important: HID and AirLeak are no longer supported here

The desktop Companion is now **BLELogger-only**. Support for **ZeroTrace HID** and **ZeroTrace AirLeak** has been **removed from this desktop app** — both devices are now managed exclusively through the **ZeroTrace mobile app**.

| Device | How to manage it now |
| --- | --- |
| **BLELogger** | ✅ This desktop app |
| **HID** | 📱 ZeroTrace mobile app |
| **AirLeak / AirLeak Pro** | 📱 ZeroTrace mobile app |

**Get the mobile app:**
- iOS — [App Store](https://apps.apple.com/us/app/zerotrace-mobile/id6775984616)
- Android — [Direct APK](https://github.com/ZeroTracePW/zerotrace-mobile/releases)

If you previously used this desktop app for HID or AirLeak, switch to the mobile app — those features will not return to desktop.

---

## Features

- **Serial device management** — connect and configure your BLELogger over USB.
- **Capture access** — browse, export, and clear logs stored on the device.
- **Firmware updates** — flash the latest BLELogger firmware directly from the app.
- **100% local** — everything runs on your machine. No accounts, no cloud sync, no logging.

## Download & Install

All builds are published on the **[Releases page](https://github.com/ZeroTracePW/desktop/releases)** — no compiling required.

1. Open the [latest release](https://github.com/ZeroTracePW/desktop/releases/latest).
2. Download the installer for your OS:
   - **Windows** — `.exe`
   - **macOS** — `.dmg`
   - **Linux** — `.AppImage` / `.deb`
3. Run the installer and launch **ZeroTrace Companion**.
4. Connect your BLELogger with a USB cable and select its serial port in the app.

### Notes per platform
- **Windows** — SmartScreen may warn on first launch; choose *More info → Run anyway*. Serial drivers are included with Windows 10/11.
- **macOS** — first launch: right-click the app → *Open* to bypass Gatekeeper.
- **Linux** — make the AppImage executable: `chmod +x ZeroTrace-Companion-*.AppImage`. To access the serial port without root, add your user to the `dialout` group: `sudo usermod -aG dialout $USER` (log out and back in).

## Requirements

- A free USB port and a data-capable USB cable.
- A ZeroTrace **BLELogger** device.
- Windows 10/11, macOS 12+, or a modern Linux distribution.

## Privacy

ZeroTrace is privacy-first by design. This app keeps all data on your device — no accounts, no telemetry, no logs leaving your machine. Made in Germany.

## Links & Support

- 📦 [Releases](https://github.com/ZeroTracePW/desktop/releases)
- 📖 [Documentation](https://zerotrace.pw/desktop-apps/zerotrace-companion-app)
- 📱 [Mobile app](https://zerotrace.pw/mobile-app)
- 🐞 [Report an issue](https://github.com/ZeroTracePW/desktop/issues)
