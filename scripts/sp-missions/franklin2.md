# franklin2.c

SP missions script. 1 anim dicts; 5 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 128,291 |
| Functions | 974 (101 unique, 873 shared) |
| Unique lines | 13,473 (10.5% of file) |

## Assets

**Animation dictionaries** (1) - `move_ped_strafing`

**Animations** (3) - `lamar_base_idle_to_standing_idle`, `pickup_low`, `lamar_base_idle`

**Models and props** (5) - `g_m_y_ballaorig_01`, `prop_woodpile_01b`, `prop_skip_01a`, `prop_weed_pallet`, `v_ilev_fh_frontdoor`

**Sounds** (10) - `FRANKLIN_2_SAVE_LAMAR_ALERT`, `FRANKLIN_2_SAVE_LAMAR_TREVOR`, `FRANKLIN_2_SAVE_LAMAR_MICHAEL`, `FRANKLIN_2_ESCAPE_IN_VEHICLE`, `FRANKLIN_2_GO_TO_FRANKLINS`, `FRANKLIN_2_PROTECT_LAMAR`, `FRANKLIN_2_SAVE_LAMAR_STEALTH`, `FRANKLIN_2_GET_TO_SAWMILL`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`

**Text labels** (9) - `LEM2AUD`, `FRANKLIN`, `TREVOR`, `MICHAEL`, `OFF`, `LAMAR`, `NULL`, `LESTER`, `FRAN2`

**Scenarios** (1) - `WORLD_HUMAN_STUPOR`

**Relationship groups** (3) - `player`, `BALLAS`, `NEUTRAL`

**Doors** (1) - `v_ilev_fh_frontdoor`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (324), `GET_ENTITY_COORDS` (253), `IS_PED_INJURED` (247), `VDIST2` (240), `DOES_ENTITY_EXIST` (186), `GET_GAME_TIMER` (151), `SET_PED_COMBAT_ATTRIBUTES` (134), `SET_PED_SPHERE_DEFENSIVE_AREA` (95), `SET_COMBAT_FLOAT` (71), `TASK_SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (65), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (57), `PLAYER_ID` (52), `SET_PED_RELATIONSHIP_GROUP_HASH` (46), `GET_SCRIPT_TASK_STATUS` (46), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (43), `IS_VEHICLE_DRIVEABLE` (43), `SET_PED_CONFIG_FLAG` (42), `OPEN_SEQUENCE_TASK` (39), `CLOSE_SEQUENCE_TASK` (39), `TASK_PERFORM_SEQUENCE` (39), `CLEAR_SEQUENCE_TASK` (39), `DOES_BLIP_EXIST` (38), `IS_ENTITY_IN_ANGLED_AREA` (36), `SET_ENTITY_COORDS` (34), `WAIT` (32), `IS_PED_IN_VEHICLE` (32), `HAS_MODEL_LOADED` (29), `GET_RANDOM_INT_IN_RANGE` (29), `FREEZE_ENTITY_POSITION` (27), `SET_ENTITY_HEALTH` (27)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x74 · `79.61f` x14 · `-516.1574f` x12 · `5247.171f` x12 · `80.3439f` x12 · `79.2676f` x12 · `0.25f` x11 · `-492.6f` x9 · `5304.7f` x9 · `81.6f` x9 · `71.0182f` x7 · `-511.0591f` x6 · `79.36004f` x6 · `14.25f` x6 · `-574.0313f` x6 · `5258.59f` x6 · `69.2144f` x5 · `-498.8398f` x5 · `5292.783f` x5 · `81.7003f` x5 · `0.1f` x5 · `-496.3577f` x4 · `5296.457f` x4 · `84.41231f` x4

## Other strings

Literals whose consuming native was not classified:

`FIRING_PATTERN_FULL_AUTO`, `GENERIC_WAR_CRY`, `move_ped_strafing`, `Franklin`, `player`, `FRA_2_EXT`, `Lamar`, `FRA_2_IG_4_ALT1_concat`, `Michael`, `Trevor`, `LM2_MORE`, `FRA2_END_VEHICLE`, `fr2_enemy1`, `FRAN2_SNIPEHELP`, `FRANKLIN_2_BUDDIES_GROUP`, `FRAN2_FIND`, `Michaels_car`, `Trevors_car`, `bulldozer`, `GET_LAMAR_OUT`, `Lm2_onphn`, `Lm2_onphn2`, `Extra_`, `FRAN2_leadL`, `FRAN2_PROT`, `LM2_Snipe3`, `LM2_driveT`, `LM2_drive`, `LM2_FRANGEN`, `LM2_TRVATT`

---

Source: `decompiled_scripts/franklin2.c`
