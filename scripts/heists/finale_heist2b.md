# finale_heist2b.c

Heists script. 3 anim dicts; 20 models; 1 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 148,385 |
| Functions | 1,176 (169 unique, 1,007 shared) |
| Unique lines | 25,444 (17.1% of file) |

## Assets

**Animation dictionaries** (3) - `VEH@BULLDOZER@BASE`, `shake_cam_all@`, `MOVE_ACTION@P_M_ONE@ARMED@1H@IDLE@HIGH_ENERGY@D`

**Animations** (28) - `cutter_run`, `cutter_spinup`, `cutter_spindown`, `idle`, `intro_90r`, `sweep_medium`, `outro_90r`, `push_trolly_walk`, `push_trolly_stand`, `base`, `start_engine`, `idle_to_leansit`, `leansit_to_idle`, `signal_forward`, `reload_rocket_a`, `push_out_vault_l`, `put_to_container_r`, `push_out_vault_r`, `put_to_container_l`, `idle_a`, `idle_b`, `idle_c`, `idle_d`, `idle_e`, `idle_f`, `michael_call_franklin`, `michael_call_franklin_goon`, `michael_call_franklin_cardoor`

**Models and props** (20) - `prop_golf_ball`, `V_FINALEBANK_PS_VAULT_INTACT`, `V_FINALEBANK_PS_VAULT_BLOWN`, `oracle2`, `prop_partsbox_01`, `baller2`, `prop_rope_hook_01`, `tailgater`, `prop_gold_cont_01`, `prop_gold_cont_01b`, `prop_large_gold`, `s_m_y_cop_01`, `prop_gold_vault_gate_01`, `v_ilev_fin_vaultdoor`, `prop_crate_10a`, `prop_woodpile_01b`, `s_m_y_swat_01`, `s_m_y_blackops_01`, `Prop_Gold_Cont_01`, `Prop_Gold_Cont_01^1`

**Audio banks** (6) - `BIG_SCORE_GOLD_CAGE_COLLISIONS`, `FBI_HEIST_3B_SHOOTOUT`, `BIG_SCORE_CUTTER_01`, `BIG_SCORE_CUTTER_02`, `BIG_SCORE_GOLD_CAGE_LOCK`, `BIG_SCORE_GOLD_VAULT_EXPLOSION`

**Sounds** (35) - `BIG_SCORE_3B_SOUNDS`, `BS_2B_ESCAPE_START`, `BS_2B_VAULT_SHOOTOUT_02`, `BS_2B_NOOSE_ABSEIL_SCENE`, `BS_2B_PLANT_C4`, `BS_2B_WAIT_FOR_DETONATION`, `BS_2B_DROP_GOLD_CUTSCENE`, `BS_2B_FOCUS_ON_TRAIN`, `BS_2B_FOCUS_ON_HELI`, `BS_2B_LESTER_RPG_scene`, `BS_2B_UNDERGROUND_GARAGE`, `BS_2B_CHOPPER_ARRIVES`, `BS_2B_VANS_ARRIVE`, `BS_2B_SHOOTOUT_ACROSS_STREET`, `BS_2B_ASCEND_TO_NEXT_AREA`, `BS_2B_SHOOTOUT_CONT`, `BS_2B_VAULT_SHOOTOUT_01`, `BS_2B_VAULT_RAYFIRE`, `BS_2B_GET_TO_BANK`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `Gold_Cage_Collisions`, `BS_2B_GET_TO_AIRSTRIP`, `BS_2B_GET_TO_TRAIN`, `BS_2B_HELI_CHASE`, `BS_2B_DRIVE_AWAY`, `BS_2B_HELI_TAKE_GOLD`, `Gold_Vault_Explosions`, `BS_2B_DRILL_THROUGH_VAULT`, `Muffling`, `Hit_Out`, `Short_Transition_In`, `1st_Person_Transition`, `SPL_RPG_DIST_FLIGHT_MASTER`, `SPL_RPG_NPC_SHOT_MASTER`, `CUTTER`

**Particle effects** (1) - `scr_bigscore_rpg_trail`

**Text labels** (22) - `MICHAEL`, `FRANKLIN`, `TREVOR`, `LESTER`, `COP`, `81TDS937`, `NULL`, `BS2BAUD`, `OFF`, `FINAL3B`, `54AJM610`, `EDDIE`, `TALINA`, `KARIM`, `GUSTAVO`, `KARL`, `PACKIE`, `CHEF`, `HUGH`, `NORM`, `DARYL`, `SURROUNDED`

**Scenarios** (2) - `Grapeseed_Planes`, `WORLD_HUMAN_SMOKING`

**Relationship groups** (4) - `player`, `COPS`, `COPS2`, `NEUTRAL`

**Interiors and entity sets** (5) - `GtaMloRoom010`, `v_31_tun_02`, `v_31_tun_03`, `v_finalebank`, `GtaMloRoomTun2`

**Doors** (2) - `v_ilev_fingate`, `v_ilev_finelevdoor01`

**Scripts launched** (1) - `mission_stat_watcher`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (509), `IS_PED_INJURED` (286), `GET_GAME_TIMER` (283), `DOES_ENTITY_EXIST` (262), `GET_ENTITY_COORDS` (209), `IS_VEHICLE_DRIVEABLE` (166), `IS_ENTITY_DEAD` (157), `VDIST2` (133), `SET_PED_COMBAT_ATTRIBUTES` (132), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (116), `SET_PED_SPHERE_DEFENSIVE_AREA` (108), `PLAYER_ID` (98), `SET_PED_CONFIG_FLAG` (98), `IS_ENTITY_IN_ANGLED_AREA` (96), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (94), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (93), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (89), `DISABLE_CONTROL_ACTION` (89), `TASK_SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (87), `SET_MODEL_AS_NO_LONGER_NEEDED` (86), `DOES_BLIP_EXIST` (83), `REMOVE_VEHICLE_RECORDING` (73), `HAS_MODEL_LOADED` (71), `SET_ENTITY_COORDS` (70), `FREEZE_ENTITY_POSITION` (69), `GET_SCRIPT_TASK_STATUS` (67), `SETTIMERB` (62), `REQUEST_MODEL` (62), `OPEN_SEQUENCE_TASK` (62), `CLOSE_SEQUENCE_TASK` (62)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x128 · `0.001f` x22 · `2.5f` x14 · `0.05f` x13 · `0.1f` x13 · `0.99f` x13 · `-154.0717f` x12 · `-549.3301f` x12 · `16.4f` x10 · `0.6f` x10 · `1.5f` x10 · `39.4888f` x10 · `48.7064f` x10 · `-1.5f` x9 · `3.5f` x9 · `0.0001f` x9 · `-173.89f` x9 · `-654.68f` x9 · `33.69f` x9 · `7.25f` x8 · `31.7f` x8 · `-132.2f` x8 · `-674.7f` x8 · `41.6f` x8

## Other strings

Literals whose consuming native was not classified:

`FIRING_PATTERN_FULL_AUTO`, `Franklin`, `Michael`, `gunman_selection_1`, `seat_dside_r`, `GENERIC_WAR_CRY`, `BIG_SCORE_HEIST_VAULT_ALARMS`, `player`, `BS2B_WAITM`, `BS2B_WAITF`, `BIG_SCORE_3B_SOUNDS`, `Lester`, `Trevor`, `BS2B_MOVEUP`, `BS2B_LETSGO`, `DEFAULT_SCRIPTED_CAMERA`, `bs_2b_mcs_1`, `BS_GOLD_TARGET_HELI_group`, `F3B_ABANCREW`, `HAND_SHAKE`, `AllowScriptedSpeechInSlowMo`, `buzzard`, `tailgater`, `AZL_BIG_SCORE_2B_WINDFARM_TURBINES`, `F3B_GETBACKHELI`, `ROAD_VIBRATION_SHAKE`, `BS2B_DOWNF`, `BS2B_DOWNM`, `MOVE_IN`, `DEFAULT_ACTION`

---

Source: `decompiled_scripts/finale_heist2b.c`
