# Races

**Source:** `fm_race_controler.c` (15M), plus `country_race.c`,
`offroad_races.c`, `stunt_plane_races.c`, `mission_race.c`, `mg_race_to_point.c`,
`triathlonsp.c`

**The checkpoint and timing system uses plain natives and ports directly.**

- `CREATE_CHECKPOINT` with `SET_CHECKPOINT_RGBA` and **`SET_CHECKPOINT_DIRECTION`**
  — the arrow pointing at the next checkpoint, 18 call sites
- Blips: `SET_BLIP_SPRITE`, `SET_BLIP_SCALE`, `SET_BLIP_PRIORITY`,
  `SET_BLIP_ROUTE`, `SET_BLIP_DISPLAY`, `SET_BLIP_NAME_FROM_TEXT_FILE`
- Timing is plain `GET_GAME_TIMER` deltas — 125 call sites, no special natives

## Scaleforms

`COUNTDOWN`, `DRAG_RACE`, `MP_CELEBRATION` with separate `_BG` and `_FG` movies,
`OPEN_WHEEL_HEALTH_INDICATOR`, `BLIMP_TEXT`, `SAVING_FOOTER`.

`MP_CELEBRATION` is the vanilla end-of-race results sequence and is reusable for
any job payout screen. Driver script is `celebrations.c` (9.1M), with
`celebration_editor.c` alongside it.

## Variants

`mg_race_to_point.c` is the simplest form — a single point-to-point dash.
Bike and quad racing anims are `mini@racing@bike@` and `mini@racing@quad@`
(`offroad_races.c`).
