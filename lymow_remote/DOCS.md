# Lymow Remote

## First start

1. Start the add-on, then open **Lymow Remote** in the sidebar (or **OPEN WEB UI**).
2. Create a Lymow Remote password — it protects the remote on your network and away from home.
3. Sign in with your **Lymow account**: the same email and password, Google or Apple you use in the official Lymow
   app. (Google and Apple open a sign-in window inside the page.)
4. Touch the picture to start the camera. The joysticks unlock as soon as the live picture is on screen.

## Driving

- **Two joysticks:** the left stick drives forward and back, the right stick turns. Hold both to drive in an arc.
  ⚙ → **Controls** switches to a single joystick.
- **Blades:** Eco, Standard, Power or Turbo at the top. They spin only while the live picture is on screen and stop
  by themselves if it stops.
- **More than one mower:** tap the mower's name at the top right to switch. The mower you leave is stopped first.

## On your phone

⚙ → **Show QR code & address** gives the phone address at home and the permanent away-from-home address. Add it to
your home screen for a full-screen icon.

## Ports

Lymow Remote uses host networking with the page on **8790** and the WiFi camera relay on **8791** (UDP + TCP). The
Lymow Toolkit add-on keeps 8787 / 8788, so both can run on the same Home Assistant.

## One connection per account

Lymow allows one app connection per Lymow account at a time. While you drive with Lymow Remote, the official app or a
Lymow Toolkit on the same account loses its connection. It comes back when you close Lymow Remote.
