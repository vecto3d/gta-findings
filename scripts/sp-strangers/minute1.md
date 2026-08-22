# minute1.c

SP strangers and freaks script. 5 anim dicts; 6 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 60,198 |
| Functions | 751 (104 unique, 647 shared) |
| Unique lines | 3,696 (6.1% of file) |

## Assets

**Animation dictionaries** (5) - `MOVE_M@BAIL_BOND_NOT_TAZERED`, `MOVE_M@BAIL_BOND_TAZERED`, `missminuteman_1ig_1`, `move_m@drunk@verydrunk`, `missminuteman_1ig_2`

**Animations** (15) - `missminuteman_1ig_1`, `missminuteman_1ig_2`, `handsup_base`, `tasered_1`, `tasered_2`, `base_drunk_mariachi_01`, `idle_sing_1_mariachi_01`, `idle_sing_2_mariachi_01`, `idle_tequila_mariachi_01`, `idle_waive_mariachi_01`, `base_drunk_mariachi_02`, `idle_sing_1_mariachi_02`, `idle_sing_2_mariachi_02`, `idle_tequila_mariachi_02`, `idle_waive_mariachi_02`

**Models and props** (6) - `prop_fnc_farm_01e`, `prop_fnclink_01d`, `prop_sign_road_03a`, `ig_janet`, `s_m_m_mariachi_01`, `a_m_m_hillbilly_01`

**Sounds** (3) - `MINUTE_01_SCENE`, `STUN_COLLECT`, `MINUTE_MAN_01_SOUNDSET`

**Text labels** (11) - `MIN1AUD`, `NULL`, `JOE`, `JOSEF`, `MARIACHI1`, `MARIACHI2`, `JANET`, `MIN1DRUNKMALE`, `TREVOR`, `MIN1`, `MARIACHI`

**Vehicle recordings** (2) - `Min1_Van`, `Min1_PV`

**Stats** (30) - `sp0_weap_addon_unlock_6`, `sp2_weap_addon_unlock_6`, `sp2_weap_addon_unlock_4`, `sp1_weap_addon_unlock_6`, `sp0_weap_addon_unlock_0`, `sp1_weap_addon_unlock_0`, `sp2_weap_addon_unlock_0`, `sp0_weap_addon_unlock_1`, `sp1_weap_addon_unlock_1`, `sp2_weap_addon_unlock_1`, `sp0_weap_addon_unlock_2`, `sp1_weap_addon_unlock_2`, `sp2_weap_addon_unlock_2`, `sp0_weap_addon_unlock_3`, `sp1_weap_addon_unlock_3`, `sp2_weap_addon_unlock_3`, `sp0_weap_addon_unlock_4`, `sp1_weap_addon_unlock_4`, `sp0_weap_addon_unlock_5`, `sp1_weap_addon_unlock_5`, `sp2_weap_addon_unlock_5`, `sp2_weap_unlock_0`, `sp0_weap_unlock_1`, `sp1_weap_unlock_1`, `sp2_weap_unlock_1`, `sp1_weap_unlock_2`, `sp2_weap_unlock_2`, `sp0_weap_unlock_2`, `sp0_weap_unlock_0`, `sp1_weap_unlock_0`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (91), `GET_GAME_TIMER` (43), `STAT_SET_INT` (30), `STAT_GET_INT` (21), `SET_PED_CONFIG_FLAG` (19), `DOES_ENTITY_EXIST` (17), `IS_PED_IN_VEHICLE` (16), `TASK_PLAY_ANIM` (13), `IS_VEHICLE_TYRE_BURST` (12), `ARE_STRINGS_EQUAL` (11), `SET_PLAYBACK_SPEED` (11), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (10), `SET_ENTITY_AS_MISSION_ENTITY` (9), `REPLAY_RECORD_BACK_FOR_TIME` (9), `REGISTER_ENTITY_FOR_CUTSCENE` (8), `PLAYER_ID` (8), `CLEAR_PRINTS` (8), `SET_MODEL_AS_NO_LONGER_NEEDED` (8), `GET_ENTITY_INDEX_OF_REGISTERED_ENTITY` (8), `DOES_BLIP_EXIST` (7), `WAIT` (7), `GET_RANDOM_INT_IN_RANGE` (7), `GET_ENTITY_HEALTH` (6), `SET_ENTITY_HEALTH` (6), `IS_PED_IN_ANY_VEHICLE` (6), `IS_PED_BEING_STUNNED` (6), `GET_PLAYER_WANTED_LEVEL` (5), `GET_ENTITY_SPEED` (5), `BRING_VEHICLE_TO_HALT` (5), `TASK_LEAVE_ANY_VEHICLE` (5)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x8 · `0.1f` x5 · `1.5f` x5 · `0.25f` x4 · `42.92f` x4 · `4141.74f` x4 · `2710.43f` x4 · `1.7f` x2 · `1.3f` x2 · `2142.74f` x2 · `3355.45f` x2 · `44.44f` x2 · `2146.07f` x2 · `3351.57f` x2 · `44.5f` x2 · `2067.85f` x2 · `3266.79f` x2 · `44.45f` x2 · `1990.335f` x1 · `3053.546f` x1 · `45.11235f` x1 · `1989.142f` x1 · `3051.733f` x1 · `48.11221f` x1

## Other strings

Literals whose consuming native was not classified:

`Josef`, `Joe`, `MMB_Camper_Van`, `MMB_Patrol_Vehicle`, `pranger`, `MIN1_BUMP`, `MIN1_01`, `MIN1_03`, `MIN1_10`, `MIN1_DRUNK`, `surfer2`, `MM1_STOP`, `DisableReplayScriptStreamRecording`, `MIN1_OUTBAR`, `MIN1_WAIT2`, `MIN1_08`, `MIN1_02`, `MIN1_06`, `MIN1_GETSOUT`, `MIN1_CRASH`, `Force cleanup [TERMINATING]`, `SF_TCBP`, `MM1_FAIL`, `MIN1_F1`, `MIN1_F2`, `MIN1_F3`, `MIN1_F4`, `MIN1_F5`, `MIN1_F6`, `MIN1_F7`

---

Source: `decompiled_scripts/minute1.c`
