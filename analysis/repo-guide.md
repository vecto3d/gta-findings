# How to mine this repo

Build **1.73-3889.0**, 1156 scripts.

- `decompiled_scripts/` — the `.c` files. Readable output: real native names,
  `joaat("...")` left as literal strings, control flow intact. Only variable
  names are gone.
- `native_tables/` — per-script native tables.
- `scripts/` — raw `_ysc` disassembly.

Rough buckets by prefix: 142 `am_*`, 125 `fm_*`, 70 `gb_*`, 38 `re_*`,
32 `launcher_*`, 26 `ob_*`.

## Do not start with the big files

`freemode.c` is 31 MB and `fm_mission_controller_v3.c` is 27 MB, and much of that
bulk is boilerplate stamped into every script — the shared money and stat
plumbing alone is thousands of lines that reappears in a 1.6 MB vending machine
script.

**Value is concentrated in the small files.** Always grep first, read narrow
slices second.

## Duplication — do not mistake clones for systems

- **13 `*_carmod.c`** scripts, all ~8.3M, all clones of `carmod_shop.c`
- **~10 `*_seating.c`** scripts, all ~8.4M
- Dozens of 1K stubs: `*_test.c`, `debug_*.c`, `globals_*_registration.c`

Read one of each family and ignore the rest.

## Search techniques that work

**Rare scaleform sweep** — the best single technique. Counting every
`REQUEST_SCALEFORM_MOVIE` and keeping names used three times or fewer isolates
one-off systems, because boilerplate appears in dozens of files:

    grep -ohE 'REQUEST_SCALEFORM_MOVIE\("[^"]+"' *.c \
      | sed 's/.*("//;s/"//' | sort | uniq -c | sort -n | awk '$1<=3'

**Activity anim prefix sweep** — list every `mini@` and `oddjobs@` dict, since
those prefixes are activity-specific by convention. This is what surfaced CPR,
safe cracking and vehicle repair.

**Categorise by filename, then read the leftovers** — the uncategorised bucket is
where unusual features hide. That is how `three_card_poker`, `word_hack`,
`circuitblockhack` and `chop` were found, all of which the prefix sweeps missed.

## Sweeps that were low yield

Recorded so they are not repeated:

- **Rare anim dicts** (used in two scripts or fewer) — returns mostly standard
  `amb@world_human_*` scenario clipsets. Well-known, not hidden mechanics.
- **Rare PTFX assets** — almost entirely event and DLC effect bundles
  (`proj_xmas_firework`, `scr_indep_parachute`, `scr_mp_tankbattle`,
  `scr_xm_stealcar`). Useful only when chasing one specific effect.
- **`gb_*` scripts** — 70 files, the large ones share one boilerplate shell with
  identical anim dicts. Value is job structure, not assets.
- **Creators** (`creator.c`, `fm_race_creator.c`, `fm_deathmatch_creator.c`,
  `public_mission_creator.c`) — editor UIs rather than mechanics. Only reusable
  asset is the `camera_gallery` scaleform.
- **Launchers** — 32 `launcher_*.c`, all trigger and availability wrappers. A
  model for gating content by time, location and player state; no assets.


## Corrections from the full sweep

Three claims made in earlier passes turned out to be wrong once every script was
parsed and deduplicated. Recording them because each one is a trap the obvious
method walks straight into.

**"The seating scripts are duplicate clones."** Wrong twice. All 52 have unique code,
and they are the canonical reference for animation alignment. They *look* empty to a
string sweep because they pass anim dictionaries through helper functions instead of
naming them inline. Low asset count does not mean low value — see
[seating](../features/seating.md).

**"The safehouse activities are nine separate implementations."** They are one engine
that branches on the model of the prop it was attached to. Porting one gets all nine.

**"`ob_*` is the complete set of prop interactions."** `atm_trigger.c` and
`laptop_trigger.c` run the identical object brain pattern without the prefix. Prefix
sweeps are a starting point, not a census.

The common thread: **naming and file layout are not evidence.** Three of the four
worst mistakes in this repo came from trusting a filename over the code, and the
fourth came from trusting a string count.

## What a low asset count actually means

The per-script documents show an asset count. It is tempting to read a low one as
"nothing here". Measured across the corpus, assets per script by category:

| Category | Assets per script |
|---|---:|
| Creators | 180 |
| Races | 130 |
| MP freemode | 115 |
| Object brains | 16 |
| Seating | 4 |
| Dev and test | 1 |

Object brains average 16 assets and are the most portable category in the game.
Seating averages 4 and taught us the alignment technique. Creators average 180 and
are close to useless for a server.

**Asset count measures how much a script names, not how much it does.** The only
category where a low count really does mean nothing is `dev-test`, where 65 of 88
scripts have no unique code at all.
