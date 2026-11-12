# Dropwell

Official downloads and issue tracker for [Dropwell](https://getdropwell.com), a paid Mac app by ELEGANT TECH LLC that turns PDF bank statements into Excel, CSV, QuickBooks and OFX files on your Mac, and fills, signs, redacts, shrinks, merges and cleans up PDF paperwork. Nothing is uploaded.

Dropwell is not open source. This repository holds no source code: only this README, the release downloads and the issue tracker.

## Download

Download Dropwell from **<https://getdropwell.com/download>**, or get the newest DMG directly from <https://getdropwell.com/download/latest>. The download page shows the version, the size and the SHA-256 of the DMG.

Each [GitHub Release](https://github.com/getdropwell/dropwell/releases) here mirrors the same notarized DMG and its SHA-256. To check a download, run this in Terminal (with the DMG's real file name) and compare the result with the SHA-256 on the download page or in the release notes:

```sh
shasum -a 256 ~/Downloads/Dropwell-<version>.dmg
```

The app updates itself: choose Check for Updates in the Dropwell menu.

## Install

1. Open the DMG from your Downloads folder.
2. Drag Dropwell to Applications.
3. Open Dropwell from Applications. It is signed with an Apple Developer ID and notarized by Apple, so macOS opens it like any other app.
4. Drop a bank statement on the window, or right-click a file in Finder and choose Dropwell. If Dropwell is not in the Finder menu, turn it on under Extensions in System Settings.

The free trial gives you every tool and 3 free jobs. Licenses are sold at <https://getdropwell.com/#pricing>.

## System requirements

- macOS 13.4 or later. Remove background needs macOS 14 or later.
- Built for Apple silicon and Intel; tested on Apple silicon.
- An internet connection only to activate a license and to check for updates. Every tool works offline.

## Report a bug

[Open an issue](https://github.com/getdropwell/dropwell/issues/new/choose) and pick Bug report or Feature request. Say which version of Dropwell and macOS you use, what you did, what you expected and what happened.

**Never attach bank statements, forms or personal data.** Issues here are public. Describe the problem and the statement layout in words only (the bank, the country and the column names), and never attach any statement or form, not even an edited copy.

Questions about an order or a license: see the email with your license key.

## License

Dropwell is commercial software. Using it is governed by the license agreement at <https://getdropwell.com/eula>. Nothing in this repository grants any other license.

Copyright 2026 ELEGANT TECH LLC. Apple, Mac and macOS are trademarks of Apple Inc., registered in the U.S. and other countries.
