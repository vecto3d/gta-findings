# fm_deathmatch_creator.c

Creators script. 1 developer state labels recovered; 1 anim dicts; 63 models; 10 scaleforms.

| | |
|---|---|
| Category | Creators |
| Total lines | 568,286 |
| Functions | 7,549 (696 unique, 6,853 shared) |
| Unique lines | 56,661 (10.0% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`Arena is loading...`

## Assets

**Animation dictionaries** (1) - `anim@mp_snowball`

**Animations** (2) - `anim@mp_snowball`, `pickup_snowball`

**Models and props** (63) - `prop_mp_placement_sm`, `prop_mp_placement_lrg`, `prop_mp_cant_place_sm`, `prop_mp_max_out_sm`, `prop_mp_max_out_lrg`, `prop_mp_cant_place_lrg`, `prop_flare_01`, `prop_const_fence02b`, `v_med_cor_emblmtable`, `prop_cs_dildo_01`, `v_res_d_dildo_b`, `ninef2`, `prop_ld_int_safe_01`, `p_v_43_safe_s`, `g_m_y_lost_02`, `g_m_y_mexgoon_02`, `g_m_y_ballaorig_01`, `g_m_y_korean_01`, `prop_armour_pickup`, `prop_ld_health_pack`, `p_parachute_s_shop`, `prop_ic_rock`, `prop_ic_boost`, `prop_ic_ghost`, `prop_hx_arm`, `prop_hx_deadl`, `prop_ic_accel`, `prop_ex_swap`, `prop_ex_b_time`, `prop_ic_deton`, `prop_ic_bomb`, `prop_ic_hop`, `prop_ic_repair`, `prop_ex_random`, `prop_hx_special_vehicle`, `prop_hx_special_ruiner`, `prop_hx_special_buggy`, `prop_container_ld_pu`, `prop_news_disp_02d`, `prop_vend_snak_01`, `prop_vend_water_01`, `prop_train_ticket_02`, `imp_prop_impexp_boxpile_01`, `imp_prop_impexp_boxpile_02`, `ba_prop_battle_track_exshort`, `ba_prop_battle_track_short`, `ba_prop_battle_tube_fn_01`, `ba_prop_battle_tube_fn_02`, `ba_prop_battle_tube_fn_03`, `ba_prop_battle_tube_fn_04`, `ba_prop_battle_tube_fn_05`, `prop_security_case_01`, `p_attache_case_01_s`, `prop_gun_case_01`, `prop_money_bag_01`, `prop_cs_duffel_01`, `hei_prop_hei_drug_pack_01a`, `bkr_prop_weed_bigbag_01a`, `bkr_prop_meth_smallbag_01a`, `bkr_prop_coke_boxeddoll` ...

**Audio banks** (2) - `SNOW_FOOTSTEPS`, `DLC_VINEWOOD/KOTH`

**Sounds** (30) - `ERROR`, `DLC_AW_Machine_Gun_Ammo_Counter_Sounds`, `NAV_UP_DOWN`, `DELETE`, `Recharging_Loop`, `SELECT`, `Fire_Powerup_Amped`, `Go_Kart_Death_Match_Soundset`, `Fire_Loop`, `DLC_IE_VV_Gun_Player_Sounds`, `Out_Of_Ammo`, `Empty_Fire_Fail`, `Recharged`, `Beast_Attack`, `DLC_AR_Beast_Soundset`, `Weapon_Force_Change_Smoke`, `Deathmatch_Sounds`, `Out_of_Bounds_Explode`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Time`, `BACK`, `Zone_Held`, `dlc_vw_koth_Sounds`, `DLC_AW_Arena_Traps_Turntable_Sounds`, `DLC_AW_Arena_Traps_Rams_Sounds`, `dlc_aw_arena_fire_pit_taking_damage_scene`, `EDIT`, `PLACE_VEHICLE`, `PLACE_OBJECT`, `ADD_SPAWN_POINT`

**Scaleform movies** (10) - `SET_DATA_SLOT`, `DISPLAY_VIEW`, `SET_TITLE`, `SHARD_ANIM_OUT`, `MIDSIZED_MESSAGE`, `SHOW_COND_SHARD_MESSAGE`, `FMMC_RANDDONE`, `FMMC_RANDFAIL`, `FMMC_RANDRES`, `MP_MISSION_DETAILS_CARD`

**Particle effects** (14) - `scr_ie_vv`, `scr_bike_adversary`, `core_snow`, `scr_ie_vv_muzzle_flash`, `scr_as_trans`, `scr_xt_trip`, `scr_xs_pits`, `scr_xs_props`, `ent_amb_fbi_fire_lg`, `exp_grd_tankshell`, `scr_adversary_gunsmith_weap_change`, `exp_xs_mine_slick`, `scr_tn_exp_mine_slick_nodecal`, `scr_mp_creator`

**Texture dicts** (2) - `MPMissMarkers128`, `MPMissMarkers256`

**Text labels** (16) - `NUMBER`, `STRING`, `XMAS`, `NULL`, `SSLDID`, `OFF`, `SANCHEZ`, `PM_DAMAGE`, `PM_FIRERATE`, `PM_ACCURACY`, `PM_RANGE`, `HIDDEN`, `FROZEN`, `INVINCIBLE`, `CLEAR`, `FMMCCRTV`

**Decorators** (3) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `EnableVehLuxeActs`

**Vehicle mods** (12) - `mule`, `mamba`, `windsor`, `bodhi2`, `chino`, `voltic`, `buccaneer`, `buccaneer2`, `chino2`, `faction`, `faction2`, `dune`

**Scripts launched** (5) - `main`, `fm_deathmatch_controler`, `FM_Deathmatch_Controler`, `freemode`, `fm_main_menu`

**Hashed names** (3) - `fm_mission_creator`, `CreateObject`, `Interrupt`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (455), `PLAYER_PED_ID` (371), `CLEAR_BIT` (303), `DOES_ENTITY_EXIST` (300), `ARE_STRINGS_EQUAL` (248), `TO_FLOAT` (148), `GET_GAME_TIMER` (119), `GET_ENTITY_MODEL` (103), `DOES_BLIP_EXIST` (97), `GET_ENTITY_COORDS` (96), `PLAYER_ID` (85), `IS_CONTROL_JUST_PRESSED` (74), `REMOVE_BLIP` (72), `DELETE_OBJECT` (65), `REQUEST_MODEL` (64), `ROUND` (61), `HAS_MODEL_LOADED` (53), `DATADICT_SET_INT` (52), `SET_MODEL_AS_NO_LONGER_NEEDED` (48), `IS_CONTROL_PRESSED` (47), `SET_ENTITY_COORDS` (44), `PLAY_SOUND_FRONTEND` (42), `DRAW_MARKER` (41), `FREEZE_ENTITY_POSITION` (40), `SET_PED_COMBAT_ATTRIBUTES` (40), `IS_PED_INJURED` (38), `GET_FILENAME_FOR_AUDIO_CONVERSATION` (38), `IS_HELP_MESSAGE_BEING_DISPLAYED` (36), `DISABLE_CONTROL_ACTION` (35), `GET_HUD_COLOUR` (34)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x28 · `0.75f` x25 · `1.5f` x12 · `0.3f` x12 · `0.1f` x12 · `0.25f` x10 · `0.6f` x6 · `0.02f` x6 · `0.2f` x6 · `0.05f` x5 · `1.32f` x4 · `1.25f` x4 · `0.00078125f` x4 · `-0.24f` x4 · `0.24f` x4 · `-0.05f` x3 · `-0.0775f` x3 · `0.7f` x2 · `0.001f` x2 · `2.5f` x2 · `0.35f` x2 · `1552.523f` x1 · `-5461.145f` x1 · `-6599.993f` x1

## Other strings

Literals whose consuming native was not classified:

`FMMC_SEL_NO`, `FMMC_SEL_YES`, `WCD_VAR_DESC`, `FMMC_SEL_OFF`, `FMMC_DM_T38`, `FMMC_DM_T50`, `FMMC_DM_T12`, `FMMC_SEL_ON`, `FMMC_SEL_DEF`, `FMMC_ER_006`, `FMMC_SS_TT_1`, `FMMC_SS_TT_0`, `FMMC_AB_13`, `FMMC_AB_15`, `FMMC_B_5`, `FMMC_B_3`, `FMMCNO_CLOUD`, `FMMC_AB_05`, `stromberg`, `MC_H_PRP_ADV`, `avenger3`, `thruster`, `vigero2`

---

Source: `decompiled_scripts/fm_deathmatch_creator.c`
