# Audio

Part of the [GTA V decompiled script findings](README.md).

## Audio

### Sound sets, by call count

`HUD_FRONTEND_DEFAULT_SOUNDSET` (6499), `GTAO_Script_Doors_Faded_Screen_Sounds`
(4497), `dlc_xm_facility_entry_exit_sounds` (2482), `GTAO_Vision_Modes_SoundSet`
(1894), `WEB_NAVIGATION_SOUNDS_PHONE` (1137), `MP_PROPERTIES_ELEVATOR_DOORS`
(592), `HUD_FREEMODE_SOUNDSET` (490), `HintCamSounds` (469),
`GTAO_FM_Events_Soundset` (427), `HUD_MINI_GAME_SOUNDSET` (304),
`PLAYER_SWITCH_CUSTOM_SOUNDSET` (260), `MP_MISSION_COUNTDOWN_SOUNDSET` (240),
`MP_SNACKS_SOUNDSET` (216), `MP_CCTV_SOUNDSET` (214), `HUD_AWARDS` (178),
`WastedSounds` (156).

`HUD_MINI_GAME_SOUNDSET` and `MP_MISSION_COUNTDOWN_SOUNDSET` are the ones to
reach for when building an activity.

### Minigame audio banks

Load these before a minigame or the sounds are silent:

- `DLC_MPHEIST\HEIST_FLEECA_DRILL` and `_DRILL_2` — drilling
- `DLC_HEIST3\HEIST_FINALE_LASER_DRILL` — laser drill
- `DLC_MPHEIST/HEIST_HACK_SNAKE` — the snake hacking minigame
- `DLC_MPHEIST/HEIST_USE_KEYPAD` — keypad
- `DLC_HEIST3/Door_Hacking` — door hack
- `DLC_24-2/DLC_24-2_Circuit_Hack` — circuit hack
- `DLC_CHRISTMAS2017/XM_Silo_Laser_Hack` — silo laser
- `SAFE_CRACK` — pairs with the `mini@safe_cracking` anims
- `SAFEHOUSE_FRANKLIN_USE_BONG`, `SAFEHOUSE_MICHAEL_SIT_SOFA`,
  `SAFEHOUSE_TREVOR_DRINK_WHISKEY` — the safehouse activities
- `VEHICLE_SHOP_HUD_1` / `_2`, `DLC_GTAO/SNACKS`, `TIME_LAPSE`, `HUD_321_GO`
