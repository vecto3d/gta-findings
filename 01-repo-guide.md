# How to mine this repo

Part of the [GTA V decompiled script findings](README.md).

## Repo shape

- `decompiled_scripts/` — 1156 `.c` files, readable output: real native names,
  `joaat("...")` left as literal strings, control flow intact.
- `native_tables/` — per-script native tables.
- `scripts/` — raw `_ysc` disassembly.

Rough buckets by prefix: 142 `am_*`, 125 `fm_*`, 70 `gb_*`, 38 `re_*`, 32
`launcher_*`, 26 `ob_*`.

**Do not start with the big files.** `freemode.c` is 31 MB and
`fm_mission_controller_v3.c` is 27 MB, and much of that bulk is boilerplate
stamped into every script — the shared money/stat plumbing alone is thousands of
lines that reappears in a 1.6 MB vending machine script. Value is concentrated in
the small ones. Always grep first, read narrow slices second.

## Duplication warning

Large parts of the repo are near-identical clones. Do not mistake them for
distinct systems:

- **13 `*_carmod.c` scripts**, all ~8.3M — `arena_`, `base_`, `car_meet_`,
  `hacker_den_`, `hangar_`, `mansion_`, `tuner_property_`, `personal_`, etc.
  All clones of `carmod_shop.c`.
- **~10 `*_seating.c` scripts**, all ~8.4M — `mansion_`, `fixer_hq_`,
  `salvage_yard_`, `multistorey_garage_`, `juggalo_hideout_`, `base_lounge_`.
- Dozens of 1K stubs: `*_test.c`, `debug_*.c`, `globals_*_registration.c`.

Read one of each family, ignore the rest.

## Rare-scaleform sweep — the fastest way to find unique mechanics

Counting every `REQUEST_SCALEFORM_MOVIE` across all 1156 scripts and keeping
only names used **three times or fewer** surfaces the one-off systems, because
shared boilerplate appears in dozens of files. Command worth reusing:

    grep -ohE 'REQUEST_SCALEFORM_MOVIE\("[^"]+"' *.c \
      | sed 's/.*("//;s/"//' | sort | uniq -c | sort -n | awk '$1<=3'

### Best hits, mapped to their scripts

| Scaleform | Script | Size |
|---|---|---|
| `ATM` | `atm_trigger.c` | 112K |
| `LETTER_SCRAPS` | `letterscraps.c` | 48K |
| `dont_cross_the_line` | `dont_cross_the_line.c` | 164K |
| `SLOT_MACHINE` | `casino_slots.c` | 360K |
| `taxi_display` | `taxiservice.c` | 272K |
| `AXE_OF_FURY` | `am_mp_arcade_strength_test.c` | 1.8M |
| `mission_complete` | `minigame_stats_tracker.c` | 12K |
| `PLAYER_SWITCH`, `PLAYER_SWITCH_STATS_PANEL` | `selector.c` | 2.1M |
| `remote_sniper_hud`, `REMOTE_SNIPER_LOADING` | `martin1.c` | |
| `CASINO_HEIST_BOARD_PREP` / `_SETUP` / `_FINALE` | `gb_casino_heist_planning.c` | |
| `BANK_JOB_LOGIN` | `gb_bank_job.c` | |
| `DIGITAL_CAMERA` | `maintransition.c` | |
| `TEXTFIELD` | `am_contact_requests.c` | |

**`atm_trigger.c` (112K)** — a dedicated `ATM` scaleform and a small script.
Probably the single easiest UI-bearing system to port.

**`letterscraps.c` (48K)** — second complete collectible hunt alongside
`spaceshipparts.c`, with its own `LETTER_SCRAPS` scaleform. Two independent
implementations of the same idea to compare.

**`minigame_stats_tracker.c` (12K)** owns `mission_complete` — a tiny script
holding the generic completion screen. Useful for any activity payout.

### Terminal / computer UIs (all in phone apps)

`ROBBERY_COMPUTER` (`apphackerden.c`), `hacker_truck_desktop`
(`apphackertruck.c`), `securoserv` (`appsecuroserv.c`), `BOUNTY_COMPUTER`
(`appbailoffice.c`), `AVENGER_OPERATIONS_TERMINAL`, `JHPB_02_Laptop`,
`FIXER_APP`, `COVERT_OPS`.

Ready-made computer interfaces — no NUI needed for a laptop or terminal prop.

### Business management UIs

`NIGHTCLUB`, `BIKER_BUSINESSES`, `ARCADE_MANAGEMENT`, `ARCADE_BUSINESS_HUB`,
`warehouse`, `IMPORT_EXPORT_WAREHOUSE`, `HANGAR_CARGO`, `DISRUPTION_LOGISTICS`,
`SALVAGE_PLANNING`, `SALVAGE_VEHICLE_TARGETS`, `STARTER_PACK_BROWSER`.

### Misc named scaleforms

`MP_MENU_GLARE` (`wardrobe_mp.c`), `camera_gallery` (all `*_creator.c` —
the snapmatic gallery), `MP_MISSION_DETAILS_CARD`, `ARENA_CAREER_WALL`,
`YACHT_GAMERNAME`, `ORBITAL_CANNON_CAM`, `PARTY_BUS`, `SPLASH_TEXT`,
`graphic_design`, `font_lib_web`, `POWER_PLAY_*` (turf, vehicle, biker,
day_night, special_races).

`p_bubblegum` in `scaleformminigametest.c` — R* test harness, minimal
scaleform example.

## Sweeps that were low yield

Recorded so they are not repeated:

- **Rare anim dicts (`<=2` scripts)** — returns mostly standard
  `amb@world_human_*` scenario clipsets (guard patrol, hang out street, stand
  impatient, smoking, tourist mobile). These are well-known scenario animations,
  not hidden mechanics. The `mini@`/`oddjobs@` prefix sweep above is the better
  tool.
- **Rare PTFX assets (`<=2` scripts)** — almost entirely event/DLC-specific
  effect bundles: `proj_xmas_firework`, `scr_indep_parachute`,
  `scr_indep_wheelsmoke`, `scr_mp_tankbattle`, `scr_xm_stealcar`,
  `scr_bike_contraband`, `scr_impexp_ploughed`, `scr_tn_phantom`. Useful only if
  chasing a specific effect; no general mechanics.

---
