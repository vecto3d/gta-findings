# Minigames, arcade and casino

Part of the [GTA V decompiled script findings](README.md).

## Minigames & activities

| Script | Size | Anim dicts | Custom scaleforms |
|---|---|---|---|
| `darts.c` | 628K | `mini@dartsoutro` | `darts_scoreboard` |
| `golf.c` | 3.0M | `mini@golfclub_bag`, `mini@golfclubhouse` | `golf`, `golf_floating_ui` |
| `tennis.c` | 2.7M | `facials@gen_male@base`, `facials@gen_female@variations@happy`, … | — |
| `am_armwrestling.c` | 2.7M | `mini@arm_wrestling` | `COUNTDOWN` |
| `range_modern.c` | 2.5M | `mini@shoot_range`, `mini@ears_defenders` | `SC_LEADERBOARD` |
| `pilot_school.c` | 2.6M | `oddjobs@basejump@`, `veh@helicopter@rps@base` | `TV_FRAME`, `MP_MEDAL_FREEMODE`, `mission_quit` |
| `yoga.c` | 1.9M | `mini@yoga`, `missfam5_yoga` | `yoga_buttons`, `yoga_keys` |

`darts_scoreboard`, `golf_floating_ui`, `yoga_keys` and `taxi_display` are
purpose-built scaleforms — usable directly, no NUI needed.

### Reusable scaleform catalogue

Seen across many scripts, safe to lean on:
`instructional_buttons`, `GENERIC_INSTRUCTIONAL_BUTTONS`, `MP_BIG_MESSAGE_FREEMODE`,
`MIDSIZED_MESSAGE`, `SC_LEADERBOARD`, `COUNTDOWN`, `MP_MEDAL_FREEMODE`,
`BREAKING_NEWS`, `SOCIAL_CLUB_TV`, `MP_SPECTATOR_CARD`, `MP_SPECTATOR_OVERLAY`.

## Casino

Scripts: `blackjack.c` (608K), `casinoroulette.c` (7.7M), `casino_slots.c`
(360K), `casino_lucky_wheel.c` (1.5M), `bigwheel.c` (660K), plus
`am_mp_casino.c`, `am_casino_peds.c` (9.5M) and six `casino_*_seating.c`.

- `casino_slots.c` drives a single `SLOT_MACHINE` scaleform — the smallest,
  most self-contained casino game and the obvious first port.
- `blackjack.c` and `casinoroulette.c` use only `instructional_buttons` /
  `GENERIC_INSTRUCTIONAL_BUTTONS`; table state is data-driven and the dealer
  animation lives in `am_casino_peds.c`.
- `am_casino_peds.c` holds the ambient casino population under
  `ANIM@AMB@CASINO@…`: `HANGOUT@PED_FEMALE@STAND@01A@BASE` / `@IDLES` /
  `@IDLES_CONVO` (numbered variants), `BAR@SPECIAL_PEDS@LAUREN@01A@BASE@`,
  `BAR@SPECIAL_PEDS@TAYLOR@01A@BASE@`, and brawl reactions
  `BRAWL@REACTS@BAR@` / `@SLOTS@` / `@STANDING@`.

## Arcade cabinets — self-contained playable games

Each cabinet is its own script, which makes them unusually good port targets:

| Script | Size | Notes |
|---|---|---|
| `am_mp_arcade_fortune_teller.c` | 60K | Tiniest activity in the repo |
| `grid_arcade_cabinet.c` | 276K | Full texture set, see below |
| `photographymonkey.c` | 460K | `MIDSIZED_MESSAGE` |
| `am_mp_arcade_claw_crane.c` | 1.8M | Claw machine |
| `am_mp_arcade_love_meter.c` | 1.8M | |
| `am_mp_arcade_strength_test.c` | 1.8M | Own scaleform **`AXE_OF_FURY`** |
| `degenatron_games.c` | 1.9M | |
| `camhedz_arcade.c` | 2.1M | |
| `gunslinger_arcade.c` | 2.1M | |
| `ggsm_arcade.c` | 2.2M | |

Plus `am_mp_arcade.c` (9.7M, the property), `am_mp_arcade_peds.c`,
`arcade_seating.c`, `apparcadebusiness.c`.

**They do not use render targets or scaleform for the screen.** The cabinets
draw with `DRAW_SPRITE` from streamed texture dictionaries. `grid_arcade_cabinet.c`
exposes the whole set: `MPArcadeCabinetGrid`, `MPArcadeCabinetGridHUD`,
`MPArcadeCabinetGridTiles`, and per-player sprites
`MPArcadeCabinetGridPlayerBlue` / `Green` / `Purple` / `Yellow`.

That means a cabinet game is: draw sprites each frame from a texture dict, read
controls, keep score. Very portable — the same approach works for any custom
minigame drawn over a screen prop.

### Correction on `VAULT_DRILL` / `VAULT_LASER`

These two are requested by nearly every arcade and heist script as **shared
boilerplate**, so grepping for them does not locate the drilling logic. The real
implementation lives in the casino heist scripts; treat the name as a pointer,
not a location.

## New minigames

- **`three_card_poker.c` (568K)** — a casino game missed entirely by the
  `casino_*` prefix sweep. Uses only `instructional_buttons`.
- **`word_hack.c` (80K)** — standalone word-based hacking minigame.
- **`circuitblockhack.c` (48K)** — standalone circuit-block hacking minigame,
  pairs with the `DLC_24-2/DLC_24-2_Circuit_Hack` audio bank.
- **`puzzle.c` (7.7M)** — large, boilerplate-heavy.

Both hack scripts are small and self-contained, unlike the heist versions buried
in 10 MB mission controllers. These are the ones to read.
