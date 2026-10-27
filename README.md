# Astro Splitter website

A tiny static site for GitHub Pages: home, support, privacy policy and `app-ads.txt`.

## Before going live with ads
1. Paste AppLovin's lines into `app-ads.txt` (AppLovin dashboard → Account → app-ads.txt).

## Publish on GitHub Pages
`app-ads.txt` must sit at the root of the domain, so use a **user site**, not a project site:
1. Create a public repository named exactly `<your-github-username>.github.io`.
2. Upload everything in this folder (including `.nojekyll`) to the repository root.
3. In the repository's Settings → Pages, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute the site is live at `https://<your-github-username>.github.io/`.
   Check `https://<your-github-username>.github.io/app-ads.txt` opens as plain text.

## Then use the URLs
- AppLovin sign-up website: `https://<username>.github.io/`
- App Store Connect: Privacy Policy URL `…/privacy/`, Support URL `…/support/`, Marketing URL `…/`
- `AstroSplitter/Services/AdConfig.swift`: set `privacyPolicyURL` and `supportURL` to the same pages.
