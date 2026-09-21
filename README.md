# Meteor Dodge

> ⚠️ **DEPRECATED — ARCHIVED.**
> This repository is preserved as-is and is no longer maintained.
> For the author's active, actual D&D project, see their other repository.

**Meteor Dodge** began as a tiny single-file Lua console arcade game — a lone ship
dodging falling meteors across a 25×12 grid, 45 turns, 3 lives — and grew, through an
AI-driven iterative development process, into a 100-floor turn-based browser roguelike
with D&D-style dice combat, a skill tree, FF7-inspired secret Weapon super-bosses, and a
live balance designer. It is archived here under its very first original name.

## Name history

| Era | Name |
|---|---|
| Phase 0 — Lua console arcade | **Meteor Dodge** ← original name, restored for archive |
| Phase 1–2 — D&D turn & web migration | Dungeon Dice: Meteor Crypt |
| Phase 3–11 — web RPG expansion | DND (Dungeon and dragons) |
| Archive | **Meteor Dodge** |

## What's inside

- `src/` — final web build (`index.html`, `styles.css`, `script.js`), v11
- `TIMELINE.md` — full project progression, Phase 0 → Phase 11
- `LORE.md` — in-universe canon of the Meteor Crypt

## Feature snapshot (final build)

- Turn-based grid roguelike, 100 floors; death returns you to Floor 1 keeping all progress
- 3 classes (Fighter / Rogue / Wizard with MP), d20 combat, crits, advantage, rogue crit spec
- Stat-point allocation with % damage scaling; skill tree with active slots & cooldowns
- Merchant with random stock (scrolls, swift shoes, holy wing), class-specific weapons,
  blacksmith enhancement +1…+20 (raw + % damage), storage inventory + item utility slots
- Secret FF7-style Weapon super-bosses (Sapphire → Diamond → Ultima → Ruby → Emerald)
  dropping relics; Tiamat, Dragon Queen as the floor-100 boss
- Multi-slot localStorage saves; only the explicit "Erase data" button can wipe them
- Live ⚙ Balance Designer panel — runtime tuning that never touches save data
- Auto-play demo AI, 1x/3x/5x speed, hold-to-walk, click-to-attack, slash & ember VFX

## Run it (for posterity)

Open `src/index.html` in any browser, or serve the folder locally.
Originally developed on OneCompiler as an HTML project (3 tabs).

## AI-driven development note

This project was built through conversational human–AI pairing: the human director set
the vision, the corrections, and the balance intent; the AI produced the code, the docs,
and the lore. The pivotal chapter was the **Lua → HTML/CSS/JS migration**, which kept all
game logic identical while replacing only the I/O layer — the step that made everything
after it possible.


---

*Archived. The ember storm over the Meteor Crypt has settled — for now.*
