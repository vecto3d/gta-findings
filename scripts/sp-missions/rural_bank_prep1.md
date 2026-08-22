# rural_bank_prep1.c

SP missions script. 5 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 19,803 |
| Functions | 353 (38 unique, 315 shared) |
| Unique lines | 3,130 (15.8% of file) |

## Assets

**Models and props** (5) - `prop_mil_crate_01`, `s_m_y_marine_03`, `s_m_m_marine_01`, `crusader`, `barracks`

**Sounds** (2) - `PS_PREP_INTERCEPT_CONVOY`, `PS_PREP_MILITARY_TRUCK_SHOOTOUT`

**Speech contexts** (7) - `GENERIC_WAR_CRY`, `DYING_MOAN`, `DYING_HELP`, `TAKE_COVER`, `COVER_ME`, `COVER_YOU`, `RELOADING`

**Text labels** (3) - `RHPAUD`, `COP`, `NULL`

**Decorators** (1) - `IgnoredByQuickSave`

**Relationship groups** (2) - `trevor`, `enemies`

**Vehicle mods** (2) - `crusader`, `barracks`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (162), `DOES_ENTITY_EXIST` (64), `GET_ENTITY_COORDS` (55), `IS_PED_IN_VEHICLE` (27), `IS_PED_IN_ANY_VEHICLE` (26), `GET_GAME_TIMER` (26), `GET_VEHICLE_PED_IS_IN` (24), `IS_EXPLOSION_IN_AREA` (23), `IS_EXPLOSION_IN_SPHERE` (23), `TASK_LEAVE_ANY_VEHICLE` (19), `CLOSE_SEQUENCE_TASK` (18), `TASK_PERFORM_SEQUENCE` (18), `CLEAR_SEQUENCE_TASK` (18), `OPEN_SEQUENCE_TASK` (18), `SET_PED_COMBAT_ATTRIBUTES` (18), `PLAYER_ID` (17), `SET_ENTITY_AS_MISSION_ENTITY` (16), `IS_ENTITY_IN_ANGLED_AREA` (15), `ENABLE_DISPATCH_SERVICE` (15), `TASK_VEHICLE_TEMP_ACTION` (13), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (12), `CLEAR_PED_TASKS` (12), `GET_ENTITY_SPEED` (11), `IS_VEHICLE_DRIVEABLE` (11), `TASK_VEHICLE_ESCORT` (9), `TASK_COMBAT_PED` (9), `IS_PED_IN_COMBAT` (9), `BRING_VEHICLE_TO_HALT` (9), `SET_RELATIONSHIP_BETWEEN_GROUPS` (9), `GET_SCRIPT_TASK_STATUS` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`33.8865f` x4 · `3596.518f` x4 · `1383.51f` x4 · `-0.5f` x3 · `-1521.829f` x2 · `2725.003f` x2 · `16.64367f` x2 · `-1600.763f` x2 · `2794.875f` x2 · `21.45629f` x2 · `-1885.875f` x2 · `3006.152f` x2 · `31.81027f` x2 · `3.8f` x2 · `0.1f` x2 · `1006.765f` x2 · `2128.32f` x2 · `48.0929f` x2 · `1.5f` x2 · `35.39456f` x2 · `3600.538f` x2 · `1375.234f` x2 · `14.25f` x2 · `1364.248f` x1

## Other strings

Literals whose consuming native was not classified:

`crusader`, `PS_PREP_VEHICLES_GROUP`, `FIRING_PATTERN_FULL_AUTO`, `RHP_END`, `Armyped`, `towtruck`, `towtruck2`, `barracks`, `RHP_END_3`, `RHP_END_1`, `Rural_prep_trigger1`, `player`, `army`, `GROUP_MELEE`, `M_ThePaletoScorePrep`, `RHP1_TRUCK`, `RHP_RTN`, `RHP_BK`, `RHP_KILL`, `Trevor`, `Michael`, `RHP1_END`, `RHP_EXIT`, `RHP1_FAIL`, `RHP_FDES`, `RHP_TRKSTCK`, `RHP_FEND`, `RHP_FABN`, `ruralp`, `stage 0: reached ambush`

---

Source: `decompiled_scripts/rural_bank_prep1.c`
