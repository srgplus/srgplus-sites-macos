# SRG+ Sites for Mac

The Mac app of SRG+ Sites, for download outside the App Store. It talks to https://sites.srgplus.com and signs in with
an SRG+ account.

**Download:** [SRG-Plus-Sites.dmg](https://github.com/srgplus/srgplus-sites-macos/releases/latest/download/SRG-Plus-Sites.dmg)
(also https://srgplus.app/download#sites)

Open the DMG and drag SRG+ Sites to Applications. The app updates itself (Sparkle): it checks once a day, and
**SRG+ Sites › Check for Updates…** checks at once. It needs macOS 14 or later.

This repository only hosts the releases (the DMG) and `appcast.xml`, the update feed the installed apps read
(GitHub Pages, `https://srgplus.github.io/srgplus-sites-macos/appcast.xml`). The app's code and the build script
(`apps/mac/scripts/mac-dmg.sh`) are in the private repository srgplus/srgplus-sites. Changes to `appcast.xml` go
through a pull request, never straight to `main`.
