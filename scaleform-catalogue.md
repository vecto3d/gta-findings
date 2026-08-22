# Scaleform catalogue

## Reusable, seen across many scripts

`instructional_buttons`, `GENERIC_INSTRUCTIONAL_BUTTONS`,
`MP_BIG_MESSAGE_FREEMODE`, `MIDSIZED_MESSAGE`, `SC_LEADERBOARD`, `COUNTDOWN`,
`MP_MEDAL_FREEMODE`, `BREAKING_NEWS`, `SOCIAL_CLUB_TV`, `MP_SPECTATOR_CARD`,
`MP_SPECTATOR_OVERLAY`, `mp_matchmaking_card`, `mp_mm_card_freemode`,
`MP_MISSION_DETAILS_CARD`, `MP_MENU_GLARE`, `SPLASH_TEXT`, `TEXTFIELD`.

## How to find unique ones

Counting every `REQUEST_SCALEFORM_MOVIE` and keeping names used three times or
fewer isolates the one-off systems, because boilerplate appears in dozens of
files:

    grep -ohE 'REQUEST_SCALEFORM_MOVIE\("[^"]+"' *.c \
      | sed 's/.*("//;s/"//' | sort | uniq -c | sort -n | awk '$1<=3'

## Unique scaleforms, mapped to their script

| Scaleform | Script |
|---|---|
| `ATM` | `atm_trigger.c` |
| `LETTER_SCRAPS` | `letterscraps.c` |
| `SLOT_MACHINE` | `casino_slots.c` |
| `taxi_display` | `taxiservice.c` |
| `TAXI_HAIL` | `am_taxi.c` |
| `AXE_OF_FURY` | `am_mp_arcade_strength_test.c` |
| `darts_scoreboard`, `DARTS_SCOREBOARD_BIKER` | `darts.c` |
| `golf`, `golf_floating_ui` | `golf.c` |
| `yoga_buttons`, `yoga_keys` | `yoga.c` |
| `mission_complete` | `minigame_stats_tracker.c` |
| `PLAYER_SWITCH`, `PLAYER_SWITCH_STATS_PANEL`, `PLAYER_SWITCH_PROLOGUE` | `selector.c` |
| `remote_sniper_hud`, `REMOTE_SNIPER_LOADING` | `martin1.c` |
| `PSYCHOLOGY_REPORT` | `shrinkletter.c` |
| `dont_cross_the_line` | `dont_cross_the_line.c` |
| `DIGITAL_CAMERA` | `maintransition.c` |
| `camera_gallery` | all `*_creator.c` — the snapmatic gallery |
| `p_bubblegum` | `scaleformminigametest.c` — minimal example |

## Property and sign scaleforms

`CLUBHOUSE_NAME`, `ORGANISATION_NAME`, `AUTO_SHOP_CREW_NAME`,
`BIKER_MISSION_WALL`, `ARENA_CAREER_WALL`, `YACHT_GAMERNAME`,
`ORBITAL_CANNON_CAM`, `PARTY_BUS`, `graphic_design`, `font_lib_web`,
`POWER_PLAY_*` (turf, vehicle, biker, day_night, special_races).
