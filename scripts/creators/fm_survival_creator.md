# fm_survival_creator.c

Creators script. 200 models; 4 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | Creators |
| Total lines | 446,632 |
| Functions | 5,879 (376 unique, 5,503 shared) |
| Unique lines | 40,703 (9.1% of file) |

## Assets

**Models and props** (200) - `prop_mp_placement_sm`, `prop_mp_placement_lrg`, `u_m_y_juggernaut_01`, `prop_mp_max_out_sm`, `prop_mp_cant_place_sm`, `prop_flare_01`, `prop_mp_max_out_lrg`, `prop_mp_cant_place_lrg`, `a_m_y_gay_01`, `a_m_y_gay_02`, `a_m_m_tranvest_01`, `a_m_m_tranvest_02`, `prop_const_fence02b`, `g_m_m_goons_01`, `ig_taostranslator`, `ig_taostranslator2`, `ig_taocheng2`, `a_m_m_salton_01`, `a_m_m_salton_02`, `s_m_y_westsec_02`, `s_m_y_casino_01`, `s_f_y_casino_01`, `a_m_y_musclbeac_01`, `ig_taocheng`, `g_m_y_salvagoon_01`, `g_m_y_salvaboss_01`, `prop_news_disp_02d`, `prop_vend_snak_01`, `prop_vend_water_01`, `prop_train_ticket_02`, `imp_prop_impexp_boxpile_01`, `imp_prop_impexp_boxpile_02`, `ba_prop_battle_track_exshort`, `ba_prop_battle_track_short`, `ba_prop_battle_tube_fn_01`, `ba_prop_battle_tube_fn_02`, `ba_prop_battle_tube_fn_03`, `ba_prop_battle_tube_fn_04`, `ba_prop_battle_tube_fn_05`, `prop_armour_pickup`, `prop_ld_health_pack`, `p_parachute_s_shop`, `prop_ic_rock`, `prop_ic_boost`, `prop_ic_ghost`, `prop_hx_arm`, `prop_hx_deadl`, `prop_ic_accel`, `prop_ex_swap`, `prop_ex_b_time`, `prop_ic_deton`, `prop_ic_bomb`, `prop_ic_hop`, `prop_ic_repair`, `prop_ex_random`, `prop_hx_special_vehicle`, `prop_hx_special_ruiner`, `prop_hx_special_buggy`, `imp_prop_ship_01a`, `gr_prop_damship_01a` ...

**Sounds** (8) - `ERROR`, `PLACE_ENEMY`, `NAV_UP_DOWN`, `ADD_SPAWN_POINT`, `DELETE`, `SELECT`, `BACK`, `EDIT`

**Scaleform movies** (4) - `MP_MISSION_DETAILS_CARD`, `SET_DATA_SLOT`, `SET_TITLE`, `DISPLAY_VIEW`

**Particle effects** (1) - `scr_mp_creator`

**Texture dicts** (2) - `MPMissMarkers128`, `MPMissMarkers256`

**Text labels** (13) - `NUMBER`, `STRING`, `NULL`, `SSLDID`, `PM_DAMAGE`, `PM_FIRERATE`, `PM_ACCURACY`, `PM_RANGE`, `CLEAR`, `FMMCCRTV`, `HIDDEN`, `FROZEN`, `INVINCIBLE`

**Decorators** (2) - `RandomID`, `EnableVehLuxeActs`

**Vehicle mods** (6) - `mule`, `windsor`, `dune`, `titan`, `cargobob`, `cargobob2`

**Scripts launched** (5) - `fm_survival_controller`, `FM_Survival_Controller`, `main`, `freemode`, `fm_main_menu`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (2956), `SET_BIT` (309), `CLEAR_BIT` (242), `DOES_ENTITY_EXIST` (228), `IS_CONTROL_JUST_PRESSED` (147), `PLAYER_PED_ID` (147), `SET_PED_PROP_INDEX` (134), `GET_RANDOM_INT_IN_RANGE` (100), `GET_ENTITY_MODEL` (94), `GET_ENTITY_COORDS` (89), `ARE_STRINGS_EQUAL` (88), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (83), `DOES_BLIP_EXIST` (79), `TO_FLOAT` (62), `REMOVE_BLIP` (58), `GET_GAME_TIMER` (57), `IS_CONTROL_PRESSED` (54), `DATADICT_SET_INT` (52), `DELETE_OBJECT` (47), `GET_HUD_COLOUR` (42), `SET_ENTITY_COORDS` (41), `SET_MODEL_AS_NO_LONGER_NEEDED` (37), `REQUEST_MODEL` (36), `DRAW_MARKER` (33), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (33), `PLAY_SOUND_FRONTEND` (32), `DELETE_VEHICLE` (32), `DRAW_POLY` (32), `DRAW_LINE` (32), `FREEZE_ENTITY_POSITION` (30)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x36 · `0.5f` x29 · `0.75f` x25 · `0.3f` x11 · `0.1f` x10 · `0.25f` x10 · `0.2f` x8 · `1.25f` x4 · `0.35f` x4 · `0.00078125f` x4 · `-0.24f` x4 · `0.24f` x4 · `0.02f` x3 · `-0.05f` x3 · `925.04f` x1 · `46.48f` x1 · `80.096f` x1 · `1.0019f` x1 · `1552.523f` x1 · `-5461.145f` x1 · `-6599.993f` x1 · `3499.965f` x1 · `0.165f` x1 · `0.225f` x1

## Other strings

Literals whose consuming native was not classified:

`FMMC_SEL_NO`, `FMMC_SEL_YES`, `FMMC_SEL_OFF`, `SC_AYS`, `FMMC_SEL_ON`, `FMMC_SEL_DEF`, `FMMC_SS_TT_1`, `FMMC_SS_TT_0`, `FMMC_AB_13`, `FMMC_AB_15`, `FMMC_B_3`, `SCOBJ_RPLC`, `FMMC_B_5`, `MC_H_PRP_ADV`, `SC_CONF_CAW`, `SC_H_VSPP`, `SC_ADV_CW_H`, `FMMC_INT_H_REQ`, `FMMC_IN_FMFTAG`, `FMMC_KEYC_P`, `cs1_02_cf_offmission`, `chemgrill_grp1`, `FMMC_AB_05`

---

Source: `decompiled_scripts/fm_survival_creator.c`
