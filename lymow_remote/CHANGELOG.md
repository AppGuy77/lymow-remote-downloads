Lymow Remote v1.1.6

What changed since v1.1.4.


- **The deck stays where it is** — the deck slider shows the height each mower reports, and opening the Remote no longer moves the deck. With two mowers, a height set on one is never applied to the other.
- **Auto keeps a WiFi picture that only drops frames** — it should move to 4G only when the picture freezes, and the 4G picture is up before the WiFi one goes: no black screen while it switches.
- **A smoother camera picture** — a short hiccup no longer throws away about two seconds of video, and the screen is redrawn only where something changed.
- **A sleeping mower is woken first** — leaving remote control and starting the 4G camera reach a mower that went to sleep; if it cannot be reached, the screen says it is still in remote control.
- **The light, camera link and map buttons fade with the other controls again.**
- **The WiFi picture no longer freezes on a damaged frame** — it should pick up again at the next full frame.
- **Consistent wording in every language** — each language names the same thing the same way throughout.


## ☕ Donations

Lymow Remote is free and always will be — donations are appreciated, never expected.

- **Ko-fi:** https://ko-fi.com/lymow_toolkit
- **Donatr:** https://donatr.ee/appguy/

## Install

- **Windows:** `LymowRemoteSetup-v1.1.6.msi`
- **Ubuntu / Linux:** `lymow-remote-ubuntu-v1.1.6.tar.gz`
- **macOS:** `lymow-remote-mac-v1.1.6.tar.gz`
- **Docker:** `lymow-remote-docker-v1.1.6.tar.gz`, or the image `ghcr.io/appguy77/lymow-remote:1.1.6` (also `appguy77/lymow-remote` on Docker Hub)
- **Home Assistant:** add `https://github.com/AppGuy77/lymow-remote-downloads` to the Add-on Store's repositories, then install **Lymow Remote**.

Already installed? Press **Install update** in ⚙ → Updates.

Lymow Remote installs next to the Lymow Toolkit on the same computer without clashing (its own ports, 8790 and up, and its own service).
It uses one cloud connection per Lymow account, like the official app: while you drive, other apps on the account are paused.

**On an iPhone**, add Lymow Remote to your Home Screen first — the camera screen shows the steps.

Lymow Remote is free software under the GNU AGPL-3.0 license. Independent project — not affiliated with Lymow.
