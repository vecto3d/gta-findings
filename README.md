# GTA V Decompiled Scripts — FiveM Port Findings

Notes from mining a full decompile of GTA V build **1.73-3889.0** for mechanics
worth porting to FiveM.

**1,156 scripts · 3.58 GB · 168,668,190 lines.** Every one parsed, deduplicated and
indexed. Everything quoted — animation dictionaries, props, scaleform names, timing
values, offsets — is taken verbatim from the decompiled source.

**Coverage:** of the 4,213 distinct natives used across the corpus, the documents here
name 1,840 — **88.7% weighted by how many scripts use each**. The rest is arithmetic.

## Layout

| Folder | What is in it |
|---|---|
| [features/](features/) | 51 hand-written notes, one per mechanic. Start here if you want to build something. |
| [scripts/](scripts/) | All 1,156 scripts, one document each, grouped into 23 categories. |
| [reference/](reference/) | 18 cross-reference indexes mapping every asset back to the scripts that use it. |
| [analysis/](analysis/) | How this was built, and how far to trust it. |

## Read this first

[analysis/coverage.md](analysis/coverage.md) — the honest accounting. All 1,156
scripts are **parsed**; 17 are **read**; 1 is **verified** against a running game.
The tables in every script document are extracted fact. The one-line descriptions
above them are inference.

## Start here

Read [object-brain-pattern](features/object-brain-pattern.md) first. All 26 prop
interactions are one skeleton with a different middle, and it is the most portable
structure in the corpus.

Then [animation-alignment](reference/animation-alignment.md) — two natives that
replace the offset-and-timing guesswork most ports are built on.

Strongest build candidates, roughly easiest first:

- [beds](features/beds.md) — enter, loop, exit. Reuses the vending skeleton verbatim
- [cash-register](features/cash-register.md) — ~170 lines, no animation at all
- [atm](features/atm.md) — dedicated `ATM` scaleform, easiest UI-bearing system
- [collectible-hunts](features/collectible-hunts.md) — two complete implementations
- [cpr-revive](features/cpr-revive.md) — paired medic/patient anims for EMS
- [safe-cracking](features/safe-cracking.md) — full dial-turning set, nothing missing
- [chop-companion-dog](features/chop-companion-dog.md) — complete K9 including scent pose
- [taxi](features/taxi.md) — two scaleforms, no UI to write
- [animated-door-collision](features/animated-door-collision.md) — moving collision on animated props
- [vending-machine](features/vending-machine.md) — the only verified document here

## Where the value is

The useful inversion: **the most portable scripts are the smallest.**

| Category | Scripts | Unique lines |
|---|---:|---:|
| [Collectibles](scripts/collectibles/) | 8 | 5,582 |
| [Street characters](scripts/street-characters/) | 18 | 12,234 |
| [Object brains](scripts/object-brains/) | 26 | 22,145 |
| [Random events](scripts/random-events/) | 38 | 81,050 |
| [Ambient world](scripts/ambient-world/) | 41 | 112,665 |
| … | | |
| [MP freemode](scripts/mp-freemode/) | 122 | 3,684,117 |

All 26 object brains together are 22,145 lines — under 4% of `freemode.c` alone,
which is 573,248. The vending machine came from the small end. So will the next one.

Full breakdown in [scripts/README.md](scripts/README.md).

## Techniques worth knowing before you build

**[TECHNIQUES.md](TECHNIQUES.md) — the full index.** Every non-obvious technique
recovered, grouped by area, each row naming what it replaces. Start there if you know
what you want to build.

Highlights:

Found by reading and surveying, not by string search. Each replaces something people
normally hand-roll:

- [animation-alignment](reference/animation-alignment.md) — ask the animation where
  the ped should stand, and when it may be interrupted. No tuned offsets.
- [move-networks](reference/move-networks.md) — input-responsive animation state
  machines. The arcade love meter reuses the casino vault drilling network.
- [audio](reference/audio.md#audio-scene-variables-the-underused-mechanism) — audio
  scene variables driven by live values, not toggled states.
- [tv-and-channels](features/tv-and-channels.md) — the named render target recipe.
- [telescope](features/telescope.md) — `USE_SCRIPT_CAM_FOR_AMBIENT_POPULATION_ORIGIN_THIS_FRAME`,
  the fix for empty streets under a scripted camera.
- [ped-control-flags](features/ped-control-flags.md) — why your scripted animation
  keeps getting interrupted.
- [pause-menu-and-buttons](features/pause-menu-and-buttons.md) — add pages to the
  game's own pause menu.

## Reference indexes

Every asset name mapped back to the scripts using it — 3,137 animation dictionaries,
4,941 models, 3,813 animations, 988 scaleforms, 608 particle effects, and more.
See [reference/README.md](reference/README.md).

The most interesting one is
[developer-state-labels](reference/developer-state-labels.md): debug strings
Rockstar left in 27 shipped scripts that name their own internal states. It is the
closest thing to written documentation in the corpus.

## How the corpus was cracked

93% of it is duplicate library code compiled into every script. Function names are
not stable across files, so bodies were normalised and hashed instead:
**2,830,909 function instances collapse to 190,106 distinct bodies.** Each script
document shows only what is left after removing everything shared.

Method in [analysis/methodology.md](analysis/methodology.md); pitfalls and search
techniques in [analysis/repo-guide.md](analysis/repo-guide.md).

## Three things that cost time

Learned building the vending machine, and worth knowing before you start:

1. **An attached entity will not delete.** Detach first, always.
2. **Model does not imply identity.** The soda machines share models, so the brand a
   machine displays cannot be derived from what it is.
3. **Animations are authored data.** Only `PLYR_BUY_DRINK_PT1/2/3` exist in the
   entire game; there is no alternate button-press clip to swap in.
