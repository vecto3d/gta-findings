# franklin1.c

SP missions script. 11 anim dicts; 24 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 136,283 |
| Functions | 1,075 (200 unique, 875 shared) |
| Unique lines | 20,647 (15.2% of file) |

## Assets

**Animation dictionaries** (11) - `missfra1leadinoutmcs_1`, `missfra1`, `misstimelapse@franklinold_home`, `missfra1_tovan`, `missfra1enter_club`, `missfra1mcs_2_crew_react`, `creatures@rottweiler@amb@world_dog_sitting@base`, `creatures@rottweiler@amb@world_dog_sitting@enter`, `creatures@rottweiler@amb@world_dog_sitting@idle_a`, `move_ped_wpn_jerrycan_generic`, `MISSCHOP_VEHICLE@BACK_OF_VAN`

**Animations** (32) - `missfra1leadinoutmcs_1`, `missfra1mcs_2_crew_react`, `_leadin_action_lamar`, `missfra1_tovan`, `_leadin_loop_lamar`, `_leadin_action_trevor`, `missfra1`, `handsup_standing_base`, `intro_m_camera`, `creatures@rottweiler@amb@world_dog_sitting@base`, `base`, `put_chop_in_van_chop`, `put_chop_in_van_lam`, `money_bag`, `_leadin_intro_lamar`, `misstimelapse@franklinold_home`, `franklin_enters_old_home`, `missfra1enter_club`, `trevor_enter_club`, `fra_1_mcs_2_clayidle`, `mcs2_f_jetski_idle01`, `mcs2_f_jetski_idle02`, `mcs2_crew_idle_m_camera`, `idle_m_camera`, `mcs2_crew_idle_m_boom`, `intro_m_boom`, `idle_m_boom`, `_open_van_door_van`, `chop_van_getout`, `creatures@rottweiler@amb@world_dog_sitting@enter`, `enter`, `creatures@rottweiler@amb@world_dog_sitting@idle_a`

**Models and props** (24) - `s_m_y_cop_01`, `police3`, `s_m_y_swat_01`, `p_dumpster_t`, `ig_lamardavis`, `g_m_y_famca_01`, `p_ld_heist_bag_s_1`, `g_m_y_famfor_01`, `ig_denise`, `polmav`, `prop_cs_trowel`, `prop_coke_block_half_b`, `a_f_y_beach_01`, `s_m_y_grip_01`, `g_m_y_ballaorig_01`, `bmx`, `cs_lamardavis`, `v_ilev_fa_frontdoor`, `prop_strip_door_01`, `ig_claypain`, `prop_worklight_03b`, `prop_v_cam_01`, `prop_v_bmike_01`, `prop_boombox_01`

**Audio banks** (2) - `SCRIPT\FRANKLIN_1_CAMERAS`, `SCRIPT\FRANKLIN_1_GIRLS`

**Sounds** (18) - `FRANKLIN_1_APPROACH_RIVER`, `FRANKLIN_1_JETSKI_START`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `FRANKLIN_1_JETSKI_GIRL_JUMP`, `FRANKLIN_01_JETSKI_CHASE_CAR`, `FRANKLIN_1_JETSKI_CAR_ARRIVE`, `FRANKLIN_1_SHOOTOUT_CAR_ARRIVE_1`, `FRANKLIN_1_JETSKI_SPLIT_UP`, `FRANKLIN_1_SHOOTOUT_MAIN`, `FRANKLIN_1_JETSKI_HELI_ESCAPE`, `FRANKLIN_1_SHOOTOUT_POLICE_ARRIVE`, `FRANKLIN_1_SHOOTOUT_CAR_ARRIVE_3`, `FRANKLIN_1_GET_TO_GROVE_ST`, `FRANKLIN_1_SHOOTOUT_CAR_ARRIVE_CRASH`, `FRANKLIN_1_PHOTO_SHOOT`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`

**Text labels** (18) - `FKN1AUD`, `COP`, `FRANKLIN`, `TREVOR`, `LAMAR`, `EXTRASUNNY`, `FRA1POLICE1`, `FRA1MODEL1`, `MCCLIP`, `NULL`, `BALLA1`, `BALLA2`, `BALLA3`, `BALLA4`, `BALLA5`, `BALLA6`, `BALLA7`, `FRAN1`

**Waypoint recordings** (3) - `fra1_cflee`, `fra1_trevor`, `fra1_lamar`

**Relationship groups** (4) - `DOG`, `BMX`, `ENEMIES`, `FILMCREW`

**Vehicle mods** (1) - `seashark`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (373), `PLAYER_PED_ID` (269), `IS_ENTITY_DEAD` (226), `IS_PED_INJURED` (191), `SET_PED_COMBAT_ATTRIBUTES` (153), `IS_VEHICLE_DRIVEABLE` (132), `GET_GAME_TIMER` (127), `GET_PLAYERS_LAST_VEHICLE` (77), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (76), `ENABLE_DISPATCH_SERVICE` (76), `PLAYER_ID` (67), `REQUEST_MODEL` (65), `REMOVE_VEHICLE_RECORDING` (65), `DOES_BLIP_EXIST` (64), `GET_ENTITY_COORDS` (63), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (62), `REQUEST_VEHICLE_RECORDING` (59), `HAS_VEHICLE_RECORDING_BEEN_LOADED` (58), `CLEAR_SEQUENCE_TASK` (56), `GIVE_WEAPON_TO_PED` (56), `HAS_MODEL_LOADED` (53), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (50), `GET_VEHICLE_PED_IS_USING` (48), `SET_MODEL_AS_NO_LONGER_NEEDED` (45), `IS_PED_IN_ANY_VEHICLE` (42), `SET_RAGDOLL_BLOCKING_FLAGS` (42), `GET_RANDOM_INT_IN_RANGE` (41), `SET_COMBAT_FLOAT` (40), `SET_PED_COMPONENT_VARIATION` (40), `IS_ENTITY_IN_ANGLED_AREA` (39)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x40 · `0.5f` x22 · `1.25f` x14 · `1.5f` x13 · `-64.65f` x9 · `-1451.78f` x9 · `31.12f` x9 · `-14.862f` x8 · `-1441.208f` x8 · `31.18f` x8 · `0.46f` x7 · `0.8f` x6 · `7.5f` x5 · `2.5f` x5 · `-19.1293f` x4 · `-1455.206f` x4 · `29.5073f` x4 · `136.4794f` x4 · `-1307.488f` x4 · `27.9153f` x4 · `-53.1256f` x4 · `-1457.981f` x4 · `30.9968f` x4 · `0.35f` x4

## Other strings

Literals whose consuming native was not classified:

`FIRING_PATTERN_FULL_AUTO`, `FIRING_PATTERN_BURST_FIRE`, `player`, `police3`, `Lamar`, `Franklin`, `Trevor`, `MotionState_Walk`, `F1_SRGIRLT`, `F1_SRGIRLF`, `F1_LCLNCR`, `Chop`, `CamPushInNeutral`, `missfra1_tovan`, `Denises_Trowel`, `SC1_27_Cut`, `baller`, `F1_LCFSOFR`, `F1_LCTSOTR`, `F1_LCFSOF`, `F1_LCTSOT`, `F1_LHILL`, `F1_COM03`, `F1_COM04`, `F1_COM05`, `F1_COM06`, `F1_COM08F`, `F1_COM08T`, `F1_GDVUD`, `seashark`

---

Source: `decompiled_scripts/franklin1.c`
