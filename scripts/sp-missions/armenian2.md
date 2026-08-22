# armenian2.c

SP missions script. 8 anim dicts; 26 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 70,085 |
| Functions | 699 (118 unique, 581 shared) |
| Unique lines | 15,962 (22.8% of file) |

## Assets

**Animation dictionaries** (8) - `MISSARMENIAN2LeadInOutMCS_6`, `MISSARMENIAN2`, `missarmenian2_mcs_5`, `reaction@points@`, `missarmenian2lamar_idles`, `missarmenian2lamar_in_cover`, `DEAD`, `ANIM_GROUP_MOVE_LEMAR_ALLEY`

**Animations** (42) - `MISSARMENIAN2`, `missarmenian2`, `missarmenian2lamar_idles`, `open_garage_franklin`, `open_garage_door`, `missarmenian2lamar_in_cover`, `MISSARMENIAN2LeadInOutMCS_6`, `_leadin_fra`, `PUNCH_REACTION_&_FALL_DRUNK`, `fake_punch_walk_by_lamar`, `exit_garage_drunk`, `reaction@points@`, `loop_0`, `lamar_impatient_c`, `lamar_explosion_react`, `lamar_cover_idle_a`, `lamar_cover_loop`, `lamar_texting`, `idle_look_behind_left`, `idle_look_behind_right`, `idle_look_left`, `idle_look_right`, `idle_a`, `idle_b`, `idle_c`, `idle_d`, `idle_e`, `idle_f`, `arm2_lamar_idle_02`, `arm2_lamar_idle_03`, `dead`, `dead_a`, `standing_idle_loop_drunk`, `car_react_gang_ds`, `car_react_gang_ps`, `drunk_getup`, `GARAGE_POINT_lemar`, `lamar_cover_intro`, `lamar_cover_idle_b`, `In_Car_Nervous`, `missarmenian2_mcs_5`, `_rider`

**Models and props** (26) - `prop_employee_month_02`, `prop_gar_door_plug`, `ig_siemonyetarian`, `baller`, `schwarzer`, `prop_ld_test_01`, `g_m_y_mexgoon_01`, `bullet`, `bison`, `prop_arm_gate_l`, `prop_employee_month_01`, `v_ilev_fib_door1`, `prop_ld_balcfnc_02b`, `prop_npc_phone`, `prop_map_door_01`, `ig_lamardavis`, `prop_ld_balcfnc_02a`, `g_m_y_mexgoon_03`, `prop_wallchunk_01`, `bagger`, `penumbra`, `u_m_o_tramp_01`, `SET_ACTION_FLAG() fail:`, `prop_gar_door_02`, `prop_gar_door_01`, `prop_bin_07c`

**Audio banks** (4) - `ARM_2_REPO_01`, `ARM_2_GAS_EXPLOSION`, `ARM_2_GARAGE_DOORS`, `ARM_2_BIKER_DRIVE_OFF`

**Sounds** (18) - `ARM_2_GAS_TRAIL`, `ARM_2_SEARCH_FOR_BIKE`, `ARM_2_RIDE_BIKE_BACK`, `ARM_2_DRIVE_TO_ALLEY`, `ARM_2_GANG_DRIVE_PAST`, `ARM_2_SHOOTOUT`, `ARM_2_RAYFIRE`, `ARM_2_GET_TO_THE_CAR`, `ARM_2_CHASE_THE_BIKE`, `ARM_2_REPO_SOUNDS`, `ARM_2_FOCUS_ON_BIKE`, `ARM_2_REPO_DOOR_KICK_OPEN`, `Gas_Explosion`, `Garage_Open_01`, `Garage_Open_02`, `Biker_Ride_Off`, `ARM_2_Repo_Ignite_Petrol`, `TargetPan`

**Speech contexts** (7) - `SPEECH_PARAMS_FORCE`, `CHAT_STATE`, `CHAT_RESP`, `AR2_DFAH`, `ARM2bum`, `SPEECH_PARAMS_FORCE_SHOUTED`, `G_M_Y_SalvaGoon_02_SALVADORIAN_MINI_02`

**Text labels** (13) - `LAMAR`, `FRANKLIN`, `MISSARMENIAN2`, `ARM2VAGOS4`, `ARM2VAGOS1`, `NULL`, `EXTRASUNNY`, `ARM2`, `AR2AUD`, `SIMEON`, `ARM2VAGOSCAR`, `ARM2VAGOS2`, `ARM2VAGOS3`

**Scenarios** (2) - `ARMENIAN_CATS`, `WORLD_HUMAN_STAND_MOBILE`

**Waypoint recordings** (5) - `arm2`, `arm2_15`, `ARM2`, `ARM2_FIRE`, `arm2_fire`

**Vehicle recordings** (1) - `ARM2`

**Relationship groups** (4) - `MYFRIEND`, `FOE`, `WARY`, `IGNORE`

**Interiors and entity sets** (1) - `v_carshowroom`

**Doors** (2) - `prop_arm_gate_l`, `prop_gar_door_03_ld`

**Vehicle mods** (2) - `bagger`, `tailgater`

**Hashed names** (1) - `Alternate_Walk_Finished`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (475), `IS_PED_INJURED` (275), `GET_GAME_TIMER` (180), `IS_VEHICLE_DRIVEABLE` (127), `DOES_ENTITY_EXIST` (102), `IS_ENTITY_IN_ANGLED_AREA` (63), `SET_PED_COMBAT_ATTRIBUTES` (59), `DOES_BLIP_EXIST` (47), `PLAYER_ID` (47), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (39), `IS_PED_IN_ANY_VEHICLE` (39), `GET_SCRIPT_TASK_STATUS` (39), `GET_ENTITY_COORDS` (38), `IS_ENTITY_DEAD` (37), `REMOVE_BLIP` (36), `TASK_PLAY_ANIM` (36), `IS_ENTITY_PLAYING_ANIM` (33), `SET_ENTITY_COORDS` (31), `GIVE_WEAPON_TO_PED` (30), `TASK_FOLLOW_NAV_MESH_TO_COORD` (29), `SET_ENTITY_HEADING` (29), `SET_ENTITY_HEALTH` (27), `GET_ENTITY_MODEL` (27), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (26), `WAIT` (25), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (25), `REQUEST_MODEL` (25), `SET_MODEL_AS_NO_LONGER_NEEDED` (25), `HAS_MODEL_LOADED` (24), `CLEAR_HELP` (22)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x25 · `0.5f` x20 · `3.4f` x16 · `25.6721f` x11 · `3.3987f` x11 · `2.125f` x11 · `25.85983f` x10 · `-1098.932f` x10 · `-43.78194f` x10 · `2.5625f` x10 · `6.75f` x10 · `9.75f` x10 · `26.3444f` x8 · `3.3985f` x8 · `-39.62799f` x8 · `-1099.24f` x8 · `25.25259f` x8 · `-1085.27f` x8 · `-1655.59f` x8 · `3.5754f` x7 · `0.2f` x7 · `-41.4259f` x6 · `-1099.648f` x6 · `26.0534f` x6

## Other strings

Literals whose consuming native was not classified:

`Lamar`, `Franklin`, `FIRING_PATTERN_FULL_AUTO`, `missarmenian2lamar_idles`, `MotionState_Run`, `ARM2_F01`, `ARM2_FIGHT_START`, `AR2_BU12`, `missarmenian2`, `ARM2_HLP07b`, `bison`, `baller`, `schwarzer`, `ARM2_CHASE_START`, `arm2VAGOSCAR`, `tailgater`, `Mexgoon_1`, `Siemon`, `bullet`, `asterope`, `ARM2_CAR`, `bagger`, `ARM2_HLP13`, `ARM2_GET4`, `ARM2_F07`, `AR2_BU03`, `Arm2bum`, `AR2_AN04b`, `open_garage_franklin`, `ARM2_INS18`

---

Source: `decompiled_scripts/armenian2.c`
