# Sân Chơi Dân Gian

Web game with two Vietnamese folk games, playable right in the browser (landscape):

- **Bầu Cua Tôm Cá**: one die. Bet 1 lì xì on one animal; if it comes up you get 6 back.
- **Ô Ăn Quan**: full rules (chain captures, capturing the quan, re-spreading when your row runs out). Play against Mai (Dễ / Vừa / Khó) or 2 players on one device.

From the home screen (bottom-left buttons):

- **Nhân vật**: pick the character you play as (Tuấn Anh, Bà Ngoại, plus Bé Mai, Ông Ngoại, Cô Tư unlocked by playing; Chú Ba comes with a Tết event). Locked characters show their unlock conditions and progress.
- **Tủ đồ**: dress Tuấn Anh in Quần / Áo / Kính / Dép, buy items with lì xì, and collect the 6-piece *Đồ chơi dân gian* set by playing (finish it for +10 lì xì).
- **Túi lì xì**: current balance, what came in and went out today, and the full history with filters (Tất cả / Nhận / Đã dùng).

Lì xì are just points for fun and cannot be exchanged for money. Progress is saved only in the player's own browser (localStorage).

## Run locally

Open `index.html` through any static server, for example:

```
npx serve .
```

## Publish with GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
After about 1 minute the game is live at `https://<username>.github.io/<repo-name>/`.

The images in `assets/` are taken from the project's Canva designs and the Figma file; the characters in the Nhân vật popup (`char-tuan-anh`, `char-ba`, `char-mai`, `char-co-tu`, `char-chu-ba` and their `av-*` avatars) are the team's own drawings with the white background removed; `char-ong`, `av-ong`, `sheet-*`, `outfits.jpg` and `ic-li-xi.jpg` were generated with Figma AI.
