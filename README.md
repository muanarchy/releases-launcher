# MuAnarchy Launcher releases

Download-only repository: releases are published here by the build pipeline; there is no source code.

## Latest: v0.0.0 (2026-10-14)

- [MuAnarchyLauncher.exe](https://github.com/muanarchy/releases-launcher/releases/latest/download/MuAnarchyLauncher.exe)

[Release page](https://github.com/muanarchy/releases-launcher/releases/tag/v0.0.0) · [all versions](https://github.com/muanarchy/releases-launcher/releases). Every release lists the SHA-256 of its files.

## Change log of v0.0.0

#### Launcher v0.0.0

Commit ce03eeb. One file: run `MuAnarchyLauncher.exe`, no installer and no .NET needed.

#### Changes
- CI: note where releases are published (retrigger with 0.0.x numbering) (ce03eeb)
- CI: README script accepts a clone URL in RELEASES_REPO (0b49733)
- Docs: setting names (41cfc20)
- Split releases into per-component repos (client/launcher) with plain vX.Y.Z tags (06a6da2)
- CI: publish to the separate releases-launcher repository, one component per repo (1f02188)
- Update Main.dll from the main.zip release layout (version.txt hash check, bounded Main.dll extraction), keep legacy loose-asset path (abace64)
- CI: keep the releases README updated with latest download links and change logs (0daab35)
- Launcher self-update: Update now replaces the exe from the latest launcher release (4500ca5)
- Update Main.dll and show news from the public GitHub releases repo (18e44dd)
- CI: publish releases to the separate releases repository with a change log (6ddf9eb)
- GitHub Action: build, test, auto-incremented tag and release of the single-file launcher exe (9233099)
- Launcher: hand the account and password to the client process through environment variables (11a7382)
- Launcher: main page with saved login, Configure view, new icon, single-file build (ca1632e)
- Add CLAUDE.md for this repo (851aee8)
- Launcher: tests and fake client (d9fcce3)
- Launcher: WinForms app for client settings and start (581a54a)

