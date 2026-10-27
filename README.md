# MarauderBox for Marauder V8

<img width="480" height="640" alt="preview" src="https://github.com/user-attachments/assets/3e55c53f-877c-48f0-821a-afe8e6eed3f3" />

**MarauderBox** is a community firmware project exploring how to bring selected NyanBox-compatible apps and Marauder capabilities into an official-style ESP32 Marauder interface. This project was specifically meant to be ran on the Marauder V8.

> **Current repository status:** The existing source tree is based on ESP32 Marauder 1.19.1 firmware and NyanBox attack flows for the Marauder v8. That does not by itself prove a completed merge or verified firmware for every Marauder version/revision. Hardware compatibility and feature parity must be validated against the exact board before flashing. MarauderBox is an independent community project, not an official JustCallMeKoKo release.

## Project goals

- Keep the familiar official Marauder menu tree and interaction style.
- Evaluate and integrate compatible NyanBox apps and selected Eternal capabilities where hardware, dependencies, and licenses permit.
- Work toward support for the intended Marauder V8 / ESP32-C5 hardware, while distinguishing verified targets from planned targets.
- Keep source, build instructions, firmware assets, release notes, checksums, and installation guidance together.


## Installation

Start with the upstream documentation and releases:

- [Official ESP32 Marauder firmware update instructions](https://github.com/justcallmekoko/ESP32Marauder/wiki/update-firmware)
- [Official ESP32 Marauder releases / downloads](https://github.com/justcallmekoko/ESP32Marauder/releases)
- [Official SD-card update instructions](https://github.com/justcallmekoko/ESP32Marauder/wiki/sd-update)

Use the official download/installer workflow only when the image and workflow explicitly support your exact board. For a supported SD-card update workflow, follow the upstream guide, including its required filename and menu steps. A clean USB installation will require bootloader and partition assets, not just an application `.bin`. (which you can get off of JCMK's official firmware-flasher website.)

## Repository contents and release assets

This project repository should retain the source tree, local libraries, build scripts, release notes, desktop flasher, screenshots, and firmware assets appropriate to the specific release. Check each asset's filename, release notes, hardware target, and checksum before use. Do not treat generated or renamed files as official upstream assets.


## Licensing and attribution

MarauderBox builds on open-source ESP32 Marauder / NyanBox / Marauder eternal firmware. Preserve upstream copyright notices and comply with the licenses for source files, libraries, assets, and redistributed binaries. Confirm each upstream component's license before redistributing modified or bundled versions.

---
