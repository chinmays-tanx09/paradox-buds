# Paradox Buds

<img src="images/icon.png" width="96" alt="Paradox Buds icon">

Paradox Buds is a companion app for any Bluetooth headphones on Android, by Paradox. It shows only what your headphones really support.

**[Download the latest release](https://github.com/chinmays-tanx09/paradox-buds/releases/latest)**: get `Paradox_Buds_v1.1.apk` from the Assets list and open it.

## What it does

- **Universal (any Bluetooth headphones):** battery (when Android reports it), media controls and volume, a 10-band equalizer with presets (Bass Boost, Balanced, Vocal, Rock, Classical, Podcast), per-headphone EQ profiles that switch automatically when they connect, connect/disconnect, and remembered devices.
- **Party mode:** play one song on several outputs at once (phone speaker, Bluetooth, wired, USB), each with its own delay slider for sync and its own volume. Works for music played inside Paradox Buds.
- **Samsung Dual Audio shortcut** (Samsung phones only): opens Samsung's Media output panel so you can play any app's audio on two Bluetooth devices.
- **Device-specific controls** (noise cancelling, built-in EQ modes, L/R battery) for some Nothing, OPPO/realme, Samsung Galaxy Buds, Sony and Huawei/Honor models. These use published community protocols and are marked "untested" in the app until confirmed on a real unit.
- **Device Lab:** export a JSON report of what your headphones expose and share it, to help add support for more models.

Every feature is labelled **Universal**, **Device-specific** or **Not controllable**. The app never shows a control your headphones don't have.

## Install

- Needs Android 8.0 or newer (Party mode needs Android 9+).
- Updating: install the new APK over the old one. Official builds are all signed with the same key, so your data is kept. The app checks this page for new releases at most every 12 hours.
- "App not installed"? You probably have a copy signed by someone else. Uninstall it first, then install the APK from this page.

## Privacy

No ads, no analytics, no accounts. The only network request is the update check against this repository's releases. Device Lab reports leave your phone only when you share them.

## Releases only

This repository holds release builds only; the source code is not published here.
