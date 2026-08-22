# am_mp_smpl_interior_int.c

MP ambient script.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 419,819 |
| Functions | 7,976 (506 unique, 7,470 shared) |
| Unique lines | 33,622 (8.0% of file) |

## Assets

**Audio banks** (1) - `DLC_CHRISTMAS2017/XM_FACILITY_ENTRY_EXIT`

**Sounds** (7) - `EXEC1_Exit_Office_In_Heli_Scene`, `FAKE_ARRIVE`, `MP_PROPERTIES_ELEVATOR_DOORS`, `hold`, `DOOR_BUZZ`, `MP_PLAYER_APARTMENT`, `EXEC1_Exit_Office_In_Heli_Cutscene_End_Scene`

**Text labels** (4) - `EXCPAAU`, `NULL`, `WHSECUROINPUT`, `MP_SPINLOADING`

**Decorators** (3) - `Player_Avenger`, `Player_Mansion_Heli`, `Player_Truck`

**Interiors and entity sets** (3) - `Basic_style_set`, `Branded_style_set`, `Urban_style_set`

**Vehicle mods** (10) - `avenger`, `hauler2`, `phantom3`, `terbyte`, `trailersmall2`, `hakuchou2`, `seasparrow2`, `avisa`, `speedo4`, `scarab`

**Scripts launched** (4) - `am_contact_requests`, `am_mp_bunker`, `am_mp_defunct_base`, `am_mp_hangar`

**Hashed names** (2) - `bunker_ModRoom`, `bunker_bigbit`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (835), `PLAYER_PED_ID` (735), `GET_VEHICLE_PED_IS_IN` (226), `IS_PED_IN_ANY_VEHICLE` (177), `SET_BIT` (174), `CLEAR_BIT` (172), `IS_ENTITY_DEAD` (114), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (114), `DOES_ENTITY_EXIST` (86), `DISABLE_CONTROL_ACTION` (67), `IS_VEHICLE_MODEL` (64), `GET_PLAYER_PED` (55), `FREEZE_ENTITY_POSITION` (51), `IS_STRING_NULL_OR_EMPTY` (39), `GET_ENTITY_MODEL` (37), `IS_SCREEN_FADED_OUT` (35), `GET_NETWORK_TIME` (34), `NETWORK_HAS_CONTROL_OF_ENTITY` (32), `GET_SCRIPT_TASK_STATUS` (30), `GET_ENTITY_HEADING` (27), `TASK_LEAVE_ANY_VEHICLE` (25), `GET_ENTITY_COORDS` (24), `DO_SCREEN_FADE_OUT` (23), `IS_SCREEN_FADED_IN` (22), `IS_PED_IN_VEHICLE` (22), `TO_FLOAT` (22), `DO_SCREEN_FADE_IN` (21), `GET_PED_IN_VEHICLE_SEAT` (21), `NETWORK_REQUEST_CONTROL_OF_ENTITY` (20), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (20)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x53 · `-0.5f` x47 · `2.7379f` x32 · `3.99592f` x28 · `3.5f` x3 · `5.5f` x3 · `0.25f` x3 · `-8.1f` x2 · `-48.5f` x2 · `-47.5f` x2 · `-46.5f` x2 · `-45.5f` x2 · `-44.5f` x2 · `-43.5f` x2 · `32.7f` x2 · `33.5f` x2 · `34.5f` x2 · `35.5f` x2 · `36.5f` x2 · `37.5f` x2 · `38.5f` x2 · `39.5f` x2 · `-3.5f` x2 · `-2.5f` x2

## Other strings

Literals whose consuming native was not classified:

`avenger`, `MP_BUNKER_KICKj`, `MP_PROP_PUR_KICK0`, `MP_PROP_PUR_KICK1`, `terbyte`, `trailerlarge`, `trailersmall2`, `MP_TRUCK_KICKi`, `halftrack`, `oppressor2`, `am_vehicle_spawn`, `tailgater`, `RUN_STATE_TELEPORTING_BACK`, `caddy2`, `caddy3`, `seasparrow3`, `avisa`, `BB_TRUCK_KICKi`, `BB_TRUCK_KICKj`, `BB_TRUCK_KICKk`, `BB_TRUCK_KICKl`, `BB_TRUCK_KICKd`, `BB_TRUCK_KICKa`, `BB_TRUCK_KICKb`, `BB_TRUCK_KICKm`, `BB_TRUCK_KICKn`, `BB_TRUCK_KICKo`, `BB_TRUCK_KICKp`, `BB_TRUCK_KICKq`, `BB_TRUCK_KICKr`

---

Source: `decompiled_scripts/am_mp_smpl_interior_int.c`
