# Contributing to Offer Floor

Thanks for helping. Offer Floor is deliberately small: one page, no accounts, no tracking, and everything stays on the driver's own phone. Contributions that keep it that way are very welcome.

## Bug reports and ideas

The most helpful thing you can do is [open an issue](https://github.com/tbookless/offer-floor/issues/new/choose):

- **Bug report:** what you did, what you expected, what happened, and your phone and browser (for example "iPhone 15, Safari" or "Pixel 8, Chrome").
- **Idea:** what problem it would solve for you as a driver.

Please don't include your home address, pickup addresses or pay details in an issue. Issues are public.

## Code changes

Please **open an issue first** and wait for a reply before writing code, so we can agree on the change before you spend time on it. Then:

1. Keep it to plain HTML, CSS and JavaScript in the existing files. No frameworks, build tools or outside scripts.
2. Don't add anything that sends data off the phone: no analytics, ads, trackers, fonts or scripts from other sites.
3. Test on a phone-sized screen, in light and dark mode, on iPhone (Safari) and Android (Chrome) if you can.
4. If you change any app file, bump `VERSION` in `sw.js` (for example `offer-floor-v2` → `offer-floor-v3`) so installed copies update.
5. Open a pull request that links the issue and fills in the checklist.

## License

Offer Floor is licensed under the [GNU AGPL v3.0](LICENSE). By sending a contribution, you agree that it's released under the same license.

## Code of conduct

Everyone taking part is expected to follow the [code of conduct](CODE_OF_CONDUCT.md).
