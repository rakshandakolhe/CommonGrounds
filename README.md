# CommonGrounds

A single-page coffee invite maker. Decorate a cup, write a message, and send someone a coffee invite they'd actually want to accept.

## How it works

1. **Create** — Decorate a cup with stickers, write a name and message, pick a date
2. **Share** — Copy the invite link and send it
3. **Recipient** — Opens the link, accepts or declines
4. **Keepsake** — Accepted invites generate a calendar card to save

## Tech

- Single self-contained `index.html` — no build step, no dependencies
- Hash-based client-side routing (`#/`, `#/create`, `#/done/`, `#/i/`, )
- All assets base64 inlined
- Google Fonts: Caveat, DM Sans

## Run locally

Just open `index.html` in a browser.
