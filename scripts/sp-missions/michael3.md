# michael3.c

SP missions script. 2 anim dicts; 20 models; 1 particle effects.

| | |
|---|---|
| Category | SP missions |
| Total lines | 125,570 |
| Functions | 994 (228 unique, 766 shared) |
| Unique lines | 12,353 (9.8% of file) |

## Assets

**Animation dictionaries** (2) - `missmic_3_ext@leadin@mic_3_ext`, `missmic3`

**Animations** (22) - `missmic3`, `idle_a`, `idle_b`, `idle_c`, `WALKWAY_B`, `Dead`, `dead_g`, `_leadin_trevor`, `WALKWAY_A`, `mw01run_into_cover`, `mw02run_into_cover`, `mw04run_into_cover`, `SWAT_RUN_2_COVER_A`, `SWAT_RUN_2_COVER_B`, `leadout_swat_a`, `leadout_swat_b`, `leadout_mic`, `leadout_trev`, `leadout_pilot`, `newspaper_dialogue_idle_dave`, `newspaper_idle_outro_dave`, `newspaper_idle_loop_dave`

**Models and props** (20) - `p_cs_newspaper_s`, `s_m_y_swat_01`, `s_m_m_ciasec_01`, `ig_andreas`, `ig_paper`, `s_m_y_blackops_01`, `dominator`, `prop_cs_ciggy_01b`, `ig_davenorton`, `carbonizzare`, `p_gdoor1colobject_s`, `prop_wrecked_buzzard`, `prop_ch1_07_door_01l`, `prop_ch1_07_door_01r`, `MT_FIB1`, `MT_FIB2`, `MT_FIB3`, `MT_FIB4`, `MT_FIB5`, `vacca`

**Sounds** (12) - `MI_3_SHOOTOUT_PLAYER_IS_TREVOR`, `MI_3_SHOOTOUT_PLAYER_IS_MICHAEL`, `MI_3_TREVOR_SHOOTS_HELICOPTER`, `MI_3_ESCAPE_IN_CAR`, `MI_3_SHOOTOUT_START`, `MI_3_SHOOTOUT_SNIPER_SCOPE`, `MI_3_ESCAPE_HELICOPTER_ATTACK`, `Hit_In`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `MI_3_KILL_ENEMIES_IN_COURTYARD`, `MI_3_HELICOPTER_CRASH_SCENE`, `MI_3_SHOOTOUT_ENEMIES_ON_STAIRS`

**Speech contexts** (2) - `STAY_DOWN`, `SPEECH_PARAMS_FORCE`

**Particle effects** (1) - `scr_mich3_heli_fire`

**Text labels** (19) - `MICHAEL`, `TREVOR`, `FRANKLIN`, `MIC3CIA3`, `M3_DVWARN`, `MIC3`, `NULL`, `M3AUD`, `MERRYWEATHERE`, `MERRYWEATHERD`, `DFDVDWNST`, `MIC3MERRYD`, `MIC3CIA1`, `MIC3AGEN3`, `MIC3CIA2`, `MIC3CIA4`, `MIC3FIB1`, `MIC3FIB2`, `MIC3FIB4`

**Scenarios** (1) - `KORTZ_SECURITY`

**Waypoint recordings** (1) - `mic3_intro_walk`

**Relationship groups** (7) - `FRIEND`, `CIA`, `FIB`, `MERRYWEATHER`, `FIB_FINAL`, `MW_FINAL`, `CIA_FINAL`

**Hashed names** (1) - `V_FakeKortzCenter`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (291), `DOES_ENTITY_EXIST` (111), `IS_PED_INJURED` (62), `SET_ENTITY_COORDS` (53), `SET_ENTITY_HEADING` (53), `SET_RELATIONSHIP_BETWEEN_GROUPS` (47), `HAS_MODEL_LOADED` (46), `TASK_COMBAT_HATED_TARGETS_AROUND_PED` (44), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (42), `SET_ENTITY_PROOFS` (38), `TASK_PUT_PED_DIRECTLY_INTO_COVER` (36), `DELETE_PED` (35), `IS_ENTITY_IN_ANGLED_AREA` (35), `GET_ENTITY_COORDS` (34), `REMOVE_PED_DEFENSIVE_AREA` (33), `SET_PED_SPHERE_DEFENSIVE_AREA` (33), `PLAYER_ID` (32), `GET_GAME_TIMER` (29), `TASK_SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (29), `SET_PED_COMPONENT_VARIATION` (29), `SET_ENTITY_INVINCIBLE` (27), `SET_BIT` (26), `DOES_BLIP_EXIST` (24), `DOOR_SYSTEM_SET_DOOR_STATE` (24), `FREEZE_ENTITY_POSITION` (23), `GIVE_WEAPON_TO_PED` (23), `START_AUDIO_SCENE` (22), `CLEAR_PED_TASKS` (21), `IS_VEHICLE_DRIVEABLE` (21), `CLEAR_BIT` (21)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`183.6019f` x32 · `0.25f` x18 · `173.602f` x18 · `0.5f` x14 · `183.6041f` x12 · `24.2243f` x12 · `168.6018f` x10 · `183.6021f` x9 · `1.5f` x8 · `173.4666f` x7 · `183.602f` x6 · `186.6019f` x6 · `-2155.383f` x5 · `237.1668f` x5 · `183.4019f` x5 · `-2150.729f` x5 · `232.467f` x5 · `183.606f` x5 · `-2360.413f` x4 · `139.9656f` x4 · `163.4271f` x4 · `-2142.358f` x4 · `438.0082f` x4 · `203.5064f` x4

## Other strings

Literals whose consuming native was not classified:

`player`, `dominator`, `carbonizzare`, `FIRING_PATTERN_FULL_AUTO`, `missmic3`, `MORE_SEATS`, `LOSE_WANTED`, `Michael`, `MI_3_MICHAEL_GROUP`, `frogger`, `vacca`, `FIB_Goon_1`, `MIC_3_EXT`, `MI_3_TREVOR_GROUP`, `MIC_3_HELICOPTER_SHOT_DOWN_MASTER`, `MIC3_SNIPE`, `MW_HELI1_1`, `Andreas_Sanchez`, `Dreyfuss`, `CIA_Goon_1`, `CIA_Goon_2`, `CIA_Goon_3`, `Lead_FBI`, `FIB_Goon_2`, `FIB_Goon_3`, `MIC3_MISSION_START`, `MIC_3_INT`, `M3_DVWARN`, `mesa3`, `VEHICLE_POLICE_PURSUIT`

---

Source: `decompiled_scripts/michael3.c`
