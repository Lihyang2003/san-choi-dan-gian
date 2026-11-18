# Sân Chơi Dân Gian

Web game with two Vietnamese folk games, playable right in the browser (landscape):

- **Bầu Cua Tôm Cá**: one die. Bet 1 lì xì on one animal; if it comes up you get 6 back.
- **Ô Ăn Quan**: full rules (chain captures, capturing the quan, re-spreading when your row runs out). Play against Mai (Dễ / Vừa / Khó) or 2 players on one device.

Lì xì are just points for fun and cannot be exchanged for money. Progress is saved only in the player's own browser (localStorage).

## Run locally

Open `index.html` through any static server, for example:

```
npx serve .
```

## Publish with GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
After about 1 minute the game is live at `https://<username>.github.io/<repo-name>/`.

The images in `assets/` are taken from the project's Canva designs.
