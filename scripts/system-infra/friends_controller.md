# friends_controller.c

System and infrastructure script. 6 anim dicts.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 42,715 |
| Functions | 476 (132 unique, 344 shared) |
| Unique lines | 5,353 (12.5% of file) |

## Assets

**Animation dictionaries** (6) - `FRIENDS@FRM@IG_2`, `FRIENDS@FRF@IG_2`, `FRIENDS@FRT@IG_2`, `friends@frm@ig_2`, `friends@frf@ig_2`, `friends@frt@ig_2`

**Text labels** (8) - `NULL`, `MICHAEL`, `TREVOR`, `LAMAR`, `ANAUD`, `FRANKLIN`, `JIMMY`, `AMANDA`

**Scenarios** (2) - `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_STAND_MOBILE`

**Relationship groups** (1) - `AmbFriendEmpty`

**Scripts launched** (1) - `appinternet`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (100), `IS_PED_INJURED` (40), `CLEAR_PED_TASKS` (38), `GET_ENTITY_COORDS` (27), `IS_PED_IN_ANY_VEHICLE` (19), `GET_VEHICLE_PED_IS_IN` (19), `DOES_ENTITY_EXIST` (11), `IS_PED_RAGDOLL` (9), `ABSF` (8), `GET_RANDOM_INT_IN_RANGE` (7), `GET_GAME_TIMER` (7), `GET_DISTANCE_BETWEEN_COORDS` (7), `IS_ANY_SPEECH_PLAYING` (6), `TASK_LOOK_AT_ENTITY` (6), `VDIST2` (6), `IS_PED_RUNNING_RAGDOLL_TASK` (5), `GET_INTERIOR_FROM_ENTITY` (5), `GET_ENTITY_SPEED` (5), `GET_PED_IN_VEHICLE_SEAT` (5), `IS_ENTITY_AT_COORD` (5), `CLEAR_ENTITY_LAST_DAMAGE_ENTITY` (5), `PLAYER_ID` (4), `IS_AMBIENT_SPEECH_PLAYING` (4), `IS_ENTITY_AT_ENTITY` (4), `IS_VEHICLE_DRIVEABLE` (4), `IS_EXPLOSION_IN_SPHERE` (4), `SET_BIT` (4), `DOES_ENTITY_BELONG_TO_THIS_SCRIPT` (4), `IS_SCREEN_FADED_OUT` (4), `IS_THREAD_ACTIVE` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`7.5f` x4 · `1977.232f` x2 · `3812.881f` x2 · `31.3578f` x2 · `2.5f` x2 · `-816.6923f` x1 · `169.9429f` x1 · `70.51423f` x1 · `-1155.24f` x1 · `-1519.908f` x1 · `3.350527f` x1 · `131.592f` x1 · `-1303.622f` x1 · `28.22608f` x1 · `0.25f` x1

## Other strings

Literals whose consuming native was not classified:

`knockout_cam`, `AM_H_NOFRND`, `EXTREME_GRIEFING`, `knockout_player`, `GENERIC_FUCK_YOU`, `FriendActivity`, `NO_RELATIONSHIP`, `MICHAEL_KNOCKS_OUT_ANYONE_0`, `MICHAEL_KNOCKOUT_FAFM_ANAA_0`, `FrOUT_M_0`, `FRANKLIN_KNOCKS_OUT_ANYONE_0`, `FRANKLIN_KNOCKOUT_FAMF_APAA_0`, `FrOUT_F_0`, `TREVOR_KNOCKS_OUT_ANYONE_0`, `TREVOR_KNOCKOUT_FAMT_ANAA_0`, `FrOUT_T_0`, `GENERIC_WHATEVER`, `JACKED_GENERIC`, `FR_PK_AMB_M`, `caddy`, `caddy2`, `player_controller`, `player_controller_b`, `family_scene_t0`, `_Amb`, `PkOk`, `PkLt`, `PkFt`

---

Source: `decompiled_scripts/friends_controller.c`
