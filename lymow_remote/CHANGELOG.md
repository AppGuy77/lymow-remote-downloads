Lymow Remote v1.1.1

What changed since v1.1.0.


- **A game controller turned off and back on should drive again by itself** — within a second, with its saved setup. No need to run Controller setup again.
- **The controller dropping out stops the mower at once** — if it turns off, runs flat or loses its connection while you drive. Before, the mower could roll on for up to a second.
- **It never drives off by itself:** when the controller comes back, or you come back to the page, a stick still pushed has to return to center before the mower moves.
- **Backing out of an on-screen menu with the controller's Cancel button (B) no longer also stops the blades**, and a button still held as a menu closes does nothing.


## ☕ Donations

Lymow Remote is free and always will be — donations are appreciated, never expected.

- **Ko-fi:** https://ko-fi.com/lymow_toolkit
- **Donatr:** https://donatr.ee/appguy/

## Install

- **Windows:** `LymowRemoteSetup-v1.1.1.msi`
- **Ubuntu / Linux:** `lymow-remote-ubuntu-v1.1.1.tar.gz`
- **macOS:** `lymow-remote-mac-v1.1.1.tar.gz`
- **Docker:** `lymow-remote-docker-v1.1.1.tar.gz`, or the image `ghcr.io/appguy77/lymow-remote:1.1.1` (also `appguy77/lymow-remote` on Docker Hub)
- **Home Assistant:** add `https://github.com/AppGuy77/lymow-remote-downloads` to the Add-on Store's repositories, then install **Lymow Remote**.

Already installed? Press **Install update** in ⚙ → Updates.

Pair the controller in your device's Bluetooth settings first; it shows Connected in ⚙ once you press a button on it.

Lymow Remote installs next to the Lymow Toolkit on the same computer without clashing (its own ports, 8790 and up, and its own service).
It uses one cloud connection per Lymow account, like the official app: while you drive, other apps on the account are paused.

**On an iPhone**, add Lymow Remote to your Home Screen first — the camera screen shows the steps.

Lymow Remote is free software under the GNU AGPL-3.0 license. Independent project — not affiliated with Lymow.
