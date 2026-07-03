# Reverse: 1999 — Team Planner

A single-file, offline web app for tracking your [Reverse: 1999](https://re1999.bluepoch.com/) roster and figuring out which team comps you can field.

Everything runs client-side in the browser and persists to `localStorage` — no build step, no server, no account. Just open `index.html`.

## Features

- **Roster tracking** — mark which characters you own and whether each has **Euphoria** unlocked.
- **Reference data for every character** — Afflatus (Beast / Intellect / Mineral / Plant / Spirit / Star), specialty/archetype tag (Poison DPS, Burn, Eureka support, Healer, etc.), and the **top 3 recommended psychubes** with a one-line reason and an acquisition tag:
  - **Shop** — standard 5★, buy anytime in the Fragment Shop with farmed materials
  - **Sig** — the character's signature, from their event shop (hardest to get)
  - **Event** — limited 6★ from a past event shop or the battle pass
- **Team comps** — pre-seeded meta teams auto-scored **Ready / Partial / Missing** against your live roster, with synergy blurbs and rotation notes. Flex slots accept interchangeable options.
- **Wishlist** — automatically surfaces which teams are exactly one pull away, so you know who to prioritize.
- **Visual team builder** — click character chips into slots to design your own comps.
- **Search & filters** — by name, specialty, psychube, afflatus, or role.
- **Export / Import** — back up your whole roster + teams as a JSON file, or move it between browsers/devices.

## Usage

Open `index.html` in any modern browser. That's it. Your data is saved locally and stays on your machine.

## Notes

Character data, psychube recommendations, and team comps reflect community guides (Prydwen, Game Rant, Sportskeeda, etc.) as of mid-2026. In-game shop availability rotates — verify the live Fragment Shop / event shops. All reference fields are editable in-app if you disagree with a call or the meta shifts.

---

*Not affiliated with Bluepoch. Reverse: 1999 is a trademark of its respective owner. This is a fan-made planning tool.*
