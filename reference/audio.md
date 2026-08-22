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


## Audio scene variables: the underused mechanism

Surveyed across `carsteal2.c`, `ob_jukebox.c`, `drunk_controller.c` and the race
scripts.

An audio scene is not just an on/off state. A scene can expose **named float
variables** that a script writes every frame, and the mix responds continuously:

    START_AUDIO_SCENE("CAR_2_HELI_FILTERING")
    SET_AUDIO_SCENE_VARIABLE("CAR_2_HELI_FILTERING", "HeliFiltering", GET_ENTITY_SPEED(veh))

Here the filtering on a helicopter chase is driven directly by the vehicle's speed.
Nothing is faded by a timer; the mix tracks a live value.

Confirmed variable names:

| Scene | Variable | Driven by |
|---|---|---|
| `CAR_2_HELI_FILTERING` | `HeliFiltering` | vehicle speed |
| `dlc_ch_arcade_music_volume` | `ArcadeRadioVolumeDucking` | distance and context |

The same idea appears without a named variable in `drunk_controller.c`, which scales
`SET_CAM_SHAKE_AMPLITUDE` and `SET_TIMECYCLE_MODIFIER_STRENGTH` from a drunkenness
value each frame. Camera shake amplitude and timecycle strength are both continuous
inputs, not switches.

That is the general pattern worth taking: **prefer a driven value over a triggered
state.** It is why the game's transitions feel analogue rather than stepped.

Other scenes seen: `RACES_SLIPSTREAM_SCENE`, `CAR_WASH_SCENE`, `ATM_PLAYER_SCENE`,
`TREVOR_SAFEHOUSE_ACTIVITIES_SCENE`, `FRANKLIN_SAFEHOUSE_ACTIVITIES_SCENE`,
`MP_CELEB_SCREEN_SCENE`, `dlc_aw_arena_speech_ducking_scene`,
`Ls_Car_Meet_Merch_Shop_Scene`, `CAR_3_GO_TO_GARAGE`.
