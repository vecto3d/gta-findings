# solomon1.c

SP missions script. 9 anim dicts; 47 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 115,955 |
| Functions | 763 (66 unique, 697 shared) |
| Unique lines | 6,605 (5.7% of file) |

## Assets

**Animation dictionaries** (9) - `MOVE_M@CLIPBOARD`, `amb@world_human_hang_out_Street@male_a@idle_a`, `amb@medic@standing@kneel@enter`, `amb@medic@standing@kneel@idle_a`, `amb@medic@standing@kneel@exit`, `REACTION@MALE_STAND@BIG_INTRO@FORWARD`, `amb@world_human_clipboard@male@idle_a`, `cellphone@str`, `misssolomon_1`

**Animations** (16) - `idle_c`, `idle_a`, `idle_b`, `misssolomon_1`, `enter`, `exit`, `reaction_forward_big_intro_c`, `reaction_forward_big_intro_a`, `idle_d`, `idle_e`, `anton_heli_loop`, `anton_heli_exit`, `anton_heli_intro`, `milton_heli_intro`, `milton_heli_loop`, `milton_heli_exit`

**Models and props** (47) - `ig_milton`, `cs_milton`, `u_m_y_antonb`, `prop_tool_hardhat`, `s_m_y_construct_01`, `ig_solomon`, `g_m_m_armgoon_01`, `frogger`, `prop_pipes_conc_02`, `prop_generator_01a`, `prop_partsbox_01`, `prop_tool_box_01`, `prop_worklight_03b`, `prop_worklight_02a`, `prop_worklight_04a`, `prop_barrier_work06a`, `prop_worklight_04c`, `prop_worklight_04d`, `prop_map_door_01`, `prop_generator_02a`, `fugitive`, `mixer`, `forklift`, `prop_facgate_03_l`, `ig_roccopelosi`, `s_m_y_pilot_01`, `p_amb_clipboard_01`, `p_amb_phone_01`, `u_m_y_guido_01`, `cavalcade2`, `coquette`, `prop_woodpile_04b`, `prop_woodpile_01a`, `prop_tool_box_04`, `prop_tool_torch`, `prop_generator_03b`, `prop_cementbags01`, `prop_cablespool_06`, `prop_cablespool_02`, `prop_worklight_01a`, `prop_worklight_03a`, `prop_conc_blocks01b`, `prop_worklight_04b`, `prop_cementmixer_02a`, `prop_cons_cements01`, `prop_pris_door_02`, `prop_gar_door_04`

**Sounds** (7) - `SOL_1_ROCCO_ARRIVES_CUTSCENE`, `SOL_1_FIGHT_ROCCO`, `SOL_1_GET_TO_HELI_STEALTH`, `SOL_1_DRIVE_TO_EAST_LS`, `SOL_1_GET_TO_HELI_ALERT`, `SOL_1_GET_TO_STUDIO`, `SOL_1_COMPOUND_OVERVIEW_CUTSCENE`

**Text labels** (16) - `SOL1AUD`, `SOL1ACTOR`, `CONSTRUCTION2`, `CONSTRUCTION1`, `CONSTRUCTION3`, `MICHAEL`, `GIANNI`, `ANTON`, `SOL1REC`, `ROCCO`, `NULL`, `SOLOMON`, `OFF`, `SOL1`, `MAFIAGOON`, `EXTRASUNNY`

**Scenarios** (1) - `SOLOMON_GATE`

**Vehicle recordings** (1) - `SOL1REC`

**Relationship groups** (2) - `enemies`, `rel_Friends`

**Vehicle mods** (2) - `fugitive`, `frogger`

**Stats** (1) - `sp0_flying_ability`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_GAME_TIMER` (125), `PLAYER_PED_ID` (105), `TASK_PLAY_ANIM` (87), `CLEAR_SEQUENCE_TASK` (44), `PLAYER_ID` (43), `IS_PED_IN_VEHICLE` (42), `GET_ENTITY_COORDS` (42), `IS_ENTITY_IN_ANGLED_AREA` (39), `OPEN_SEQUENCE_TASK` (38), `TASK_FOLLOW_NAV_MESH_TO_COORD` (38), `CLOSE_SEQUENCE_TASK` (38), `TASK_PERFORM_SEQUENCE` (38), `TASK_LOOK_AT_ENTITY` (35), `TASK_SMART_FLEE_PED` (30), `ARE_STRINGS_EQUAL` (30), `TASK_TURN_PED_TO_FACE_ENTITY` (27), `CLEAR_PED_TASKS` (27), `DOES_ENTITY_EXIST` (26), `HAS_PED_RECEIVED_EVENT` (24), `IS_PED_FLEEING` (24), `TRIGGER_MUSIC_EVENT` (22), `IS_ENTITY_AT_COORD` (22), `GET_VEHICLE_PED_IS_IN` (19), `DOES_BLIP_EXIST` (16), `IS_ENTITY_PLAYING_ANIM` (16), `IS_PED_HEADTRACKING_PED` (15), `IS_PED_IN_ANY_VEHICLE` (14), `CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY` (13), `IS_MESSAGE_BEING_DISPLAYED` (13), `IS_AUDIO_SCENE_ACTIVE` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x38 · `-1.5f` x33 · `1.5f` x31 · `41.06182f` x23 · `50.13412f` x9 · `0.5f` x7 · `0.1f` x6 · `1.6f` x6 · `945.0175f` x6 · `-1679.363f` x6 · `0.3f` x5 · `-1037.912f` x5 · `-495.8833f` x5 · `-1016.928f` x5 · `-471.0461f` x5 · `956.918f` x5 · `-1693.617f` x5 · `28.2963f` x5 · `966.4474f` x5 · `-1720.887f` x5 · `29.6126f` x5 · `41.97026f` x4 · `907.2717f` x4 · `-1692.093f` x4

## Other strings

Literals whose consuming native was not classified:

`Anton`, `Milton`, `Michael`, `SOL1Actor`, `SOL1_1ST_ENEMY`, `csb_anton`, `SOl1_SCARE`, `SOl1_SCARE2`, `GROUP_MELEE`, `frogger`, `rocco`, `cavalcade2`, `coquette`, `player`, `SOL1_HEAR`, `SOL1_FAIL`, `misssolomon_1`, `CMN_GENGETBCKHE`, `SOL1_HELI_ID`, `SOL1_NOSCAR`, `SOL1_SCARY`, `Rocco_Goon`, `Main_heli`, `SOL1_TEXT`, `SOL1_HEAR1`, `SOL1_HEAR1b`, `SOl1_HEAR2`, `SOl1_HEAR3`, `SOL1_SEE1`, `SOL1_CALL1`

---

Source: `decompiled_scripts/solomon1.c`
