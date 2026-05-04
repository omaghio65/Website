# The IceCube — Website

Static site for **The IceCube UG (haftungsbeschränkt)**, Düsseldorf.

## Deploy

This repo is deployed via **GitHub Pages**.

- **Live URL:** `https://<your-gh-username>.github.io/icecube-website/` *(update once Pages is enabled)*
- **Source:** `index.html` (single-file site, all CSS/JS inline) + `images/`

## Status

- Site is live behind `<meta name="robots" content="noindex,nofollow">` while the legal pages are being prepared.
- Pending before public launch: Impressum, Datenschutzerklärung, AGB, Widerrufsbelehrung, About — all linked from the footer but not yet authored.
- Booking form currently has placeholder Web3Forms key — submissions disappear until the real key is set in the `CONFIG` block.

## Local preview

Open `index.html` in any browser, or run a local server:

```
cd /path/to/Website && python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
