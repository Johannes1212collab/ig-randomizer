# IG Randomizer

Pick one fair winner from an Instagram post's comments.

Paste the comments (copied from instagram.com, a CSV or JSON export, or one per line), set the giveaway rules, and draw. Everything runs in the browser; no comments are sent anywhere.

## Rules it supports

- One entry per account, or every comment counts (word-for-word repeats ignored)
- A minimum number of tagged friends
- Words or hashtags the comment must include
- Accounts to leave out

The pick uses the browser's cryptographic random number generator with rejection sampling, so every entry has the same chance.

## Install on a phone

Open the site, then:

- iPhone (Safari): Share, then Add to Home Screen
- Android (Chrome): menu, then Add to Home screen or Install app

## Files

- `index.html` is the whole app
- `manifest.webmanifest`, `sw.js` and the icons make it installable and usable offline
