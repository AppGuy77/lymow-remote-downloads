# Lymow Remote

**Remote control for Lymow One and One Plus robot mowers** — the remote control of the
[Lymow Toolkit](https://github.com/AppGuy77/lymow-toolkit-downloads) on its own: a live camera, always full screen, two
joysticks on a phone (one with a mouse), blades, deck height and the light. Pause/Resume, Clear Fault, Cancel Task and
Dock. At home through a QR code, and from anywhere through your own permanent away-from-home address.

> **Independent project — not affiliated with, endorsed or supported by Lymow.** Lymow Remote is experimental: a Lymow
> firmware or cloud update can change or stop it at any time. You use it at your own risk and accept the
> [disclaimer](#disclaimer) every time it opens.

## ⬇️ Download

**[Latest release →](https://github.com/AppGuy77/lymow-remote-downloads/releases/latest)**

| Platform | File |
|---|---|
| Windows 10 / 11 | `LymowRemoteSetup-vX.Y.Z.msi` |
| Ubuntu / Debian / Raspberry Pi OS | `lymow-remote-ubuntu-vX.Y.Z.tar.gz` |
| macOS | `lymow-remote-mac-vX.Y.Z.tar.gz` |
| Docker (Linux, NAS, Pi, Docker Desktop) | `lymow-remote-docker-vX.Y.Z.tar.gz` — or the image `ghcr.io/appguy77/lymow-remote` (also `appguy77/lymow-remote` on Docker Hub) |
| Home Assistant | this repository as an add-on repository — see below |

Every release lists a `SHA256SUMS` file; Lymow Remote's own updater checks it before installing an update.

## Install

**Windows** — run `LymowRemoteSetup-vX.Y.Z.msi`. Lymow Remote runs as a background service; open **Lymow Remote** from
the Start menu (or `http://127.0.0.1:8790`).

**Ubuntu / Linux**
```bash
tar xzf lymow-remote-ubuntu-vX.Y.Z.tar.gz
cd lymow-remote-ubuntu
sudo bash install.sh        # installs the background service; prints your link and a QR code
```
Open `http://127.0.0.1:8790` on that machine, or the `http://<its-ip>:8790` link install.sh prints from a phone.

**macOS**
```bash
tar xzf lymow-remote-mac-vX.Y.Z.tar.gz
cd lymow-remote-mac
sudo bash install.sh        # a system service needs sudo on macOS (Local Network privacy); prints your link + QR code
```
Then double-click **Lymow Remote** on your Desktop (`http://127.0.0.1:8790`).

**Docker**
```bash
tar xzf lymow-remote-docker-vX.Y.Z.tar.gz
cd lymow-remote-docker
docker compose up -d                                        # Linux, NAS, Raspberry Pi
docker compose -f docker-compose.desktop.yml up -d          # macOS / Windows Docker Desktop
```
Open `http://localhost:8790` (from a phone: `http://<host-ip>:8790`). Update:
`docker compose pull && docker compose up -d && docker image prune -f`

**Home Assistant** — Settings → Add-ons → Add-on Store → ⋮ → **Repositories** → add
`https://github.com/AppGuy77/lymow-remote-downloads` → install **Lymow Remote** → Start → Open Web UI.

**On an iPhone**, add Lymow Remote to your Home Screen first (Share → Add to Home Screen → Add) and open it from the new
icon — an iPhone only shows a web page full screen that way. The camera screen shows the steps.

Lymow Remote installs **next to the Lymow Toolkit** on the same computer without clashing (its own ports 8790 / 8791,
its own service and settings). Like the official app, it uses the one cloud connection your Lymow account allows:
while you drive, other apps on the account are paused.

## ☕ Donations

Lymow Remote is free and always will be — donations are appreciated, never expected.

- Ko-fi: https://ko-fi.com/lymow_toolkit
- Donatr: https://donatr.ee/appguy/

Community: https://www.facebook.com/share/g/1Jc7YfPStf/ · Problems or questions:
[open an issue](https://github.com/AppGuy77/lymow-remote-downloads/issues).

## Disclaimer

Lymow Remote shows this and asks you to accept it every time it opens, before the camera or remote control can be used.

1. **Independent, experimental software.** Lymow Remote is independent, experimental software. It is not made, endorsed, supported or authorized by Lymow or by the maker of your mower, and it relies on unofficial interfaces that can change at any time.
2. **Firmware and service changes.** A firmware, app or cloud-service update by Lymow may change, limit, disable or break Lymow Remote, in whole or in part, at any time and without notice. No function, feature, availability or compatibility is guaranteed.
3. **Safe operation is your responsibility.** You alone control the mower through Lymow Remote, including its movement, cutting blades, deck, lights and camera, and you are solely responsible for operating it safely and lawfully. Keep people, children, pets and property clear of the mower, supervise it at all times, and follow the manufacturer's safety instructions.
4. **Delays and lost connections.** Commands and video travel over WiFi, cellular networks and the internet. They can be delayed, arrive out of order or fail, and the picture can freeze or lag behind what is really happening. The mower may keep moving or cutting after you release a control or the connection drops. Never rely on Lymow Remote as your only way to stop the mower.
5. **Camera, privacy and data costs.** You are responsible for obeying the privacy and recording laws that apply where the camera is used. Using the mower's cellular (4G) connection may cause data charges from your provider.
6. **Manufacturer warranty.** Using unofficial software with your mower may affect its warranty, support or service from the manufacturer.
7. **No warranty.** Lymow Remote is provided “as is” and “as available”, without warranty of any kind, express or implied, including merchantability, fitness for a particular purpose, accuracy, reliability and non-infringement (see also sections 15 and 16 of the GNU AGPL-3.0 license).
8. **Assumption of risk.** You use Lymow Remote entirely at your own risk. You assume all risk of personal injury, death, damage to property, loss of data and any other loss arising from its normal use, misuse, malfunction or unavailability.
9. **Release, hold harmless and indemnity.** To the fullest extent permitted by law, you release, hold harmless and indemnify the authors, contributors, distributors and every other party involved with Lymow Remote from any claim, demand, liability, damage, loss, cost or expense, including legal fees, arising from or related to your use or misuse of Lymow Remote or of the mower through it.
10. **Limitation of liability.** In no event will any of those parties be liable for any direct, indirect, incidental, special, consequential or punitive damages, however caused, even if advised of their possibility.
11. **Severability.** If any part of these terms is found unenforceable, the remaining parts stay in full effect.

> I understand that Lymow Remote is experimental and that a firmware update can change or end its usability at any time.
> I use it at my own risk, I am of legal age, and I hold all parties harmless against any negative outcome from normal
> use or misuse of the application.

## License

Lymow Remote is free software, licensed under the **GNU Affero General Public License v3.0** — see [LICENSE](LICENSE).
This repository holds the installers; the complete corresponding source code of any release is available on request —
[open an issue](https://github.com/AppGuy77/lymow-remote-downloads/issues) naming the version.
