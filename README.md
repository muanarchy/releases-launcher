# MuAnarchy Launcher releases

Download-only repository: releases are published here by the build pipeline; there is no source code.

## Latest: v0.0.6 (2026-10-14)

- [MuAnarchyLauncher.exe](https://github.com/muanarchy/releases-launcher/releases/latest/download/MuAnarchyLauncher.exe)

[Release page](https://github.com/muanarchy/releases-launcher/releases/tag/v0.0.6) · [all versions](https://github.com/muanarchy/releases-launcher/releases). Every release lists the SHA-256 of its files.

## Windows warns about the download?

New or rarely downloaded files get a SmartScreen / browser warning ("isn't commonly downloaded") because they are not code-signed yet. It does not mean the file is bad:

- Browser: keep / "Keep anyway". SmartScreen: **More info** then **Run anyway**.
- Check the file if you like: its SHA-256 is in `version.txt` on the release page.
- The launcher updates itself and the mod afterwards, so this only happens on the first download.

## Change log of v0.0.6

#### Launcher v0.0.6

Commit e409f09. One file: run `MuAnarchyLauncher.exe`, no installer and no .NET needed.

#### Changes since v0.0.5
- Self-update: the child copies itself over the old exe and starts it; the running exe is never renamed (e409f09)

