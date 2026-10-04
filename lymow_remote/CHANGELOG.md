Lymow Remote v1.0.4

What changed since v1.0.3.


- **The arrow keys drive the mower** on a computer, like the joystick. The first arrow press asks for a sensitivity — 1 light, 2 middle or 3 full — and you can press 1, 2 or 3 at any time to change it.
- **When the camera picture ends, the mower stops** — whether the picture drops, restarts or is turned off. Press the stick or an arrow again to drive on.
- **The WiFi picture should be sharper in fast motion:** once it plays, Lymow Remote moves it to the mower's direct WiFi link in the background, without a gap — and never takes the picture from another screen.
- **On a plain http:// address, Windows and iPhone should get a clean WiFi picture** — no more green picture on Windows, and an iPhone no longer has to use 4G.
- **⚙ → Show on camera** chooses which controls stay on the camera picture, separately for phones and computers. On tablets and computers the camera controls are smaller.


## Also in this release

- If another program already uses Lymow Remote's port (for example Home Assistant's go2rtc or Frigate), Lymow Remote takes the next free one and keeps it; ⚙ shows the address in use. Docker Desktop on Windows and Mac publishes the usual ports.
- Mower names in any language should work everywhere, and camera errors give the camera helper's own reason.
- A few short words that stayed in English (the arrow levels, On, OK, reachable) are now translated.

## ☕ Donations

Lymow Remote is free and always will be — donations are appreciated, never expected.

- **Ko-fi:** https://ko-fi.com/lymow_toolkit
- **Donatr:** https://donatr.ee/appguy/

## Install

- **Windows:** `LymowRemoteSetup-v1.0.4.msi`
- **Ubuntu / Linux:** `lymow-remote-ubuntu-v1.0.4.tar.gz`
- **macOS:** `lymow-remote-mac-v1.0.4.tar.gz`
- **Docker:** `lymow-remote-docker-v1.0.4.tar.gz`, or the image `ghcr.io/appguy77/lymow-remote:1.0.4` (also `appguy77/lymow-remote` on Docker Hub)
- **Home Assistant:** add `https://github.com/AppGuy77/lymow-remote-downloads` to the Add-on Store's repositories, then install **Lymow Remote**.

Already installed? Press **Install update** in ⚙ → Updates.

Lymow Remote installs next to the Lymow Toolkit on the same computer without clashing (its own ports, 8790 and up, and its own service).
It uses one cloud connection per Lymow account, like the official app: while you drive, other apps on the account are paused.

**On an iPhone**, add Lymow Remote to your Home Screen first — the camera screen shows the steps.

Lymow Remote is free software under the GNU AGPL-3.0 license. Independent project — not affiliated with Lymow.
