# AdrBubbleBooter.VPKEdition

[![Version](https://img.shields.io/badge/Version-1.3-blue.svg)](https://github.com/yourusername/AdrBubbleBooter.VPKEdition/releases)
[![License](https://img.shields.io/badge/License-Unlicense-lightgrey.svg)](LICENSE)

> **Note: This is an archive and mirror repository.**
> The original project by LMAN (LeecherMan) has been discontinued and its original homepage is no longer available. This repository exists solely to preserve the source code, compiled binaries, and documentation for historical, educational, and maintenance purposes within the PS Vita homebrew community.

Adrenaline Bubble Booter VPK Edition (C) 2017-2020 LMAN (LeecherMan)

Directly boot any PSP file (ISO, CSO, PBP, PSOne) from your PS Vita's LiveArea.

---

## 📖 Table of Contents

- [Features](#-features)
- [Compatibility](#-compatibility)
- [Installation](#-installation)
- [Usage](#-usage)
- [Creating Bubbles](#-creating-bubbles)
- [Configuration](#-configuration)
- [Changelog](#-changelog)
- [Troubleshooting](#-troubleshooting)
- [Donations](#-donations)
- [Credits](#-credits)
- [Disclaimer](#-disclaimer)

## ✨ Features

*   **Direct Boot:** Launch PSP ISOs, CSOs, PBPs, and PSOne games directly from LiveArea bubbles.
*   **Per-Bubble Configuration:**
    *   Custom CPU clock speed
    *   Toggle High Memory Layout
    *   Enable/Disable Nonpdrm engine
    *   Manage plugins individually
    *   Auto-load specific saved states on boot (cancelable by holding L)
*   **Customization:**
    *   Use any 480x272 PNG image as a custom boot logo.
    *   Change Adrenaline menu colors via `menucolor.bin`.
*   **Enhanced Menu:** Adrenaline menu displays date, time, and battery percentage.
*   **Quality of Life:**
    *   Suspend game when opening Adrenaline menu.
    *   Remap PS button function (Open Menu or LiveArea).
    *   Keep aspect ratio option for scaling.
    *   Improved frame pacing in Original graphics mode.
    *   Restart or reset the booter from the menu.
    *   Exit game directly from the booter tab.

## ✅ Compatibility

*   **Requires:** A PS Vita (PCH-1000 or PCH-2000) or PS TV (VTE-1000) with custom firmware (HENkaku/enso).
*   **Requires:** [Adrenaline](https://github.com/TheOfficialFloW/Adrenaline) v6.0 or later and the `661.PBP` firmware file.

## 📥 Installation

### Prerequisites
1.  Ensure **Adrenaline** is installed and working correctly on your device.
2.  Make sure the `661.PBP` file is placed in the correct location (usually `ux0:app/PSPEMUCFW/`).

### Installing the Booter
1.  Copy the `AdrBubbleBooterInstaller.vpk` file to the root of your Vita's `ux0:` partition.
2.  Use a homebrew app like VitaShell to browse to the file and install it.
3.  Run the **AdrBubbleBooterInstaller** bubble once to install the necessary files.
4.  *(Optional but recommended)*: Reboot your PS Vita for all changes to take effect.
5.  You can now delete the `AdrBubbleBooterInstaller.vpk` and its bubble.

## 🎮 Usage

### Creating Bubbles
To create a bubble for a specific game or homebrew:
1.  On your PC, run `AdrBubbleBooterCreator.exe`.
2.  Fill in the required fields (e.g., path to the game file, title ID, name, icon image).
3.  Click the "Create" button to generate a `.vpk` file.
4.  Transfer this `.vpk` file to your Vita and install it like any other homebrew. A new bubble will appear on your LiveArea.

### Configuration
Each bubble can be configured individually:
1.  Boot the game from its newly created bubble.
2.  Open the **Adrenaline menu** (usually by pressing the **PS button** + **Select**).
3.  Navigate to the **"Booter"** tab.
4.  Adjust the settings to your preference (CPU speed, auto-load state, etc.).
5.  Exit the menu to save the configuration for that specific bubble.

## 📋 Changelog

### v1.3
- Updated Adrenaline to v7.0.
- Added suspend threads option to the menu.

### v1.2
- Added new PS button option.
- Improved frame pacing (Original graphics mode).
- Fixed "Cannot access the virtual memory card" issue for PSOne games.

### v1.1
- Restored USB option visibility on non-PSTV devices.
- Fixed a typo in the installer.

### v1.0
- Updated Adrenaline to v6.9.
- Added per-bubble CPU clock, high memory, nonpdrm, and plugin settings.
- Updated configuration file structure.

### v0.9
- Initial public release with rewritten code (Adrenaline v6.8).
- Added custom boot logo, auto-load states, menu color editing, and many other features.

[View full changelog](CHANGELOG.md)

## 🛠️ Troubleshooting

*   **"Adrenaline couldn't find the 661.PBP"**: Ensure Adrenaline is fully installed and working on its own first.
*   **Game doesn't boot**: Double-check the file path used in the Bubble Creator. The game file must be accessible from the Vita (e.g., in `ux0:pspemu/ISO/`).
*   **Bubble crashes**: Try rebuilding the database via Safe Mode (hold POWER + PS + R Shoulder buttons on boot).

## ❤️ Donations

If you appreciate this project and want to support the developer, you can buy them a coffee:

[**Donate via PayPal**](https://sites.google.com/site/theleecherman/donate)

## 🙏 Credits

*   **TheFloW**: For the incredible Adrenaline PSP emulator.
*   **LMAN (LeecherMan)**: For creating and maintaining AdrBubbleBooter.
*   **CruelTott**: For improvements to frame pacing.

**Homepage for more tools and updates:** [TheLeecherMan's Site](https://sites.google.com/site/theleecherman)

---

## ⚠️ Disclaimer

This software is provided "as is", without any warranty. Use it at your own risk. The developers are not responsible for any damage to your device or account.
