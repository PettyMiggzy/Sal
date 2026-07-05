# $SALMONAD

The purple salmon of Monad — the OG by timestamp. Community site, sticker packs, and two 3D games.

**Live:** https://salmonad.vercel.app (→ salmonad.net)
**Token:** [$SALMONAD on nad.fun](https://nad.fun/tokens/0x0a917fCC0799E43d0232780aA359aA0D389d7777)
`CA: 0x0a917fCC0799E43d0232780aA359aA0D389d7777`
**Socials:** [X](https://x.com/Salmonads) · [Telegram](https://t.me/salmonads) · admin@salmonad.net

---

## What's here

| Path | What it is |
|------|-----------|
| `index.html` | The landing site (self-contained: all images inlined as base64). Served at `/`. |
| `game/` | **Game v1 — "Shrimp to Whale"**: stylized 3D free-swim eat-to-grow. `/game` |
| `game2/` | **Game v2 — "CGI Ocean"**: same game with CGI creature sprites. `/game2` |
| `game/three.min.js` | Vendored Three.js r137 (shared by both games; no CDN). |
| `game2/creatures/` | 9 transparent CGI creature textures (clownfish → whale + player). |
| `assets/salmonad/` | Source art — see below. |
| `vercel.json` | Static hosting config (`cleanUrls`). |

## Games
Both are single-player, **no wallet**, self-contained. Eat fish smaller than you to grow through
tiers (Shrimp → … → Whale); dodge anything bigger — the **MONAD whales**. Steer with mouse/finger,
hold click / Space / the on-screen button to dash. Aim reticle + green lock-ring show what you can eat.
Append `?test=1` to auto-feed for testing. Not linked in the site nav yet.

## Site features
- Live **nad.fun** price / market cap / holders (client-side fetch, no key)
- OG-timestamp lore (the Salmonad-CTO rug), CGI Monanimals lineup, meme gallery
- Custom Salmonad cursor + favicon; buy buttons link to nad.fun (no wallet-connect)

## `assets/salmonad/`
`cgi/` cinematic renders · `monanimals/` CGI Monanimal cast · `stickers_2d/` `stickers_cgi/`
`stickers_3d/` `stickers_transparent/` Telegram sticker packs (animated `.webm` + static `.png`) ·
`video/` promo clip · plus hero stills and the canonical reference.

## Notes
Source PNGs/MP4s are full-resolution (the repo is media-heavy by design so the raw deliverables
live with the project). The live site does **not** load these — it embeds optimized copies inline.

---

### Disclaimer
$SALMONAD is a community meme project and cultural tribute inspired by the Monad "Monanimals."
It is **not affiliated with, endorsed by, or officially connected to** Monad, its team, or its
founders. "Keone's favorite token" is community folklore/satire. Nothing here is financial advice;
memecoins are high-risk. Always verify the official contract address yourself.
