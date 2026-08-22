# paparazzo2.c

SP strangers and freaks script. 7 anim dicts; 23 models.

| | |
|---|---|
| Category | SP strangers and freaks |
| Total lines | 59,131 |
| Functions | 682 (151 unique, 531 shared) |
| Unique lines | 10,726 (18.1% of file) |

## Assets

**Animation dictionaries** (7) - `rcmpaparazzo_2`, `move_f@sexy@a`, `RANDOM@CAR_THIEF@waiting_ig_4`, `random@escape_paparazzi@standing@`, `veh@std@ds@base`, `cover@move@base@core`, `rcmpaparazzo_2ig_3`

**Animations** (20) - `rcmpaparazzo_2`, `rcmpaparazzo_2ig_3`, `idle_d`, `RANDOM@CAR_THIEF@waiting_ig_4`, `waiting`, `idle_l_corner_c`, `idle_l_corner_a`, `idle_l_corner_b`, `pm_incar_fuckinlosers`, `pm_incar_gimmethtcam`, `pm_incar_ih8u`, `pm_incar_illsueyou`, `pm_incar_imavirgin`, `pm_incar_itwasyoga`, `shag_action_poppy`, `shag_action_a`, `pm_incar_notdoinanythin`, `shag_loop_poppy`, `shag_loop_a`, `pap_2_rcm_base`

**Models and props** (23) - `prop_pap_camera_01`, `s_m_y_construct_01`, `taxi`, `s_m_y_busboy_01`, `s_f_m_maid_01`, `a_m_m_beach_02`, `prop_npc_phone`, `prop_table_06`, `prop_parasol_03`, `bus`, `blista`, `u_m_y_justin`, `u_f_y_poppymich`, `s_m_m_bouncer_01`, `prop_tool_broom`, `prop_rag_01`, `prop_pipes_02b`, `prop_cablespool_02`, `prop_barrier_wat_04c`, `prop_consign_01a`, `prop_barrier_work06a`, `prop_sign_road_03g`, `prop_sign_road_03m`

**Audio banks** (4) - `PAPARAZZO_02_INTRO`, `SCRIPT\PAPARAZZO_02_A`, `SCRIPT\PAPARAZZO_02_B`, `SCRIPT\PAPARAZZO_02_C`

**Sounds** (15) - `PAPARAZZO_02_SOUNDSETS`, `PAPARAZZO_02_INTRO`, `PAPARAZZO_02_CHASE`, `ZOOM_FUNCTION`, `ZOOM_SPEED`, `ZOOM`, `SMALL_CRASH`, `LOOP_REV`, `BUILDING_SITE_CRASH`, `HIGHREV`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `AMBIENT_SEX`, `ONESHOT_VOLUME`, `CAMERA_FOLEY`

**Texture dicts** (2) - `helicopterhud`, `hud_corner`

**Text labels** (15) - `EXTRASUNNY`, `BEVERLY`, `FRANKLIN`, `POPPY`, `P4P4R4Z0`, `NULL`, `PAP2AUD`, `JUMPED`, `SHAGGER`, `BODYGUARD `, `P0PPYM14`, `PAP2`, `CHASE`, `PAP2UBA`, `OVERCAST`

**Scenarios** (9) - `WORLD_HUMAN_PAPARAZZI`, `WORLD_HUMAN_MOBILE_FILM_SHOCKING`, `WORLD_HUMAN_CLIPBOARD`, `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_MAID_CLEAN`, `WORLD_HUMAN_AA_COFFEE`, `WORLD_HUMAN_DRINKING`, `WORLD_HUMAN_SEAT_STEPS`

**Waypoint recordings** (1) - `Pap2_Maid`

**Vehicle recordings** (1) - `PAP2UBA`

**Relationship groups** (1) - `POPPY_GROUP`

**Timecycle modifiers** (1) - `player_transition_scanlines`

**Doors** (1) - `prop_ss1_14_garage_door`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (334), `GET_GAME_TIMER` (81), `DOES_ENTITY_EXIST` (65), `DOES_CAM_EXIST` (59), `DISABLE_CONTROL_ACTION` (54), `GET_SCRIPT_TASK_STATUS` (43), `IS_ENTITY_IN_ANGLED_AREA` (37), `REQUEST_MODEL` (31), `SET_PED_COMPONENT_VARIATION` (31), `IS_SYNCHRONIZED_SCENE_RUNNING` (29), `PLAYER_ID` (25), `TASK_PLAY_ANIM` (23), `TASK_LOOK_AT_ENTITY` (23), `IS_ENTITY_DEAD` (22), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (22), `HAS_MODEL_LOADED` (21), `SET_MODEL_AS_NO_LONGER_NEEDED` (21), `IS_ENTITY_PLAYING_ANIM` (20), `IS_VEHICLE_DRIVEABLE` (18), `GET_CAM_FOV` (17), `CLEAR_AREA_OF_PEDS` (17), `FORCE_NEXT_MESSAGE_TO_PREVIOUS_BRIEFS_LIST` (17), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (16), `GET_ENTITY_COORDS` (15), `TASK_FOLLOW_NAV_MESH_TO_COORD` (15), `CLEAR_PED_TASKS` (15), `SET_PLAYER_CONTROL` (15), `SET_VEHICLE_ON_GROUND_PROPERLY` (15), `ARE_STRINGS_EQUAL` (15), `DESTROY_CAM` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x9 · `0.013f` x8 · `111.696f` x8 · `-30.8601f` x7 · `301.192f` x7 · `2.5f` x7 · `111.6961f` x6 · `112.1164f` x5 · `0.25f` x5 · `-0.0022f` x5 · `-0.0289f` x5 · `0.7901f` x5 · `-0.6123f` x5 · `0.1f` x5 · `-33.8491f` x4 · `319.335f` x4 · `184.4715f` x4 · `1.3f` x4 · `0.3f` x4 · `-37.2396f` x4 · `325.3983f` x4 · `0.4f` x3 · `10.7485f` x3 · `-9.8457f` x3

## Other strings

Literals whose consuming native was not classified:

`PAP2_CHASE2`, `taxi`, `PAP2_IG1_POPPYSEX`, `DEFAULT_SCRIPTED_CAMERA`, `bus`, `HAND_SHAKE`, `penumbra`, `PAP2_STAFF`, `PAP2_POP`, `rocoto`, `fq2`, `TK************ SETTING SYNCH SCENE AUDIO POSITION THIS FRAME ************TK`, `Beverlys_camera`, `landstalker`, `futo`, `PAP2_00`, `PAP2_06`, `PAP2_BADCAM1`, `Beverley`, `PAP2_START`, `pap_2_mcs_1`, `PAP_2_RCM_P2`, `Loading`, `PAP2_FAILATT`, `polmav`, `DEFAULT_ACTION`, `DisableAbortConversationForRagdoll`, `PAP2_PASS`, `PAP2_08`, `PAP2_WALKA`

---

Source: `decompiled_scripts/paparazzo2.c`
