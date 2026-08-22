# public_mission_creator.c

Creators script. 104 anim dicts; 200 models; 19 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | Creators |
| Total lines | 504,206 |
| Functions | 8,076 (2,858 unique, 5,218 shared) |
| Unique lines | 119,193 (23.6% of file) |

## Assets

**Animation dictionaries** (104) - `move_m@drunk@VERYDRUNK_IDLES@`, `misssolomon_5@crowd_idles`, `amb@code_human_cower_stand@male@react_cowering`, `amb@world_human_maid_clean@idle_a`, `AMB@WORLD_HUMAN_MAID_CLEAN@IDLES_A`, `amb@world_human_cop_idles@male@idle_a`, `amb@world_human_stand_impatient@male@no_sign@idle_a`, `NIGHTCLUB@DANCE_MINIGAME@DANCE_SOLO@MALE@VAR_A`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_SOLO@MALE@VAR_A@`, `NIGHTCLUB@DANCE_MINIGAME@DANCE_SOLO@FEMALE@VAR_A`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_SOLO@FEMALE@VAR_A@`, `amb@world_human_stupor@male@idle_a`, `anim@scripted@ulp_missions@empty_crate@heeled@`, `amb@world_human_maid_clean@idle_b`, `AMB@WORLD_HUMAN_MAID_CLEAN@IDLES_b`, `amb@world_human_cop_idles@male@idle_b`, `anim@amb@world_human_valet@formal_left@idle_b@`, `amb@code_human_police_investigate@idle_b`, `missmartin1@pointing_sky1@idle_a`, `anim@mp_radio@high_life_apment`, `ANIM@SCRIPTED@HEIST@IG3_BUTTON_PRESS@MALE@`, `ANIM_HEIST@HS3F@IG12_CHANGE_CLOTHES@`, `anim@scripted@player@freemode@gen_grab@heeled@`, `anim@scripted@player@freemode@gen_grab@male@`, `anim@scripted@player@mission@tunf_conv_ig1_monyplate@heeled@`, `anim@scripted@player@mission@tunf_conv_ig1_monyplate@male@`, `anim@scripted@player@mission@trn_ig1_loot_v2@heeled@`, `anim@scripted@player@mission@trn_ig1_loot_v2@male@`, `anim@scripted@player@mission@trn_ig2_empty_v2@heeled@`, `anim@scripted@player@mission@trn_ig2_empty_v2@male@`, `ANIM@SCRIPTED@TYCOON@BT1@IG4_USB_HACK@HEELED@`, `ANIM@SCRIPTED@TYCOON@BT1@IG4_USB_HACK@MALE@`, `anim@scripted@player@mission@tunf_hack_keypad@heeled@`, `anim@scripted@player@mission@tunf_hack_keypad@male@`, `anim@scripted@pmc@IG1_GEN_HACK@heeled@`, `anim@scripted@pmc@IG1_GEN_HACK@male@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@CASH@HEELED@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@CASH@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@GOLD@HEELED@`, `ANIM@SCRIPTED@PLAYER@MISSION@TUN_TABLE_GRAB@GOLD@`, `anim@scripted@heist@ig15_safe_crack@male@`, `ANIM@SCRIPTED@CBR6@IG3_UNLOCK_OFFICE_DOOR@HEELED@`, `ANIM@SCRIPTED@CBR6@IG3_UNLOCK_OFFICE_DOOR@MALE@`, `ANIM@SCRIPTED@TYCOON@BT1@IG3_LCKP@HEELED@`, `ANIM@SCRIPTED@TYCOON@BT1@IG3_LCKP@MALE@`, `ANIM@SCRIPTED@TYCOON@BT1@IG3_LCKP_ALT@HEELED@`, `ANIM@SCRIPTED@TYCOON@BT1@IG3_LCKP_ALT@MALE@`, `anim@heists@humane_labs@finale@keycards_heels`, `anim@heists@humane_labs@finale@keycards`, `anim@GangOps@Facility@Servers@BodySearch@`, `ANIM@SCRIPTED@CHARLIE_MISSIONS@MISSION_6@IG1_BUTTON_PRESS@HEELED@`, `ANIM@SCRIPTED@CHARLIE_MISSIONS@MISSION_6@IG1_BUTTON_PRESS@MALE@`, `ANIM@SCRIPTED@ULP_MISSIONS@PAPERWORK@HEELED@`, `ANIM@SCRIPTED@ULP_MISSIONS@PAPERWORK@MALE@`, `anim@scripted@player@fix_club_ig1_hdd_remove@heeled@`, `anim@scripted@player@fix_club_ig1_hdd_remove@male@`, `anim@scripted@player@mission@tunf_bunk_ig2_hdd_nas@heeled@`, `anim@scripted@player@mission@tunf_bunk_ig2_hdd_nas@male@`, `anim@scripted@player@mission@tun_iaa_dig@heeled@`, `anim@scripted@player@mission@tun_iaa_dig@male@` ...

**Animations** (6) - `IDLE_B`, `IDLE_C`, `IDLE_D`, `IDLE_A`, `COWBOY_RIDING_HORSE`, `DRIVING`

**Models and props** (200) - `prop_ld_test_01`, `prop_mk_random`, `hei_prop_hei_keypad_01`, `ch_prop_fingerprint_scanner_01a`, `ch_prop_fingerprint_scanner_01b`, `ch_prop_fingerprint_scanner_01c`, `ch_prop_fingerprint_scanner_01d`, `ch_prop_fingerprint_scanner_01e`, `ch_prop_fingerprint_scanner_error_01b`, `s_m_m_movalien_01`, `u_m_y_rsranger_01`, `g_m_y_ballaorig_01`, `ig_orleans`, `u_m_m_yeti`, `ch_prop_ch_ld_bomb_01a`, `v_ilev_door_orange`, `s_m_y_blackops_01`, `s_m_y_marine_03`, `u_m_m_yulemonster`, `prop_mp_placement_sm`, `v_ilev_ph_door01`, `ch_prop_ch_cctv_cam_01a`, `v_ilev_rc_door2`, `prop_abat_slide`, `v_ilev_bl_shutter2`, `v_ilev_cf_officedoor`, `v_ilev_fb_door01`, `v_ilev_fb_door02`, `v_ilev_fb_doorshortl`, `v_ilev_fb_doorshortr`, `prop_gate_airport_01`, `u_m_y_juggernaut_01`, `u_m_y_juggernaut_02`, `s_f_y_cop_01`, `s_m_m_fibsec_01`, `s_m_y_swat_01`, `u_m_y_pogo_01`, `s_m_m_movspace_01`, `prop_const_fence02b`, `prop_mp_placement_lrg`, `v_ilev_ph_door002`, `v_ilev_fib_door1`, `v_ilev_roc_door4`, `v_ilev_abbmaindoor`, `v_ilev_bl_door_r`, `v_ilev_bl_doorsl_l`, `v_ilev_bl_doorsl_r`, `v_ilev_bl_doorel_l`, `v_ilev_bl_doorel_r`, `v_ilev_rc_door3_l`, `v_ilev_rc_door3_r`, `v_ilev_cor_darkdoor`, `v_ilev_lostdoor`, `gr_prop_gr_adv_case`, `prop_cs_server_drive`, `prop_cs_duffel_01`, `p_michael_backpack_s`, `sf_prop_sf_backpack_01a`, `prop_mp_cant_place_sm`, `v_ilev_gb_vauldr` ...

**Sounds** (41) - `ERROR`, `DELETE`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT_LOCATION`, `ADD_SPAWN_POINT`, `CONTINUE`, `continue`, `PLACE_VEHICLE`, `EDIT`, `Shard_Disappear`, `Reset_Win`, `Go_Kart_Death_Match_Soundset`, `Bike_Time_Trials_Soundset`, `SELECT`, `Resurrected`, `DLC_SR_RS_Player_Sounds`, `DLC_SR_RS_Team_Sounds`, `DLC_SR_RS_Enemy_Sounds`, `shard`, `dlc_vw_hidden_collectible_sounds`, `killer_down`, `dlc_ch_hidden_collectibles_sk_sounds`, `PowerupShard_Appear`, `Par_Beaten`, `Fail`, `MP_RANK_UP`, `NAV_UP_DOWN`, `NAV_LEFT_RIGHT`, `Blade_Appear`, `Metal_Detector_Unlocked_Shard`, `Tuner_Hidden_Collectibles_MD_Sounds`, `BACK`, `PLACE_ENEMY`, `Creator_Snap`, `DLC_Stunt_Race_Frontend_Sounds`, `HUD_Static_Loop`, `DLC_BTL_Drone_Sounds`, `GTAO_Biker_FM_Shard_Sounds`, `GTAO_Boss_Goons_FM_Shard_Sounds`, `PowerupShard_Disappear`, `GTAO_FM_Events_Soundset`

**Scaleform movies** (19) - `STRING`, `ADD_BACKGROUND_TO_WALL`, `ADD_INTRO_TO_WALL`, `BM_POS`, `SET_RANK_ICON_RGB`, `SET_MESSAGE`, `SET_COLOUR`, `SET_SCROLL_SPEED`, `BM_LAP_STR`, `AGR_LAPS`, `BM_WAVE_COMP`, `BM_PPLAY_TEAM`, `BM_PPLAY_TUN`, `BM_PPLAY_NAME`, `BLIMP_TEXT`, `camera_gallery`, `SHARD_ANIM_OUT`, `SHOW_MISSION_PASSED_MESSAGE`, `TRANSITION_UP`

**Particle effects** (1) - `scr_mp_creator`

**Texture dicts** (3) - `MPMissMarkers256`, `CommonMenu`, `MPMissMarkers128`

**Text labels** (40) - `NUMBER`, `STRING`, `ACTION`, `FMMC`, `$`, `- $`, `DEFAULT`, `MP_SPINLOADING`, `PUBC`, `NULL`, `SANCHEZ`, `SSLDID`, `INVALID`, `SURVIVAL`, `DEATHMATCH`, `ENTER`, `ERROR_CHECKPROFANITY`, `TTPH`, `PPRBS`, `ORMSR`, `ORMCR`, `CAIPL`, `CAIPLB`, `CAIN`, `CAIL`, `CAID`, `CAIM`, `WSBS`, `DMATCH`, `RACES`, `FMMC_DOWNLOAD`, `47RPB540`, `28AVY903`, `29FNS081`, `62QCH889`, `FMMCCRTV`, `PERCENTAGE`, `FO_TWO_NUM`, `MTPHPER_XPNO`, `ESDOLLA`

**Decorators** (2) - `MC_Prop`, `EnableVehLuxeActs`

**Interiors and entity sets** (10) - `bkr_biker_dlc_int_03`, `v_faceoffice`, `v_factory1`, `v_factory2`, `v_factory3`, `v_factory4`, `v_farmhouse`, `v_franklins`, `v_trevors`, `hei_dlc_apart_high2_new`

**Doors** (1) - `v_ilev_gtdoor02`

**Vehicle mods** (11) - `issi2`, `mule`, `annihilator`, `seashark`, `voltic`, `windsor`, `titan`, `cargobob`, `cargobob2`, `dune`, `stinger`

**Scripts launched** (3) - `main`, `fm_main_menu`, `creator`

**Hashed names** (1) - `hairOverlay`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_CREATE_ARRAY` (791), `SET_BIT` (685), `DATAARRAY_ADD_INT` (630), `CLEAR_BIT` (526), `DOES_ENTITY_EXIST` (449), `PLAYER_PED_ID` (215), `IS_STRING_NULL_OR_EMPTY` (205), `ARE_STRINGS_EQUAL` (197), `GET_ENTITY_MODEL` (196), `GET_ENTITY_COORDS` (184), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (137), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (124), `END_TEXT_COMMAND_SCALEFORM_STRING` (124), `DOES_BLIP_EXIST` (123), `PLAY_SOUND_FRONTEND` (110), `GET_GAME_TIMER` (110), `DELETE_OBJECT` (94), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (92), `REMOVE_BLIP` (90), `ENABLE_CONTROL_ACTION` (88), `TO_FLOAT` (82), `DATAARRAY_ADD_FLOAT` (78), `GET_HUD_COLOUR` (75), `SET_ENTITY_COORDS` (73), `DRAW_POLY` (72), `ROUND` (70), `COPY_SCRIPT_STRUCT` (68), `DRAW_LINE` (68), `PLAYER_ID` (67), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (60)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x58 · `0.75f` x32 · `1.5f` x27 · `0.1f` x23 · `0.25f` x16 · `0.2f` x10 · `0.05f` x9 · `0.9f` x8 · `0.3f` x7 · `0.02f` x7 · `0.4f` x6 · `1.25f` x6 · `2.5f` x6 · `0.8f` x5 · `0.95f` x4 · `1.2f` x4 · `-0.24f` x4 · `0.24f` x4 · `1.249f` x4 · `0.15f` x3 · `4.864f` x3 · `1.187f` x3 · `0.006f` x3 · `-8.75f` x3

## Other strings

Literals whose consuming native was not classified:

`FMMC_SEL_NO`, `FMMC_SEL_YES`, `PMC_SEL_YES`, `PMC_SEL_NO`, `PMC_SEL_OFF`, `FMMC_SEL_OFF`, `FMMC_SEL_MET`, `PMCD_PED_PSET`, `FMMC_SEL_DEF`, `FMMC_PERCENT`, `FMMC_SEL_NON`, `PMC_SEL_ON`, `FMMC_SEL_ON`, `mp_m_freemode_01`, `mp_f_freemode_01`, `lft`, `PMC_SEL_DBLED`, `PMCT_TYPE`, `idle`, `FMMC_SEL_SEC`, `PMC_SEL_ENBLE`, `PMCT_EPR_OO`, `PMCT_EPR`, `swcdf`, `PMCD_ENT_JMPT`, `type`

---

Source: `decompiled_scripts/public_mission_creator.c`
