# fm_content_hacker_cargo_finale.c

Minigames script. 2 anim dicts; 11 models; 1 particle effects.

| | |
|---|---|
| Category | Minigames |
| Total lines | 515,970 |
| Functions | 10,865 (492 unique, 10,373 shared) |
| Unique lines | 13,712 (2.7% of file) |

## Assets

**Animation dictionaries** (2) - `anim@scripted@freemode@ig5_underwater_bomb@female@`, `anim@scripted@freemode@ig5_underwater_bomb@male@`

**Models and props** (11) - `prop_amb_phone`, `s_m_m_ciasec_01`, `prop_contr_03b_ld`, `prop_box_wood01a`, `prop_barrel_float_2`, `prop_box_wood03a`, `prop_air_cargo_01a`, `prop_air_cargo_04a`, `prop_container_03mb`, `prop_rub_cont_01b`, `sm_prop_smug_cont_01a`

**Sounds** (7) - `Sonar_Pulse_No_Target`, `dlc_hei4_hidden_collectibles_sonar_locator_sounds`, `TimeRemaining`, `Background`, `MP_CCTV_SOUNDSET`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`

**Particle effects** (1) - `scr_xm_submarine`

**Text labels** (2) - `M4RSH4LL`, `EXTRASUNNY`

**Timecycle modifiers** (2) - `MissileOutOfRange`, `CAMERA_secuirity`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (97), `SET_PED_COMBAT_ATTRIBUTES` (30), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (23), `NET_TO_ENT` (21), `SET_ENTITY_INVINCIBLE` (18), `SET_PED_CONFIG_FLAG` (18), `GET_ENTITY_COORDS` (16), `FREEZE_ENTITY_POSITION` (16), `DISABLE_CONTROL_ACTION` (14), `SET_BIT` (14), `NETWORK_FADE_IN_ENTITY` (12), `SET_ENTITY_VISIBLE` (11), `DOES_ENTITY_EXIST` (9), `SET_ENTITY_SHOULD_FREEZE_WAITING_ON_COLLISION` (9), `GET_ENTITY_BONE_INDEX_BY_NAME` (8), `IS_STRING_NULL_OR_EMPTY` (8), `SET_VEHICLE_DOORS_LOCKED_FOR_ALL_PLAYERS` (8), `CLEAR_PED_TASKS` (7), `IS_NEW_LOAD_SCENE_ACTIVE` (7), `NEW_LOAD_SCENE_STOP` (7), `SET_PED_COMPONENT_VARIATION` (7), `GET_DISTANCE_BETWEEN_COORDS` (6), `GET_ENTITY_MODEL` (6), `SET_VEHICLE_ON_GROUND_PROPERLY` (6), `SET_VEHICLE_ENGINE_ON` (6), `ACTIVATE_PHYSICS` (6), `SET_ENTITY_DYNAMIC` (6), `SET_ENTITY_HEALTH` (6), `NEW_LOAD_SCENE_START_SPHERE` (5), `IS_NEW_LOAD_SCENE_LOADED` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.3f` x2 · `0.1f` x2 · `0.03f` x2 · `91.28709f` x2 · `286.5989f` x1 · `3866.233f` x1 · `30.3402f` x1 · `13.2f` x1 · `0.99f` x1 · `-3.5f` x1 · `0.7f` x1 · `0.5f` x1 · `0.393f` x1 · `0.11f` x1 · `18.5f` x1 · `0.4f` x1 · `-539.0534f` x1 · `4407.771f` x1 · `28.52234f` x1 · `-536.4273f` x1 · `4434.892f` x1 · `34.47235f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `typ`, `sprt`, `hclr`, `scl`, `bsa`, `ibs`, `Hacker_CargoPlane_0`, `blp`, `veh`, `rot`, `rad`, `MP242_MED_INTENSITY`, `exhaust`, `exhaust_3`, `exhaust_2`, `MAX_NUM_SCENARIOS`, `grp`, `buzzard`, `exhaust_4`, `HCF_BL_9`, `X24_JODI`, `X24_PAVEL`

---

Source: `decompiled_scripts/fm_content_hacker_cargo_finale.c`
