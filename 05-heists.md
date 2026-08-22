# Heists

Part of the [GTA V decompiled script findings](README.md).

## Heist minigames — scaleform names

From `gb_data_hack.c`, `gb_casino_heist.c`, `fm_mission_controller_2020.c`:

- `VAULT_DRILL` — the drilling minigame.
- `VAULT_LASER` — laser cutting.
- `DIGITAL_SAFE_DISPLAY` — keypad / safe entry.
- `HACKING_MESSAGE` — hacking overlay.
- `SECURITY_CAM`, `DRONE_CAM` — camera feeds.
- `digiscanner` — scanner overlay.
- `POWER_PLAY_GENERIC`, `mp_mm_card_freemode`, `mp_matchmaking_card`.

These are the exact movies behind the vanilla heist minigames. Each needs its
`BEGIN_SCALEFORM_MOVIE_METHOD` call sequence traced before use.

## Heist planning boards

`heist_island_planning.c`, `kortz_planning.c`, `tuner_planning.c`,
`vehrob_planning.c`, plus `gb_casino_heist_planning.c` found earlier. Each drives
a corkboard interface for choosing approach and crew.
