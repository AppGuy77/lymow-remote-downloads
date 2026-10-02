Lymow Remote v1.0.3

What changed since v1.0.2.


- **The camera should open faster on WiFi** — it now starts through Lymow Remote, the same way VLC does, and the camera helper is ready from the start.
- **The 💡 should show the night light** the mower turns on in remote control, and show it off again when you leave remote control.
- **Two screens on one mower:** the newest screen gets the picture; the other one says so, and a tap takes it back.
- **The camera should reconnect cleanly** — short drops wait instead of restarting, and "IP unreachable" should no longer appear while the mower's WiFi works.
- **Auto follows your Camera settings** (leave WiFi on dropped frames or a weak signal) on every WiFi picture.


## Also in this release

- Camera messages are a few words. The full reason and a **Network** line (the mower's WiFi name, its address and this computer's) are in ⚙ → Camera.
- When WiFi keeps failing while the network is fine, the camera stops retrying after three tries and offers a tap to retry.
- Progress on the camera bar is the mower's own number, shown only while it mows.
- Commands, the camera and the mower's details should always stay with the mower on your screen.

## ☕ Donations

Lymow Remote is free and always will be — donations are appreciated, never expected.

- **Ko-fi:** https://ko-fi.com/lymow_toolkit
- **Donatr:** https://donatr.ee/appguy/

## Install

- **Windows:** `LymowRemoteSetup-v1.0.3.msi`
- **Ubuntu / Linux:** `lymow-remote-ubuntu-v1.0.3.tar.gz`
- **macOS:** `lymow-remote-mac-v1.0.3.tar.gz`
- **Docker:** `lymow-remote-docker-v1.0.3.tar.gz`, or the image `ghcr.io/appguy77/lymow-remote:1.0.3` (also `appguy77/lymow-remote` on Docker Hub)
- **Home Assistant:** add `https://github.com/AppGuy77/lymow-remote-downloads` to the Add-on Store's repositories, then install **Lymow Remote**.

Already installed? Press **Install update** in ⚙ → Updates.

Lymow Remote installs next to the Lymow Toolkit on the same computer without clashing (its own ports 8790/8791 and service).
It uses one cloud connection per Lymow account, like the official app: while you drive, other apps on the account are paused.

**On an iPhone**, add Lymow Remote to your Home Screen first — the camera screen shows the steps.

Lymow Remote is free software under the GNU AGPL-3.0 license. Independent project — not affiliated with Lymow.
