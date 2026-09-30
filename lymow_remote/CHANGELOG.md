Lymow Remote v1.0.2

What changed since v1.0.1.


- **✕ Close** in the top-bar corner: leaves the mower safe (blades and camera off) and closes Lymow Remote in one tap.
- **Update dot on ⚙** when a new version is out — on the remote control screen itself.
- **Commands should always reach the mower on your screen**, also with two screens on two mowers.
- **The stick and the camera picture should no longer fall behind.** When the picture is more than 1 second late, driving and blades wait for it and the screen says why.
- **The 💡 should show the real light after the camera starts**, and a parked mower should no longer be woken by background checks.


## Also in this release

- Every language should be as fast as English.
- iPhone: the faster WiFi picture. On a plain `http://` address an iPhone uses 4G and says why.
- Touchscreen computers get the computer layout; no control sits under a phone's camera cutout or home indicator.
- "Touch to start camera" works between the two sticks, and the ⚙ sheet's Close is reachable on an upright iPhone.
- Lymow Remote writes no log files, so nothing can fill your disk.

## ☕ Donations

Lymow Remote is free and always will be — donations are appreciated, never expected.

- **Ko-fi:** https://ko-fi.com/lymow_toolkit
- **Donatr:** https://donatr.ee/appguy/

## Install

- **Windows:** `LymowRemoteSetup-v1.0.2.msi`
- **Ubuntu / Linux:** `lymow-remote-ubuntu-v1.0.2.tar.gz`
- **macOS:** `lymow-remote-mac-v1.0.2.tar.gz`
- **Docker:** `lymow-remote-docker-v1.0.2.tar.gz`, or the image `ghcr.io/appguy77/lymow-remote:1.0.2` (also `appguy77/lymow-remote` on Docker Hub)
- **Home Assistant:** add `https://github.com/AppGuy77/lymow-remote-downloads` to the Add-on Store's repositories, then install **Lymow Remote**.

Already installed? Press **Install update** in ⚙ → Updates.

Lymow Remote installs next to the Lymow Toolkit on the same computer without clashing (its own ports 8790/8791 and service).
It uses one cloud connection per Lymow account, like the official app: while you drive, other apps on the account are paused.

**On an iPhone**, add Lymow Remote to your Home Screen first — the camera screen shows the steps.

Lymow Remote is free software under the GNU AGPL-3.0 license. Independent project — not affiliated with Lymow.
