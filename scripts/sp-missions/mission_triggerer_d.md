# mission_triggerer_d.c

SP missions script. 8 anim dicts; 28 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 117,055 |
| Functions | 1,090 (218 unique, 872 shared) |
| Unique lines | 4,896 (4.2% of file) |

## Assets

**Animation dictionaries** (8) - `missmic2leadinmic_2_int`, `cellphone@`, `MISSHeistFBI3BleadInOut`, `missheist_agency3aleadinoutah_3a_int`, `missheistfbisetup1leadinoutah_1_int`, `missfinale_c2leadinoutfin_c_int`, `misssolomon_2leadinout`, `MISSBIGSCORE2ALEADINOUT@BS_2A_2B_INT`

**Animations** (31) - `misssolomon_2leadinout`, `MISSHeistFBI3BleadInOut`, `missfinale_c2leadinoutfin_c_int`, `missheistfbisetup1leadinoutah_1_int`, `missmic2leadinmic_2_int`, `missheist_agency3aleadinoutah_3a_int`, `_leadin_action_lester`, `_intro_loop_lester`, `AH_3B_INT_leadin_lester`, `_LEADIN_ACTION_LESTER`, `_LEADIN_LOOP2_LESTER`, `idle_01_sol_2_int_rocco`, `idle_01_sol_2_int_milton`, `idle_01_sol_2_int_solomon`, `_leadin_loop_lester`, `idle_03_sol_2_int_rocco`, `idle_03_sol_2_int_milton`, `idle_03_sol_2_int_solomon`, `idle_02_sol_2_int_rocco`, `idle_02_sol_2_int_milton`, `idle_02_sol_2_int_solomon`, `_LEADIN_LOOP1_LESTER`, `cellphone@`, `cellphone_text_in`, `mic_2_int_alt1_leadin_denise`, `mic_2_int_alt1_leadin_f1`, `mic_2_int_alt1_leadin_f2`, `ah_3b_int_leadin_lester`, `AH_3B_INT_loop_Lester`, `MISSBIGSCORE2ALEADINOUT@BS_2A_2B_INT`, `LESTER_BASE_IDLE`

**Models and props** (28) - `prop_cs_walking_stick`, `s_m_y_construct_01`, `prop_cs_lester_crate`, `ig_roccopelosi`, `u_m_y_guido_01`, `s_m_y_cop_01`, `s_m_y_fireman_01`, `v_ilev_fa_frontdoor`, `s_m_m_security_01`, `prop_phone_ing`, `police3`, `ig_solomon`, `prop_wheelchair_01_s`, `ig_lestercrest`, `csb_denise_friend`, `v_ind_ss_chair3_cso`, `gauntlet`, `armytrailer2`, `packer`, `policet`, `fugitive`, `baller2`, `rapidgt`, `surano`, `carbonizzare`, `player_zero`, `v_ind_ss_chair01`, `firetruk`

**Audio banks** (3) - `SCRIPT\ASSASSINATION_MULTI`, `Lester1A_01`, `INTERCOM`

**Sounds** (5) - `ASS_PAYPHONE_RING_master`, `UNLOCK_DOOR`, `LESTER1A_SOUNDS`, `DOOR_BUZZER_LOOP`, `FINALE_INTRO_SOUNDSET`

**Text labels** (13) - `MICHAEL`, `NULL`, `COP`, `LESTER`, `FBS1AUD`, `AH3BAUD`, `FINPRB`, `FINC1AU`, `ROCCO`, `FBIPRAU`, `SOL2AUD`, `FRANKLIN`, `DENISE`

**Scenarios** (4) - `SCRAP_SECURITY`, `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_SMOKING`

**Decorators** (1) - `MapGauntlet`

**Relationship groups** (7) - `Player Group`, `WorkerPedGroup`, `GuardGroup`, `FIREMEN`, `player`, `TS_FINC1`, `REL_TS_FRIENDLY`

**Interiors and entity sets** (3) - `v_strip3`, `v_franklins`, `v_sweatempty`

**Doors** (3) - `prop_com_gar_door_01`, `prop_fnclink_03gate5`, `v_ilev_fa_frontdoor`

**Vehicle mods** (9) - `gauntlet`, `fugitive`, `baller2`, `firetruk`, `towtruck`, `towtruck2`, `rapidgt`, `surano`, `carbonizzare`

**Hashed names** (1) - `AGENCY_PREP_1`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (206), `DOES_ENTITY_EXIST` (75), `IS_PED_INJURED` (54), `SET_MODEL_AS_NO_LONGER_NEEDED` (44), `GET_ENTITY_COORDS` (42), `DOOR_SYSTEM_SET_DOOR_STATE` (38), `HAS_MODEL_LOADED` (36), `REQUEST_MODEL` (36), `CLEAR_AREA` (29), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (28), `VDIST2` (28), `IS_ENTITY_IN_ANGLED_AREA` (27), `REMOVE_RELATIONSHIP_GROUP` (24), `IS_ENTITY_DEAD` (24), `SET_BIT` (24), `CREATE_PED` (23), `TASK_SYNCHRONIZED_SCENE` (21), `GET_VEHICLE_PED_IS_IN` (19), `SET_PED_COMPONENT_VARIATION` (18), `REMOVE_SCENARIO_BLOCKING_AREA` (17), `IS_VEHICLE_DRIVEABLE` (16), `IS_PED_IN_ANY_VEHICLE` (16), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (16), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (14), `CREATE_SYNCHRONIZED_SCENE` (13), `CREATE_VEHICLE` (12), `DOOR_SYSTEM_SET_OPEN_RATIO` (12), `PLAYER_ID` (12), `SET_PED_RELATIONSHIP_GROUP_HASH` (11), `REMOVE_DOOR_FROM_SYSTEM` (11)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`29.3953f` x7 · `2.5f` x6 · `-14.23323f` x6 · `-1441.486f` x6 · `30.10742f` x6 · `29.05389f` x5 · `940.2881f` x4 · `-1573.877f` x4 · `29.3866f` x4 · `917.5028f` x4 · `-1517.401f` x4 · `29.9673f` x4 · `869.6423f` x4 · `-1541.423f` x4 · `29.2516f` x4 · `884.3046f` x4 · `-1573.188f` x4 · `29.8247f` x4 · `903.8805f` x4 · `-1575.02f` x4 · `29.8327f` x4 · `906.2186f` x4 · `-1575.108f` x4 · `29.8125f` x4

## Other strings

Literals whose consuming native was not classified:

`Trevor`, `HACKER_SELECTION`, `missheistfbisetup1leadinoutah_1_int`, `Franklin`, `player_one`, `gauntlet`, `player`, `AZL_LESTERS_DOGS`, `missfinale_c2leadinoutfin_c_int`, `lester`, `rapidgt`, `surano`, `carbonizzare`, `csb_denise_friend`, `armytrailer2`, `packer`, `police3`, `policet`, `player_zero`, `AM_H_AHP1`, `AM_H_PREP6`, `firetruk`, `_intro_loop_cane`, `fugitive`, `baller2`, `MIC_2_INT`, `Lester`, `FBS1_INT_LI`, `AM_H_GAUNT_R`, `FIN_A_INT`

---

Source: `decompiled_scripts/mission_triggerer_d.c`
