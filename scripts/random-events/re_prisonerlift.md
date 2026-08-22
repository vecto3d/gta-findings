# re_prisonerlift.c

Random events script. 1 anim dicts; 6 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 7,831 |
| Functions | 191 (29 unique, 162 shared) |
| Unique lines | 2,269 (29.0% of file) |

## Assets

**Animation dictionaries** (1) - `random@prisoner_lift`

**Animations** (3) - `random@prisoner_lift`, `arms_waving`, `loop2_idlelook2`

**Models and props** (6) - `s_m_y_ranger_01`, `sheriff`, `ratloader`, `bfinjection`, `g_m_y_lost_02`, `s_m_y_prisoner_01`

**Speech contexts** (2) - `REPRI1Lost`, `G_M_Y_STREETPUNK02_BLACK_MINI_04`

**Text labels** (7) - `PRI1AU`, `PRI2AU`, `COP`, `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Scenarios** (1) - `WORLD_HUMAN_SMOKING`

**Relationship groups** (1) - `PedPrisoner`

**Vehicle mods** (2) - `towtruck`, `towtruck2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (160), `IS_PED_INJURED` (53), `GET_ENTITY_COORDS` (53), `PLAYER_ID` (42), `TASK_SMART_FLEE_COORD` (28), `SET_PED_KEEP_TASK` (27), `GET_VEHICLE_PED_IS_IN` (26), `DOES_BLIP_EXIST` (24), `WAIT` (19), `CLEAR_PED_TASKS` (19), `IS_PED_IN_GROUP` (18), `REMOVE_PED_FROM_GROUP` (18), `IS_ENTITY_AT_ENTITY` (17), `IS_VEHICLE_DRIVEABLE` (17), `OPEN_SEQUENCE_TASK` (16), `CLOSE_SEQUENCE_TASK` (16), `TASK_PERFORM_SEQUENCE` (16), `CLEAR_SEQUENCE_TASK` (16), `IS_PED_IN_ANY_VEHICLE` (15), `GET_PLAYERS_LAST_VEHICLE` (11), `REMOVE_BLIP` (11), `IS_ENTITY_AT_COORD` (11), `GET_SCRIPT_TASK_STATUS` (10), `REQUEST_MODEL` (10), `GET_ENTITY_SPEED` (9), `CREATE_PED_INSIDE_VEHICLE` (9), `GIVE_WEAPON_TO_PED` (9), `TIMERA` (7), `IS_PLAYER_WANTED_LEVEL_GREATER` (7), `IS_PED_IN_VEHICLE` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1449.05f` x8 · `2507.258f` x8 · `44.8843f` x8 · `2.5f` x6 · `0.5f` x3 · `0.25f` x2 · `333.9002f` x2 · `0.1f` x2 · `990.7705f` x2 · `-105.594f` x2 · `73.3055f` x2 · `954.8849f` x2 · `-145.3864f` x2 · `79.1073f` x2 · `8.8125f` x2 · `1449.851f` x2 · `2452.661f` x2 · `81.56557f` x2 · `1203.85f` x2 · `2579.351f` x2 · `35.1549f` x2 · `224.125f` x2 · `10.5f` x1 · `1524.332f` x1

## Other strings

Literals whose consuming native was not classified:

`PRI1_SOB`, `PRI2_FLEE`, `PRI1_THK`, `PRI1_UVH2`, `PRI1_UVH`, `PRI1_POL`, `FIRING_PATTERN_FULL_AUTO`, `RE_PL`, `PRI2_ASK`, `rhino`, `bus`, `PRI1_LOS`, `PRI2_STEAL`, `PRI1_STA`, `PRI1_CHAT1`, `PRI1_CHAT2`, `PRI1_CHAT1b`, `PRI1_CHAT2b`, `PRI1_CHAT1c`, `PRI1_CHAT2c`, `PRI1_WLK`, `PRI1_SLO`, `PRI1_CH`, `PRI2_WHTM`, `PRI2_WHTF`, `PRI2_WHTT`, `PRI2_THREAT`, `PRI2_HIJ`, `PRI1_ASK`, `PRI1_GETONM`

---

Source: `decompiled_scripts/re_prisonerlift.c`
