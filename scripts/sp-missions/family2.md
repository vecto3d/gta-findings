# family2.c

SP missions script. 6 developer state labels recovered; 6 anim dicts; 21 models; 3 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 58,485 |
| Functions | 623 (99 unique, 524 shared) |
| Unique lines | 9,790 (16.7% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`Player in front` · `Jimmy in front` · `Michael take over line should fire` · `Jimmy take over line should fire` · `bPlayerHasCheated` · `bPlayerHasBumpedJimmy`

## Assets

**Animation dictionaries** (6) - `missfam2ig_3`, `veh@bicycle@mountain_f@front@base`, `missfam2_tracy_jetski`, `missfam2_pier`, `missfam2mcs_intp1`, `missfam2leadinoutmcs3`

**Animations** (22) - `missfam2_tracy_jetski`, `missfam2leadinoutmcs3`, `missfam2ig_3`, `tracy_jetski_a`, `tracy_jetski_c`, `tracy_jetski_d`, `shouting_jimmy_base`, `tracy_point_right`, `tracy_point_left`, `tracy_jetski_e`, `tracy_jetski_f`, `tracy_jetski_g`, `tracy_jetski_h`, `onboat_leadin_pornguy_a`, `onboat_leadin_pornguy_b`, `onboat_leadin_porngal_a`, `onboat_leadin_porngal_b`, `onboat_leadin_tracy`, `missfam2mcs_intp1`, `fam_2_int_p1_michael`, `missfam2_pier`, `pier_lean_toss_cigarette`

**Models and props** (21) - `cruiser`, `csb_porndudes`, `ig_jimmydisanto`, `u_m_m_bikehire_01`, `seashark`, `v_ilev_mm_doorm_l`, `v_ilev_mm_doorm_r`, `a_f_y_beach_01`, `ig_tracydisanto`, `prop_table_03_chr`, `prop_cigar_01`, `prop_mp3_dock`, `a_c_stingray`, `prop_cs_office_chair`, `a_m_y_genstreet_01`, `prop_ld_test_01`, `bmx`, `scorcher`, `tribike`, `Prop_MP3_Dock`, `a_m_y_musclbeac_01`

**Audio banks** (1) - `TIME_LAPSE`

**Sounds** (7) - `FAMILY_2_JETSKI_GO_TO_BEACH`, `FAMILY_2_SWIM_TO_YACHT`, `FAMILY_2_BIKE_RACE_JIMMY`, `FAMILY_2_DRIVE_TO_BEACH`, `FAMILY_2_JETSKI_CHASE`, `FAMILY_2_DIVE_INTO_WATER`, `TIME_LAPSE_MASTER`

**Particle effects** (3) - `cs_cig_exhale_mouth`, `cs_cig_smoke`, `cs_cig_exhale_nose`

**Text labels** (12) - `FAMILY2`, `EXTRASUNNY`, `OFF`, `NULL`, `TRACEY`, `MICHAEL`, `COP`, `FAM2MAN2`, `BREATHING`, `FAM2AUD`, `JIMMY`, `FAM2BIKEHIRE`

**Scenarios** (2) - `WORLD_VEHICLE_DRIVE_SOLO`, `PROP_HUMAN_SEAT_CHAIR`

**Waypoint recordings** (1) - `fam2Stairs`

**Vehicle recordings** (5) - `famtwo`, `famtwoplayer`, `fam2amb`, `famtwoCanalsAlt`, `fam2`

**Relationship groups** (2) - `chasing_peds`, `buddies`

**Vehicle mods** (8) - `bmx`, `scorcher`, `cruiser`, `tribike`, `taxi`, `tribike2`, `tribike3`, `tailgater`

**Hashed names** (2) - `MISS_FAMILY2_JIMMY_BICYCLE`, `mission_stat_watcher`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (407), `GET_ENTITY_COORDS` (200), `DOES_ENTITY_EXIST` (190), `IS_PED_INJURED` (146), `IS_VEHICLE_DRIVEABLE` (139), `GET_GAME_TIMER` (95), `IS_PED_IN_VEHICLE` (91), `VDIST2` (71), `DOES_BLIP_EXIST` (59), `WAIT` (59), `REMOVE_BLIP` (56), `PLAYER_ID` (44), `IS_ENTITY_IN_ANGLED_AREA` (34), `SETTIMERA` (32), `IS_PED_IN_ANY_VEHICLE` (31), `SET_ENTITY_COORDS` (31), `REQUEST_MODEL` (31), `HAS_MODEL_LOADED` (27), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (25), `STOP_PLAYBACK_RECORDED_VEHICLE` (25), `SET_ENTITY_HEADING` (25), `TIMERA` (24), `GET_VEHICLE_PED_IS_IN` (24), `IS_AUDIO_SCENE_ACTIVE` (23), `CLEAR_PRINTS` (22), `VDIST` (22), `SET_PED_COMPONENT_VARIATION` (22), `DISABLE_CONTROL_ACTION` (21), `IS_ENTITY_DEAD` (20), `REQUEST_VEHICLE_RECORDING` (20)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`4.89f` x25 · `-2033.821f` x24 · `-1031.864f` x24 · `2.5f` x20 · `0.25f` x8 · `0.5f` x8 · `13.25f` x6 · `0.01f` x6 · `-1105.241f` x6 · `-1697.025f` x6 · `3.3678f` x6 · `0.1f` x5 · `0.3f` x5 · `-1099.756f` x5 · `-1700.726f` x5 · `3.349046f` x5 · `-1111.517f` x5 · `-1683.962f` x5 · `5.340389f` x5 · `1.75f` x4 · `1.5f` x4 · `5.75302f` x4 · `-1325.827f` x4 · `-1329.113f` x4

## Other strings

Literals whose consuming native was not classified:

`famtwo`, `Tracy`, `cruiser`, `Michael`, `smboat`, `seashark`, `Jimmy`, `FM2_JSPOOK`, `MotionState_Walk`, `Guy_on_sofa`, `smBoat`, `famtwoCanalsAlt`, `FAM2_STOP`, `FM2_TRAAB`, `csb_porndudes`, `FM2_DIVOFF`, `family_2_mcs_2`, `FM2_BIKE2`, `stage_drive_to_beach`, `player`, `FAM2_COMING`, `FAM2_WHO`, `FM2_TSPOOK`, `FM2_BIKE1`, `FM2_JIMAB`, `family_2_mcs_4`, `FAM2_TSHOUT`, `Man_getting_wood`, `Girl_on_sofa`, `Girl_being_chatted_up`

---

Source: `decompiled_scripts/family2.c`
