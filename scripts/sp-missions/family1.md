# family1.c

SP missions script. 17 anim dicts; 13 models; 3 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 128,073 |
| Functions | 947 (109 unique, 838 shared) |
| Unique lines | 11,887 (9.3% of file) |

## Assets

**Animation dictionaries** (17) - `MISSFAM1_YachtBattleonYacht02_`, `MISSFAM1_YachtBattle`, `MISSFAM1_YachtBattleincar01_`, `clipset@missfam1_jimmy_sit`, `MISSFAM1_YACHTBATTLEonYacht02_`, `MISSFAM1_YachtBattleonYacht01_`, `clipset@missfam1_jimmy_sit_rear`, `MISSFAM1_YACHTBATTLEinCar01_`, `MISSFAM1_YACHTBATTLEonYacht01_`, `MISSFAM1_YACHTBATTLEinCar02_`, `veh@drivebystd_ds`, `MISSFAM1_YachtBattleincar02_`, `drive_by@low_ds`, `MISSFAM1_YachtBattleinCar02_`, `MISSFAM2MCS_intp1`, `missfam1leadinoutfamily_1_intp1_3`, `MISSFAM1_YachtBattleonyacht01_`

**Animations** (24) - `MISSFAM1_YACHTBATTLEonYacht02_`, `MISSFAM1_YACHTBATTLEonYacht01_`, `grab_pistol`, `MISSFAM1_YachtBattle`, `yacht_door_opening`, `onYacht_hitByBoom_boom`, `onYacht_fight02Success_thug`, `onBoom_shuffleAlong_Thug`, `onBoom_hangLoop_J`, `MISSFAM1_YachtBattleonYacht02_`, `onYacht_jumpToCarIntro_F`, `onYacht_fight02Success_f`, `onYacht_failIdle_thug`, `MISSFAM2MCS_intp1`, `FAM_2_INT_P1_MICHAEL`, `missfam1leadinoutfamily_1_intp1_3`, `base`, `onYacht_getOnBoom_thug`, `Yacht_Door_Opening_mastOUT`, `onBoom_hitJimmyLoop_Thug`, `onBoom_twohand_hang_enter`, `onBoom_twohand_hang_idle`, `onboom_loop_goon`, `onBoom_liftLegs_J`

**Models and props** (13) - `ig_jimmydisanto`, `g_m_y_salvagoon_01`, `prop_ld_test_01`, `trailers2`, `prop_champ_box_01`, `phantom`, `v_ilev_mm_doorm_l`, `v_ilev_mm_doorm_r`, `prop_streetlight_03d`, `tr3`, `prop_lrggate_02_ld`, `p_tumbler_02_s1`, `prop_cigar_02`

**Audio banks** (5) - `FAMILY_1_CHASE_01`, `FAMILY_1_CHASE_02`, `CAR_CRASHES_01`, `FAMILY_1_BOAT_STRAIN`, `FAMILY_1_CAR_BREAKDOWN`

**Sounds** (32) - `FAM1_HIGHWAY_CHASE`, `FAMILY_1_FOCUS_ON_YACHT`, `FAMILY1_FAKE_RICOCHET`, `FAMILY1_CAR_CRASH_BIG`, `FAMILY_1_CAR_BREAKS_DOWN`, `FAMILY1_BOAT`, `FAMILY1_BOX_HIT_FRANKLIN`, `FAMILY_1_PROTECT_FRANKLIN`, `FAMILY_1_SHOOT_THE_ENEMY_02`, `FAMILY_1_YACHT_ARRIVES`, `FAMILY_1_FRANKLIN_CLIMBING`, `FAMILY_1_SAVE_JIMMY`, `FAMILY_1_CATCH_FRANKLIN`, `FAMILY_1_GET_THE_YACHT`, `FAMILY_1_CAR_BREAKDOWN`, `FAMILY_1_CAR_BREAKDOWN_ADDITIONAL`, `TEST_SCREAM_LONG`, `FAMILY_1_DRIVE_TO_HIGHWAY`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `FAMILY_1_FRANKLIN_JUMPS`, `FAMILY1_JUMPTOYACHT`, `FAM1_THROWN_OVERBOARD`, `FAMILY1_THROWN_OVERBOARD1`, `FAMILY1_BOOM_SWING1`, `FAM1_BOOM_SWING`, `FAM1_DROP_IN_CAR`, `FAM1_JUMP_TO_YACHT`, `FAM1_LAND_ON_BONNET`, `FAMILY1_LAND_ON_BONNET`, `FAMILY1_DROP_IN_CAR`, `FAM1_RADIO_FADE`

**Particle effects** (3) - `damage`, `scr_fam1_veh_smoke`, `scr_fam1_blood_headshot`

**Text labels** (13) - `FAM1AUD`, `JIMMY`, `FRANKLIN`, `MICHAEL`, `FAMILY1`, `NULL`, `HAO`, `YACHTPED1`, `YACHTPED2`, `YACHTPED4`, `TRACEY`, `YACHTPED3`, `EXTRASUNNY`

**Vehicle recordings** (5) - `Fam1New`, `Fam1Cine`, `Fam1End`, `Fam1Cam`, `Fam1`

**Relationship groups** (2) - `player`, `THIEVES`

**Timecycle modifiers** (1) - `sunglasses`

**Interiors and entity sets** (1) - `v_michael`

**Vehicle mods** (3) - `sentinel2`, `sentinel`, `tr3`

**Hashed names** (2) - `MISS_FAMILY1_JIMMY_SIT_REAR`, `MISS_FAMILY1_JIMMY_SIT`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (236), `IS_ENTITY_DEAD` (211), `IS_PED_INJURED` (100), `DOES_ENTITY_EXIST` (71), `GET_SYNCHRONIZED_SCENE_PHASE` (64), `GET_GAME_TIMER` (62), `PLAYER_ID` (58), `IS_SYNCHRONIZED_SCENE_RUNNING` (53), `GET_ENTITY_COORDS` (52), `DISABLE_CONTROL_ACTION` (41), `REQUEST_MODEL` (36), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (34), `IS_PED_IN_VEHICLE` (33), `SET_MODEL_AS_NO_LONGER_NEEDED` (33), `IS_SCRIPTED_CONVERSATION_ONGOING` (33), `SET_CAM_FOV` (32), `HAS_MODEL_LOADED` (31), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (31), `SET_PED_INTO_VEHICLE` (30), `TRIGGER_MUSIC_EVENT` (30), `POINT_CAM_AT_ENTITY` (29), `WAIT` (28), `ATTACH_CAM_TO_ENTITY` (28), `GET_ENTITY_SPEED` (28), `DOES_BLIP_EXIST` (28), `SET_AIR_DRAG_MULTIPLIER_FOR_PLAYERS_VEHICLE` (27), `REMOVE_ANIM_DICT` (25), `STOP_PLAYBACK_RECORDED_VEHICLE` (25), `GET_ENTITY_BONE_INDEX_BY_NAME` (25), `SET_CAM_ACTIVE` (24)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x14 · `3.5f` x12 · `96.2191f` x9 · `3.9f` x8 · `0.25f` x7 · `-1104.313f` x7 · `-1975.673f` x7 · `12.0489f` x7 · `72.83f` x7 · `0.5f` x5 · `723.9294f` x5 · `-1087.5f` x5 · `21.1693f` x5 · `0.7f` x5 · `0.99f` x5 · `2.25f` x4 · `1.5f` x4 · `-816.72f` x4 · `179.1f` x4 · `0.0001f` x4 · `3.5141f` x3 · `-2605.764f` x3 · `-1127.798f` x3 · `-1980.447f` x3

## Other strings

Literals whose consuming native was not classified:

`feltzer2`, `chassis`, `phantom`, `seat_pside_f`, `MISSFAM1_YachtBattleonYacht02_`, `FAM1_FAIL`, `asterope`, `manana`, `bison`, `misc_e`, `MISSFAM1_YachtBattleinCar01_`, `Franklin`, `CMN_FLEAVE`, `jackal`, `Michael`, `CMN_GENGETBCK`, `MISSFAM1_YachtBattleincar01_`, `dilettante`, `MISSFAM1_YachtBattleonYacht01_`, `DEFAULT_SCRIPTED_CAMERA`, `trailers2`, `FAMILY_1_BOAT_PEDS`, `YB_GETIN`, `CMN_FDIED`, `blista`, `GENERIC_FRIGHTENED_HIGH`, `FRANKLIN_NORMAL`, `FAM1_ATTACK`, `Fam1Cam`, `FAM1_START`

---

Source: `decompiled_scripts/family1.c`
