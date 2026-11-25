# Budget Season — static app for Webflow Cloud

Single self-contained page. No build step, no dependencies.

- `index.html` — the whole game (fonts, runtime and logic inlined)
- `webflow.json` — pins Webflow Cloud to the `static` framework

## Deploy

1. Push this folder's contents to the root of `priyanshuu-101/technologymatch` on `main`.
2. Webflow Cloud app mounts it at `/it-budget-season-game` on the Technology Match site.
3. The sign-up form is a native Webflow form on the Webflow page `/budget-season-form` (form name `Budget Season Game`, ID `bsg-form`). The game shows that page in an iframe on its "Before we start" screen and unlocks the year when the page posts a `success` message. Edit the form in the Webflow Designer, not here.
4. `?gate=done` still unlocks the game directly (kept for old links).

Everything is relative or inlined, so it serves correctly from a non-root mount path.
