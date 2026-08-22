# minute2.c

SP strangers and freaks script. 6 anim dicts; 14 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 55,101 |
| Functions | 597 (68 unique, 529 shared) |
| Unique lines | 6,577 (11.9% of file) |

## Assets

**Animation dictionaries** (6) - `MOVE_M@BAIL_BOND_NOT_TAZERED`, `MOVE_M@BAIL_BOND_TAZERED`, `rcmminute2`, `rcmminute2lean`, `missminuteman_2ig_1`, `missminuteman_2ig_3`

**Animations** (19) - `rcmminute2`, `arrest_walk`, `missminuteman_2ig_1`, `kneeling_arrest_get_up`, `entertrunk_josef`, `kneeling_arrest_idle`, `missminuteman_2ig_3`, `handsup_exit`, `entertrunk_manuel`, `rcmminute2lean`, `passport_josef`, `trunk_manuel`, `trunk_josef`, `exit`, `intro_90_r`, `loop_90_r`, `outro_90_r`, `idle_c`, `passport_manuel`

**Models and props** (14) - `s_m_m_migrant_01`, `sanchez`, `s_m_m_gaffer_01`, `pranger`, `prop_passport_01`, `blazer`, `speedo`, `ig_josef`, `ig_joeminuteman`, `prop_facgate_03_l`, `prop_facgate_03_ld_l`, `prop_fnclink_06gate3`, `p_amb_phone_01`, `s_m_y_construct_01`

**Sounds** (3) - `MINUTE_02_SCENE`, `PASSPORT`, `MINUTE_02_SOUNDSET`

**Text labels** (8) - `MIN2AU`, `MANUEL`, `IMMIGRANTMALE`, `JOSEF`, `NULL`, `TREVOR`, `JOE`, `MIN2`

**Scenarios** (3) - `WORLD_VEHICLE_DRIVE_SOLO`, `WORLD_VEHICLE_CONSTRUCTION_SOLO`, `WORLD_VEHICLE_CONSTRUCTION_PASSENGERS`

**Waypoint recordings** (3) - `Min2_Bike02`, `Min2_Traffic01`, `Min2_Traffic02`

**Vehicle recordings** (3) - `Min2DB1`, `Min2DB2`, `Min2Rolling`

**Doors** (3) - `prop_facgate_03_l`, `prop_facgate_03_ld_l`, `prop_fnclink_06gate3`

**Vehicle mods** (3) - `pranger`, `sanchez`, `blazer`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (205), `GET_SCRIPT_TASK_STATUS` (153), `IS_PED_IN_VEHICLE` (148), `GET_GAME_TIMER` (109), `IS_PED_IN_ANY_VEHICLE` (46), `DOES_BLIP_EXIST` (37), `TASK_ENTER_VEHICLE` (32), `CLEAR_PED_TASKS` (26), `DOES_ENTITY_EXIST` (25), `SET_PED_COMBAT_ATTRIBUTES` (25), `CLEAR_SEQUENCE_TASK` (24), `SET_PED_COMPONENT_VARIATION` (22), `SET_PED_CONFIG_FLAG` (22), `SET_MODEL_AS_NO_LONGER_NEEDED` (21), `GET_ENTITY_SPEED` (21), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (20), `IS_PED_RAGDOLL` (20), `TASK_PLAY_ANIM` (18), `SET_BLIP_SCALE` (17), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (14), `IS_SYNCHRONIZED_SCENE_RUNNING` (14), `IS_ENTITY_PLAYING_ANIM` (14), `PROCESS_ENTITY_ATTACHMENTS` (14), `IS_PED_SITTING_IN_VEHICLE` (13), `TASK_VEHICLE_DRIVE_TO_COORD` (13), `TASK_SYNCHRONIZED_SCENE` (13), `GET_RANDOM_INT_IN_RANGE` (12), `HAS_ENTITY_BEEN_DAMAGED_BY_WEAPON` (12), `SET_ENTITY_HEALTH` (12), `CREATE_SYNCHRONIZED_SCENE` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x19 · `0.7f` x10 · `267.2497f` x9 · `2852.167f` x9 · `42.6129f` x9 · `1.4f` x7 · `0.1f` x6 · `0.25f` x5 · `-1.8f` x5 · `-0.2f` x5 · `43.747f` x4 · `4214.055f` x4 · `-199.286f` x4 · `1.2f` x3 · `21.25f` x3 · `-4.5f` x3 · `2.5f` x3 · `1.5f` x3 · `42.6421f` x3 · `1.6f` x3 · `0.54f` x2 · `4.5f` x2 · `0.3f` x2 · `263.6694f` x2

## Other strings

Literals whose consuming native was not classified:

`pranger`, `blazer`, `DisableAbortConversationForRagdoll`, `MIN2_31`, `seat_pside_r`, `MIN2_29`, `MIN2_06`, `MIN2_19`, `IMMIGRANTMALE2`, `MIN2_01`, `MIN2_33`, `FIRING_PATTERN_FULL_AUTO`, `sanchez`, `MIN2_48`, `MIN2_49`, `MIN2_32`, `MIN2_CAR`, `MIN2_43`, `empty`, `Josef`, `MMB_Parked_car`, `MIN2_17`, `MIN2_JJ8`, `MIN2_47`, `MIN2_COPS`, `MIN2_STUN`, `MIN2_JJ4`, `MIN2_35`, `MIN2_23`, `speedo`

---

Source: `decompiled_scripts/minute2.c`
