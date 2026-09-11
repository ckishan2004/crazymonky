# 🐒 CrazyMonky

Personal site of **Kishan Chavda** — algo-trading software for Indian markets.
AlgoBridge · Breakout Elite (Pine Script v6) · SmartWave Academy.

Single-file site: everything lives in `index.html` (HTML + CSS + JS, no build step).

## Edit your details

Open `index.html`, find the `PROFILE` object near the bottom inside `<script>`:

```js
const PROFILE = {
  name:  "Kishan Chavda",
  title: "Builds algo-trading software for Indian markets",
  place: "Vadodara, Gujarat",
  email: "hello@example.com",   // <-- change this
  ticker: [ ... ]               // lines in the scrolling strip
};
```

## Host free on GitHub Pages

1. Create a new repo (e.g. `crazymonky`) and upload `index.html` + `README.md`.
2. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.
3. After a minute the site is live at `https://<your-username>.github.io/crazymonky/`.

Tip: name the repo `<your-username>.github.io` instead and the site lives at the root URL.
