# fm_content_kortz_scoping.c

MP freemode script. 7 anim dicts; 9 models; 4 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 513,174 |
| Functions | 10,704 (455 unique, 10,249 shared) |
| Unique lines | 25,974 (5.1% of file) |

## Assets

**Animation dictionaries** (7) - `anim@door_trans@hinge_l@`, `mini@strip_club@throwout_d@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@gangops@morgue@office@laptop@`, `anim@scripted@pmc@IG1_GEN_HACK@heeled@`, `anim@scripted@pmc@IG1_GEN_HACK@male@`

**Models and props** (9) - `prop_off_chair_01`, `v_ilev_garageliftdoor`, `hei_prop_hst_usb_drive`, `prop_phone_ing`, `Prop_M61_Desktop_01a`, `a_f_y_clubcust_04`, `a_f_y_gencaspat_01`, `a_m_y_clubcust_04`, `a_m_y_gencaspat_01`

**Sounds** (6) - `Background`, `MP_CCTV_SOUNDSET`, `Push`, `GTAO_APT_DOOR_DOWNSTAIRS_GENERIC_SOUNDS`, `Keycard_Success`, `DLC_HEISTS_BIOLAB_FINALE_SOUNDS`

**Scaleform movies** (4) - `STRING`, `SET_VALUE`, `SET_MISSION_INFO`, `BTM_COST`

**Text labels** (2) - ` `, `EXTRASUNNY`

**Timecycle modifiers** (1) - `MissileOutOfRange`

**Interiors and entity sets** (1) - `GtaMloRoom001`

**Scripts launched** (1) - `fmmc_lasers`

**Hashed names** (1) - `m26_kortz_override`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (82), `PLAYER_ID` (75), `SET_PED_COMPONENT_VARIATION` (44), `SET_BIT` (22), `CLEAR_BIT` (14), `TO_FLOAT` (14), `GET_RANDOM_FLOAT_IN_RANGE` (12), `DOES_ENTITY_EXIST` (12), `VMAG` (11), `GET_ENTITY_COORDS` (11), `IS_STRING_NULL_OR_EMPTY` (11), `GET_ID_OF_THIS_THREAD` (10), `DISABLE_CONTROL_ACTION` (10), `NETWORK_GET_RANDOM_INT_RANGED` (9), `CEIL` (9), `GET_RANDOM_INT_IN_RANGE` (8), `GET_SYNCHRONIZED_SCENE_PHASE` (8), `GET_INTERIOR_AT_COORDS` (7), `VDIST` (7), `IS_PLAYER_DEAD` (6), `PLAYER_PED_ID` (6), `CLEAR_PED_TASKS` (6), `IS_NEW_LOAD_SCENE_ACTIVE` (6), `IS_SCREEN_FADED_OUT` (5), `NEW_LOAD_SCENE_STOP` (5), `RENDER_SCRIPT_CAMS` (5), `SET_PED_PROP_INDEX` (5), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (5), `END_TEXT_COMMAND_SCALEFORM_STRING` (5), `NETWORK_SEED_RANDOM_NUMBER_GENERATOR` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x8 · `-38.85f` x4 · `0.5f` x3 · `-48.85f` x3 · `2603.2f` x3 · `5903.8f` x3 · `0.99f` x2 · `2592.853f` x2 · `5925.925f` x2 · `2594.315f` x2 · `5925.932f` x2 · `0.3f` x2 · `0.6f` x2 · `2601.042f` x2 · `2596.552f` x2 · `-50.002f` x2 · `5920.9f` x2 · `5900.961f` x2 · `0.7f` x2 · `-0.2f` x1 · `3.5f` x1 · `2599.627f` x1 · `5922.294f` x1 · `-49.99965f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `ibs`, `bsa`, `sprt`, `hclr`, `scl`, `rot`, `rad`, `typ`, `SM26_RAF`, `XM25_AISECRETARY`, `XM25_AIBUTLER`, `XM25_AIGANG`, `KSC_OBJ_SEND`, `KSC_OBJ_COE`, `KSC_OBJ_SERV`, `MAX_NUM_SCENARIOS`, `blp`, `grp`, `veh`, `KSC_OBJ_SOLI`, `KSC_OBJ_ENT`, `MAX_NUM_TRANSITIONS`

---

Source: `decompiled_scripts/fm_content_kortz_scoping.c`
