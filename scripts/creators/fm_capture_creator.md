# fm_capture_creator.c

Creators script. 83 models; 2 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | Creators |
| Total lines | 440,245 |
| Functions | 5,677 (256 unique, 5,421 shared) |
| Unique lines | 37,123 (8.4% of file) |

## Assets

**Models and props** (83) - `prop_mp_placement_sm`, `prop_mp_placement_lrg`, `prop_mp_max_out_sm`, `prop_mp_cant_place_sm`, `prop_flare_01`, `prop_mp_max_out_lrg`, `prop_mp_cant_place_lrg`, `prop_const_fence02b`, `s_m_m_ciasec_01`, `ig_michelle`, `ig_karen_daniels`, `ig_golfer_a`, `ig_golfer_b`, `ig_party_promo`, `ig_billionaire`, `ig_ballas_leader`, `ig_vernon`, `ig_vagos_leader`, `ig_ary_02`, `ig_johnny_guns`, `s_m_y_cop_01`, `prop_armour_pickup`, `prop_ld_health_pack`, `p_parachute_s_shop`, `prop_ic_rock`, `prop_ic_boost`, `prop_ic_ghost`, `prop_hx_arm`, `prop_hx_deadl`, `prop_ic_accel`, `prop_ex_swap`, `prop_ex_b_time`, `prop_ic_deton`, `prop_ic_bomb`, `prop_ic_hop`, `prop_ic_repair`, `prop_ex_random`, `prop_hx_special_vehicle`, `prop_hx_special_ruiner`, `prop_hx_special_buggy`, `prop_ld_int_safe_01`, `p_v_43_safe_s`, `prop_box_ammo03a_set2`, `prop_box_ammo03a_set`, `hei_prop_crate_stack_01`, `prop_drop_crate_01_set`, `prop_mb_crate_01a_set`, `hei_prop_mini_sever_02`, `hei_prop_mini_sever_03`, `hei_prop_mini_sever_broken`, `hei_prop_hei_ammo_pile`, `hei_prop_heist_tub_truck`, `hei_prop_heist_weed_pallet_02`, `hei_prop_drug_statue_stack`, `hei_prop_heist_transponder`, `prop_news_disp_02d`, `prop_vend_snak_01`, `prop_vend_water_01`, `prop_train_ticket_02`, `imp_prop_impexp_boxpile_01` ...

**Sounds** (10) - `ERROR`, `ADD_SPAWN_POINT`, `PLACE_ENEMY`, `SELECT`, `DELETE`, `NAV_UP_DOWN`, `PLACE_VEHICLE`, `PLACE_OBJECT`, `BACK`, `EDIT`

**Scaleform movies** (2) - `STRING`, `ADD_INTRO_TO_WALL`

**Particle effects** (1) - `scr_mp_creator`

**Texture dicts** (3) - `MPMissMarkers128`, `MPOnMissMarkers`, `MPMissMarkers256`

**Text labels** (8) - `NUMBER`, `STRING`, `$`, `- $`, `NULL`, `FMMCCRTV`, `SSLDID`, `FACE`

**Decorators** (1) - `EnableVehLuxeActs`

**Relationship groups** (4) - `sRGH.rghLike`, `sRGH.rghPlayer`, `sRGH.rghHate`, `sRGH.rghIgnore`

**Vehicle mods** (6) - `mule`, `dune`, `windsor`, `titan`, `cargobob`, `cargobob2`

**Scripts launched** (5) - `FM_Mission_Controller`, `fm_mission_controller`, `main`, `freemode`, `fm_main_menu`

**Hashed names** (1) - `fm_mission_creator`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (359), `CLEAR_BIT` (308), `DATADICT_GET_ARRAY` (239), `ARE_STRINGS_EQUAL` (221), `DATAARRAY_GET_INT` (201), `DOES_ENTITY_EXIST` (201), `DATAARRAY_GET_TYPE` (168), `PLAYER_PED_ID` (149), `IS_CONTROL_JUST_PRESSED` (148), `DOES_BLIP_EXIST` (95), `GET_ENTITY_MODEL` (93), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (91), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (88), `END_TEXT_COMMAND_SCALEFORM_STRING` (88), `GET_ENTITY_COORDS` (78), `REMOVE_BLIP` (76), `DELETE_OBJECT` (57), `IS_CONTROL_PRESSED` (57), `DATADICT_SET_INT` (52), `GET_GAME_TIMER` (50), `PLAYER_ID` (44), `SET_MODEL_AS_NO_LONGER_NEEDED` (42), `TO_FLOAT` (39), `SET_ENTITY_COORDS` (37), `PLAY_SOUND_FRONTEND` (36), `GET_FILENAME_FOR_AUDIO_CONVERSATION` (36), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (34), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (32), `REQUEST_MODEL` (31), `IS_PED_INJURED` (27)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x36 · `0.75f` x25 · `0.5f` x22 · `0.3f` x12 · `0.2f` x7 · `0.25f` x6 · `0.02f` x6 · `0.1f` x6 · `-0.24f` x4 · `0.24f` x4 · `0.4f` x3 · `1.25f` x2 · `925.04f` x1 · `46.48f` x1 · `80.096f` x1 · `0.09f` x1 · `-0.001f` x1 · `0.35f` x1 · `-0.6f` x1 · `-0.4f` x1 · `0.07f` x1 · `0.015f` x1 · `1.0019f` x1

## Other strings

Literals whose consuming native was not classified:

`FMMC_SEL_NO`, `FMMC_SEL_YES`, `FMMC_SEL_OFF`, `mp_m_freemode_01`, `FMMC_SEL_ON`, `FMMC_ER_006`, `FMMC_SEL_DEF`, `FMMC_SS_TT_1`, `FMMC_SS_TT_0`, `FMMCNO_CLOUD`, `FMMC_AB_13`, `FMMC_AB_15`, `MC_H_PRP_ADV`, `FMMCNO_SCLUB`, `FMMC_B_5`, `CRE_DEL_SPAR`, `CRE_DEL_SPWN`, `FMMC_IN_FMFTAG`, `FMMC_KEYC_P`, `FMMC_B_11`, `FMMC_ER_024`

---

Source: `decompiled_scripts/fm_capture_creator.c`
