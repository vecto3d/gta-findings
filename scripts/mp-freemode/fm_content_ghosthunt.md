# fm_content_ghosthunt.c

MP freemode script. 1 anim dicts; 3 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 475,358 |
| Functions | 9,581 (109 unique, 9,472 shared) |
| Unique lines | 5,854 (1.2% of file) |

## Assets

**Animation dictionaries** (1) - `ANIM@SCRIPTED@FREEMODE@IG2_GHOST@`

**Audio banks** (4) - `DLC_24-1/GH_DM_01`, `DLC_25-1/DLC_25-1_GH_JN_01`, `DLC_26-1/DLC_26-1_GH_DW_01`, `DLC_MP2023_1/DLC_MP2023_1_GH`

**Sounds** (5) - `Collect_Shard`, `DLC_24-1_Ghost_Hunt_Sounds`, `DLC_25-1_Ghost_Hunt_Sounds`, `DLC_26-1_Ghost_Hunt_Sounds`, `Ghost_Hunt_Sounds`

**Particle effects** (3) - `scr_srr_hal`, `scr_srr_hal_ghost_haze`, `smoke`

**Hashed names** (16) - `m23_1_prop_m31_ghostrurmeth_01a`, `m23_1_prop_m31_ghostsalton_01a`, `m23_1_prop_m31_ghostskidrow_01a`, `m23_1_prop_m31_ghostzombie_01a`, `COLLECTABLE_GHOSTHUNT2024`, `COLLECTABLE_GHOSTHUNT2025`, `COLLECTABLE_GHOSTHUNT2026`, `COLLECTABLE_GHOSTHUNT`, `Ecto1Livery`, `GHOSTEXPOOUTFIT`, `GHOSTEXPOCAP`, `GHOSTEXPOREWARD26`, `m24_1_Prop_M41_Ghost_Dom_01a`, `m25_1_Prop_M51_GhostJay_01a`, `m26_1_Prop_M61_Ghost_Devin`, `m23_1_prop_m31_ghostjohnny_01a`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (68), `GET_HASH_KEY` (56), `GET_GAME_TIMER` (12), `PLAYER_PED_ID` (9), `REQUEST_SCRIPT_AUDIO_BANK` (8), `SET_ENTITY_LOCALLY_INVISIBLE` (5), `SET_BIT` (4), `GET_ENTITY_COORDS` (4), `NETWORK_EARN_COLLECTABLE_ITEM` (4), `NETWORK_EARN_COLLECTABLE_COMPLETED_COLLECTION` (4), `PLAY_SOUND_FRONTEND` (4), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (4), `PARTICIPANT_ID_TO_INT` (3), `IS_STRING_NULL_OR_EMPTY` (3), `PLAYER_ID` (3), `NETWORK_FADE_OUT_ENTITY` (3), `SET_ENTITY_LOCALLY_VISIBLE` (3), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (2), `NET_TO_ENT` (2), `IS_ENTITY_DEAD` (2), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (2), `IS_SYNCHRONIZED_SCENE_RUNNING` (2), `DOES_BLIP_EXIST` (2), `IS_MODEL_A_VEHICLE` (2), `NETWORK_HASH_FROM_PLAYER_HANDLE` (2), `NETWORK_IS_PARTICIPANT_ACTIVE` (2), `IS_PLAYER_PLAYING` (2), `NETWORK_GET_NUM_PARTICIPANTS` (2), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (2), `GET_RANDOM_INT_IN_RANGE` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.7f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `head`, `int`, `num`, `H24_GH_DB_STOP_MUSIC`, `H24_GH_STOP_MUSIC`, `bsa`, `sprt`, `hclr`, `scl`, `H24_GH_DB_START_MUSIC`, `H24_GH_START_MUSIC`, `rot`, `ibs`, `H24_GH_STOP_MUSIC_1S`, `blp`, `grp`, `veh`, `Ghost_Hunt_Sounds`, `MAX_NUM_TRANSITIONS`, `fmbs`, `crt`, `wpn`, `scen`

---

Source: `decompiled_scripts/fm_content_ghosthunt.c`
