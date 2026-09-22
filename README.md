# MacRemote Agent

Runs in the menu bar and lets the MacRemote iPhone app drive this Mac over
Wi-Fi: pointer and trackpad gestures, keyboard, media keys, volume, system
actions, and a mirror of the Dock.

This repository carries the downloads. The source lives elsewhere.

## Install

1. Download the latest disk image from [Releases](../../releases/latest).
2. Drag **MacRemote Agent** into Applications and open it.
3. Allow Accessibility when the panel asks — macOS blocks synthetic input
   until you do, so the pointer and keyboard stay dead without it.
4. On the iPhone, open MacRemote, pick this Mac, and type the pairing code
   the panel shows.

Both devices need to be on the same Wi-Fi network.

The build is signed and notarised by Apple, so it opens without warnings.

## Requirements

- macOS 26.5 or later
- iPhone running iOS 26.5 or later
