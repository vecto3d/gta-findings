# gb_biker_stand_your_ground.c

MP gang ops script. 5 models; 2 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 482,853 |
| Functions | 8,678 (104 unique, 8,574 shared) |
| Unique lines | 17,923 (3.7% of file) |

## Assets

**Models and props** (5) - `prop_conc_sacks_02a`, `prop_rub_table_02`, `prop_paint_stepl02`, `prop_radio_01`, `prop_flare_01`

**Sounds** (5) - `DLC_Biker_SYG_Sounds`, `Intensity`, `Enemy_In_Zone`, `Enter_Zone`, `Leave_Zone`

**Particle effects** (2) - `scr_finders_flare`, `scr_finders_package_flare`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (36), `TO_FLOAT` (13), `PARTICIPANT_ID` (9), `DOES_PARTICLE_FX_LOOPED_EXIST` (9), `PARTICIPANT_ID_TO_INT` (7), `SET_BIT` (7), `DOES_ENTITY_EXIST` (7), `PLAYER_PED_ID` (7), `GET_PLAYER_PED` (6), `CLEAR_BIT` (5), `DOES_BLIP_EXIST` (4), `SET_AUDIO_FLAG` (4), `CLEAR_HELP` (4), `PLAY_SOUND_FRONTEND` (4), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (3), `VDIST` (3), `GET_PED_INDEX_FROM_ENTITY_INDEX` (3), `HAS_SOUND_FINISHED` (3), `SET_PLAYER_HEALTH_RECHARGE_MULTIPLIER` (3), `SET_PLAYER_HEALTH_RECHARGE_MAX_PERCENT` (3), `SET_PLAYER_WEAPON_DAMAGE_MODIFIER` (3), `SET_PLAYER_WEAPON_DEFENSE_MODIFIER` (3), `SET_VARIABLE_ON_SOUND` (3), `GET_ENTITY_COORDS` (3), `SET_PARTICLE_FX_LOOPED_COLOUR` (3), `SET_RADAR_ZOOM_PRECISE` (3), `GET_BLIP_COLOUR` (2), `SET_BLIP_PRIORITY` (2), `SET_BLIP_NAME_FROM_TEXT_FILE` (2), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x2 · `0.1f` x2

## Other strings

Literals whose consuming native was not classified:

`SYG_AREA`, `SYG_ST_MODE`, `SYG_GT_DKILL`, `SYG_GT_DDEF`, `SYG_GT_DGOTO`, `SYG_GT_EXVEH`, `SYG_GT_RCAP`, `DisableFlightMusic`, `WantedMusicDisabled`, `SYG_BLIP`, `BIKER_MP_MUSIC_STOP`, `GB_WINNER`, `SYG_BAC`, `CLUB_WORK_END`, `SYG_GOTOTIMER`, `SYG_DEF`, `SYG_CAP`, `SYG_BA`, `SYG_HELP_DI`, `SYG_HELP_AI`, `SYG_HELP_DC`, `SYG_HELP_AC`, `SYG_HELP_EXVEH`, `SYG_HELP_DSD`, `SYG_HELP_ASD`, `SYG_HELP_DDB`, `SYG_HELP_ADB`, `BIKER_SYG_START`, `BIKER_SYG_ATTACKED`, `BIKER_SYG_CALM`

---

Source: `decompiled_scripts/gb_biker_stand_your_ground.c`
