# Audio

## Sound sets, by call count

| Sound set | Uses |
|---|---|
| `HUD_FRONTEND_DEFAULT_SOUNDSET` | 6499 |
| `GTAO_Script_Doors_Faded_Screen_Sounds` | 4497 |
| `dlc_xm_facility_entry_exit_sounds` | 2482 |
| `GTAO_Vision_Modes_SoundSet` | 1894 |
| `WEB_NAVIGATION_SOUNDS_PHONE` | 1137 |
| `MP_PROPERTIES_ELEVATOR_DOORS` | 592 |
| `HUD_FREEMODE_SOUNDSET` | 490 |
| `HintCamSounds` | 469 |
| `GTAO_FM_Events_Soundset` | 427 |
| `HUD_MINI_GAME_SOUNDSET` | 304 |
| `PLAYER_SWITCH_CUSTOM_SOUNDSET` | 260 |
| `MP_MISSION_COUNTDOWN_SOUNDSET` | 240 |
| `MP_SNACKS_SOUNDSET` | 216 |
| `MP_CCTV_SOUNDSET` | 214 |
| `HUD_AWARDS` | 178 |
| `WastedSounds` | 156 |

`HUD_MINI_GAME_SOUNDSET` and `MP_MISSION_COUNTDOWN_SOUNDSET` are the ones to
reach for when building an activity.

## Audio banks

Load with `REQUEST_AMBIENT_AUDIO_BANK` or `REQUEST_SCRIPT_AUDIO_BANK` before the
mechanic runs, or it is silent.

**Minigames:** `DLC_MPHEIST\HEIST_FLEECA_DRILL` and `_DRILL_2`,
`DLC_HEIST3\HEIST_FINALE_LASER_DRILL`, `DLC_MPHEIST/HEIST_HACK_SNAKE`,
`DLC_MPHEIST/HEIST_USE_KEYPAD`, `DLC_HEIST3/Door_Hacking`,
`DLC_24-2/DLC_24-2_Circuit_Hack`, `DLC_CHRISTMAS2017/XM_Silo_Laser_Hack`,
`SAFE_CRACK`.

**Activities:** `VENDING_MACHINE`, `SAFEHOUSE_FRANKLIN_USE_BONG`,
`SAFEHOUSE_MICHAEL_SIT_SOFA`, `SAFEHOUSE_TREVOR_DRINK_WHISKEY`,
`VEHICLE_SHOP_HUD_1` / `_2`, `DLC_GTAO/SNACKS`, `TIME_LAPSE`, `HUD_321_GO`,
`SCRIPT\LIFTS`.

**Most-requested overall:** `DLC_CHRISTMAS2017/XM_FACILITY_ENTRY_EXIT` (749),
`DLC_25-2/DLC_25-2_Freemode` (252), `DLC_HEI4/DLC_HEI4_Submarine` (250).

## Speech contexts

`BOUNCER_EJECT_GENERIC` (745 — the most-used speech line in the repo),
`GENERIC_SHOCKED_HIGH`, `GENERIC_CURSE_MED`, `GENERIC_FRIGHTENED_MED`,
`GENERIC_HI`, `BUMP`, `CHAT_STATE`, `KIFFLOM_GREET`, `ARENA_ANNOUNCE1`,
plus the `SHOP_*` family listed in [shops.md](../features/shops.md).
