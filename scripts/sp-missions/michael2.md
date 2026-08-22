# michael2.c

SP missions script. 15 anim dicts; 16 models; 8 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 133,701 |
| Functions | 985 (64 unique, 921 shared) |
| Unique lines | 13,043 (9.8% of file) |

## Assets

**Animation dictionaries** (15) - `MOVE_STRAFE@COP`, `cellphone@`, `shake_cam_all@`, `missmic2@goon1`, `missmic2@goon2`, `missmic2@meat_hook`, `missmic2@switch`, `missmic2@enemy`, `missmic2@franklin_beckon`, `amb@world_human_hang_out_street@male_a@idle_a`, `amb@world_human_hang_out_street@male_b@idle_a`, `amb@world_human_hang_out_street@male_c@base`, `amb@world_human_hang_out_street@male_c@idle_a`, `missmic2@machine`, `move_ped_strafing`

**Animations** (41) - `smoking_loop`, `goon_meatslicer`, `michael_meat_hook_fall`, `goon_rundownstair`, `mic_2_ig_11_b_p_one`, `beefsplitter_loop`, `goon_leap_rail`, `michael_meat_hook_react_c`, `mic_2_ig_11_winning_p_one`, `mic_2_ig_11_losing_p_one`, `idle_a`, `idle_b`, `idle_c`, `cellphone@`, `mic_2_ig_11_winning_goon`, `mic_2_ig_11_losing_goon`, `michael_meat_hook_react_b`, `idle_d`, `beckon_a_player1`, `beckon_b_player1`, `mic_2_ig_11_intro_p_one`, `mic_2_ig_11_a_p_one`, `cellphone_text_read_base`, `michael_meat_hook_react_a`, `michael_meat_hook_react_d`, `goonfall_into_grinder`, `goon_fall_onto_conveyor`, `michael_washing_face`, `idle_e`, `base`, `goon_pushcow_goon`, `mic_2_ig_11_b_goon`, `mic_2_ig_11_intro_goon`, `mic_2_ig_11_a_goon`, `meathook_gun_switch_mic`, `meathook_gun_switch_fra`, `mic_2_int_leadout_ped`, `cellphone_text_in`, `cellphone_call_to_text`, `goonfall_into_bin`, `michael_meat_hook_minced`

**Models and props** (16) - `g_m_m_chigoon_02`, `g_m_m_chigoon_01`, `prop_watercrate_01`, `prop_ld_hook`, `prop_cs_ciggy_01`, `prop_cs_padlock`, `prop_cs_leg_chain_01`, `g_m_y_famca_01`, `prop_phone_ing_03`, `v_ind_coo_half`, `v_ilev_abmincer`, `coquette`, `feltzer2`, `bison`, `p_beefsplitter_s`, `prop_phone_overlay_01`

**Audio banks** (7) - `Michael_2_Meat_Chopper`, `Michael_2_Kidnap_Rail`, `Michael_2_Chopped_Up`, `FAM5_WASH_FACE`, `Michael_2_Break_Free`, `Michael_2_Acid_Bath`, `Michael_2_Kidnap_Mincer`

**Sounds** (34) - `MI_2_MEAT_SLICER`, `MICHAEL_2_SOUNDS`, `MI_2_DRIVE_TO_SLAUGHTERHOUSE`, `MI_2_SHOOTOUT_ACID`, `MI_2_GRINDER_1`, `MI_2_SHOOT_THE_GUARD`, `MI_2_THROW_THE_GUN`, `MI_2_SHOOT_FROM_MEATHOOK`, `MI_2_ESCAPE_SHOOTOUT`, `MI_2_DRIVE_HOME`, `MI_2_MICHAEL_ON_MEATHOOK`, `MI_2_SHOOTOUT_MAIN`, `MI_2_FRANKLIN_KNIFE_ATTACK`, `MI_2_SPLINE_2`, `MI_2_SAVE_FRANKLIN`, `MI_2_GRINDER_2`, `MI_2_ESCAPE_IN_CAR`, `MINCER_FALL`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `MI_2_FIND_A_WAY_IN`, `MI_2_SPLINE_CAM_1`, `1st_Person_Transition`, `MIC_2_CHOPPED_UP_JUMPIN_MASTER`, `MEAT_SLIDE`, `Hit_Out`, `Short_Transition_In`, `MINCER_LOOP`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `ACID_BATH_FALL`, `Rail_Loop_Skip_Start`, `Pull_Out`, `Phone_SoundSet_Franklin`, `RAIL_LOOP`

**Particle effects** (8) - `scr_abattoir_ped_minced`, `scr_abattoir_ped_sliced`, `cs_cig_smoke`, `cs_cig_exhale_mouth`, `scr_pts_headsplash`, `scr_mich2_spark_impact`, `scr_mich2_blood_stab`, `scr_acid_bath_splash`

**Text labels** (15) - `MICHAEL`, `FRANKLIN`, `MCH2CHIN5`, `MCH2CHIN1`, `MCH2GOON`, `MCH2CHIN2`, `MCH2CHIN6`, `MCH2CHIN3`, `MCH2CHIN4`, `NULL`, `MCH2AUD`, `DENISE`, `LESTER`, `MCH2`, `SMOKINGPUFF`

**Vehicle recordings** (1) - `ALrollingstart`

**Relationship groups** (4) - `FRIEND`, `BUDDIES`, `ENEMIES`, `PASSIVE`

**Interiors and entity sets** (8) - `v_abattoir`, `abaSLAUGHT`, `abattmainsec2`, `ababackpass`, `ababetween`, `V_Michael`, `abaprodfloor`, `abattmainsec1`

**Doors** (3) - `prop_abat_slide`, `v_ilev_abbmaindoor`, `v_ilev_fa_frontdoor`

**Vehicle mods** (2) - `feltzer2`, `coquette`

**Scripts launched** (1) - `mission_stat_watcher`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (386), `DOES_ENTITY_EXIST` (298), `IS_PED_INJURED` (241), `GET_ENTITY_COORDS` (200), `SET_PED_COMBAT_ATTRIBUTES` (103), `TIMERA` (94), `GET_DISTANCE_BETWEEN_COORDS` (86), `IS_ENTITY_PLAYING_ANIM` (84), `GET_GAME_TIMER` (82), `IS_ENTITY_AT_COORD` (78), `TO_FLOAT` (63), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (61), `SET_PED_COMBAT_MOVEMENT` (61), `PLAYER_ID` (61), `IS_AUDIO_SCENE_ACTIVE` (59), `IS_PED_IN_ANY_VEHICLE` (58), `IS_ENTITY_DEAD` (57), `IS_ENTITY_IN_ANGLED_AREA` (55), `SET_CURRENT_PED_WEAPON` (53), `DISABLE_CONTROL_ACTION` (50), `IS_SYNCHRONIZED_SCENE_RUNNING` (50), `SET_PED_CONFIG_FLAG` (48), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (45), `ENABLE_DISPATCH_SERVICE` (42), `STOP_AUDIO_SCENE` (41), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (39), `DOES_CAM_EXIST` (38), `GET_SCRIPT_TASK_STATUS` (37), `GET_RANDOM_INT_IN_RANGE` (37), `SET_CAM_PARAMS` (36)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x33 · `914.99f` x28 · `-2146.68f` x28 · `28.63f` x28 · `981.29f` x28 · `-2201.92f` x28 · `40.55f` x28 · `0.25f` x22 · `0.75f` x19 · `1.5f` x14 · `29.5517f` x14 · `6.28f` x13 · `2.5f` x12 · `44.65416f` x12 · `-1446.622f` x12 · `-26.81648f` x12 · `55.97744f` x12 · `-2149.353f` x12 · `966.1083f` x12 · `29.4753f` x10 · `28.4762f` x10 · `980.3362f` x10 · `-2159.359f` x10 · `32.68386f` x10

## Other strings

Literals whose consuming native was not classified:

`Michael`, `FIRING_PATTERN_FULL_AUTO`, `DEFAULT_SCRIPTED_CAMERA`, `ShotgunLargeMonolithic`, `Franklin`, `bison`, `MCH2_TRAP`, `feltzer2`, `coquette`, `MCH2_ESCF1`, `player`, `MIC_2_MICHAEL_CHOPPED_UP_MASTER`, `Trevor`, `MCH2_ABATTF`, `DEFAULT_ACTION`, `MIC2_START`, `MIC2_FIGHT_BEGINS`, `MIC2_ACID_BATH_OS`, `MIC2_MULCHED`, `MIC2_SPINNING_BLADES`, `MIC3_FRANK_DOWN`, `MIC2_FRANK_SAVED`, `MIC2_LOSE_TRIADS`, `MIC2_RADIO_SETUP`, `MCH2_KNIFE`, `sEnemyOutside[0]Blocking`, `sEnemyOutside[2]Blocking`, `CMN_MLEAVE`, `move_ped_strafing`, `csb_chin_goon`

---

Source: `decompiled_scripts/michael2.c`
