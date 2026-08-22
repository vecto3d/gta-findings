# fm_content_hacker_zancudo_fin.c

Minigames script. 9 anim dicts; 10 models; 2 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 520,806 |
| Functions | 10,623 (312 unique, 10,311 shared) |
| Unique lines | 11,433 (2.2% of file) |

## Assets

**Animation dictionaries** (9) - `ANIM@SCRIPTED@HEIST@IG3_BUTTON_PRESS@MALE@`, `anim@heists@humane_labs@emp@hack_door`, `anim@heists@chicken_heist@ig_5_guard_wave_in`, `anim@door_trans@elevator@`, `anim@scripted@player@mission@tunf_uni_ig1_elevator_pass_p1@heeled@`, `anim@scripted@player@mission@tunf_uni_ig1_elevator_pass_p1@male@`, `anim@heists@keycard@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`

**Models and props** (10) - `w_vehicle_weapon_kinetic_pulse_sounds`, `prop_workwall_02`, `prop_air_generator_03`, `prop_weeds_nxg02`, `prop_weeds_nxg04`, `s_m_m_marine_01`, `s_m_y_marine_01`, `s_m_m_marine_02`, `s_m_y_armymech_01`, `s_m_y_marine_03`

**Audio banks** (3) - `SCRIPT/ALARM_KLAXON_05`, `DLC_24-2/DLC_24-2_Zancudo_Finale`, `DLC_MPHEIST/HEIST_USE_KEYPAD`

**Particle effects** (2) - `scr_hr_rob_fort`, `scr_hr_rob_kinetic_pulse`

**Text labels** (6) - `22GAR176`, `46FKU714`, `27HVE813`, `M4RSH4LL`, `EXTRASUNNY`, `88FLK820`

**Scripts launched** (1) - `word_hack`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (114), `PLAYER_PED_ID` (52), `GET_GAME_TIMER` (40), `DISABLE_CONTROL_ACTION` (20), `GET_ENTITY_COORDS` (19), `SET_BIT` (18), `DOES_ENTITY_EXIST` (18), `IS_ENTITY_DEAD` (17), `IS_ENTITY_AT_COORD` (16), `SET_PED_COMPONENT_VARIATION` (16), `PLAYER_ID` (14), `GET_DISTANCE_BETWEEN_COORDS` (11), `CREATE_MODEL_HIDE` (10), `REMOVE_MODEL_HIDE` (10), `SET_PED_CONFIG_FLAG` (9), `GET_RANDOM_INT_IN_RANGE` (8), `SET_PED_PROP_INDEX` (7), `SET_CURRENT_PED_WEAPON` (6), `IS_CONTROL_PRESSED` (6), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (6), `CLEAR_PED_TASKS` (5), `ADD_EXPLOSION` (5), `IS_ENTITY_ON_SCREEN` (5), `GET_PLAYER_WANTED_LEVEL` (5), `HIDE_HUD_COMPONENT_THIS_FRAME` (4), `SET_ENTITY_PROOFS` (4), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (4), `SET_PED_COMBAT_ATTRIBUTES` (4), `IS_ENTITY_PLAYING_ANIM` (4), `GET_ENTITY_ANIM_CURRENT_TIME` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`31.8418f` x6 · `1.5f` x6 · `5.5f` x4 · `5922.044f` x4 · `-155.605f` x4 · `-1807.283f` x2 · `3099.239f` x2 · `33.1869f` x2 · `-1812.625f` x2 · `3101.556f` x2 · `8.5f` x2 · `0.5f` x2 · `525.9183f` x2 · `5914.004f` x2 · `-159.0749f` x2 · `-1582.326f` x2 · `2793.237f` x2 · `15.8416f` x2 · `-1812.777f` x2 · `3103.274f` x2 · `33.041f` x2 · `583.788f` x2 · `5953.587f` x2 · `-158.03f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `typ`, `ibs`, `sprt`, `hclr`, `scl`, `Klaxon_05`, `ALARMS_SOUNDSET`, `rot`, `bsa`, `rad`, `HZF_PROMPT3`, `HZF_OBJ5`, `HZF_OBJ5b`, `blp`, `veh`, `HZF_OBJ1`, `HZF_OBJ7`, `MAX_NUM_SCENARIOS`, `grp`, `DLC_24-2_Zancudo_Finale_Sounds`, `HZF_SHARD1`, `PORT_OF_LS_HEIST_FORT_ZANCUDO_ALARMS`

---

Source: `decompiled_scripts/fm_content_hacker_zancudo_fin.c`
