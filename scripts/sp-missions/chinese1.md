# chinese1.c

SP missions script. 2 anim dicts; 26 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 120,784 |
| Functions | 913 (190 unique, 723 shared) |
| Unique lines | 11,411 (9.4% of file) |

## Assets

**Animation dictionaries** (2) - `MissChinese1`, `MissChinese1LeadInOutCHI_1_MCS_4`

**Animations** (10) - `MissChinese1LeadInOutCHI_1_MCS_4`, `misschinese1`, `CHI_1_MCS_4_TAO_ACTION`, `CHI_1_MCS_4_TRANSLATOR_ACTION`, `CHI_1_MCS_4_TAO_IDLE_2`, `CHI_1_MCS_4_TRANSLATOR_IDLE_2`, `CHI_1_MCS_4_TAO_IDLE_1`, `CHI_1_MCS_4_TRANSLATOR_IDLE_1`, `throwgrenl_cook`, `throwgrenl_player`

**Models and props** (26) - `phoenix`, `v_39_ShopRm`, `v_39_UpperRm3`, `v_39_UpperRm2`, `sadler`, `dubsta2`, `v_methlab`, `v_39_UpperRm1`, `pcj`, `ig_janet`, `ig_josef`, `ig_old_man1a`, `ig_old_man2`, `ig_russiandrunk`, `prop_gascyl_01a`, `v_ret_ml_win5`, `prop_cs_dumpster_01a`, `prop_ice_box_01`, `ig_taostranslator`, `V_39_UpperRm3`, `v_39_StairsRm`, `g_m_y_mexgoon_02`, `g_m_y_azteca_01`, `p_ice_box_01_s`, `p_ice_box_proxy_col`, `prop_boxpile_02b`

**Audio banks** (1) - `CHINESE1_ICEBOX`

**Sounds** (13) - `CHI_1_TRUCK_ARRIVES`, `CHI_1_SHOOTOUT_04`, `CHI_1_SHOOTOUT_03`, `CHI_1_SHOOTOUT_GRENADE_LAUNCHER`, `CHI_1_SHOOTOUT_01`, `CHI_1_GO_TO_ICEBOX`, `CHI_1_GET_TO_SHOOTOUT_04`, `CHI_1_ENEMIES_ESCAPE`, `CHI_1_GET_TO_SHOOTOUT_03`, `CHI_1_CATCH_GRENADE_LAUNCHER`, `CHI_1_SHOOTOUT_02`, `CHI_1_DRIVE_TO_LAB`, `CR_WEAPONS_BURST_SHORT`

**Speech contexts** (2) - `GENERIC_WAR_CRY`, `SPEECH_PARAMS_FORCE`

**Text labels** (12) - `OFF`, `METH_GOD_18`, `VAGOS`, `NULL`, `GETIN`, `CH1CAL`, `CH1CAL2`, `BANT1AV1`, `TRESP`, `THANKS`, `HERE`, `METH`

**Scenarios** (1) - `WORLD_HUMAN_STUPOR`

**Waypoint recordings** (5) - `methlab3`, `methlab4`, `methlab7`, `methlab1`, `methlab5`

**Vehicle recordings** (1) - `lkmethlab`

**Relationship groups** (1) - `player`

**Interiors and entity sets** (2) - `v_methlab`, `v_hicksbar`

**Doors** (4) - `v_ilev_ml_door1`, `v_ilev_ss_doorext`, `prop_arm_gate_l`, `v_ilev_ss_door04`

**Hashed names** (1) - `START_CUTSCENE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (360), `DOES_ENTITY_EXIST` (128), `REQUEST_MODEL` (111), `HAS_MODEL_LOADED` (109), `IS_PED_INJURED` (107), `IS_VEHICLE_DRIVEABLE` (85), `OPEN_SEQUENCE_TASK` (81), `CLOSE_SEQUENCE_TASK` (81), `TASK_PERFORM_SEQUENCE` (81), `CLEAR_SEQUENCE_TASK` (81), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (77), `REQUEST_VEHICLE_RECORDING` (70), `HAS_VEHICLE_RECORDING_BEEN_LOADED` (70), `GET_ENTITY_COORDS` (63), `GET_GAME_TIMER` (58), `SET_PED_COMPONENT_VARIATION` (48), `IS_ENTITY_IN_ANGLED_AREA` (46), `SET_LOCKED_UNSTREAMED_IN_DOOR_OF_TYPE` (45), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (45), `PLAYER_ID` (42), `CLEAR_PED_TASKS` (42), `TASK_COMBAT_PED` (42), `SET_MODEL_AS_NO_LONGER_NEEDED` (39), `TASK_GO_TO_COORD_WHILE_AIMING_AT_ENTITY` (38), `SET_PED_SPHERE_DEFENSIVE_AREA` (32), `GET_WEAPONTYPE_MODEL` (29), `SET_ENTITY_COORDS` (29), `DOES_BLIP_EXIST` (28), `SET_ENTITY_HEADING` (28), `REMOVE_BLIP` (25)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x44 · `0.8f` x41 · `35.13f` x20 · `38.5f` x19 · `1.5f` x19 · `1.6f` x16 · `46.0491f` x11 · `37.9419f` x11 · `0.25f` x11 · `1829.64f` x10 · `3625.69f` x10 · `1538.96f` x10 · `3710.29f` x10 · `1392.93f` x10 · `3599.47f` x10 · `1395.37f` x10 · `3600.36f` x10 · `2.3f` x10 · `1373.8f` x10 · `3615.3f` x10 · `35.4f` x10 · `1587.6f` x9 · `4259.42f` x9 · `646.61f` x9

## Other strings

Literals whose consuming native was not classified:

`methaud`, `FIRING_PATTERN_FULL_AUTO`, `Tao`, `Taos_Translator`, `phoenix`, `trevor`, `MotionState_Walk`, `dubsta2`, `METH_GOD_18`, `player`, `sadler`, `cook`, `DEFAULT_SCRIPTED_CAMERA`, `chin_M4_LI1_2`, `pcj`, `Cook`, `cheng`, `METH_GOD_14`, `translator`, `chin_end`, `chin_cookice`, `chin_shout`, `METH_FAIL_5`, `Wave 2 after grenade launcher cutscene`, `Mission start`, `chin_M4_LI1`, `MissChinese1LeadInOutCHI_1_MCS_4`, `CHN1_FINAL_CS`, `chin_M4_LI1_1`, `getaway_car`

---

Source: `decompiled_scripts/chinese1.c`
