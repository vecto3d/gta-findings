# fm_content_ufo_abduction.c

MP freemode script. 9 anim dicts; 3 models; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 502,327 |
| Functions | 10,100 (233 unique, 9,867 shared) |
| Unique lines | 7,458 (1.5% of file) |

## Assets

**Animation dictionaries** (9) - `anim@fidgets@coughs`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@heist@ig2_hand_lever@heeled@`, `anim@scripted@heist@ig2_hand_lever@male@`, `anim@scripted@player@mission@trn_ig1_loot_v2@heeled@`, `anim@scripted@player@mission@trn_ig1_loot_v2@male@`, `creatures@cat@amb@world_cat_sleeping_ground@idle_a`, `anim@scripted@freemode@alien_ig_bed@male@`, `get_up@standard`

**Animations** (2) - `get_up@standard`, `front`

**Models and props** (3) - `prop_idol_case_02`, `m23_1_prop_m31_lamp_ceiling_03a`, `w_me_crowbar`

**Audio banks** (2) - `DLC_CM2022/CM2022_GENERIC_01`, `DLC_HEIST3/CASINO_HEIST_FINALE_GENERAL_01`

**Sounds** (9) - `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`, `Abduction_Soundset`, `Fake_Close`, `Union_Depository_Elevator_Sounds`, `dlc_ch_heist_finale_poison_gas_coughs_sounds`, `Wrong_Final`, `Wrong`, `Correct`

**Particle effects** (2) - `scr_bh_hal`, `scr_bh_hal_poison_gas`

**Texture dicts** (1) - `ROOM_01`

**Text labels** (4) - `NULL`, `WEAPON_UNLOCK`, `OPENING`, `OPENED`

**Hashed names** (1) - `BONEMASK_UPPERONLY`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (80), `SET_PED_COMPONENT_VARIATION` (12), `DISABLE_CONTROL_ACTION` (11), `IS_STRING_NULL_OR_EMPTY` (10), `NET_TO_ENT` (9), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `SET_BIT` (6), `GET_RANDOM_INT_IN_RANGE` (6), `CLEAR_PED_TASKS` (6), `IS_ENTITY_PLAYING_ANIM` (5), `DOES_ENTITY_EXIST` (5), `NET_TO_OBJ` (4), `IS_PAUSE_MENU_ACTIVE` (4), `IS_ENTITY_IN_ANGLED_AREA` (4), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (4), `REQUEST_SCRIPT_AUDIO_BANK` (4), `TASK_PLAY_ANIM` (4), `CREATE_MODEL_SWAP` (4), `NETWORK_IS_PARTICIPANT_ACTIVE` (3), `GET_CLOUD_TIME_AS_INT` (3), `GET_ENTITY_COORDS` (3), `PLAYER_PED_ID` (3), `OBJ_TO_NET` (3), `GET_ENTITY_ANIM_CURRENT_TIME` (3), `CLEAR_HELP` (3), `HIDE_HUD_AND_RADAR_THIS_FRAME` (3), `IS_PED_RAGDOLL` (3), `PLAY_SOUND_FROM_ENTITY` (3), `FORCE_ROOM_FOR_ENTITY` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x8 · `-100.6458f` x4 · `-98.64577f` x2 · `0.25f` x2 · `0.125f` x2 · `3753.232f` x2 · `-99.496f` x2 · `-1900.087f` x2 · `3745.655f` x2 · `-100.646f` x2 · `-1878.442f` x1 · `3749.887f` x1 · `-1919.265f` x1 · `3749.804f` x1 · `-97.14577f` x1 · `5.5f` x1 · `-1896.798f` x1 · `3738.413f` x1 · `-99.0182f` x1 · `-1897.411f` x1 · `3749.702f` x1 · `-96.89532f` x1 · `0.3f` x1 · `0.75f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `head`, `int`, `num`, `rot`, `ibs`, `name`, `bsa`, `typ`, `BTLOC_HT_ROOM`, `MAX_NUM_SCENARIOS`, `grp`, `veh`, `sprt`, `hclr`, `scl`, `MAX_NUM_TRANSITIONS`, `blp`, `fcs`, `fmbs`, `crt`, `wpn`, `scen`, `anim`, `asi`

---

Source: `decompiled_scripts/fm_content_ufo_abduction.c`
