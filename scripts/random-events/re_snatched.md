# re_snatched.c

Random events script. 1 developer state labels recovered; 2 anim dicts; 6 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 10,646 |
| Functions | 268 (58 unique, 210 shared) |
| Unique lines | 3,285 (30.9% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`Checking for warp`

## Assets

**Animation dictionaries** (2) - `random@kidnap_girl`, `RANDOM@KIDNAP_GIRL`

**Animations** (9) - `IG_1_ALT1_GIRL_IN_VAN_LOOP`, `IG_1_ALT1_EXIT_VAN`, `IG_1_GIRL_ON_PHONE_LOOP`, `IG_1_GUY1_IN_VAN_LOOP`, `IG_1_GUY2_IN_VAN_LOOP`, `IG_1_GIRL_DRAG_INTO_VAN`, `IG_1_GUY1_DRAG_INTO_VAN`, `IG_1_GUY2_DRAG_INTO_VAN`, `IG_1_ALT1_EXIT_VAN_BURR`

**Models and props** (6) - `prop_ld_test_01`, `IG_1_ALT1_EXIT_VAN`, `g_m_y_lost_01`, `g_m_y_lost_02`, `u_f_y_bikerchic`, `IG_1_ALT1_EXIT_VAN_CAM`

**Sounds** (2) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Speech contexts** (1) - `LostKidnapGirl`

**Text labels** (5) - `MICHAEL`, `FRANKLIN`, `TREVOR`, `NULL`, `RESNAAU`

**Scenarios** (3) - `WORLD_VEHICLE_PARK_PERPENDICULAR_NOSE_IN`, `WORLD_VEHICLE_DRIVE_SOLO`, `WORLD_HUMAN_SMOKING`

**Relationship groups** (2) - `re_snatched badGuys`, `re_snatched pedVictim`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (117), `IS_PED_INJURED` (73), `GET_ENTITY_COORDS` (64), `IS_VEHICLE_DRIVEABLE` (40), `DOES_BLIP_EXIST` (39), `GET_GAME_TIMER` (33), `DOES_ENTITY_EXIST` (31), `IS_PED_IN_ANY_VEHICLE` (28), `REMOVE_BLIP` (20), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (19), `GET_VEHICLE_PED_IS_IN` (19), `SET_PED_CONFIG_FLAG` (18), `SET_PED_COMBAT_ATTRIBUTES` (18), `VDIST2` (17), `VDIST` (16), `SET_PED_KEEP_TASK` (13), `IS_SYNCHRONIZED_SCENE_RUNNING` (13), `GIVE_WEAPON_TO_PED` (12), `PLAYER_ID` (11), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (11), `CLEAR_PED_TASKS` (11), `IS_ENTITY_OCCLUDED` (10), `TASK_VEHICLE_DRIVE_TO_COORD` (10), `IS_ENTITY_DEAD` (10), `IS_ENTITY_AT_ENTITY` (9), `GET_SYNCHRONIZED_SCENE_PHASE` (9), `SET_ENTITY_INVINCIBLE` (9), `REQUEST_MODEL` (9), `HAS_MODEL_LOADED` (9), `FREEZE_ENTITY_POSITION` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`9.361914f` x4 · `442.6952f` x4 · `-3055.088f` x4 · `0.4f` x4 · `0.75f` x3 · `2.5f` x3 · `-1133.993f` x3 · `558.3267f` x3 · `107.351f` x3 · `1.25f` x2 · `-2.5f` x2 · `7.25f` x2 · `25.25f` x2 · `104.0503f` x2 · `560.4913f` x2 · `-1126.376f` x2 · `5.75f` x2 · `19.25f` x2 · `39.75f` x2 · `0.421191f` x2 · `-1.99042f` x2 · `0.20134f` x2 · `174.612f` x2 · `-1116.946f` x1

## Other strings

Literals whose consuming native was not classified:

`RESNA_B4`, `player`, `RESNA_MOR`, `RESNA_B3D`, `RESNA_B2`, `RESNA_B5`, `RESNA_B6`, `RESNA_B3B`, `RESNA_B3C`, `RESNA_B5b`, `LostKidnapper`, `LostKidnapGirl`, `RESNA_BANT`, `chassis`, `gburrito`, `daemon`, `RE_SN`, `RESNA_LOST`, `DRAG_INTO_VAN_BURR`, `RESNA_HELP`, `vehicle_weapon_tank`, `RESNA_THX3`, `CamPushInNeutral`, `RESNA_FINGER`, `RESNA_ARRV`, `AC_STOP`, `RESNA_JACK`, `RESNA_HOME`, `RESNA_RESP`, `RESNA_ADD`

---

Source: `decompiled_scripts/re_snatched.c`
