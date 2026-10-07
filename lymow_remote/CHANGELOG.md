Lymow Remote v1.1.3

What changed since v1.1.1.


- **A picture that falls behind stops the mower on every connection** — on 4G and the direct WiFi link too, a picture more than a second behind stops the stick and the blades, as the relayed WiFi picture always did.
- **Safer driving** — a menu opened while you drive with a game controller stops the mower (it kept the last push), a stop lost on a bad connection is sent again as soon as the connection is back, and when the blades cannot be stopped because the mower is unreachable you are told (the stop keeps being sent).
- **Auto should stay on WiFi** unless your own rule (dropped frames or signal, ⚙ → Camera) says leave — no more switching to 4G every half minute.
- **Only errors in the middle of the screen** — what the camera is doing shows on its status line; a stop that could not reach the mower is shown and says it may still be moving.
- **The camera no longer stops at "Camera link closed"** — it retries at once and says why; a mower that is not answering, or another app on your account, is said on the Remote.
- **Banners, pop-ups and the away-from-home status in your language**, the arrow keys only drive, a controller's deck buttons show a height only once the mower accepts it, every WiFi picture starts clean, and security patches.


## ☕ Donations

Lymow Remote is free and always will be — donations are appreciated, never expected.

- **Ko-fi:** https://ko-fi.com/lymow_toolkit
- **Donatr:** https://donatr.ee/appguy/

## Install

- **Windows:** `LymowRemoteSetup-v1.1.3.msi`
- **Ubuntu / Linux:** `lymow-remote-ubuntu-v1.1.3.tar.gz`
- **macOS:** `lymow-remote-mac-v1.1.3.tar.gz`
- **Docker:** `lymow-remote-docker-v1.1.3.tar.gz`, or the image `ghcr.io/appguy77/lymow-remote:1.1.3` (also `appguy77/lymow-remote` on Docker Hub)
- **Home Assistant:** add `https://github.com/AppGuy77/lymow-remote-downloads` to the Add-on Store's repositories, then install **Lymow Remote**.

Already installed? Press **Install update** in ⚙ → Updates.

Lymow Remote installs next to the Lymow Toolkit on the same computer without clashing (its own ports, 8790 and up, and its own service).
It uses one cloud connection per Lymow account, like the official app: while you drive, other apps on the account are paused.

**On an iPhone**, add Lymow Remote to your Home Screen first — the camera screen shows the steps.

Lymow Remote is free software under the GNU AGPL-3.0 license. Independent project — not affiliated with Lymow.
