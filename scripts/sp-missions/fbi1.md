# fbi1.c

SP missions script. 6 anim dicts; 13 models; 2 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 122,959 |
| Functions | 854 (90 unique, 764 shared) |
| Unique lines | 6,557 (5.3% of file) |

## Assets

**Animation dictionaries** (6) - `missfbi1`, `missfbi1ig_7`, `MISSFBI1LEADINOUTFBI_1_EXT`, `dead`, `missfbi1ig_9`, `Dead`

**Animations** (22) - `missfbi1ig_9`, `missfbi1`, `cpr_pumpchest_idle`, `look_front`, `look_left`, `look_right`, `Dead`, `dead_c`, `missfbi1ig_7`, `MISSFBI1LEADINOUTFBI_1_EXT`, `_LEADIN_FRANKLIN`, `ledge_jump`, `idle_a`, `idle_b`, `idle_c`, `ledge_climbout`, `fbi_1_ig_1_b_clipb`, `fbi_1_ig_1_a`, `fbi_1_ig_3_b_clipb`, `fbi_1_ig_3_a`, `fbi_1_ig_2_b_clipb`, `fbi_1_ig_2_a`

**Models and props** (13) - `s_m_m_ciasec_01`, `v_ilev_cor_windowsmash`, `v_coroner`, `s_m_y_autopsy_01`, `v_ilev_cor_windowsolid`, `s_m_y_cop_01`, `prop_ld_rub_binbag_01`, `p_cs_clipboard`, `prop_pencil_01`, `prop_bonesaw`, `prop_bin_14b`, `u_f_y_corpse_01`, `u_f_m_corpse_01`

**Audio banks** (4) - `SCRIPT\FBI_01_DMW_02`, `SCRIPT\FBI_01_DMW_01`, `script\FBI_01_DMW_Autopsy_1`, `FBI_01_DMW_Autopsy_1`

**Sounds** (18) - `FBI_1_AGENT_BURSTS_THROUGH_DOOR`, `FBI_1_ESCAPE_BASE_SCENE`, `FBI_1_STEALTH_KILL_AGENT`, `FBI_1_LOSE_COPS`, `FBI_01_DMW_IN_BODY_BAG`, `FBI_1_AIM_AT_WINDOW`, `FBI_1_INSPECT_BODIES`, `FBI_1_SHOOTOUT_GROUND_FLOOR`, `FBI_1_GET_UPSTAIRS`, `FBI_1_JUMP`, `FBI_01_SOUNDS`, `FBI_01_DMW_GARBAGE_LAND`, `FBI_01_DMW_02_SOUNDS`, `FBI_1_JUMPR`, `PICK_UP_PARACHUTE`, `HUD_FRONTEND_CUSTOM_SOUNDSET`, `FBI_01_DMW_LIFT_ARRIVE`, `UNZIP`

**Particle effects** (2) - `scr_fbi1_litter`, `scr_fbi_autopsy_blood`

**Texture dicts** (2) - `fbi1`, `zipbig`

**Text labels** (11) - `FBI1AUD`, `CIA1`, `COP`, `NULL`, `LOSE_WANTED`, `CIA3`, `CIA8`, `CIA5`, `CIA4`, `CIA2`, `CIA6`

**Waypoint recordings** (1) - `fbi1_0`

**Vehicle recordings** (1) - `lkfbi1`

**Interiors and entity sets** (10) - `v_coroner`, `V_Coroner`, `V_coroner`, `Reception`, `topoff_right`, `AutopsyLargeA`, `AutopsyLargeB`, `CorridorBottom`, `topoff_mid`, `rm_bsmt_AutopsySmall`

**Doors** (6) - `v_ilev_cor_firedoor`, `v_ilev_cor_doorglassa`, `v_ilev_cor_doorglassb`, `v_ilev_cor_doorlift01`, `v_ilev_cor_doorlift02`, `v_ilev_cor_firedoorwide`

**Stats** (21) - `sp0_weap_addon_purch_2`, `sp0_weap_addon_purch_3`, `sp1_weap_addon_purch_3`, `sp2_weap_addon_purch_3`, `sp0_weap_addon_purch_4`, `sp1_weap_addon_purch_4`, `sp2_weap_addon_purch_4`, `sp0_weap_addon_purch_0`, `sp1_weap_addon_purch_0`, `sp2_weap_addon_purch_0`, `sp0_weap_addon_purch_1`, `sp1_weap_addon_purch_1`, `sp2_weap_addon_purch_1`, `sp1_weap_addon_purch_2`, `sp2_weap_addon_purch_2`, `sp0_weap_addon_purch_5`, `sp1_weap_addon_purch_5`, `sp2_weap_addon_purch_5`, `sp0_weap_addon_purch_6`, `sp1_weap_addon_purch_6`, `sp2_weap_addon_purch_6`

**Hashed names** (19) - `AutopsySmall`, `topoff_mid`, `CorridorBottom`, `BodyStorage`, `fbi_1_door_0`, `fbi_1_door_1`, `fbi_1_door_2`, `fbi_1_door_3`, `fbi_1_door_4`, `fbi_1_door_5`, `fbi_1_door_6`, `fbi_1_door_7`, `fbi_1_door_8`, `fbi_1_door_9`, `fbi_1_door_10`, `fbi_1_door_11`, `fbi_1_door_12`, `fbi_1_door_13`, `fbi_1_door_14`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (464), `SET_PED_COMPONENT_VARIATION` (185), `REQUEST_MODEL` (64), `SET_PED_COMBAT_ATTRIBUTES` (64), `SET_PED_PRELOAD_VARIATION_DATA` (63), `IS_ENTITY_IN_ANGLED_AREA` (57), `HAS_MODEL_LOADED` (56), `GET_ENTITY_COORDS` (53), `IS_PED_INJURED` (47), `PLAYER_ID` (46), `DOES_ENTITY_EXIST` (41), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (34), `SET_PED_SPHERE_DEFENSIVE_AREA` (30), `GET_HASH_KEY` (30), `DOES_BLIP_EXIST` (29), `OPEN_SEQUENCE_TASK` (29), `CLOSE_SEQUENCE_TASK` (29), `TASK_PERFORM_SEQUENCE` (29), `CLEAR_SEQUENCE_TASK` (29), `WAIT` (28), `REMOVE_BLIP` (28), `GET_INTERIOR_AT_COORDS_WITH_TYPE` (27), `TRIGGER_MUSIC_EVENT` (26), `GET_GAME_TIMER` (25), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (25), `DOOR_SYSTEM_SET_OPEN_RATIO` (23), `DOOR_SYSTEM_SET_DOOR_STATE` (23), `SET_MODEL_AS_NO_LONGER_NEEDED` (22), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (22), `STAT_GET_INT` (21)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x32 · `23.538f` x14 · `0.99f` x12 · `26.538f` x11 · `23.247f` x11 · `279.9322f` x10 · `-1337.49f` x10 · `23.7419f` x10 · `24.57f` x8 · `236.03f` x7 · `-1357.49f` x7 · `40.45f` x7 · `287.9576f` x7 · `-1345.725f` x7 · `23.2416f` x7 · `1.5f` x7 · `2.5f` x7 · `0.1f` x7 · `0.8f` x7 · `24.68f` x6 · `-1343.9f` x6 · `0.25f` x6 · `25.3f` x6 · `287.544f` x5

## Other strings

Literals whose consuming native was not classified:

`michael`, `FIRING_PATTERN_FULL_AUTO`, `cia_attak0`, `cia_attak5`, `cia_attak1`, `fbi1_doc2`, `cia_guard`, `MICHAEL_ACTION`, `FBI_01_MORGUE_ALARMS`, `fbi1aud`, `fbi1_doc3`, `FBI1_help4`, `coroner2`, `coroner_stairs`, `player`, `MotionState_Aiming`, `FBI1_LIFT_ENEMY`, `FBI1_God_14`, `mr_k_0`, `mr_k_1`, `fbi1_doc4`, `missfbi1`, `doctor1`, `MotionState_Stealth_Idle`, `FBI1_WAKE_UP`, `Michael`, `lift0`, `cia_attak4`, `cia_attak2`

---

Source: `decompiled_scripts/fbi1.c`
