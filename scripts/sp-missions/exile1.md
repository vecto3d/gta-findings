# exile1.c

SP missions script. 2 anim dicts; 13 models; 1 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 130,484 |
| Functions | 1,043 (208 unique, 835 shared) |
| Unique lines | 13,936 (10.7% of file) |

## Assets

**Animation dictionaries** (2) - `shake_cam_all@`, `CELLPHONE@`

**Animations** (14) - `get_on_bottom_front_stand_high`, `get_off_bottom_front_stand`, `get_off_top_back_stand_right_hand`, `climb_up`, `climb_down`, `CALL_RADIO_SECURITY`, `jump_launch_l_to_skydive`, `_LeadOut_Michael`, `_LeadOut_Patricia`, `CALL_RADIO_PLAYER2`, `Sit_Pilot_Seat`, `base_left_hand_up`, `Michael_inTrailer`, `Franklin_atHouse`

**Models and props** (13) - `cs_ex1_cargo_fire`, `cs_ex1_sparking_wires_sm`, `prop_phone_ing_03`, `prop_phone_ing`, `s_m_y_blackops_01`, `s_m_m_pilot_01`, `s_m_m_pilot_02`, `prop_mil_crate_01`, `prop_mil_crate_02`, `prop_ld_test_01`, `prop_chair_06`, `p_police_radio_hset_s`, `prop_npc_phone`

**Sounds** (17) - `EXILE_1`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `INOUT`, `Transition_Sound`, `exile_1`, `Generic_Alarm_Fire_Electronic`, `1st_Person_Transition`, `Falling_Crates`, `Pt2_Fail`, `SPL_RPG_DIST_FLIGHT_MASTER`, `Jet_Explosions`, `Altitude_Warning`, `Intensity`, `Hit_Out`, `Short_Transition_In`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`

**Scaleform movies** (1) - `DISPLAY_VIEW`

**Particle effects** (1) - `scr_ex1_heatseeker`

**Text labels** (15) - `MERCPLANE`, `EXL1AUD`, `NULL`, `LADDERSBASE`, `LADDERS`, `FLYBY`, `TREVOR`, `MERC1`, `PFIGHT`, `MILITARYJET`, `MILITARYJET2`, `MERRYPLANE1`, `MERRYPLANE2`, `MICHAEL`, `FRANKLIN`

**Relationship groups** (2) - `player`, `Enemy Group`

**Timecycle modifiers** (1) - `exile1_plane`

**Interiors and entity sets** (2) - `v_trailerrm`, `v_trailer`

**Vehicle mods** (8) - `cuban800`, `stunt`, `titan`, `jet`, `shamal`, `luxor`, `mammatus`, `velum`

**Hashed names** (3) - `DOORHASH_T_TRAILER_CS`, `V_FakeCargoPlaneDive`, `V_FakeCargoPlaneClimb`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (300), `GET_GAME_TIMER` (194), `IS_VEHICLE_DRIVEABLE` (100), `DOES_ENTITY_EXIST` (97), `IS_PED_INJURED` (94), `GET_ENTITY_COORDS` (52), `PLAYER_ID` (38), `WAIT` (34), `TIMESTEP` (34), `IS_ENTITY_DEAD` (31), `SET_PED_CONFIG_FLAG` (28), `DELETE_PED` (24), `DELETE_OBJECT` (23), `DOES_BLIP_EXIST` (22), `FREEZE_ENTITY_POSITION` (21), `DELETE_VEHICLE` (20), `SET_ENTITY_PROOFS` (19), `GET_RANDOM_INT_IN_RANGE` (19), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (19), `IS_ENTITY_AT_ENTITY` (18), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (18), `SET_PLAYER_CONTROL` (17), `SET_ENTITY_COORDS` (16), `ARE_STRINGS_EQUAL` (16), `IS_PED_IN_ANY_VEHICLE` (15), `GET_ENTITY_HEADING` (15), `DISABLE_CONTROL_ACTION` (15), `IS_ENTITY_AT_COORD` (15), `GET_FOLLOW_PED_CAM_VIEW_MODE` (14), `IS_PED_IN_VEHICLE` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`3.5f` x6 · `0.5f` x5 · `16.5f` x4 · `1969.672f` x4 · `3818.383f` x4 · `33.59213f` x4 · `0.25f` x3 · `8.4f` x3 · `40.00207f` x3 · `43.99516f` x3 · `-817.6671f` x3 · `177.7958f` x3 · `71.22737f` x3 · `1903.29f` x2 · `4085.2f` x2 · `1462.66f` x2 · `0.4f` x2 · `38.74771f` x2 · `3802.386f` x2 · `30.7101f` x2 · `0.6f` x2 · `0.3f` x2 · `810.2f` x2 · `448.4f` x2

## Other strings

Literals whose consuming native was not classified:

`Hold_Guard_Rear`, `NervousRon`, `Hold_Guard_Front`, `Ron`, `Hold_Guard_Middle`, `Trevor`, `EXILE_1`, `Car_01`, `FIRING_PATTERN_FULL_AUTO`, `EXL_Plane`, `PF_DWNHLP`, `DisableAbortConversationForRagdoll`, `PF_FALLHLP`, `PF_PARHLP`, `PF_PARHLP3`, `EXL1_MISSION_FAILED`, `extrasunny`, `EXL_1_MCS_1_P3_B`, `Ramp_Guard_L`, `Ramp_Guard_R`, `npcphone`, `missexile1_cargoplaneleadinoutexile_1_intleadin`, `EXL1_JUMPED`, `PF_PARHLP2`, `PF_FALHLP`, `EXL1_LANDED`, `PF_LAND`, `scr_ex1_cargo_debris`, `Car_02`, `Car_03`

---

Source: `decompiled_scripts/exile1.c`
