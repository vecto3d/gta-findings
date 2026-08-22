# fbi4.c

SP missions script. 8 anim dicts; 8 models; 1 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 139,362 |
| Functions | 1,121 (201 unique, 920 shared) |
| Unique lines | 16,680 (12.0% of file) |

## Assets

**Animation dictionaries** (8) - `missfbi4`, `misssagrab`, `missheat`, `misscommon@std_take_off_masks`, `missfbi4leadinoutfbi_4_mcs_3`, `mini@strip_club@idles@bouncer@idle_a`, `mini@strip_club@idles@bouncer@idle_c`, `shake_cam_all@`

**Animations** (19) - `missfbi4`, `misscommon@std_take_off_masks`, `take_off_mask_ds`, `REACT_Explosion`, `missheat`, `_binoculars_trevor`, `missfbi4leadinoutfbi_4_mcs_3`, `_leadin_michael`, `mini@strip_club@idles@bouncer@idle_a`, `idle_a`, `mini@strip_club@idles@bouncer@idle_c`, `idle_c`, `Idle_Loop_Devin`, `push_agents_agent2`, `push_agents_agent1`, `push_agents_player0`, `Guard_Dead_DS`, `Guard_Dead_PS`, `binoculars_loop`

**Models and props** (8) - `s_m_y_cop_01`, `s_m_y_swat_01`, `s_m_m_armoured_01`, `s_m_y_devinsec_01`, `prop_binoc_01`, `prop_cs_envolope_01`, `prop_securityvan_lightrig`, `prop_phone_ing`

**Audio banks** (3) - `SCRIPT\SIREN_DISTANT`, `SCRIPT\FBI_04_HEAT_02`, `SCRIPT\FBI_04_HEAT_GARBAGE_TRUCK_EXPLODE`

**Sounds** (31) - `FBI_4_CUTSCENE_TRUCK`, `FBI_4_CUTSCENE_BINOCULARS`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `FBI_4_SHOOTOUT_FRANKLIN`, `FBI_4_PICKUP_TRUCK_INT`, `FBI_4_GO_TO_ALLEYWAY`, `FBI_4_SHOOTOUT_MICHAEL`, `FBI_4_SHOOTOUT_TREVOR`, `FBI_4_COLLISION_RAYFIRE`, `FBI_4_TRUCK_SMASH_MAIN`, `FBI_4_BLOCK_THE_STREET`, `FBI_04_HEAT_SOUNDS`, `FBI_4_DRIVE_TO_CYPRUS_FLATS`, `Hit_out`, `Distant_Sirens`, `FBI_4_GO_TO_MEETING`, `FBI_4_DESTROY_TRUCK`, `FBI_4_COPS_ARRIVE`, `FBI_4_PREP_FOR_COPS`, `FBI_4_RIG_EXPLOSIVES`, `FBI_4_EXPLOSION_RAYFIRE`, `Short_Transition_In`, `FBI_04_HEAT_C4_DOORS`, `RURAL_BANK_HEIST_SETUP_HIJACK_SCENE`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `Distant_Sirens_Skip_Start`, `Garbage_Truck_Explosion`, `1st_Person_Transition`, `Securicar_Horn`, `SIRENS_DISTANT_01_MASTER`

**Scaleform movies** (1) - `binoculars`

**Particle effects** (1) - `scr_fbi4_trucks_crash`

**Text labels** (16) - `TREVOR`, `COP`, `AGENT1`, `AGENT2`, `NULL`, `EXTRASUNNY`, `CNTRY1`, `OFF`, `cntry_god36`, `cntry_god34`, `cntry_god33`, `cntry_god32`, `cntry_god31`, `cntry_god7`, `cntry_god3`, `cntry_god15`

**Waypoint recordings** (3) - `heat1`, `heat3`, `heat2`

**Vehicle recordings** (3) - `lkheat`, `lkcountry`, `lkfbi4`

**Timecycle modifiers** (1) - `telescope`

**Stats** (12) - `sp0_helis_exploded`, `sp1_helis_exploded`, `sp2_helis_exploded`, `sp0_cars_cops_exploded`, `sp1_cars_cops_exploded`, `sp2_cars_cops_exploded`, `sp0_kills_swat`, `sp1_kills_swat`, `sp2_kills_swat`, `sp0_kills_cop`, `sp1_kills_cop`, `sp2_kills_cop`

**Hashed names** (1) - `EXP_VFXTAG_FBI4_TRUCK_DOORS`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (347), `REQUEST_VEHICLE_RECORDING` (206), `HAS_VEHICLE_RECORDING_BEEN_LOADED` (188), `DOES_ENTITY_EXIST` (188), `IS_PED_INJURED` (141), `GET_GAME_TIMER` (122), `REQUEST_MODEL` (120), `HAS_MODEL_LOADED` (115), `GET_ENTITY_COORDS` (89), `IS_VEHICLE_DRIVEABLE` (86), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (77), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (64), `CREATE_VEHICLE` (58), `SET_MODEL_AS_NO_LONGER_NEEDED` (53), `SET_PED_COMBAT_ATTRIBUTES` (53), `DOES_BLIP_EXIST` (49), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (48), `SET_PED_SPHERE_DEFENSIVE_AREA` (46), `START_PLAYBACK_RECORDED_VEHICLE` (45), `CLOSE_SEQUENCE_TASK` (45), `OPEN_SEQUENCE_TASK` (44), `TASK_PERFORM_SEQUENCE` (44), `FORCE_PLAYBACK_RECORDED_VEHICLE_UPDATE` (43), `CLEAR_SEQUENCE_TASK` (43), `IS_ENTITY_DEAD` (42), `SKIP_TIME_IN_PLAYBACK_RECORDED_VEHICLE` (39), `PLAYER_ID` (39), `DELETE_PED` (38), `IS_ENTITY_IN_ANGLED_AREA` (37), `STOP_PLAYBACK_RECORDED_VEHICLE` (35)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x59 · `-1982.81f` x37 · `798.06f` x19 · `1013.58f` x11 · `-2445.88f` x11 · `840.267f` x11 · `-2312.316f` x11 · `29.342f` x11 · `863.364f` x11 · `-2314.499f` x11 · `32.342f` x11 · `890.4393f` x10 · `-2346.476f` x10 · `29.3413f` x9 · `1372.22f` x8 · `-2752.3f` x8 · `30.15f` x8 · `0.01f` x8 · `906.8f` x7 · `-2365.1f` x7 · `1.1f` x7 · `50.9983f` x7 · `901.9453f` x7 · `-2383.368f` x7

## Other strings

Literals whose consuming native was not classified:

`heataud`, `michael`, `franklin`, `default_scripted_camera`, `HeatAud`, `trevor`, `police3`, `FIRING_PATTERN_FULL_AUTO`, `trevors_car`, `cntry_help8`, `cntry_fail5`, `Truck_Crash_Stream`, `FBI_04_HEAT_SOUNDS`, `stanier`, `player`, `cntry_fail7`, `heat_tofar0`, `trash`, `towtruck`, `cntry_fail8`, `cntry_fail3`, `cntry_fail18`, `cntry_fail6`, `park_truck`, `cntry_god13`, `fbi_bin_lorry`, `fbi_truck`, `fbi_4_mcs_3_concat`, `polmav`, `intruder`

---

Source: `decompiled_scripts/fbi4.c`
