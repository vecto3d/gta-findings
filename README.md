# GTA V Decompiled Scripts — FiveM Port Findings

Notes from mining a full decompile of GTA V build **1.73-3889.0** (1156 scripts)
for mechanics worth porting to FiveM. Everything quoted — anim dictionaries,
props, scaleform names, timing values, offsets — is taken verbatim from the
decompiled source.

## Contents

| File | What is in it |
|---|---|
| [01-repo-guide.md](01-repo-guide.md) | Repo shape, which files to avoid, duplication warnings, and the search techniques that actually surface features |
| [02-object-interactions.md](02-object-interactions.md) | `ob_*` object brains and `re_*` random events, with the full anim and prop tables |
| [03-vending-machine.md](03-vending-machine.md) | Complete flow of `ob_vend1.c`, ported as `od_vending`, plus the ranked list of what to port next |
| [04-minigames.md](04-minigames.md) | Darts, golf, tennis, arm wrestling, shooting range, yoga, arcade cabinets, casino and the standalone hacking minigames |
| [05-heists.md](05-heists.md) | Heist minigame scaleforms and the planning boards |
| [06-jobs-and-activities.md](06-jobs-and-activities.md) | Taxi, towing, car wash, hunting, bail bonds, `am_*` activities, `gb_*` business work, rides and races |
| [07-world-and-ambient.md](07-world-and-ambient.md) | Street characters, the Chop companion-dog system, collectible hunts, nightlife and small world systems |
| [08-ui-and-scaleforms.md](08-ui-and-scaleforms.md) | Phone, render targets, notifications, shops, properties and creators |
| [09-animations.md](09-animations.md) | Activity anim dictionaries including CPR and safe cracking, sync scenes, scenarios and camera shakes |
| [10-audio.md](10-audio.md) | Sound sets and the minigame audio banks |
| [11-natives-reference.md](11-natives-reference.md) | Decorators, doors, interior entity sets, relationship groups, timecycles, pickups, weapons, IPLs, task vocabulary, waypoint recordings and native call counts |
| [script-inventory.md](script-inventory.md) | All 1156 scripts, grouped into categories |

## Start here

If you are looking for something to build, the strongest candidates found were:

- **`atm_trigger.c`** (112K) — dedicated `ATM` scaleform, the easiest UI-bearing system
- **`spaceshipparts.c`** / **`letterscraps.c`** (36K / 48K) — two complete collectible hunts
- **CPR revive** — `mini@cpr@` paired anims plus the `CODE_HUMAN_MEDIC_KNEEL` scenario
- **Safe cracking** — full dial-turning anim set and the `SAFE_CRACK` audio bank
- **`chop.c`** (212K) — complete K9 system, including the scent-indication pose
- **Taxi job** — `TAXI_HAIL` and `taxi_display` scaleforms, no UI to write
- **Arcade cabinets** — sprite-drawn, and `am_mp_arcade_fortune_teller.c` is only 60K
- **Beds** (`ob_mp_bed_*`) — reuses the vending machine skeleton almost verbatim

## Three things that cost time

Learned building the vending machine, and worth knowing before you start:

1. **An attached entity will not delete.** Detach first, always.
2. **Model does not imply identity.** The soda machines share models, so the
   brand a machine displays cannot be derived from what it is.
3. **Animations are authored data.** Only `PLYR_BUY_DRINK_PT1/2/3` exist in the
   entire game; there is no alternate button-press clip to swap in.
