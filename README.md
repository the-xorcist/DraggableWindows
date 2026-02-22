# DraggableWindows

**Version:** 1.0.0  
**Author:** the-xorcist  
**Release Date:** 2026-02-22

## Description

DraggableWindows is a BepInEx mod for Erenshor that allows you to freely reposition any popup window by clicking and dragging on non-interactive areas. Window positions are automatically saved and restored between game sessions, giving you complete control over your UI layout.

## Features

- **Drag any popup window** - Click and drag on window frames or backgrounds to reposition
- **Persistent positions** - Window locations are automatically saved and restored
- **Comprehensive window support** including:
  - Spellbook
  - Skillbook
  - Inventory
  - Vendor window
  - Quest log
  - Loot window
  - Guild manager
  - Group builder
  - Auction house
  - Bank
  - World map
  - BetterStatsPage (if installed)
- **Smart drag detection** - Only non-interactive areas respond to dragging (buttons and item slots remain fully functional)

## Installation

1. Install [BepInEx](https://github.com/BepInEx/BepInEx) for Erenshor
2. Copy `DraggableWindows.dll` to `BepInEx/plugins/` folder
3. Launch the game

## Usage

1. Open any supported window (inventory, spellbook, vendor, etc.)
2. Click and drag on any non-interactive area (background or frame)
3. Release to drop the window in its new position
4. Position is automatically saved to `BepInEx/config/noone.draggablewindows.cfg`

To reset a window to its default position, delete the corresponding entries in the config file.

## Source Code

Source code is included in the `-source.zip` archive.
