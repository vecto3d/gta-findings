# family3.c

SP missions script. 2 anim dicts; 13 models; 3 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 131,054 |
| Functions | 1,016 (96 unique, 920 shared) |
| Unique lines | 12,782 (9.8% of file) |

## Assets

**Animation dictionaries** (2) - `missfam3`, `switch@michael@bench`

**Animations** (22) - `missfam3`, `shout_out_window_michael`, `switch@michael@bench`, `coach_idle`, `argument_outro_michael`, `shout_out_window_coach`, `incar_lookbehind_exit_driver`, `incar_lookbehind_idle_passenger`, `react_incar_brace_loop_f`, `shout_out_window_franklin`, `cellphone_call_listen_base`, `cellphone_call_out`, `react_incar_bumps_loop_f`, `react_incar_brace_exit_f`, `argument_outro_coach`, `bench_on_phone_idle_listen`, `exit_forward`, `incar_lookbehind_enter_driver`, `incar_lookbehind_idle_driver`, `incar_lookbehind_enter_passenger`, `incar_lookbehind_exit_passenger`, `react_incar_brace_enter_f`

**Models and props** (13) - `g_m_y_pologoon_01`, `prop_tennis_rack_01`, `baller`, `prop_windowbox_broken`, `prop_ld_rope_t`, `prop_ld_dummy_rope`, `prop_rope_family_3`, `prop_tail_gate_col`, `prop_windowbox_b`, `prop_tennis_rack_01b`, `a_m_m_bevhills_01`, `prop_phone_ing`, `cs_tenniscoach`

**Audio banks** (1) - `FAMILY3_1`

**Sounds** (21) - `FAMILY_3_RAYFIRE`, `FAMILY_3_FOCUS_ON_COACH`, `FAMILY_3_FIND_THE_COACH`, `FAMILY_3_ESCAPE_AS_FRANKLIN`, `FAMILY_3_ESCAPE_AS_MICHAEL`, `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `FAMILY_3_ARRIVE_AT_HOUSE`, `FAMILY_3_FOLLOW_THE_COACH`, `FAMILY_3_DRIVE_HOME`, `FAMILY_3_PULL_DOWN_HOUSE_SCENE`, `FAMILY_3_DRIVE_IN_TO_POSITION`, `FAMILY_3_RV_BLOCKS_ROAD`, `All`, `SHORT_PLAYER_SWITCH_SOUND_SET`, `FAMILY3_REAR_END_MASTER`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `FAMILY3_CABLE_STRAIN_MASTER`, `apply`, `FAMILY3_POST_DEBRIS_MASTER`

**Particle effects** (3) - `wheelspin`, `ent_ray_fam3_dust_settle`, `scr_fam3_wheelspin_dirt`

**Text labels** (10) - `FAM3AUD`, `TENNISCOACH`, `MICHAEL`, `FRANKLIN`, `NULL`, `CLOUDS`, `COP`, `FAM3`, `NATHALIA`, `LESTER`

**Relationship groups** (2) - `ENEMIES`, `TENNISCOACH`

**Vehicle mods** (7) - `tailgater`, `bison2`, `bison`, `bison3`, `sadler`, `blista`, `baller`

**Hashed names** (1) - `bonemask_head_neck_and_r_arm`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (298), `DOES_ENTITY_EXIST` (199), `IS_PED_INJURED` (134), `GET_GAME_TIMER` (112), `IS_VEHICLE_DRIVEABLE` (106), `DOES_BLIP_EXIST` (89), `IS_ENTITY_DEAD` (69), `GET_ENTITY_COORDS` (63), `DISABLE_CONTROL_ACTION` (62), `PLAYER_ID` (43), `SET_PED_CONFIG_FLAG` (39), `REMOVE_BLIP` (38), `SET_BIT` (33), `GET_VEHICLE_PED_IS_USING` (32), `CLEAR_PED_TASKS` (31), `IS_ENTITY_IN_ANGLED_AREA` (29), `IS_ENTITY_PLAYING_ANIM` (27), `SET_PED_COMBAT_ATTRIBUTES` (27), `REQUEST_MODEL` (24), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (23), `IS_AUDIO_SCENE_ACTIVE` (23), `IS_PED_IN_VEHICLE` (23), `SET_MODEL_AS_NO_LONGER_NEEDED` (22), `STOP_AUDIO_SCENE` (22), `HAS_MODEL_LOADED` (21), `IS_PED_IN_ANY_VEHICLE` (21), `SET_VEHICLE_ON_GROUND_PROPERLY` (21), `IS_PED_SITTING_IN_VEHICLE` (21), `CLEAR_BIT` (20), `IS_ENTITY_AT_COORD` (20)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x13 · `0.5f` x12 · `7.5f` x5 · `0.75f` x5 · `-1.5f` x4 · `0.9f` x4 · `-819.05f` x4 · `177.24f` x4 · `70.83f` x4 · `-1017.985f` x4 · `660.4285f` x4 · `147.4662f` x4 · `-2.1f` x4 · `0.6f` x4 · `43.51022f` x4 · `50.25604f` x4 · `-90.22699f` x3 · `-417.3332f` x3 · `45.11008f` x3 · `37.58002f` x3 · `-0.04153f` x3 · `-165.6635f` x3 · `1.5f` x3 · `0.3f` x3

## Other strings

Literals whose consuming native was not classified:

`player`, `Franklin`, `Michael`, `baller`, `LOSE_WANTED`, `bison2`, `Racket_1`, `Racket_2`, `Amanda`, `TennisCoach`, `FAM3_BALC`, `FAM3_GCSGS`, `FAM3_GCEL`, `FAM3_LOST`, `blista`, `FAM3_LOOK`, `FAM3_HSWITCH`, `FAM3_DBHA`, `FAM3_DBHB`, `FAM3_HPULL`, `FAM3_VAN`, `FAM3_GBIT`, `HAND_SHAKE`, `CamPushInNeutral`, `FAM3_SPOT`, `FAM3_STATA`, `FAM3_STATB`, `FAM3_GCEK`, `FAM3_FTC`, `CMN_FLEAVE`

---

Source: `decompiled_scripts/family3.c`
