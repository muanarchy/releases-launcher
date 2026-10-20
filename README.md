# MuAnarchy Launcher releases

Download-only repository: releases are published here by the build pipeline; there is no source code.

## Latest: v0.0.11 (2026-10-20)

- [MuAnarchyLauncher.exe](https://github.com/muanarchy/releases-launcher/releases/latest/download/MuAnarchyLauncher.exe)

[Release page](https://github.com/muanarchy/releases-launcher/releases/tag/v0.0.11) · [all versions](https://github.com/muanarchy/releases-launcher/releases). Every release lists the SHA-256 of its files.

## Windows warns about the download?

New or rarely downloaded files get a SmartScreen / browser warning ("isn't commonly downloaded") because they are not code-signed yet. It does not mean the file is bad:

- Browser: keep / "Keep anyway". SmartScreen: **More info** then **Run anyway**.
- Check the file if you like: its SHA-256 is in `version.txt` on the release page.
- The launcher updates itself and the mod afterwards, so this only happens on the first download.

## Change log of v0.0.11

#### Launcher v0.0.11

Commit cdb7ea1. One file: run `MuAnarchyLauncher.exe`, no installer and no .NET needed.

#### Changes since v0.0.10
- CLAUDE.md: Language setting (cdb7ea1)
- Language dropdown on the Connection tab (Default, English, Portuguese) and About text (0845d83)
- Client data sync: optional Language setting, ?lang= on the manifest and override downloads, applied language and release recorded (c5b4686)

