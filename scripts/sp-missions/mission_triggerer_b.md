# mission_triggerer_b.c

SP missions script. 9 anim dicts; 34 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 120,873 |
| Functions | 1,142 (255 unique, 887 shared) |
| Unique lines | 7,863 (6.5% of file) |

## Assets

**Animation dictionaries** (9) - `missheistdocks2bleadinoutlsdh_2b_int`, `missheistdocks2aleadinoutlsdh_2a_int`, `cellphone@str`, `missheistdocksprep1ig_1`, `oddjobs@assassinate@hotel@leaning@`, `misstrevor3leadinout`, `misstrevor2leadinouttrv_2_int`, `misstimelapse@franklinold_home`, `mini@repair`

**Animations** (76) - `missheistdocks2aleadinoutlsdh_2a_int`, `missheistdocks2bleadinoutlsdh_2b_int`, `missfra1leadinoutfra_1_int_trevor`, `MISSChinese2_crystalMazeMCS1_IG`, `MISSCHINESE1LEADINOUTCHINESE_1_INT`, `missheistdockssetup1leadinout`, `missfra1leadinout`, `missfbi4leadinoutfbi_4_int`, `misstrevor2leadinouttrv_2_int`, `franklin_1_int_leadin_action_denise`, `misstrevor3leadinout`, `action_floyd`, `cleaning_wade`, `standing_loop_peda`, `franklin_1_int_leadin_loop_denise`, `_trevor_leadin_loop_denise`, `_trevor_leadin_talk_denise`, `MISSFBI1LEADINOUT`, `trevor_dri_int_leadin_action_wade`, `trv_2_int_ron_idle`, `action_wade`, `stand_loop_wade`, `stand_loop_floyd`, `Sitting_loop_Wade`, `Sitting_loop_Floyd`, `massage_loop_floyd`, `massage_loop_trevor`, `massage_loop_2_floyd`, `massage_loop_2_trevor`, `sitting_loop_michael`, `cellphone@str`, `cellphone_call_listen_c`, `lsdh_int_leadin_action_floyd`, `lsdh_int_leadin_action_wade`, `lsdh_int_leadin_react_floyd`, `lsdh_int_leadin_react_wade`, `action_trevor`, `leg_massage_floyd`, `leg_massage_trevor`, `leg_massage_b_floyd`, `leg_massage_b_trevor`, `standing_loop_michael`, `_trevor_leadin_loop_lamar`, `_trevor_leadin_loop_b_lamar`, `_trevor_leadin_loop_chop`, `_trevor_leadin_loop_franklin`, `_trevor_leadin_loop_b_franklin`, `MISSFBI4LEADINOUTFBI_4_MCS_3`, `_LEADIN_LOOP_MICHAEL`, `lsdh_int_leadin_loop_floyd`, `lsdh_int_leadin_loop_wade`, `mini@repair`, `fixing_a_ped`, `fbi_4_int_fra_idle_trv`, `FBI_1_INT_LEADIN_ACTION_DAVEN`, `FBI_1_INT_LEADIN_LOOP_DAVEN`, `bar_peds_action_janet`, `bar_peds_action_old_a`, `bar_peds_action_old_b`, `bar_peds_action_transl` ...

**Models and props** (34) - `s_m_y_marine_01`, `prop_tumbler_01_empty`, `prop_ld_test_01`, `ig_janet`, `ig_old_man1a`, `ig_old_man2`, `s_m_m_dockwork_01`, `prop_sub_release`, `p_amb_phone_01`, `prop_cs_trowel`, `p_ld_heist_bag_s_1`, `s_m_y_garbage`, `ig_josef`, `cs_wade`, `player_zero`, `player_one`, `player_two`, `cargobob`, `buzzard`, `submersible`, `v_ilev_fa_frontdoor`, `ig_denise`, `trash`, `towtruck`, `s_m_m_trucker_01`, `prop_player_phone_01`, `ig_taostranslator`, `ig_russiandrunk`, `prop_tumbler_01`, `ig_lamardavis`, `peyote`, `ruiner`, `a_f_m_tourist_01`, `cs_russiandrunk`

**Audio banks** (2) - `SCRIPT\ASSASSINATION_MULTI`, `PORT_OF_LS_2B_HEIST_TOILET_FLUSH`

**Sounds** (3) - `ASS_PAYPHONE_RING_master`, `Flush`, `DOCKS_HEIST_FINALE_2B_SOUNDS`

**Text labels** (24) - `TREVOR`, `MICHAEL`, `FRANKLIN`, `D2AAUD`, `D1AUD`, `D2BAUD`, `FKN1AUD`, `FLOYD`, `WADE`, `DENISE`, `TRV3AUD`, `T2AUD`, `NULL`, `FBIPRAU`, `DOCKP1`, `DOCKH1`, `EXTRASUNNY`, `STEVE`, `FBI1AUD`, `DAVE`, `METHAUD`, `JANET`, `RON`, `SJC`

**Scenarios** (1) - `ARMY_GUARD`

**Waypoint recordings** (6) - `FBI4_P1_BlipRoute1`, `trv3_1`, `T2leadin`, `d1leadin`, `docksprep1`, `t2leadin`

**Relationship groups** (3) - `Player Group`, `MarineLeadInGroupHash`, `FRANKLIN_1_TS_RELGROUP`

**Doors** (1) - `v_ilev_fh_door4`

**Vehicle mods** (3) - `towtruck`, `trash`, `cargobob`

**Hashed names** (3) - `START_AUDIO`, `START_CS`, `FBI2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (378), `DOES_ENTITY_EXIST` (117), `IS_PED_INJURED` (100), `IS_ENTITY_IN_ANGLED_AREA` (76), `GET_ENTITY_COORDS` (71), `SET_MODEL_AS_NO_LONGER_NEEDED` (63), `TASK_SYNCHRONIZED_SCENE` (62), `SET_PED_COMPONENT_VARIATION` (52), `CREATE_SYNCHRONIZED_SCENE` (46), `VDIST2` (45), `SET_BIT` (38), `IS_ENTITY_DEAD` (36), `SET_SYNCHRONIZED_SCENE_LOOPED` (33), `REMOVE_RELATIONSHIP_GROUP` (32), `PLAYER_ID` (30), `GET_VEHICLE_PED_IS_IN` (30), `IS_PED_IN_ANY_VEHICLE` (27), `FREEZE_ENTITY_POSITION` (26), `SET_PLAYER_CONTROL` (24), `REMOVE_SCENARIO_BLOCKING_AREA` (24), `REQUEST_MODEL` (23), `HAS_MODEL_LOADED` (21), `CLEAR_AREA` (21), `SET_PED_MAX_MOVE_BLEND_RATIO` (21), `IS_VEHICLE_DRIVEABLE` (20), `SET_GAMEPLAY_HINT_CAMERA_BLEND_TO_FOLLOW_PED_MEDIUM_VIEW_MODE` (19), `CLEAR_BIT` (19), `IS_SYNCHRONIZED_SCENE_RUNNING` (18), `DISABLE_CONTROL_ACTION` (18), `GET_GAME_TIMER` (17)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x24 · `0.25f` x13 · `1.5f` x11 · `0.8f` x9 · `46.2151f` x9 · `11.63272f` x7 · `-13.865f` x7 · `-1446.12f` x7 · `29.625f` x7 · `2.88f` x7 · `-1.5f` x7 · `57.6f` x7 · `2.5f` x6 · `0.1f` x5 · `9.3184f` x5 · `-440.4123f` x5 · `1073.885f` x5 · `327.1169f` x5 · `46.214f` x5 · `5.5f` x5 · `9.432723f` x4 · `0.2f` x4 · `1.11f` x4 · `12.88272f` x4

## Other strings

Literals whose consuming native was not classified:

`Lamar`, `player_zero`, `player_two`, `player_one`, `towtruck`, `trash`, `AM_H_FBIC9`, `Wade`, `player`, `cargobob`, `buzzard`, `submersible`, `MISSFBI4LEADINOUTFBI_4_MCS_3`, `FBI_3_MDRPCA`, `FBI_3_FDRPCA`, `FBI_3_TDRPCA`, `FBI4_P1_BlipRoute1`, `CHINESE_1_INT_LEADIN`, `object`, `DH2A_INT_LI3`, `DS1_LDI`, `_LEADIN_LOOP_HEIST_BAG`, `AM_H_FBIPCASH`, `AM_H_FBIC11A`, `AM_H_FBIC11B`, `AM_H_FBIC10A`, `AM_H_FBIC10B`, `AM_H_FBIC5`, `AM_H_FBIC3`, `AM_H_FBIC1A`

---

Source: `decompiled_scripts/mission_triggerer_b.c`
