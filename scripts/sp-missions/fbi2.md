# fbi2.c

SP missions script. 15 anim dicts; 25 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 152,503 |
| Functions | 1,180 (251 unique, 929 shared) |
| Unique lines | 23,658 (15.5% of file) |

## Assets

**Animation dictionaries** (15) - `clipset@missfbi2_driveby`, `amb@prop_human_seat_computer@male@base`, `amb@prop_human_seat_computer@male@react_shock`, `amb@world_human_stand_guard@male@base`, `reaction@male_stand@small_intro@left`, `reaction@male_stand@small_intro@right`, `reaction@male_stand@small_variations@idle_a`, `combat@aim_variations@pistol`, `combat@gestures@pistol@panic`, `combat@gestures@pistol@overthere`, `combat@panic@pistol`, `combat@gestures@pistol@beckon`, `MISSFBI2@LeadInOut`, `MISSFBI2@LeadInOutFBI_2_MCS_1`, `shake_cam_all@`

**Animations** (23) - `Rappel_jump_a`, `ig_7_m_door_f_sniping_franklin`, `MISSFBI2@LeadInOut`, `idle`, `hostage_low_intro_mrk`, `_leadin_loop_FBI`, `FBI_2_INT_LeadInOut_loop_DaveN`, `Hang_idle_mrk`, `Interrogation_Michelle`, `Interrogation_MRK`, `_leadin_loop_Trevor`, `_leadin_loop_Franklin`, `_leadin_action_Trevor`, `_leadin_action_FBI`, `_leadin_loop_Trevor_02_trevor`, `FBI_2_INT_LeadInOut_loop_steve`, `FBI_2_INT_LeadInOut_loop_ANDREAS`, `FBI_2_INT_LeadIn_action_DaveN`, `FBI_2_INT_LeadIn_action_Steve`, `FBI_2_INT_LeadIn_action_Andreas`, `Direct_Heli_loop`, `mrk_in_chopper`, `FRANKLIN_SNIPER_CROUCH`

**Models and props** (25) - `v_corp_offchair`, `prop_chair_01a`, `PROP_CS_POLICE_TORCH`, `V_CIA_PS_WINDOW_UNBROKEN`, `P_CS_15M_ROPE_S`, `P_RPULLEY_S`, `prop_parasol_01`, `p_ing_coffeecup_01`, `prop_cs_police_torch`, `V_CIA_PS_WINDOW_BROKEN`, `prop_chair_01a^1`, `prop_chair_01a^2`, `prop_chair_01a^3`, `cs_mrk`, `ig_mrk`, `s_m_m_ciasec_01`, `s_m_m_pilot_02`, `cs_michelle`, `s_m_m_fiboffice_01`, `v_ilev_fib_door1`, `p_mrk_harness_s`, `p_cs_15m_rope_s`, `p_rpulley_s`, `ig_fbisuit_01`, `prop_table_07`

**Sounds** (16) - `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `Hit_Out`, `Short_Transition_In`, `INOUT`, `Hit_In`, `1st_Person_Transition`, `CHARACTER_CHANGE_IN_SKY_SCENE`, `PlayerSpeed`, `FBI_02_SNATCH_AND_GRAB_DANGLE`, `Remote_Sniper_Rifle_Fire`, `FBI_02_SNATCH_AND_GRAB_SMASH_WINDOW`, `FBI_02_SNATCH_AND_GRAB_AMB_HELI`, `FBI_02_SNATCH_AND_GRAB_HELI_DOWN`, `CHARACTER_CHANGE_UP_MASTER`, `CHARACTER_CHANGE_SKY_MASTER`, `CHARACTER_CHANGE_DOWN_MASTER`

**Text labels** (28) - `FBI2AUD`, `FRANKLIN`, `MICHAEL`, `TREVOR`, `BASE`, `DAVE`, `SAGRAB`, `FBI2CIACHOP2`, `FBI2AGENT5`, `FBI2AGENT7`, `FBI2AGENT8`, `MICHELLE`, `EXTRASUNNY`, `NULL`, `MISSSAGRAB`, `MISSFBI2`, `MISSFBI2CUTS`, `FBI2AGENT1`, `FBI2AGENT2`, `FBI2AGENT6`, `FBI2AGENT4`, `FBI2AGENT3`, `GUARD0`, `GUARD1`, `GUARD2`, `GUARD3`, `GUARD4`, `GUARD5`

**Waypoint recordings** (1) - `davewalk`

**Relationship groups** (2) - `player`, `Agency Group`

**Interiors and entity sets** (1) - `V_CIA01_cur_offc3`

**Doors** (1) - `v_ilev_fib_door1`

**Vehicle mods** (5) - `maverick`, `polmav`, `buzzard2`, `cargobob`, `annihilator`

**Hashed names** (3) - `AM_BASE_GLASS_STRONG`, `V_FakeDT1_05`, `MISSFBI2_MICHAEL_DRIVEBY`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (351), `IS_PED_INJURED` (345), `GET_GAME_TIMER` (282), `DOES_ENTITY_EXIST` (165), `IS_VEHICLE_DRIVEABLE` (128), `PLAYER_ID` (89), `DOES_BLIP_EXIST` (65), `GET_ENTITY_COORDS` (58), `DOES_CAM_EXIST` (53), `GET_RANDOM_INT_IN_RANGE` (52), `DELETE_PED` (43), `REGISTER_ENTITY_FOR_CUTSCENE` (40), `WAIT` (39), `DISABLE_CONTROL_ACTION` (38), `SET_PED_COMPONENT_VARIATION` (38), `CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY` (36), `RENDER_SCRIPT_CAMS` (34), `SET_PED_CONFIG_FLAG` (31), `IS_ENTITY_AT_COORD` (31), `GET_SYNCHRONIZED_SCENE_PHASE` (29), `SET_PLAYER_CONTROL` (27), `DELETE_OBJECT` (27), `TASK_SYNCHRONIZED_SCENE` (25), `REMOVE_BLIP` (24), `DISPLAY_RADAR` (23), `PLAY_SOUND_FRONTEND` (23), `FREEZE_ENTITY_POSITION` (22), `IS_PED_IN_VEHICLE` (22), `TIMESTEP` (22), `DESTROY_CAM` (21)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x13 · `0.2f` x10 · `0.4f` x9 · `0.8f` x8 · `145.5f` x7 · `-0.25f` x7 · `0.1f` x7 · `148.31f` x5 · `-677.19f` x5 · `41.02f` x5 · `205.05f` x5 · `41.84525f` x5 · `0.98f` x5 · `0.05f` x4 · `-125.7f` x4 · `-15.47f` x4 · `0.06f` x4 · `148.2744f` x4 · `-677.2391f` x4 · `50.998f` x4 · `-87.5f` x4 · `80.15606f` x3 · `-689.0754f` x3 · `153.5127f` x3

## Other strings

Literals whose consuming native was not classified:

`Michael`, `thisSwitchCam`, `Trevor`, `MR_K`, `FBI2_MRKSHT`, `FIRING_PATTERN_FULL_AUTO`, `Dave_FBI`, `DEFAULT_SCRIPTED_CAMERA`, `Main_Heli`, `SG_TROHLP2`, `CameraInfo_FIB2_HeliMichaelToFranklin.txt`, `CameraInfo_FIB2_HeliMichaelToFranklin.xml`, `back_right`, `CIA_Office_Chair`, `CIA_Office_Chair^1`, `CIA_Office_Chair^2`, `CIA_Office_Chair^3`, `Mr_K_Harness`, `MotionState_Walk`, `MotionState_Aiming`, `DT1_05_FIB_Reflection`, `SwitchHUDMichaelOut`, `SwitchHUDFranklinOut`, `FBI2_IAA`, `FIB2_COMPLETE`, `Main_heli`, `FBI2_MIDAIR`, `base`, `Michelle`, `CIA_Goon_1`

---

Source: `decompiled_scripts/fbi2.c`
