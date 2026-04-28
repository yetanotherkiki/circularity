# circularity @ skullspace

A proposal for a circularity / right-to-repair events subcommittee at [SkullSpace](https://skullspace.ca), Winnipeg’s hackerspace.

This repo hosts the live web version of the proposal. There is also a printable PDF handout intended for the in-person member meeting.

## what’s in here

- `index.html` — the proposal site, fully self-contained (inline CSS, base64-embedded logo, no external assets)
- `.nojekyll` — tells GitHub Pages to serve files as-is, no Jekyll processing
- `LICENSE` — content licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## deploying to github pages

1. push this repo to GitHub
1. settings → pages → deploy from branch → `main` → `/` (root)
1. wait a minute, get your URL (e.g. `https://USERNAME.github.io/circularity-at-skullspace/`)
1. update the QR code in the printable PDF to point at the deployed URL (see the PDF’s render script for the one-line `SITE_URL` change)

## editing

Everything is inline in `index.html`. To swap the logo, replace the base64 string on the `<img class="logo">` line. To change content, edit the HTML directly — there is no build step.

## license

Content is [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) — share and adapt freely with attribution. Other hackerspaces are welcome (encouraged!) to fork and adapt this for their own circularity initiatives.
