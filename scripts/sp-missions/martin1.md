# martin1.c

SP missions script. 8 anim dicts; 31 models; 7 scaleforms; 14 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 154,458 |
| Functions | 1,052 (61 unique, 991 shared) |
| Unique lines | 12,474 (8.1% of file) |

## Assets

**Animation dictionaries** (8) - `missmartin1@pointing_sky1@base`, `missmartin1@exit_plane`, `missmartin1@leadinoutmartin_1_dead_pilot`, `missmartin1@leadinoutmartin_1_ext`, `COMBAT@DAMAGE@WRITHEIDLE_A`, `COMBAT@DAMAGE@WRITHEIDLE_B`, `missmartin1@switch`, `shake_cam_all@`

**Animations** (14) - `missmartin1@exit_plane`, `missmartin1@pointing_sky1@base`, `base`, `missmartin1@switch`, `exit_plane_guy_b`, `exit_plane_guy_a`, `trevor_switch_trevor`, `missmartin1@leadinoutmartin_1_dead_pilot`, `dead_pilot_leadin_loop`, `trevor_switch_case`, `prop_barrel_01a`, `missmartin1@leadinoutmartin_1_ext`, `martin_1_ext_leadin`, `loop_guy_b`

**Models and props** (31) - `a_m_y_business_01`, `s_m_m_pilot_01`, `p_rcss_folded`, `prop_shamal_crash`, `g_m_y_mexgang_01`, `burrito3`, `g_m_y_mexgoon_02`, `shamal`, `s_m_y_barman_01`, `sanchez`, `bus`, `s_m_y_construct_01`, `a_m_m_tramp_01`, `s_m_m_lathandy_01`, `prop_pool_ball_01`, `fusilade`, `hauler`, `patriot`, `baller`, `dilettante`, `freight`, `freightcar`, `freightcont2`, `tornado3`, `dump`, `bobcatxl`, `prop_barrel_01a`, `cs_patricia`, `prop_phone_ing_02`, `player_two`, `p_attache_case_01_s`

**Audio banks** (3) - `MARTIN_1_SNIPER`, `MARTIN_1_01`, `MARTIN_1_02`

**Sounds** (31) - `MARTIN_1_CHASE_DUMP_TRUCK`, `MARTIN_1_SNIPER_CAMERA`, `MARTIN_1_CHASE_MAIN`, `MARTIN_1_CHASE_JUMP_01`, `MARTIN_1_PLANE_CHASE_SCENE`, `MARTIN_1_TRAIN_SCENE`, `MARTIN_1_BULLET_HITS_PLANE_SCENE`, `MARTIN_1_DRIVE_TO_OBSERVATORY`, `MARTIN_1_PLANE_CRASH`, `MARTIN_1_CHASE_JUMP_TRAIN`, `MARTIN_1_DRIVE_BACK`, `MARTIN_1_KILL_PASSENGERS`, `MARTIN_1_FOCUS_CAM`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `y_direction`, `MARTIN1_DISTANT_TRAIN_HORNS_MASTER`, `SUBWAY_TRAIN_HORNS_AIR_HORN`, `SOLOMON_1_JET_SHOT_EXPLODE`, `In`, `SHORT_PLAYER_SWITCH_SOUND_SET`, `Hit_In`, `Short_Transition_In`, `movement_speed`, `Remote_Sniper_Rifle_Move`, `Remote_Sniper_Rifle_Zoom`, `zoom_speed`, `Remote_Sniper_Rifle_Fire`, `SCOPE_UI_MASTER`, `MARTIN_1_PLANE_CRASH_MASTER`, `Hit_Out`, `PLANE_ON_FIRE`

**Scaleform movies** (7) - `SET_ZOOM_LEVEL`, `SET_COMPASS`, `SET_WIND`, `REMOTE_SNIPER_LOADING`, `START_LOADING`, `IS_LOAD_ANIM_FINISHED`, `remote_sniper_hud`

**Particle effects** (14) - `scr_sol1_fire_trail`, `scr_sol1_plane_smoke_loop`, `scr_sol1_plane_wreck`, `scr_sol1_fire_spot`, `scr_sol1_fire_drip`, `scr_sol1_plane_tail_fire`, `scr_sol1_plane_engine_fire`, `scr_sol1_plane_elec_crackle`, `scr_sol1_plane_crash_dust`, `scr_sol1_sniper_impact`, `scr_sol1_plane_smoke`, `Shot1`, `Shot2`, `Shot3`

**Text labels** (21) - `SLM1AUD`, `MICHAEL`, `TREVOR`, `BFHELPTXT2`, `JAVIER`, `BFDAMAGE`, `BFFLOST`, `EXTRASUNNY`, `BFINJEC`, `BFCHASE`, `BFHELPTXT4`, `2SLOW`, `NULL`, `SNIPE4`, `BFDRIVE`, `SNIPE8`, `22LJK483`, `MADRAZO`, `SNIPE5`, `SNIPE7`, `SNIPE9`

**Vehicle recordings** (14) - `BB_SOL_JET`, `DGBFReady`, `DGTitanEntry`, `BB_SOL_BLR`, `BB_SOL_DIL`, `BB_SOL_BUS2`, `DGTitanCrash`, `BB_SOL_TRK`, `BB_SOL_VAN`, `BB_SOL_BUS`, `BB_SOL_DMP`, `BB_SOL_TOR`, `END_MARTIN_1`, `BB_SOL_BOB`

**Timecycle modifiers** (1) - `RemoteSniper`

**Vehicle mods** (3) - `sanchez`, `dump`, `baller`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (329), `DOES_ENTITY_EXIST` (267), `IS_VEHICLE_DRIVEABLE` (128), `SET_PED_COMPONENT_VARIATION` (120), `REQUEST_MODEL` (89), `HAS_MODEL_LOADED` (71), `GET_GAME_TIMER` (67), `SET_MODEL_AS_NO_LONGER_NEEDED` (61), `IS_PED_INJURED` (59), `WAIT` (58), `DOES_BLIP_EXIST` (57), `IS_AUDIO_SCENE_ACTIVE` (54), `GET_ENTITY_COORDS` (52), `REMOVE_BLIP` (42), `GET_ENTITY_MODEL` (41), `DELETE_VEHICLE` (38), `STOP_AUDIO_SCENE` (38), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (36), `IS_MESSAGE_BEING_DISPLAYED` (35), `PLAYER_ID` (35), `IS_PED_IN_ANY_VEHICLE` (35), `IS_PED_IN_VEHICLE` (32), `DOES_PARTICLE_FX_LOOPED_EXIST` (30), `REMOVE_VEHICLE_RECORDING` (30), `IS_SUBTITLE_PREFERENCE_SWITCHED_ON` (30), `IS_THIS_MODEL_A_HELI` (30), `CLEAR_PRINTS` (27), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (26), `REQUEST_VEHICLE_RECORDING` (26), `DELETE_PED` (26)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x15 · `0.5f` x11 · `1360.32f` x11 · `1166.077f` x11 · `89.5f` x10 · `-363.519f` x6 · `1142.171f` x6 · `323.0888f` x6 · `2807.692f` x5 · `4796.449f` x5 · `47.6684f` x5 · `-11.34007f` x5 · `-0.0162f` x5 · `-0.0524f` x5 · `-0.1071f` x5 · `0.9927f` x5 · `1216.6f` x5 · `0.002f` x5 · `-0.3f` x5 · `0.2f` x5 · `47.7f` x5 · `78.1f` x5 · `-1638.618f` x4 · `-2734.44f` x4

## Other strings

Literals whose consuming native was not classified:

`Trevor`, `Michael`, `burrito3`, `shamal`, `sanchez`, `player_two`, `player_zero`, `MotionState_Walk`, `asterope`, `Pilot_Martin_1`, `DEFAULT_SCRIPTED_CAMERA`, `AllowScriptedSpeechInSlowMo`, `SOL1_BUS_JUMP`, `SOL1_TRAIN_JUMP`, `bus`, `baller`, `SOL1_FRANKLIN_STARTS`, `S1_MISS`, `SOL1_APP_ACTIVE`, `mesa`, `SOL1_DRIVE_TO_OBS_RT`, `Martin_1_mcs_1`, `Madrazos_Car`, `Briefcase`, `Trevors_phone`, `stab`, `ShotgunLargeMonolithic`, `ShotgunSmall`, `M1_FAIL1`, `SOL1_AIR_TRAFFIC`

---

Source: `decompiled_scripts/martin1.c`
