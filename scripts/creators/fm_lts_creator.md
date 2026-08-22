# fm_lts_creator.c

Creators script. 1 anim dicts; 77 models; 2 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | Creators |
| Total lines | 441,645 |
| Functions | 5,686 (284 unique, 5,402 shared) |
| Unique lines | 38,072 (8.6% of file) |

## Assets

**Animation dictionaries** (1) - `anim@mp_snowball`

**Animations** (2) - `anim@mp_snowball`, `pickup_snowball`

**Models and props** (77) - `prop_mp_placement_sm`, `prop_mp_placement_lrg`, `prop_mp_max_out_sm`, `prop_mp_cant_place_sm`, `prop_flare_01`, `prop_mp_max_out_lrg`, `prop_mp_cant_place_lrg`, `g_m_y_lost_02`, `prop_const_fence02b`, `prop_ld_keypad_01`, `prop_ld_keypad_01b`, `g_m_y_mexgoon_02`, `g_m_y_ballaorig_01`, `g_m_y_korean_01`, `prop_armour_pickup`, `prop_ld_health_pack`, `p_parachute_s_shop`, `prop_ic_rock`, `prop_ic_boost`, `prop_ic_ghost`, `prop_hx_arm`, `prop_hx_deadl`, `prop_ic_accel`, `prop_ex_swap`, `prop_ex_b_time`, `prop_ic_deton`, `prop_ic_bomb`, `prop_ic_hop`, `prop_ic_repair`, `prop_ex_random`, `prop_hx_special_vehicle`, `prop_hx_special_ruiner`, `prop_hx_special_buggy`, `prop_ld_int_safe_01`, `p_v_43_safe_s`, `prop_box_ammo03a_set2`, `prop_box_ammo03a_set`, `hei_prop_crate_stack_01`, `prop_drop_crate_01_set`, `prop_mb_crate_01a_set`, `hei_prop_mini_sever_02`, `hei_prop_mini_sever_03`, `hei_prop_mini_sever_broken`, `hei_prop_hei_ammo_pile`, `hei_prop_heist_tub_truck`, `hei_prop_heist_weed_pallet_02`, `hei_prop_drug_statue_stack`, `hei_prop_heist_transponder`, `prop_news_disp_02d`, `prop_vend_snak_01`, `prop_vend_water_01`, `prop_train_ticket_02`, `prop_container_ld_pu`, `imp_prop_impexp_boxpile_01`, `imp_prop_impexp_boxpile_02`, `ba_prop_battle_track_exshort`, `ba_prop_battle_track_short`, `ba_prop_battle_tube_fn_01`, `ba_prop_battle_tube_fn_02`, `ba_prop_battle_tube_fn_03` ...

**Sounds** (11) - `ERROR`, `ADD_SPAWN_POINT`, `PLACE_ENEMY`, `NAV_UP_DOWN`, `SELECT`, `BACK`, `DELETE`, `PLACE_VEHICLE`, `PLACE_OBJECT`, `NAV_LEFT_RIGHT`, `EDIT`

**Scaleform movies** (2) - `STRING`, `ADD_INTRO_TO_WALL`

**Particle effects** (1) - `scr_mp_creator`

**Texture dicts** (3) - `MPMissMarkers128`, `MPOnMissMarkers`, `MPMissMarkers256`

**Text labels** (13) - `NUMBER`, `STRING`, `$`, `- $`, `XMAS`, `NULL`, `BOT`, `FMMCCRTV`, `SSLDID`, `ERROR_CHECKYACHTNAME`, `ERROR_CHECKVEHICLENAME`, `ERROR_CHECKPROFANITY`, `FACE`

**Decorators** (1) - `EnableVehLuxeActs`

**Relationship groups** (4) - `sRGH.rghLike`, `sRGH.rghPlayer`, `sRGH.rghHate`, `sRGH.rghIgnore`

**Vehicle mods** (6) - `mule`, `dune`, `windsor`, `titan`, `cargobob`, `cargobob2`

**Scripts launched** (8) - `FM_Mission_Controller`, `fm_mission_controller`, `fm_capture_creator`, `main`, `freemode`, `creator`, `fm_main_menu`, `appinternet`

**Hashed names** (3) - `CreateObject`, `Interrupt`, `fm_mission_creator`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (375), `CLEAR_BIT` (331), `ARE_STRINGS_EQUAL` (213), `DOES_ENTITY_EXIST` (204), `PLAYER_PED_ID` (203), `IS_CONTROL_JUST_PRESSED` (139), `DOES_BLIP_EXIST` (99), `GET_ENTITY_MODEL` (95), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (91), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (88), `END_TEXT_COMMAND_SCALEFORM_STRING` (88), `GET_ENTITY_COORDS` (83), `REMOVE_BLIP` (77), `IS_CONTROL_PRESSED` (62), `DELETE_OBJECT` (56), `PLAYER_ID` (56), `GET_GAME_TIMER` (52), `DATADICT_SET_INT` (52), `IS_STRING_NULL_OR_EMPTY` (44), `SET_MODEL_AS_NO_LONGER_NEEDED` (43), `DISPLAY_ONSCREEN_KEYBOARD` (40), `PLAY_SOUND_FRONTEND` (38), `SET_ENTITY_COORDS` (37), `GET_FILENAME_FOR_AUDIO_CONVERSATION` (36), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (34), `REQUEST_MODEL` (33), `TO_FLOAT` (32), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (32), `IS_PED_INJURED` (30), `FREEZE_ENTITY_POSITION` (27)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x36 · `0.75f` x25 · `0.5f` x21 · `0.3f` x12 · `0.25f` x6 · `0.02f` x6 · `0.1f` x6 · `0.2f` x5 · `-0.24f` x4 · `0.24f` x4 · `1.25f` x2 · `-0.1f` x1 · `-0.4f` x1 · `0.4f` x1 · `925.04f` x1 · `46.48f` x1 · `80.096f` x1 · `1.0019f` x1 · `0.7f` x1 · `0.09f` x1 · `-0.001f` x1 · `0.35f` x1 · `-0.6f` x1

## Other strings

Literals whose consuming native was not classified:

`FMMC_SEL_NO`, `FMMC_SEL_YES`, `FMMC_SEL_OFF`, `mp_m_freemode_01`, `FMMC_SEL_ON`, `FMMC_SEL_DEF`, `FMMC_SS_JO_OFF`, `FMMC_SS_JO_ON`, `MC_H_JTO_PP_T`, `FMMC_SS_TT_1`, `FMMC_SS_TT_0`, `FMMC_ER_006`, `FMMC_AB_13`, `FMMC_AB_15`, `FMMCNO_CLOUD`, `type`, `CTF_H_ZONE1`, `MC_H_ZONE1`, `FMMC_SPDADJF`, `MC_H_PRP_ADV`, `subtype`, `FMMC_SPDADJ`, `FMMC_ER_024`, `FMMC_JTO_P_T`

---

Source: `decompiled_scripts/fm_lts_creator.c`
