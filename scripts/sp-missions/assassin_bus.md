# assassin_bus.c

SP missions script. 9 anim dicts; 9 models; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 25,588 |
| Functions | 565 (120 unique, 445 shared) |
| Unique lines | 5,103 (19.9% of file) |

## Assets

**Animation dictionaries** (9) - `oddjobs@assassinate@bus@call`, `move_m@casual@d`, `ODDJOBS@assassinate@vice@incar`, `veh@bus@passenger@rds@idle_panic`, `veh@bus@passenger@rps@idle_panic`, `mini@hookers_spvanilla`, `ODDJOBS@assassinate@old_lady`, `oddjobs@assassinate@bus@`, `misscommon@response`

**Animations** (11) - `oddjobs@assassinate@bus@`, `base`, `sit`, `veh@bus@passenger@rds@idle_panic`, `veh@bus@passenger@rps@idle_panic`, `looking_for_help`, `misscommon@response`, `ODDJOBS@ASSASSINATE@VICE@HOOKER`, `idle_b`, `oddjobs@assassinate@bus@call`, `ass_bus_call_p1`

**Models and props** (9) - `a_m_m_eastsa_01`, `a_f_o_genstreet_01`, `p_phonebox_01b_s`, `coach`, `bus`, `a_m_m_business_01`, `a_m_m_eastsa_02`, `a_m_o_tramp_01`, `prop_phonebox_01b`

**Sounds** (4) - `ASSASSINATION_BUS_SCREAMS_INT_SCENE`, `ASSASSINATION_BUS_SCREAMS_EXT_SCENE`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`

**Particle effects** (1) - `scr_ojbusass_bus_impact`

**Text labels** (7) - `OJASAUD`, `LESTER`, `INVESTOR`, `FRANKLIN`, `NULL`, `ASS_BS_EXIT`, `ASS_BS_BOARD`

**Waypoint recordings** (9) - `OJASbs_102`, `OJASbs01`, `OJASbs02`, `OJASbs03`, `OJASbs04`, `OJAShk_101`, `OJAShk_102`, `OJAShk_103`, `OJAShk_104`

**Relationship groups** (1) - `Target`

**Vehicle mods** (1) - `bus`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (131), `SET_PED_COMPONENT_VARIATION` (97), `DOES_ENTITY_EXIST` (62), `IS_VEHICLE_DRIVEABLE` (42), `IS_ENTITY_DEAD` (39), `IS_PED_INJURED` (37), `PLAYER_ID` (25), `REMOVE_BLIP` (24), `IS_PED_IN_VEHICLE` (24), `DOES_BLIP_EXIST` (22), `GET_IS_WAYPOINT_RECORDING_LOADED` (18), `GET_SCRIPT_TASK_STATUS` (16), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (16), `WAIT` (15), `DISABLE_CONTROL_ACTION` (14), `SET_VEHICLE_ON_GROUND_PROPERLY` (13), `GET_ENTITY_COORDS` (11), `CREATE_VEHICLE` (11), `GET_RANDOM_INT_IN_RANGE` (10), `GET_PED_IN_VEHICLE_SEAT` (10), `RENDER_SCRIPT_CAMS` (10), `SET_PED_INTO_VEHICLE` (10), `CLEAR_PED_TASKS` (10), `SET_ENTITY_COORDS` (10), `SET_ENTITY_HEADING` (10), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (10), `CREATE_PED` (10), `REQUEST_MODEL` (10), `CREATE_PED_INSIDE_VEHICLE` (10), `GET_ENTITY_MODEL` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`8.5f` x12 · `9.5f` x6 · `0.1098f` x5 · `0.2f` x4 · `-644.93f` x4 · `-26.48f` x4 · `-110.66f` x4 · `56.0227f` x4 · `1.5f` x3 · `5.6201f` x3 · `0.25f` x3 · `0.5f` x3 · `435.0773f` x3 · `-650.2194f` x3 · `27.74271f` x3 · `436.3171f` x3 · `-642.8832f` x3 · `27.73943f` x3 · `435.6569f` x3 · `-645.5588f` x3 · `27.73775f` x3 · `436.6802f` x3 · `-629.7325f` x3 · `27.71444f` x3

## Other strings

Literals whose consuming native was not classified:

`BusPed3`, `BusPed1`, `BusPed2`, `bus`, `coach`, `ASS_HK_COMP`, `ASS_BS_COMP`, `ASS_ML_COMP`, `ASS_BS_COPS`, `OJAS_BUCOM`, `PASSENGERS_Group`, `ASS_BS_EXIT`, `ASS_BS_AREA`, `assassin_bus_stage_drive_to_stops`, `OJASbs_FOOT3`, `Franklin`, `Mugger`, `Mugging_Victim`, `Franklins_Coach`, `Franklins_Bus`, `Stolen_Bike`, `scorcher`, `ASS_MCS_1`, `ASS_HELP_02`, `OJASbs_NOPE`, `player`, `ASS_HK_LOST`, `M_ASS4`, `FRANKLIN_BIG_01`, `ES_XPAND`

---

Source: `decompiled_scripts/assassin_bus.c`
