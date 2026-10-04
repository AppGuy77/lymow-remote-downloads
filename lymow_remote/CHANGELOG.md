Lymow Remote v1.0.7

What changed since v1.0.4.


- **The WiFi picture through Lymow Remote should no longer smear into blocks while the mower moves** — at home and through the away address. Every download now carries Lymow Remote's own camera helper, which reads every frame of the mower's camera.
- **Safer driving:** a move that cannot reach the mower right away is dropped instead of being delivered late, and the stick waits while the mower is not answering or the picture is more than 1.5 seconds old. A stop always goes out.
- **Arrow keys:** the sensitivity is asked at the first arrow press after every camera start, with your saved level marked. Level 2 is now half of the stick. Tap a choice or press 1, 2 or 3 — and press 1, 2 or 3 at any time while driving to change it at once.
- **The WiFi picture is kept ready for 5 minutes after you leave,** so coming back should start faster. Stop camera ends it right away.
- **Camera errors are in plain words** — for example "the mower did not answer on WiFi — it may be out of range or its WiFi signal is weak".


## Also in this release

- In every language, the messages Lymow Remote shows after an action or an error are now translated — sign-in, camera (including the reasons in ⚙ → Camera), away access, updates and the mower's answers. Many were English until now.
- Every text names Lymow Remote; some still said "the Toolkit".
- Every size on the screen now follows the screen, including thin borders, gaps and small icons.
- The camera helper is included in every download; nothing is fetched from the internet for it during install.
- On Linux and macOS, Lymow Remote should come back by itself if it ever stops.

## ☕ Donations

Lymow Remote is free and always will be — donations are appreciated, never expected.

- **Ko-fi:** https://ko-fi.com/lymow_toolkit
- **Donatr:** https://donatr.ee/appguy/

## Install

- **Windows:** `LymowRemoteSetup-v1.0.7.msi`
- **Ubuntu / Linux:** `lymow-remote-ubuntu-v1.0.7.tar.gz`
- **macOS:** `lymow-remote-mac-v1.0.7.tar.gz`
- **Docker:** `lymow-remote-docker-v1.0.7.tar.gz`, or the image `ghcr.io/appguy77/lymow-remote:1.0.7` (also `appguy77/lymow-remote` on Docker Hub)
- **Home Assistant:** add `https://github.com/AppGuy77/lymow-remote-downloads` to the Add-on Store's repositories, then install **Lymow Remote**.

Already installed? Press **Install update** in ⚙ → Updates.

Lymow Remote installs next to the Lymow Toolkit on the same computer without clashing (its own ports, 8790 and up, and its own service).
It uses one cloud connection per Lymow account, like the official app: while you drive, other apps on the account are paused.

**On an iPhone**, add Lymow Remote to your Home Screen first — the camera screen shows the steps.

Lymow Remote is free software under the GNU AGPL-3.0 license. Independent project — not affiliated with Lymow.
