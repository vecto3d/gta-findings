# carsteal3.c

Heists script. 13 anim dicts; 29 models; 3 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 122,119 |
| Functions | 834 (107 unique, 727 shared) |
| Unique lines | 10,915 (8.9% of file) |

## Assets

**Animation dictionaries** (13) - `misscarsteal4@actor`, `misscarsteal4@director_grip`, `dead`, `move_m@intimidation@cop@unarmed`, `reaction@intimidation@cop@unarmed`, `misscarsteal4@toilet`, `misscarsteal4@actress`, `misscarsteal4@aliens`, `misscarsteal4@meltdown`, `missarmenian3_tryopendoor`, `misscarsteal4leadinoutcar_4_ext`, `move_injured_generic`, `move_m@generic`

**Animations** (48) - `misscarsteal4@actor`, `misscarsteal4@director_grip`, `misscarsteal4@toilet`, `misscarsteal4leadinoutcar_4_ext`, `actor_warming_up_loop_1`, `actor_warming_up_loop_2`, `actor_warming_up_loop_3`, `actor_warming_up_loop_4`, `misscarsteal4@actress`, `leadin_action_devin`, `mcs_2_loop_grip1`, `react_director`, `assistant_berated`, `actor_berating_assistant`, `desperate_toilet_base_idle`, `desperate_toilet_idle_a`, `desperate_toilet_idle_b`, `desperate_toilet_idle_c`, `end_loop_grip`, `end_loop_director`, `leadin_loop_devin`, `beginning_loop_director`, `misscarsteal4@meltdown`, `misscarsteal4@aliens`, `react_grip`, `flee_exit_fwd_director`, `dead`, `dead_d`, `beginning_loop_grip`, `car_fight_girl`, `eject_girl`, `stumble`, `dazed_idle`, `missarmenian3_tryopendoor`, `lockeddoor_tryopen`, `assistant_loop`, `actor_berating_loop`, `car_panic_girl`, `reaction@intimidation@cop@unarmed`, `intro`, `move_m@intimidation@cop@unarmed`, `idle`, `_rehearsal_actor_a`, `_rehearsal_actor_b`, `_rehearsal_camera_man`, `_rehearsal_boom_op`, `rehearsal_base_idle_director`, `sit`

**Models and props** (29) - `u_m_m_spyactor`, `s_m_y_grip_01`, `prop_tyre_spike_01`, `prop_a_trailer_door_01`, `PROP_HUMAN_MOVIE_STUDIO_LIGHT`, `u_f_y_spyactress`, `u_m_m_filmdirector`, `s_m_m_movalien_01`, `prop_sc1_06_gate_l`, `prop_sc1_06_gate_r`, `s_m_m_security_01`, `A_M_M_GENERICMALE_01_WHITE_MINI_01`, `A_M_M_GENERICMALE_01_WHITE_MINI_02`, `A_M_M_GENERICMALE_01_WHITE_MINI_03`, `A_M_M_GENERICMALE_01_WHITE_MINI_04`, `PROP_HUMAN_MOVIE_BULB`, `A_M_Y_Vinewood_03_White_FULL_01 `, `A_F_Y_VINEWOOD_01_WHITE_FULL_01`, `a_f_y_hipster_04`, `prop_studio_light_02`, `prop_direct_chair_02`, `p_cs_clipboard`, `prop_portaloo_01a`, `prop_ld_greenscreen_01`, `prop_v_cam_01`, `prop_v_bmike_01`, `ig_milton`, `u_m_y_antonb`, `ig_devin`

**Audio banks** (2) - `CAR_THEFT_MOVIE_LOT`, `CAR_STEAL_3_SCREAM`

**Sounds** (10) - `CAR_3_INSIDE_STUDIO`, `CAR_3_ESCAPE_SECURITY`, `CAR_3_TAKE_OUT_ACTOR`, `CAR_3_GO_TO_GARAGE`, `CAR_STEAL_3_AGENT`, `CAR_3_ACTIVATE_EJECTOR_SEAT`, `CAR_STEAL_3_AGENT_TYRE_BURST`, `CAR_THEFT_MOVIE_LOT_DROP_SPIKES`, `CAR_THEFT_MOVIE_LOT_EJECT_SEAT`, `Ejector_Scream`

**Particle effects** (3) - `scr_carsteal3_tyre_spikes`, `scr_carsteal4_tyre_spiked`, `scr_carsteal3_eject`

**Text labels** (16) - `CST4AUD`, `ANTON`, `CST4RUNNER3`, `CST4ACTRESS`, `FREEZE`, `FRANKLIN`, `CST4DIRECTOR`, `CST4ACTOR`, `COP`, `EXTRASUNNY`, `MOLLY`, `NULL`, `DYLAN`, `FITCH`, `CAR4`, `DEVIN`

**Scenarios** (3) - `WORLD_HUMAN_GUARD_STAND`, `MOVIE_STUDIO_SECURITY`, `WORLD_HUMAN_STAND_IMPATIENT`

**Relationship groups** (1) - `FilmCrew`

**Doors** (3) - `prop_bh1_03_gate_l`, `prop_bh1_03_gate_r`, `prop_sc1_06_gate_r`

**Vehicle mods** (1) - `jb700`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (185), `DOES_ENTITY_EXIST` (161), `IS_ENTITY_DEAD` (120), `GET_GAME_TIMER` (102), `IS_PED_INJURED` (91), `SET_PED_COMBAT_ATTRIBUTES` (72), `IS_ENTITY_PLAYING_ANIM` (70), `SET_PED_COMPONENT_VARIATION` (61), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (51), `DOES_BLIP_EXIST` (51), `PLAYER_ID` (48), `IS_VEHICLE_DRIVEABLE` (46), `ARE_STRINGS_EQUAL` (45), `GET_ENTITY_COORDS` (45), `GET_ENTITY_ANIM_CURRENT_TIME` (35), `REMOVE_BLIP` (32), `GET_RANDOM_INT_IN_RANGE` (32), `IS_ENTITY_IN_ANGLED_AREA` (32), `SET_PED_FLEE_ATTRIBUTES` (32), `REMOVE_ANIM_DICT` (30), `HAS_PED_RECEIVED_EVENT` (30), `IS_AMBIENT_SPEECH_PLAYING` (27), `GET_DISTANCE_BETWEEN_COORDS` (27), `SET_PED_AS_NO_LONGER_NEEDED` (26), `TASK_LOOK_AT_ENTITY` (24), `CLEAR_PED_TASKS` (24), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (24), `SET_COMBAT_FLOAT` (22), `IS_SYNCHRONIZED_SCENE_RUNNING` (22), `IS_DOOR_REGISTERED_WITH_SYSTEM` (22)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x17 · `0.8f` x16 · `0.1f` x10 · `1.5f` x10 · `-1.5f` x10 · `0.5f` x9 · `0.6f` x7 · `34.57f` x5 · `0.75f` x5 · `0.2f` x4 · `0.988f` x4 · `-1130.464f` x4 · `-455.5777f` x4 · `36.56462f` x4 · `44.2f` x3 · `2.5f` x3 · `-1114.511f` x3 · `-501.777f` x3 · `35.81f` x3 · `69.48f` x3 · `-1090.1f` x3 · `-431.85f` x3 · `35.62f` x3 · `41.16f` x3

## Other strings

Literals whose consuming native was not classified:

`Devin`, `CST4_TOILET`, `CST4_MSVOC1_1`, `CST4_MSVOC1_2`, `CST4_MSVOC2_1`, `CST4_MSVOC2_2`, `CST4_MSVOC3_1`, `CST4_MSVOC3_2`, `CST4_MSVOC4_1`, `CST4_MSVOC4_2`, `CST4_ECALLM`, `CST4_MELT`, `CST4_DBRAN`, `SCREAM_PANIC`, `WAVELOAD_PAIN_MALE`, `CST4_MSSPO`, `CAR4_HCARE`, `CST4_ECALLC`, `CST4_SCALL`, `CST4_MSSEC`, `CST4_MSFIG`, `jb700`, `CMN_GENGETIN`, `CST4_BUTTON1`, `CST4_ENDCALL`, `CST4_ASSC`, `CST4_AFLEE1`, `move_injured_generic`, `Franklin`, `spy_actor`

---

Source: `decompiled_scripts/carsteal3.c`
