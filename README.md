# CipherVault — Browser AES-256-GCM Encryption

**Encrypt and decrypt files and text with a passphrase — the key never leaves your device.**

CipherVault performs authenticated AES-256-GCM encryption with a key derived from your passphrase using PBKDF2-HMAC-SHA256 (200,000 iterations). Because it's GCM, any tampering is detected on decrypt. All processing is in-memory and client-side.

## Highlights
- **Pure front-end** — HTML, CSS and vanilla JavaScript. No backend, no build step, no Python.
- **Private by design** — everything runs locally in your browser; nothing is uploaded or sent to a server.
- **Zero install** — just open `index.html`.

## Run it
- **Easiest:** double-click `index.html` (or drag it into your browser).
- **Local server (optional):** `npx serve .` then open the printed URL.
- **Publish free:** push to GitHub and enable **GitHub Pages** (Settings → Pages → deploy from `main`) for a shareable live link.

## Tech
Vanilla JavaScript + the Web Crypto API · responsive single-page UI · no dependencies.

## License
MIT © 2025 Harsha Malepati
