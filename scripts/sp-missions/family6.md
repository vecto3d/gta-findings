# family6.c

SP missions script. 8 anim dicts; 23 models; 4 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 146,217 |
| Functions | 1,069 (75 unique, 994 shared) |
| Unique lines | 11,869 (8.1% of file) |

## Assets

**Animation dictionaries** (8) - `missfam6ig_7_tattoo`, `missfam6ig_1_pierce`, `missfam6leadinoutfam_6_mcs_5`, `missfam6ig_8_ponytail`, `missfam6leadinoutfam_6_mcs_1`, `missfam2mcs_intp1`, `missfam6leadinoutfam_6_mcs_2`, `amb@world_human_stand_impatient@female@no_sign@idle_a`

**Animations** (37) - `missfam6leadinoutfam_6_mcs_1`, `missfam6ig_7_tattoo`, `missfam6ig_1_pierce`, `missfam6leadinoutfam_6_mcs_5`, `missfam6ig_8_ponytail`, `leadin_action_amanda`, `leadin_action_fabien`, `ig_1_loop_michael`, `ig_1_loop_lazlow`, `_leadout_loop_lazlow`, `ig_7_idle_02_jimmy`, `ig_7_idle_01_tracey`, `ig_7_idle_01_jimmy`, `_leadout_loop_tattoo_guy`, `ig_7_idle_02_tracey`, `leadin_action_laptop_girl`, `ig_7_loop_michael`, `ig_7_loop_lazlow`, `missfam6leadinoutfam_6_mcs_2`, `amb@world_human_stand_impatient@female@no_sign@idle_a`, `idle_c`, `ig_1_ear_michael`, `ig_1_ear_lazlow`, `ig_7_idle_03_tracey`, `ig_1_nose_michael`, `ig_1_nose_lazlow`, `ig_1_brow_michael`, `ig_1_brow_lazlow`, `_leadin_loop_tracy`, `_leadin_loop_lazlow`, `missfam2mcs_intp1`, `fam_2_int_p1_michael`, `leadin_loop_a_amanda`, `leadin_loop_b_fabien`, `leadin_loop_c_laptop_girl`, `ig_7_outro_michael`, `ig_7_outro_lazlow`

**Models and props** (23) - `cs_lazlow`, `ig_7_loop_scissors`, `ig_7_loop_michael`, `ig_7_loop_lazlow`, `ig_fabien`, `u_m_y_tattoo_01`, `ig_7_Loop_cam`, `ig_1_ear_cam`, `ig_1_nose_cam`, `ig_1_brow_cam`, `v_ilev_mm_doorm_l`, `v_ilev_mm_doorm_r`, `p_laptop_02_s`, `prop_mug_04`, `p_lazlow_shirt_s`, `p_cs_laz_ptail_s`, `prop_piercing_gun`, `v_ilev_ta_tatgun`, `prop_cs_scissors`, `ig_7_Outro_Cam`, `ig_7_outro_scissors`, `ig_7_back_intro_cam`, `ig_7_front_intro_cam`

**Audio banks** (3) - `FAM6_PIERCING_GUN`, `TIME_LAPSE`, `FAM6_PONYTAIL`

**Sounds** (15) - `FAMILY_6_SOUNDS`, `Pierce`, `TOD_SHIFT_SCENE`, `DoTattoo`, `FAMILY_6_PIERCE_LAZLOW_MG`, `FAMILY_6_DRIVE_TO_TATTOO`, `Amanda_Pulls_Away`, `FAMILY_6_AMANDA_PULLS_AWAY`, `FAMILY_6_DRIVE_TO_AMANDA`, `FAMILY_6_DRIVE_HOME`, `FAMILY_6_DRIVE_TO_THERAPIST`, `FAMILY_6_HAIRCUT_LAZLOW_MG`, `Snip_Ponytail`, `FAMILY_6_TATTOO_LAZLOW_MG`, `Tattoo`

**Scaleform movies** (4) - `ADD_BUTTON`, `tattoo_buttons`, `tattoo_keys`, `SET_STICK_POINTER_ANGLE`

**Particle effects** (1) - `cs_fam6_hair_snip`

**Text labels** (12) - `FAM6AUD`, `EXTRASUNNY`, `AMANDA`, `LAZLOW`, `NULL`, `22LJK483`, `FAM6`, `MICHAEL`, `JIMMY`, `TRACEY`, `FABIAN`, `FAMILY6`

**Decorators** (1) - `IgnoredByQuickSave`

**Vehicle mods** (2) - `taxi`, `blimp`

**Stats** (1) - `sp_ambient_switch_count`

**Hashed names** (1) - `last_piercing`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (404), `IS_PED_INJURED` (184), `DOES_ENTITY_EXIST` (109), `PLAYER_ID` (91), `SET_PED_COMPONENT_VARIATION` (87), `GET_GAME_TIMER` (71), `IS_ENTITY_DEAD` (51), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (51), `IS_SCREEN_FADED_OUT` (49), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (45), `IS_PED_IN_ANY_VEHICLE` (43), `GET_RANDOM_INT_IN_RANGE` (39), `ARE_STRINGS_EQUAL` (39), `DOES_CAM_EXIST` (38), `IS_TASK_MOVE_NETWORK_ACTIVE` (36), `SET_MODEL_AS_NO_LONGER_NEEDED` (35), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (34), `DOES_BLIP_EXIST` (33), `REGISTER_ENTITY_FOR_CUTSCENE` (32), `TASK_FOLLOW_NAV_MESH_TO_COORD` (32), `BEGIN_SCALEFORM_MOVIE_METHOD` (32), `END_SCALEFORM_MOVIE_METHOD` (32), `IS_TASK_MOVE_NETWORK_READY_FOR_TRANSITION` (30), `CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY` (29), `IS_ENTITY_IN_ANGLED_AREA` (29), `GET_PLAYERS_LAST_VEHICLE` (29), `REQUEST_MODEL` (28), `CLEAR_SEQUENCE_TASK` (28), `GET_VEHICLE_PED_IS_USING` (28), `GET_ENTITY_COORDS` (28)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x35 · `324.13f` x25 · `181.29f` x25 · `102.6f` x25 · `-22.32f` x25 · `0.5f` x14 · `-817.305f` x9 · `179.33f` x9 · `71.241f` x8 · `-1894.676f` x8 · `-567.7178f` x8 · `10.61473f` x8 · `-1906.34f` x8 · `-557.9231f` x8 · `13.81239f` x8 · `71.15f` x6 · `71.16f` x6 · `-641.8773f` x6 · `247.5781f` x6 · `80.30839f` x6 · `-607.4605f` x6 · `244.6178f` x6 · `87.00999f` x6 · `1.5f` x5

## Other strings

Literals whose consuming native was not classified:

`player`, `Jimmy`, `Michael`, `Lazlow`, `MotionState_Walk`, `FAM6_JWANT`, `Tracy`, `player_zero`, `Amanda`, `FAM6_JBAD`, `FAM6_JLOST`, `FAM6_WEIRD`, `FAM6_JTALK`, `FAM6_CHAT1`, `FAM6_CHAT2`, `FAM6_JTALK2`, `FAM6_TATTOO`, `FAM6_TATT2`, `Fabien`, `FAM6_BEAN`, `FAM6_BEAN2`, `FAM6_DRF1`, `FAM6_DRF2`, `missfam6ig_7_tattoo`, `Tattoo_Gun`, `FAM6_JWARN`, `missfam6ig_8_ponytail`, `FAM6_JLOST_3`, `FAM6_JLOSE_5`, `FAM6_JBAD_5`

---

Source: `decompiled_scripts/family6.c`
