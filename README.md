# Offer Floor

A free, private calculator for drive-away drivers: is this offer worth taking?

**Use it here: [tbookless.github.io/offer-floor](https://tbookless.github.io/offer-floor/)**

- Runs entirely in the browser. No accounts, no analytics, no server.
- Each driver's pickups, rates and home address are stored only on their own device.
- Works offline once opened, and installs to your phone's home screen like an app.

## Install it on your phone

**iPhone:** open the link in **Safari**, tap **Share → Add to Home Screen**.

**Android:** open the link in **Chrome**, tap the **⋮** menu → **Add to Home screen** (or **Install app**).

From then on, open it from the home-screen icon. That keeps your saved pickups from being cleared by the browser. Use **Setup → Save backup file** now and then, and **Setup → Restore from file** if you ever switch phones.

## Privacy statement

Offer Floor is a static web page. It has no server-side code, no accounts, no cookies, no analytics and no advertising. Everything you enter is stored in your own browser on your own device and is never sent to the publisher. The only time data leaves the device is when you tap **Look up in Maps**, which opens Google Maps (on Android) or Apple Maps (on iPhone and everything else) with the home and pickup addresses you entered, so those two addresses go to Google or Apple. The hosting provider (GitHub) sees ordinary web-server logs, such as IP addresses, when the page is loaded.

Estimates only — not tax advice.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets phones install it to the home screen |
| `sw.js` | Caches the app so it opens offline |
| `icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App icons |

## Making changes

The site is published with GitHub Pages from the `main` branch, so any change committed to `main` goes live within a minute or two. Whenever you change a file, also bump `VERSION` in `sw.js` (e.g. `offer-floor-v3`) so phones that installed the app pick up the new version.

## License

Copyright (C) 2026 Tod Bookless

Offer Floor is free software, licensed under the GNU Affero General Public License v3.0 (see `LICENSE`). You may use, change and share it, but any modified version you distribute or host for others must also be released under the AGPL with its source code.
