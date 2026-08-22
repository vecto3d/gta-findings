# docks_heista.c

Heists script. 7 anim dicts; 27 models; 1 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 136,928 |
| Functions | 1,071 (119 unique, 952 shared) |
| Unique lines | 13,451 (9.8% of file) |

## Assets

**Animation dictionaries** (7) - `missheistdocks2a@alert`, `missheistdocks2a@crouch`, `missswitch`, `swimming@scuba`, `missheistdocks2a@swimtocontainer`, `missheistdocks2aswitchig_8`, `SWIMMING@scuba`

**Animations** (31) - `missheistdocks2a`, `missheistdocks2a@alert`, `IDLE_guard`, `missheistdocks2a@crouch`, `missheistdocks2aig_1`, `spot_high`, `stabbing_guard_guard`, `missheistdocks2aswitchig_7`, `idle_guard`, `enter_crouch_a`, `crouching_idle_a`, `missheistdocks2aswitchig_8`, `ig_8_switch`, `SWIMMING@scuba`, `dive_run`, `missheistdocks2a@swimtocontainer`, `Michael_Swim_to_Container`, `missswitch`, `mid_mission_inside_helicopter_trevor`, `stabbing_guard_michael`, `IG_1_MichaelEnterBoat_Action`, `IG_1_MichaelEnterBoat_Action_DOOR`, `IG_1_MichaelEnterBoat_Stealth`, `IG_1_MichaelEnterBoat_Stealth_DOOR`, `IG_7_m_door_f_sniping_franklin`, `IG_7_F_SNIPING_M_CLIMBING_FRANKLIN`, `ig_1_michaelclimboverboat`, `missheistdocks2aswitchig_6`, `IG_6_f_sniping_m_dingy_franklin`, `IG_7_f_sniping_franklin`, `IG_7_m_dinghy_f_sniping_michael`

**Models and props** (27) - `prop_mil_crate_02`, `landstalker`, `prop_cratepile_07a`, `s_m_y_blackops_01`, `dinghy`, `prop_military_pickup_01`, `prop_flare_01`, `s_m_y_swat_01`, `p_po1_01_doorm_s`, `ig_wade`, `ig_floyd`, `prop_cs_sub_rope_01`, `submersible`, `p_cs_sub_hook_01_s`, `prop_rope_hook_01`, `polmav`, `buzzard`, `port_xr_door_05`, `IG_1_MichaelEnterBoat_Action_cam`, `IG_1_MichaelEnterBoat_stealth_cam`, `IG_7_m_door_f_sniping_cam`, `IG_7_F_SNIPING_M_CLIMBING_CAM`, `ig_1_michaelclimboverboat_cam`, `v_res_tre_sofa_mess_c`, `IG_6_f_sniping_m_dingy_franklin_cam`, `IG_7_f_sniping_cam`, `IG_7_m_dinghy_f_sniping_cam`

**Audio banks** (4) - `PORT_OF_LS_ATTACH_CARGO`, `PORT_OF_LS_SHIP_DOOR`, `script\underwater`, `PORT_OF_LS_SNIPING`

**Sounds** (41) - `DH2A_SNIPE_GUARDS_scene`, `docks_heist_finale_2a_sounds`, `DH2A_SHOOTOUT_SNIPING_SCENE`, `DH2A_PLANT_BOMBS_SCENE`, `DH2A_SHOOTOUT_SCENE`, `DH2A_SNIPING_SCENE`, `DH2A_SWIM_TO_CONTAINER`, `DH2A_CHOPPER_SHOOTING`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `DOCKS_HEIST_FINALE_2A_SOUNDS`, `DH2A_RAYFIRE`, `DH_2A_DETONATE_BOMBS`, `DH2A_CHOPPER_ARRIVES`, `DH2A_PLANT_BOMBS_scene`, `DH2A_GET_TO_VANTAGE_POINT`, `dh2a_shootout_sniping_scene`, `BODY_FALL_DIVE_WATER_MASTER`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `DH2A_MICHAEL_DASH_AND_DIVE`, `DH2A_SNIPING_scene`, `dh2a_plant_bombs_scene`, `dh2a_sniping_scene`, `DH2A_CONTROL_SUB`, `DH2A_PREPARE_DETONATION`, `SNIPER_SHOT_SPLAT`, `SNIPER_SHOT_SPRAY`, `rebreather`, `swimspeed`, `dock_heist_underwater_scene`, `dh2a_shootout_scene`, `1st_Person_Transition`, `Attach_Cargo`, `CONDUCTORS_PORT_OF_LS_2A_LOOP`, `Hit_Out`, `Short_Transition_In`, `SNIPER_SHOT_ZIP`, `bombdistance`, `uw_ambience`, `foot_swish`, `sonar_pulse`

**Particle effects** (1) - `scr_bio_flare`

**Text labels** (15) - `D2AAUD`, `MICHAEL`, `FRANKLIN`, `DH2AREC`, `TREVOR`, `MERRYWEATHER5`, `DCKH_BOMB2`, `NULL`, `FLOYD`, `DCKH_BOMB1`, `DCKH_SNIPER`, `MERRYWEATHER1`, `MERRYWEATHER2`, `MERRYWEATHER3`, `MERRYWEATHER4`

**Waypoint recordings** (3) - `docksheist2A02`, `docksheist2A03`, `docksheist2a01`

**Vehicle recordings** (2) - `DH2AREC`, `dh2arec`

**Relationship groups** (2) - `buddy`, `enemies`

**Timecycle modifiers** (2) - `ship_explosion_underwater`, `PORT_heist_underwater`

**Vehicle mods** (3) - `tailgater`, `buffalo`, `forklift`

**Scripts launched** (1) - `docks2ASubHandler`

**Hashed names** (2) - `v_fakeboatpo1sh1`, `v_fakeboatpo1sh1sunk`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (225), `GET_ENTITY_COORDS` (113), `DOES_ENTITY_EXIST` (98), `GET_GAME_TIMER` (96), `TASK_FOLLOW_NAV_MESH_TO_COORD` (95), `MODIFY_WATER` (81), `WAIT` (65), `CLEAR_SEQUENCE_TASK` (65), `PLAYER_ID` (64), `GET_RANDOM_INT_IN_RANGE` (61), `DOES_BLIP_EXIST` (57), `SET_ENTITY_LOD_DIST` (53), `OPEN_SEQUENCE_TASK` (50), `CLOSE_SEQUENCE_TASK` (50), `TASK_PERFORM_SEQUENCE` (50), `CREATE_OBJECT` (47), `SET_PED_SPHERE_DEFENSIVE_AREA` (44), `SET_ENTITY_ROTATION` (42), `CREATE_VEHICLE` (38), `CLEAR_PED_TASKS` (37), `GET_DISTANCE_BETWEEN_COORDS` (37), `TRIGGER_MUSIC_EVENT` (36), `IS_AUDIO_SCENE_ACTIVE` (36), `SET_VEHICLE_COLOUR_COMBINATION` (35), `SET_ENTITY_COORDS` (33), `START_AUDIO_SCENE` (32), `IS_ENTITY_AT_COORD` (32), `REPLAY_RECORD_BACK_FOR_TIME` (31), `NEW_LOAD_SCENE_STOP` (30), `SET_CURRENT_PED_WEAPON` (30)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x109 · `0.5f` x99 · `8.3191f` x63 · `1.5f` x42 · `5.0013f` x18 · `-2377.504f` x15 · `0.1f` x13 · `5.0012f` x13 · `-143.8203f` x13 · `-2488.261f` x13 · `43.4412f` x13 · `-222.02f` x10 · `8.31911f` x10 · `-0.75f` x10 · `-2383.558f` x10 · `5.000676f` x10 · `-2375.396f` x9 · `0.4f` x9 · `16.3326f` x8 · `-165.34f` x8 · `-2350.03f` x8 · `0.2f` x8 · `12.3329f` x8 · `8.3192f` x8

## Other strings

Literals whose consuming native was not classified:

`dinghy`, `DCKH_QUICK`, `landstalker`, `PORT_OF_LS_HEIST_SHIP_ALARMS`, `missheistdocks2aswitchig_7`, `missheistdocks2a`, `missheistdocks2aig_1`, `WORLD_HUMAN_GUARD_STAND`, `DH2A_MOVE1`, `DH2A_DECK2`, `FIRING_PATTERN_FULL_AUTO`, `submersible`, `Michael`, `player_zero`, `Trevor`, `DH2A_2A`, `dh2arec`, `SUNK_SHIP_FIRE`, `DH2A_CLEAR`, `buzzard`, `Franklin`, `player`, `DCKH_PROTECT`, `DH2A_MVE_NS`, `DCKH_BOMB2`, `docksheist2a02`, `docksheist2a03`, `missheistdocks2aswitchig_8`, `lsdh_2a_int`, `player_two`

---

Source: `decompiled_scripts/docks_heista.c`
