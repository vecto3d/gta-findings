# armenian3.c

SP missions script. 3 anim dicts; 20 models; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 125,943 |
| Functions | 944 (57 unique, 887 shared) |
| Unique lines | 8,499 (6.7% of file) |

## Assets

**Animation dictionaries** (3) - `clipset@missarmenian3@franklin_driving`, `missarmenian3@simeon_tauntsidle_b`, `MOVE_M@LEAF_BLOWER`

**Animations** (38) - `michaelappears_loop_michael`, `tracey_argument`, `michaelappears_intro_michael`, `_leadout_action_simeon_car`, `Blower_Idle_a`, `michaelappears_loop2_michael`, `michaelappears_loop3_michael`, `michaelappears_loop4_michael`, `michaelappears_loop5_michael`, `michaelappears_loop6_michael`, `cmon`, `jimmy_playingvideogame_fail`, `tracey_fail`, `_leadout_action_simeon`, `areyounotman`, `lookathim`, `tracey_idle_a`, `_leadout_loop_simeon`, `LockedDoor_TryOpen_Stealth`, `lockeddoor_tryopen`, `_leadout_action_customer`, `jimmy_playingvideogame_base`, `jimmy_playingvideogame_loop_d`, `tracey_idle_b`, `tracey_idle_c`, `tracey_idle_d`, `michaelappears_intro_franklin`, `_leadout_loop_customer`, `_leadout_loop_simeon_car`, `_leadin_mic`, `_leadin_fra`, `tennis_coach_loop_wife`, `tennis_coach_loop_coach`, `tennis_coach_intro_wife`, `tennis_coach_intro_coach`, `climb_in_window_v2`, `open_garage_fail_stealth`, `open_garage_fail`

**Models and props** (20) - `a_m_m_bevhills_02`, `bjxl`, `v_ilev_mm_windowwc`, `s_m_m_gardener_01`, `prop_showroom_glass_1b`, `V_CARSHOWROOM_PS_WINDOW_UNBROKEN`, `premier`, `V_CARSHOWROOM_PS_WINDOW_BROKEN`, `v_ilev_mm_door`, `prop_phone_ing_02`, `V_MICHAEL_PS_BATHROOM_WITH_WINDOW`, `tailgater`, `prop_controller_01`, `prop_headset_01`, `prop_tennis_rack_01`, `p_tennis_bag_01_s`, `prop_leaf_blower_01`, `ig_siemonyetarian`, `V_MICHAEL_PS_BATHROOM_WITHOUT_WINDOW`, `bison3`

**Audio banks** (4) - `ARM_3_03`, `GARDEN_LEAF_BLOWER`, `ARM_3_01`, `ARM_3_02_CAR_CRASH`

**Sounds** (19) - `ARM_3_CLIMB_INTO_GARDEN`, `ARM_3_RAM_DEALERSHIP`, `ARM_3_TAKE_OUT_GARDENER`, `ARM_3_TARGET_GARDENER`, `ARM_3_BEAT_DOWN`, `ARM_3_WINDOW_FOCUS_CAM`, `ARM_3_INSIDE_HOUSE`, `ARM_3_STEAL_CAR`, `ARM_3_DRIVE_TO_MICHAELS_HOUSE`, `ARM_3_ENTER_GARAGE`, `ARM_3_DRIVE_TO_DEALERSHIP`, `ARM_3_EXIT_THROUGH_GATE`, `ARM_3_ENTER_HOUSE`, `ARM_3_DRIVE_PHONE_SIMEON`, `GARDENING_LEAFBLOWER_ANIM_TRIGGERED`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `ARM_3_CAR_GLASS_CRASH`, `ARM_3_PISTOL_COCK`

**Particle effects** (1) - `ent_anim_leaf_blower`

**Text labels** (12) - `MICHAEL`, `SIMEON`, `JIMMY`, `TRACEY`, `ARM3AUD`, `FRANKLIN`, `NULL`, `GARDENER`, `AMANDA`, `TENNISCOACH`, `57EIG117`, `ARM3`

**Relationship groups** (2) - `BUDDIES`, `ENEMIES`

**Timecycle modifiers** (1) - `Hint_cam`

**Interiors and entity sets** (6) - `V_Michael`, `v_carshowroom`, `csr_beforeMission`, `csr_afterMissionA`, `csr_afterMissionB`, `csr_inMission`

**Doors** (8) - `v_ilev_mm_doorw`, `v_ilev_fib_door1`, `v_ilev_mm_doorson`, `v_ilev_mm_doordaughter`, `v_ilev_mm_door`, `v_ilev_csr_door_l`, `v_ilev_csr_door_r`, `prop_bh1_48_gate_1`

**Vehicle mods** (2) - `bjxl`, `patriot`

**Hashed names** (1) - `MISS_ARMENIAN3_FRANKLIN_TENSE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (444), `DOES_ENTITY_EXIST` (223), `IS_ENTITY_IN_ANGLED_AREA` (124), `PLAYER_ID` (86), `IS_ENTITY_DEAD` (79), `GET_ENTITY_COORDS` (66), `IS_ENTITY_PLAYING_ANIM` (60), `GET_GAME_TIMER` (59), `IS_PED_INJURED` (58), `IS_AUDIO_SCENE_ACTIVE` (56), `IS_DOOR_REGISTERED_WITH_SYSTEM` (40), `IS_ENTITY_AT_COORD` (40), `STOP_AUDIO_SCENE` (40), `FREEZE_ENTITY_POSITION` (39), `SET_MODEL_AS_NO_LONGER_NEEDED` (36), `SET_VEHICLE_EXTRA` (36), `CLEAR_PED_TASKS` (35), `DISABLE_CONTROL_ACTION` (33), `SET_PED_KEEP_TASK` (30), `SET_VEHICLE_DOORS_LOCKED` (29), `GET_DISTANCE_BETWEEN_COORDS` (29), `IS_SYNCHRONIZED_SCENE_RUNNING` (28), `TASK_PLAY_ANIM_ADVANCED` (27), `REGISTER_ENTITY_FOR_CUTSCENE` (26), `SET_PED_COMPONENT_VARIATION` (26), `WAIT` (24), `CLEAR_AREA` (24), `TASK_PLAY_ANIM` (24), `GET_ENTITY_HEADING` (23), `REQUEST_MODEL` (23)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x36 · `23.1441f` x28 · `-1150.328f` x28 · `-149.383f` x28 · `0.5f` x19 · `0.2f` x19 · `71.825f` x17 · `-800.835f` x15 · `170.158f` x15 · `75.79f` x15 · `-56.13f` x13 · `-1097.6f` x13 · `25.16f` x13 · `3.5f` x11 · `71.60547f` x9 · `0.25f` x9 · `75.74074f` x9 · `-1.5f` x9 · `-793.703f` x9 · `181.647f` x9 · `76.89f` x8 · `-806.52f` x8 · `169.751f` x8 · `75.693f` x8

## Other strings

Literals whose consuming native was not classified:

`bjxl`, `premier`, `HaltVehicle`, `ARM3_DRIV`, `Franklin`, `Siemon`, `ARM3_STOP`, `ARM3_GUN`, `Michael`, `tailgater`, `ARM3HLP_SNEAK`, `LockedDoor_TryOpen_Stealth`, `lockeddoor_tryopen`, `ARM3_HIT`, `bison3`, `WindowSmashed`, `Destination1`, `Destination2`, `Destination3`, `Destination4`, `DES_Showroom`, `ARM3_GUNA`, `ARM3_GUNB`, `RagdollBlock`, `ARM3_START`, `ARM3_MIC`, `ARM3_BLOWN`, `customer`, `Showroom_Car`, `ARM3HLP_LOCKON`

---

Source: `decompiled_scripts/armenian3.c`
