# Offer Floor

A free, private calculator for drive-away drivers: is this offer worth taking?

- Runs entirely in the browser. No accounts, no analytics, no server.
- Each driver's pickups, rates and home address are stored only on their own device.
- Works offline once opened, and installs to the iPhone Home Screen like an app.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets phones install it to the Home Screen |
| `sw.js` | Caches the app so it opens offline |
| `icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App icons |

## Put it online with GitHub Pages (free)

1. Create a free account at github.com if you don't have one.
2. Click **+ → New repository**. Name it `offer-floor`, set it to **Public**, and create it.
3. On the new repository page, click **uploading an existing file**, drag in every file in this folder, and click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**, and **Save**.
5. After a minute the page shows the address, e.g. `https://YOUR-USERNAME.github.io/offer-floor/`.

### Optional: your own address

To use something like `offerfloor.bookless.net`: in **Settings → Pages → Custom domain**, enter it and save. Then, at whoever hosts the DNS for bookless.net, add a **CNAME** record named `offerfloor` pointing to `YOUR-USERNAME.github.io`. Tick **Enforce HTTPS** once GitHub offers it.

## Updating it later

Upload the changed files to the same repository. Also open `sw.js` and bump `VERSION` (e.g. `offer-floor-v2`) so phones that installed it pick up the new version.

## Telling drivers how to install

> Open the link in Safari, tap **Share → Add to Home Screen**. Open it from the Home Screen icon from then on — that keeps your saved pickups from being cleared. Use **Setup → Save backup file** now and then.

## Privacy statement (for anyone who asks)

Offer Floor is a static web page. It has no server-side code, no accounts, no cookies, no analytics and no advertising. Everything you enter is stored in your own browser on your own device and is never sent to the publisher. The only time data leaves the device is when you tap **Look up in Maps**, which opens Google Maps (on Android) or Apple Maps (on iPhone and everything else) with the home and pickup addresses you entered, so those two addresses go to Google or Apple. The hosting provider (GitHub) sees ordinary web-server logs, such as IP addresses, when the page is loaded.

Estimates only — not tax advice.

## License

Copyright (C) 2026 Tod Bookless

Offer Floor is free software, licensed under the GNU Affero General Public License v3.0 (see `LICENSE`). You may use, change and share it, but any modified version you distribute or host for others must also be released under the AGPL with its source code.
