# keepingledger.com

The website for Ledger, a habit, task, journal and mood app for iPhone, iPad and Mac (with Apple Watch coming), made by Arca Holdings LLC.

Plain HTML, CSS and a little JavaScript. No build step, no cookies, no analytics, nothing loaded from other sites.
Light and dark follow the visitor's device.

- `index.html`, `home.css`, `home.js`: the home page. Its hero is a working copy of Ledger's Today page, built from
  Ledger 2.0's own colours, type and spacing, with made-up data. Nothing a visitor does is stored or sent anywhere.
- `privacy.html`, `support.html`, `styles.css`: the privacy and support pages. When the privacy page changes, update
  "Last updated" and add a line to its Changes list.
- `images/shots/`: screenshots of Ledger Test's made-up data, a light and a dark version of each. Replace a file with
  the same name to update a picture.
- `fonts/`: Inter, self-hosted for devices without Apple's system font (SIL Open Font License, see `OFL-Inter.txt`).

Hosted on GitHub Pages from the `main` branch, at keepingledger.com (see `CNAME`).
To preview locally the way GitHub Pages serves it: `node ~/Developer/site-preview/serve.mjs . 8123`.
