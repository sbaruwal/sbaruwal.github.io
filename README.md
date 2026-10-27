# sbaruwal apps website

Static site on GitHub Pages at https://sbaruwal.github.io/.

- `/` lists all apps.
- `/app-ads.txt` is shared by every app and must stay at the root (ad networks only look there).
- Each app has its own folder with a home page, `privacy/` and `support/`, e.g. `/astrosplitter/`.

To add an app, copy `astrosplitter/` to a new folder, edit its pages, and add a card to `index.html`.
When it uses another ad network, add that network's lines to `app-ads.txt`.

## Before going live with ads
1. Paste AppLovin's lines into `app-ads.txt` (AppLovin dashboard → Account → app-ads.txt).

## Publishing
This repository is `sbaruwal/sbaruwal.github.io`; GitHub Pages serves `main` from the root.
Push to `main` and the site updates within a minute.

## URLs to use
- AppLovin sign-up website: `https://sbaruwal.github.io/`
- App Store Connect (Astro Splitter): Privacy Policy `…/astrosplitter/privacy/`, Support `…/astrosplitter/support/`,
  Marketing `…/astrosplitter/`
- Each app's code links to its own privacy and support pages.
