# michael1.c

SP missions script. 6 anim dicts; 9 models; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 127,257 |
| Functions | 997 (131 unique, 866 shared) |
| Unique lines | 12,621 (9.9% of file) |

## Assets

**Animation dictionaries** (6) - `missmic1ig_2`, `missmic1ig_zero_hit_wheel`, `dead`, `missmic1leadinoutmic_1_mcs_2`, `missmic1ig_3_patrol`, `missmic1`

**Animations** (13) - `missmic1ig_2`, `jump_out_peda`, `jump_out_pedb`, `jump_out_pedc`, `jump_out_pedd`, `missmic1leadinoutmic_1_mcs_2`, `_leadin_trevor`, `dead`, `dead_g`, `missmic1ig_3_patrol`, `search_walk_fwd_b`, `missmic1ig_zero_hit_wheel`, `michael_hit_wheel`

**Models and props** (9) - `cs_bradcadaver`, `prop_cs_gravyard_gate_l`, `prop_cs_gravyard_gate_r`, `prop_ld_shovel`, `prop_tool_pickaxe`, `prop_coffin_02`, `prop_golf_ball`, `s_m_m_trucker_01`, `g_m_m_chicold_01`

**Audio banks** (6) - `Prologue_Train_Sounds`, `SCRIPT\FBI_HEIST_3B_SHOOTOUT`, `CHURCH_BELL`, `ICE_FOOTSTEPS`, `SNOW_FOOTSTEPS`, `Prologue_Sounds`

**Sounds** (24) - `MI_1_MIC_DUCKING_FOR_SPEECH_SCENE`, `MI_1_MIC_DRIVE_TO_GRAVEYARD`, `MI_1_GET_TO_CAR`, `MI_1_MIC_DRIVE_TO_AIRPORT`, `MI_1_TREV_DRIVE_TO_PLANE`, `MI_1_MIC_WALK_TO_GRAVEYARD`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `MI_1_SHOOTOUT_STEALTH`, `MI_1_SHOOTOUT_ENEMIES_ALERTED`, `MI_1_VAN_ARRIVES_02`, `MI_1_TREV_FLY_TO_LUDENDORFF`, `MIC1_RADIO_DISABLE`, `Train_Bell`, `Prologue_Sounds`, `MI_1_VAN_ARRIVES_03`, `MI_1_VAN_ARRIVES_01`, `MIC_1_RAIN_ON_PLANE_MASTER`, `MI_1_FLY_PRE_PHONECALL`, `RING`, `CHURCH_BELL_SOUNDSET`, `CHURCH_BELL_RING_COUNT`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`

**Particle effects** (1) - `cs_mich1_spade_dirt_throw`

**Text labels** (20) - `MCH1AUD`, `MICHAEL`, `OFF`, `TREVOR`, `EXTRASUNNY`, `OVERCAST`, `RAIN`, `THUNDER`, `NULL`, `MCH1CHIN1`, `MCH1CHIN2`, `MCH1CHIN3`, `MCH1CHIN4`, `MCH1CHIN5`, `LB080984`, `MCH1`, `SNOWLIGHT`, `DAVE`, `NERVOUSRON`, `CHENGSR`

**Waypoint recordings** (2) - `mic1_tdrive`, `mic1_c`

**Relationship groups** (1) - `ENEMIES`

**Timecycle modifiers** (1) - `graveyard_shootout`

**Vehicle mods** (5) - `asea2`, `mesa2`, `taxi`, `policeold1`, `policeold2`

**Hashed names** (1) - `door`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (364), `DOES_ENTITY_EXIST` (217), `IS_PED_INJURED` (130), `SET_PED_COMBAT_ATTRIBUTES` (110), `GET_GAME_TIMER` (94), `IS_ENTITY_DEAD` (93), `IS_VEHICLE_DRIVEABLE` (68), `GET_RANDOM_INT_IN_RANGE` (56), `DOES_BLIP_EXIST` (50), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (44), `GET_ENTITY_COORDS` (43), `GET_PLAYERS_LAST_VEHICLE` (43), `PLAYER_ID` (41), `IS_ENTITY_AT_COORD` (37), `REMOVE_IPL` (31), `REQUEST_IPL` (31), `IS_IPL_ACTIVE` (30), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (29), `IS_SCREEN_FADED_OUT` (29), `IS_ENTITY_PLAYING_ANIM` (28), `REGISTER_ENTITY_FOR_CUTSCENE` (28), `IS_ENTITY_IN_ANGLED_AREA` (26), `CLEAR_RAGDOLL_BLOCKING_FLAGS` (24), `TRIGGER_MUSIC_EVENT` (23), `SET_VEHICLE_ON_GROUND_PROPERLY` (22), `IS_STREAM_PLAYING` (22), `SET_VEHICLE_ENGINE_ON` (22), `STOP_AUDIO_SCENE` (21), `DISABLE_CONTROL_ACTION` (21), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (20)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x16 · `0.1f` x8 · `0.4f` x7 · `0.5f` x6 · `2.5f` x6 · `-1.5f` x5 · `3.5f` x5 · `1.5f` x5 · `-16.5368f` x5 · `3238.347f` x4 · `-4687.663f` x4 · `114.673f` x4 · `3263.05f` x4 · `-4704.67f` x4 · `104.67f` x4 · `3267.14f` x4 · `-4561.37f` x4 · `132.76f` x4 · `3257.505f` x4 · `-4658.069f` x4 · `116.6803f` x4 · `0.01f` x4 · `71.15f` x4 · `0.12f` x4

## Other strings

Literals whose consuming native was not classified:

`FIRING_PATTERN_BURST_FIRE`, `FIRING_PATTERN_FULL_AUTO`, `MCH1_GBRLC`, `Trevor`, `player`, `Michael`, `Chinese_Goon`, `Michaels_car`, `Chinese_gunman`, `basic_dirt_skin`, `basic_dirt_cloth`, `MIC1_Shovel`, `MIC1_PickAxe`, `Coffin`, `MCH1_TRON`, `Chinese_Goon_Car`, `MIC1_ARRIVED_CHURCH`, `Dead_Brad`, `cuban800`, `prologue03_grv_cov`, `prologue03_grv_dug`, `prologue_grv_torch`, `MCH1_SPOT1`, `MCH1_SPOT2`, `MCH1_SPOT3`, `MCH1_SURROUND`, `component_at_ar_flsh`, `HAND_SHAKE`, `MCH1_TTMC`, `tailgater`

---

Source: `decompiled_scripts/michael1.c`
