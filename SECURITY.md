# Security policy

## Supported version

Only the live version at [tbookless.github.io/offer-floor](https://tbookless.github.io/offer-floor/), which is always the latest code on the `main` branch, is supported.

## How Offer Floor handles data

Offer Floor is a static web page. It has no server, no accounts and no analytics. Settings and pickups are stored only in the browser on the driver's own device. The only time data leaves the device is when the driver taps **Look up in Maps**, which sends the home and pickup addresses to Google Maps (on Android) or Apple Maps (everywhere else).

## What counts as a security problem

For example:

- A way for someone else's page, file or link to read or change a driver's saved data.
- A way to run unwanted code in the app, for example through a crafted backup file or pickup name.
- Anything that sends data off the device that the privacy statement doesn't mention.

## Reporting a problem

Please **don't open a public issue** for security problems. Report privately instead:

1. Go to the repository's [**Security** tab](https://github.com/tbookless/offer-floor/security).
2. Click **Report a vulnerability** and describe what you found and how to reproduce it.

This is a one-person volunteer project, so I can't promise a response time. I'll aim to reply within a week and fix confirmed problems as quickly as I can. You're welcome to be credited in the fix if you'd like.
