# epsilon8.c

SP strangers and freaks script. 2 anim dicts; 15 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 49,266 |
| Functions | 514 (48 unique, 466 shared) |
| Unique lines | 5,698 (11.6% of file) |

## Assets

**Animation dictionaries** (2) - `rcmepsilonism8`, `move_ped_wpn_jerrycan_generic`

**Animations** (11) - `rcmepsilonism8`, `bag_handler_load_walk_away_left`, `worship_base`, `jump_off_heli`, `worship_exit`, `worship_idle_a`, `worship_enter`, `security_greet`, `security_idle`, `grab_all_4_bags_carrier`, `bag_handler_walk`

**Models and props** (15) - `s_m_m_highsec_01`, `a_m_y_epsilon_01`, `p_ld_heist_bag_s_1`, `sentinel`, `tailgater`, `tractor`, `maverick`, `landstalker`, `a_f_y_epsilon_01`, `a_m_y_epsilon_02`, `taxi`, `sadler`, `habanero`, `schafter2`, `rumpo`

**Sounds** (3) - `EPSILONISM_08_COMPLIANCE`, `EPSILONISM_08_CHOPPER`, `EPSILONISM_08_NON_COMPLIANCE`

**Speech contexts** (7) - `SPEECH_PARAMS_FORCE`, `EPS8_ANAA`, `EPSGUARD2`, `EPS8_AOAA`, `EPSGUARD7`, `EPS8_APAA`, `EPSGUARD8`

**Texture dicts** (1) - `helicopterhud`

**Text labels** (13) - `EPS8AU`, `K1FFL0M`, `EPSGUARD2`, `EPSGUARD8`, `CRIS`, `NULL`, `K1FFL0M1`, `EPSGUARD`, `EPSPILOT`, `EPSGUARD7`, `EPS8`, `MICHAEL`, `EPSGUARD4`

**Scenarios** (1) - `WORLD_HUMAN_GUARD_STAND`

**Waypoint recordings** (8) - `Eps8LS01`, `Eps8EPED`, `Eps8TRAFFIC01`, `Eps8TRAFFIC02`, `Eps8TRAFFIC03`, `Eps8TRAFFIC04`, `Eps8TRAFFIC05`, `Eps8TRAFFIC06`

**Vehicle recordings** (1) - `Ep8Heli01`

**Relationship groups** (3) - `Epsilon`, `EpsilonCivilian`, `gang`

**Vehicle mods** (4) - `tailgater`, `landstalker`, `sentinel`, `sentinel2`

**Stats** (1) - `num_epsilon_step`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (226), `GET_GAME_TIMER` (98), `SET_PED_COMPONENT_VARIATION` (61), `IS_PED_IN_VEHICLE` (53), `IS_ENTITY_DEAD` (51), `SET_PED_COMBAT_ATTRIBUTES` (48), `DOES_ENTITY_EXIST` (39), `DOES_BLIP_EXIST` (29), `GET_SCRIPT_TASK_STATUS` (28), `IS_ENTITY_IN_ANGLED_AREA` (25), `GET_ENTITY_COORDS` (24), `GIVE_WEAPON_TO_PED` (20), `REMOVE_ENTITY_FROM_AUDIO_MIX_GROUP` (18), `TASK_LOOK_AT_ENTITY` (18), `SET_PED_RELATIONSHIP_GROUP_HASH` (18), `TASK_COMBAT_PED` (17), `SET_BLIP_SCALE` (17), `ADD_ENTITY_TO_AUDIO_MIX_GROUP` (17), `SET_MODEL_AS_NO_LONGER_NEEDED` (16), `IS_WAYPOINT_PLAYBACK_GOING_ON_FOR_VEHICLE` (15), `SET_PED_ACCURACY` (15), `SET_PED_SHOOT_RATE` (15), `TASK_VEHICLE_FOLLOW_WAYPOINT_RECORDING` (14), `HAS_MODEL_LOADED` (14), `REQUEST_MODEL` (14), `SET_ENTITY_IS_TARGET_PRIORITY` (14), `DETACH_ENTITY` (13), `GET_SYNCHRONIZED_SCENE_PHASE` (13), `SET_PED_KEEP_TASK` (13), `GIVE_WEAPON_COMPONENT_TO_PED` (13)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x5 · `0.25f` x4 · `0.075f` x4 · `-0.3f` x4 · `-358.0764f` x4 · `-88.2705f` x4 · `44.5901f` x4 · `0.2f` x4 · `-0.1f` x4 · `0.4f` x3 · `-1.5f` x3 · `47043.75f` x3 · `-366.3542f` x3 · `-107.6003f` x3 · `31.93177f` x3 · `-355.0581f` x3 · `-74.91284f` x3 · `55.84066f` x3 · `85.25f` x3 · `-696.1459f` x3 · `41.7659f` x3 · `42.218f` x3 · `25.269f` x3 · `-711.6323f` x2

## Other strings

Literals whose consuming native was not classified:

`schafter2`, `EPS8_CH2`, `taxi`, `sadler`, `rumpo`, `habanero`, `EPSILONISM_08_NON_COMPLIANCE_ENEMY_CAR`, `rcmepsilonism8`, `EPS8_T1`, `EPS8_LS`, `EPSILONISM_08_CLOSE_CAR_MG`, `EPS8_16`, `EPS8_12`, `EPS8_E1`, `SE_LOS_SANTOS_EPSILONISM_BUILDING_01`, `EPS8_11`, `EPS8_CH3`, `EPS8_START`, `landstalker`, `EPS8_06`, `EPS8_25`, `EPS8_05`, `sentinel`, `maverick`, `Michael`, `tailgater`, `EPS8_19`, `EPS8_18`, `EPS8_FAIL`, `Force cleanup [TERMINATING]`

---

Source: `decompiled_scripts/epsilon8.c`
