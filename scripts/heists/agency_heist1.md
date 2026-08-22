# agency_heist1.c

Heists script. 6 anim dicts; 13 models.

| | |
|---|---|
| Category | Heists |
| Total lines | 116,942 |
| Functions | 786 (75 unique, 711 shared) |
| Unique lines | 5,682 (4.9% of file) |

## Assets

**Animation dictionaries** (6) - `missheist_agency2aig_2`, `missheistfbisetup1`, `missheistfbisetup1leadinoutah_1_mcs_1`, `move_lester_CaneUp`, `cellphone@`, `missheistfbisetup1leadinoutah_1_int`

**Animations** (11) - `missheist_agency2aig_2`, `look_at_phone_a`, `missheistfbisetup1`, `missheistfbisetup1leadinoutah_1_mcs_1`, `hassle_intro_loop_f`, `hassle_f`, `unlock_enter_janitor`, `unlock_loop_janitor`, `unlock_exit_janitor`, `leadin_janitor_idle_01`, `leadin_janitor_idle_action`

**Models and props** (13) - `s_m_m_janitor`, `prop_npc_phone`, `v_ilev_janitor_frontdoor`, `a_f_y_hipster_01`, `prop_cs_walking_stick`, `a_f_y_hipster_03`, `prop_cs_beer_bot_01`, `p_ld_heist_bag_s_2`, `dilettante`, `a_m_y_business_01`, `a_f_y_hippie_01`, `prop_ld_test_01`, `tailgater`

**Audio banks** (1) - `FBI_Heist_1_Tail_Janitor_01`

**Sounds** (14) - `AGENCY_H_1_FOCUS_ON_JANITOR`, `AGENCY_H_1_NON_TARGET_CARS`, `AGENCY_H_1_FOLLOW_JANITOR`, `AGENCY_H_1_DRIVE_TO_FACTORY`, `AGENCY_H_1_FOLLOW_ON_FOOT`, `AGENCY_H_1_GET_TO_FIB`, `AGENCY_H_1_WAIT_FOR_CARS`, `AGENCY_H_1_JANITORS_CAR`, `AGENCY_H_1_FOCUS_ON_PLATES`, `FBI_HEIST_SETUP_1_Car_Park_Skid_CR`, `FBI_HEIST_SETUP_1_Car_Park_tyre_bump_CR`, `FBI_HEIST_SETUP_1_Car_Park_tyre_bump_creak_CR`, `FBI_HEIST_SETUP_1_Car_Park_tyre_bump_no_skid_CR`, `FBI_HEIST_SETUP_1_Car_Park_tyre_bump_scraped_CR`

**Speech contexts** (1) - `AGENCYJANITOR`

**Text labels** (9) - `FBS1AUD`, `AGENCYJANITOR`, `COP`, `NULL`, `83QSL722`, `LESTER`, `JANITOR`, `H1SET1`, `MICHAEL`

**Scenarios** (1) - `PROP_HUMAN_SEAT_CHAIR`

**Waypoint recordings** (1) - `janitor_route`

**Vehicle recordings** (2) - `FBIs1UBER`, `FBIs1`

**Relationship groups** (2) - `NEUTRAL PEDS`, `BUDDIES`

**Vehicle mods** (3) - `tailgater`, `intruder`, `taxi`

**Scripts launched** (1) - `lesterHandler`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (226), `DOES_ENTITY_EXIST` (140), `GET_ENTITY_COORDS` (90), `IS_VEHICLE_DRIVEABLE` (83), `IS_PED_INJURED` (74), `IS_ENTITY_IN_ANGLED_AREA` (43), `IS_PED_IN_VEHICLE` (41), `WAIT` (39), `SETTIMERA` (39), `TIMERA` (32), `IS_AUDIO_SCENE_ACTIVE` (31), `DOES_BLIP_EXIST` (26), `IS_PED_IN_ANY_VEHICLE` (25), `DELETE_PED` (23), `PLAYER_ID` (23), `DOES_CAM_EXIST` (22), `DISABLE_CONTROL_ACTION` (22), `VDIST2` (21), `REMOVE_BLIP` (20), `REQUEST_MODEL` (19), `STOP_AUDIO_SCENE` (19), `SET_PED_COMPONENT_VARIATION` (18), `CLEAR_PED_TASKS` (17), `HAS_MODEL_LOADED` (16), `HIDE_HUD_COMPONENT_THIS_FRAME` (16), `SET_ENTITY_VISIBLE` (15), `DELETE_VEHICLE` (14), `GET_VEHICLE_PED_IS_IN` (14), `SET_GAMEPLAY_CAM_RELATIVE_HEADING` (14), `SET_GAMEPLAY_CAM_RELATIVE_PITCH` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x7 · `-107.5401f` x6 · `-9.0258f` x6 · `70.6696f` x6 · `-83.2189f` x5 · `-23.8057f` x5 · `65.321f` x5 · `9.75f` x5 · `-105.0312f` x4 · `-8.6584f` x4 · `69.5201f` x4 · `259.2958f` x4 · `0.05f` x4 · `-98.8604f` x3 · `-10.5318f` x3 · `65.5199f` x3 · `0.5f` x3 · `29.3953f` x3 · `5.5f` x3 · `-87.36494f` x3 · `-31.34193f` x3 · `63.48099f` x3 · `-80.96227f` x3 · `-15.8854f` x3

## Other strings

Literals whose consuming native was not classified:

`S1_JSPOOK`, `Lester`, `MotionState_Walk`, `asterope`, `tailgater`, `S1_FAILED_K`, `player`, `FBS1_LTURN`, `S1_FOCUS`, `stanier`, `Michael`, `missheistfbisetup1`, `FBS1_FRONT`, `FBS1_CLOSE`, `S1_VEHSTUCK`, `CMN_GENDEST`, `dilettante`, `S1_BKINCAR`, `Franklin`, `ah_1_ext_t6`, `STAGE_WAIT_FOR_JANITOR`, `STAGE_TAIL_THE_JANITOR`, `STAGE_FOLLOW_JANITOR_ON_FOOT`, `STAGE_DRIVE_BACK_TO_SAFEHOUSE`, `FBS1_DAMN`, `unlock_enter_janitor`, `AH1_RESTART`, `AGENCY_H_1_JANITORS_CAR_GROUP`, `FBIs1UBER`, `S1_FAILED`

---

Source: `decompiled_scripts/agency_heist1.c`
