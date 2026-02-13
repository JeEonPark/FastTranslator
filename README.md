<p align="center">
  <img src="assets/app-icon.png" width="128" height="128" alt="FastTranslator Icon">
</p>

<h1 align="center">FastTranslator</h1>

<p align="center">
  <strong>Translate selected text instantly with a global hotkey.</strong><br>
  A lightweight macOS menu bar app powered by Apple Translation.
</p>

<p align="center">
  <a href="https://github.com/JeEonPark/FastTranslator/releases/latest"><img src="https://img.shields.io/github/v/release/JeEonPark/FastTranslator?style=flat-square&color=blue" alt="Latest Release"></a>
  <img src="https://img.shields.io/badge/platform-macOS%2015.0+-black?style=flat-square&logo=apple" alt="macOS 15.0+">
  <img src="https://img.shields.io/badge/swift-5.0-orange?style=flat-square&logo=swift" alt="Swift 5.0">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-All%20Rights%20Reserved-lightgrey?style=flat-square" alt="License"></a>
</p>

<p align="center">
  <img width="400" alt="image" src="https://github.com/user-attachments/assets/a2cb8f2b-ea68-4f11-87eb-69fa31cc08ad" />
</p>

---

## Features

- **Global Hotkey Translation** — Select any text in any app, press `⌃ ⌥ ⌘ Space` (customizable), and get an instant floating translation popup
- **Menu Bar App** — Lives in your menu bar, always ready without cluttering your Dock
- **Apple Translation API** — Uses the built-in macOS Translation framework, no external API keys needed
- **Auto Language Detection** — Automatically detects the source language, or set it manually
- **Multi-Language Support** — Korean, English, Japanese, Chinese (Simplified/Traditional), Spanish, French, German
- **Customizable Hotkeys** — Set your own global shortcut for translation and font size controls
- **Adjustable Font Size** — Resize translation popup text with shortcuts or the slider
- **Dark Mode** — Native dark appearance throughout

## Download

> **[Download Latest Release](https://github.com/JeEonPark/FastTranslator/releases/latest)**

### Installation

1. Download the `.dmg` file from the [latest release](https://github.com/JeEonPark/FastTranslator/releases/latest)
2. Open the DMG and drag **FastTranslator** to your Applications folder
3. Launch FastTranslator from Applications or Spotlight

## Setup

### Accessibility Permission

FastTranslator requires Accessibility permission to detect global hotkeys and read selected text from other apps.

1. On first launch, a system dialog will appear automatically
2. Go to **System Settings → Privacy & Security → Accessibility**
3. Toggle **FastTranslator** on
4. Restart FastTranslator if needed

### Default Hotkeys

| Action | Shortcut |
|---|---|
| Translate selected text | `⌃ ⌥ ⌘ Space` |
| Increase popup font | `⌘ =` |
| Decrease popup font | `⌘ -` |

All hotkeys can be customized from the menu bar popover settings.

## How It Works

1. Select any text in any application
2. Press the global hotkey (`⌃ ⌥ ⌘ Space` by default)
3. A floating popup appears with the translation
4. Press `Esc` to dismiss the popup

## Requirements

- macOS 15.0 (Sequoia) or later
- Accessibility permission enabled

## License

All rights reserved. This software is provided as-is for personal use.

---

<p align="center">
  Made by <a href="https://github.com/JeEonPark">DevJonny</a>
</p>
