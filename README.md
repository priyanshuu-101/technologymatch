# Budget Season — static app for Webflow Cloud

Single self-contained page. No build step, no dependencies.

- `index.html` — the whole game (fonts, runtime and logic inlined)
- `webflow.json` — pins Webflow Cloud to the `static` framework

## Deploy

1. Push this folder's contents to the root of `priyanshuu-101/technologymatch` on `main`.
2. Webflow Cloud app mounts it at `/it-budget-season-game` on the Technology Match site.
3. Set the HubSpot form redirect to `https://www.technologymatch.com/it-budget-season-game?gate=done`.

Everything is relative or inlined, so it serves correctly from a non-root mount path.
