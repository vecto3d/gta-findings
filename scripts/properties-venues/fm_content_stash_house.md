# fm_content_stash_house.c

Properties and venues script. 4 anim dicts; 12 models; 3 scaleforms.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 503,809 |
| Functions | 10,239 (253 unique, 9,986 shared) |
| Unique lines | 17,798 (3.5% of file) |

## Assets

**Animation dictionaries** (4) - `ANIM@SCRIPTED@PLAYER@FREEMODE@IG5_SAFE_CRACK@MALE@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@IG5_SAFE_CRACK@HEELED@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@IG6_STASH_ENTRY@DOOR_TRANS@HINGE_L@`, `anim@door_trans@hinge_l@`

**Models and props** (12) - `prop_whiskey_bottle`, `prop_ld_wallet_01`, `gr_prop_gunlocker_ammo_01a`, `vw_prop_casino_calc`, `bkr_prop_coke_doll`, `prop_cs_box_clothes`, `hei_prop_heist_docs_01`, `prop_cs_lester_crate`, `prop_champ_01a`, `gr_prop_gr_laptop_01c`, `bkr_prop_weed_table_01a`, `bkr_prop_weed_table_01b`

**Audio banks** (2) - `SCRIPT/ALARM_KLAXON_04`, `DLC_HEI4/DLCHEI4_GENERIC_01`

**Sounds** (8) - `Safe_Minigame_Sounds`, `GTAO_XM3_FRM_IG6_STASH_ENTRY_Door_Breach_Kick`, `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Input_Code_Enter_Correct_Final`, `Input_Code_Enter_Wrong`, `Input_Code_Up`, `Input_Code_Down`

**Scaleform movies** (3) - `SET_VALUE`, `SET_CURSOR_POSITION`, `SET_STATE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (79), `SET_BIT` (29), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (25), `NET_TO_ENT` (22), `ROUND` (18), `PLAYER_PED_ID` (17), `CLEAR_BIT` (8), `GET_ENTITY_COORDS` (8), `IS_STRING_NULL_OR_EMPTY` (7), `DISABLE_CONTROL_ACTION` (6), `CLEAR_PED_TASKS` (6), `DOES_ENTITY_EXIST` (6), `PLAY_SOUND_FRONTEND` (6), `PLAYER_ID` (5), `NETWORK_IS_PARTICIPANT_ACTIVE` (5), `SET_ENTITY_VISIBLE` (5), `SET_ENTITY_COLLISION` (5), `IS_SYNCHRONIZED_SCENE_RUNNING` (4), `GET_SYNCHRONIZED_SCENE_PHASE` (4), `TO_FLOAT` (4), `IS_DISABLED_CONTROL_JUST_PRESSED` (4), `IS_ENTITY_VISIBLE` (4), `SET_ENTITY_COORDS` (4), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (4), `IS_PED_INJURED` (4), `ABSF` (4), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (4), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (3), `INT_TO_PARTICIPANTINDEX` (3), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.01f` x2 · `2.5f` x2 · `0.4f` x2 · `0.6f` x1 · `0.99f` x1 · `0.004f` x1 · `0.205f` x1 · `0.17f` x1 · `-0.8f` x1

## Other strings

Literals whose consuming native was not classified:

`Kick_Door_Wood`, `pos`, `Kick_Door_Metal`, `head`, `num`, `int`, `veh`, `rot`, `bsa`, `typ`, `ibs`, `MAX_NUM_SCENARIOS`, `grp`, `sprt`, `hclr`, `scl`, `xm3_safe_01a`, `MAX_NUM_TRANSITIONS`, `baller`, `primo2`, `sabregt2`, `blp`, `fmbs`, `crt`, `wpn`

---

Source: `decompiled_scripts/fm_content_stash_house.c`
