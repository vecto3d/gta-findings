# fm_race_creator.c

Creators script. 1 developer state labels recovered; 24 anim dicts; 200 models; 28 scaleforms.

| | |
|---|---|
| Category | Creators |
| Total lines | 926,681 |
| Functions | 16,255 (2,968 unique, 13,287 shared) |
| Unique lines | 180,086 (19.4% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`Arena is loading...`

## Assets

**Animation dictionaries** (24) - `skydive@freefall`, `mini@strip_club@throwout_d@`, `anim@veh@skydive@parachute@chute`, `amb@world_human_cheering@male_e`, `anim@scripted@races@ig1_street_race@female@`, `anim@mp_corona_idles@female_a@idle_c`, `ANIM_GROUP_MOVE_BALLISTIC`, `MOVE_STRAFE_BALLISTIC`, `anim@mp_player_intincarslow_clapstd@rps@`, `amb@world_human_cheering@female_c`, `amb@world_human_cheering@female_d`, `amb@world_human_cheering@male_a`, `amb@world_human_cheering@male_d`, `amb@world_human_cop_idles@male@idle_a`, `amb@world_human_window_shop@male@idle_a`, `amb@world_human_stand_impatient@male@no_sign@idle_a`, `random@street_race`, `amb@code_human_cross_road@male@idle_a`, `anim@amb@code_human_patrol@male@1h@idle_a`, `anim@mp_corona_idles@male_d@idle_a`, `amb@code_human_cross_road@female@idle_a`, `mp_corona_idles@female_a@idle_a`, `anim@amb@facility@hangerdoors@base@enter_exit@male@`, `anim@amb@facility@hangerdoors@base@enter_exit@female@`

**Animations** (7) - `exit`, `throwout_d_bouncer_a`, `throwout_d_bouncer_b`, `throwout_d_victim`, `intro`, `loop`, `control_operation`

**Models and props** (200) - `prop_ld_test_01`, `prop_cs_dildo_01`, `v_res_d_dildo_b`, `s_m_y_blackops_01`, `prop_mp_placement_sm`, `prop_mp_placement_lrg`, `prop_flare_01`, `s_m_y_cop_01`, `prop_mp_max_out_sm`, `prop_mp_cant_place_sm`, `gr_prop_gr_bunkeddoor_col`, `prop_roller_car_02`, `prop_ex_swap`, `prop_ex_b_time`, `prop_ex_random`, `prop_jetski_ramp_01`, `ba_prop_battle_tube_fn_01`, `ba_prop_battle_tube_fn_02`, `ba_prop_battle_tube_fn_03`, `ba_prop_battle_tube_fn_04`, `ba_prop_battle_tube_fn_05`, `xs_prop_arena_oil_jack_01a`, `xs_prop_arena_oil_jack_02a`, `prop_mp_max_out_lrg`, `prop_mp_cant_place_lrg`, `SET_SOFT_KEYS`, `ba_prop_battle_track_exshort`, `ba_prop_battle_track_short`, `prop_ic_boost`, `prop_ic_rock`, `prop_ic_ghost`, `prop_hx_arm`, `prop_hx_deadl`, `prop_ic_accel`, `prop_ex_swap_p`, `prop_ex_b_time_p`, `prop_ic_deton`, `prop_ic_bomb`, `prop_ic_hop`, `prop_ic_repair`, `prop_ex_random_p`, `prop_hx_special_vehicle`, `prop_hx_special_ruiner`, `prop_hx_special_buggy`, `prop_choc_pq`, `prop_choc_ego`, `prop_ecola_can`, `prop_ld_can_01b`, `prop_amb_beer_bottle`, `prop_cs_ciggy_01`, `bkr_prop_coke_boxeddoll`, `v_med_cor_emblmtable`, `a_m_y_genstreet_28_lod`, `prop_roadcone02a`, `s_f_y_cop_01`, `s_m_y_swat_01`, `s_m_m_fiboffice_01`, `s_m_y_sheriff_01`, `s_f_y_sheriff_01`, `s_m_y_ranger_01` ...

**Audio banks** (12) - `SNOW_FOOTSTEPS`, `DLC_STUNT/STUNT_RACE_01`, `DLC_STUNT/STUNT_RACE_02`, `DLC_STUNT/STUNT_RACE_03`, `DLC_24-2/DLC_24-2_LUNAR_RACE_SFX`, `DLC_AIRRACES/AIR_RACE_01`, `DLC_AIRRACES/AIR_RACE_02`, `DLC_23_2/DLC_23_2_Drift_Race`, `DLC_VINEWOOD/DLC_VW_HIDDEN_COLLECTIBLES`, `DLC_23_2/DLC_23_2_Drag_Race`, `HUD_321_GO`, `MP_RACES_SLIPSTREAM`

**Sounds** (105) - `ERROR`, `DLC_23_2_Drift_Sounds`, `DLC_23_2_Drag_Race_Sounds`, `DLC_Air_Race_Sounds_Player`, `HUD_MINI_GAME_SOUNDSET`, `HUD_FRONTEND_MP_COLLECTABLE_SOUNDS`, `CHECKPOINT_PERFECT`, `DELETE`, `Boss_Message_Orange`, `movie_prop`, `DLC_SUM20_HIDDEN_COLLECTIBLES`, `DLC_sum20_Open_Wheel_Racing_Sounds`, `DLC_23_2_Drag_Race_Mixscenes_General_Scene`, `NAV_UP_DOWN`, `DLC_AR_Beast_Soundset`, `dlc_xm_facility_entry_exit_sounds`, `EDIT`, `GTAO_Boss_Goons_FM_Soundset`, `DLC_23_2_Drag_Race_Mixscenes_Perfect_Shift_Scene`, `DLC_23_2_Drag_Race_Mixscenes_Nitrous_Boost_Scene`, `Score_Mulitply_Amount`, `BACK`, `Intensity`, `Vehicle_Transform`, `Mission_Pass_Notify`, `DLC_HEISTS_GENERAL_FRONTEND_SOUNDS`, `GTAO_Biker_FM_Soundset`, `DLC_IE_Vip_Stockpile_Sounds`, `dlc_vw_hidden_collectible_sounds`, `health_lost`, `DLC_23_2_Drag_Race_Mixscenes_Intro_mixscene`, `PLACE_CHECKPOINT`, `YES`, `SELECT`, `Score_Tick_Loop`, `Vehicle_Warp`, `Beast_Sprint_Loop`, `Hang_Up`, `DLC_Stunt_Race_Alarms_Soundset`, `Text_Arrive_Tone`, `Goon_Paid_Large`, `Menu_Accept`, `Phone_SoundSet_Default`, `Friend_Deliver`, `Enemy_Deliver`, `Deliver_Pick_Up`, `Dropped`, `Friend_Pick_Up`, `Enemy_Pick_Up`, `Crate_Pickup_Remote`, `Crate_Destroy_Remote`, `Pickup_Standard`, `GTAO_Biker_Modes_Soundset`, `playing_card`, `tyre_health_warning`, `tyre_burst`, `Pit_Stop_Loop`, `DLC_H3_Circuit_Racing_Sounds`, `Orientation_Success`, `Orientation_Fail` ...

**Scaleform movies** (28) - `STRING`, `SET_MESSAGE`, `DRAG_RACE`, `ADD_INTRO_TO_WALL`, `BM_POS`, `SET_SCREEN_POSITION`, `SET_CHECKPOINT_TEXT`, `FMMC_NO`, `OPEN_WHEEL_HEALTH_INDICATOR`, `BM_LAP_STR`, `AGR_LAPS`, `BM_WAVE_COMP`, `BM_PPLAY_TEAM`, `BM_PPLAY_TUN`, `BM_PPLAY_NAME`, `NUMBER`, `SET_COUNTDOWN_LIGHTS`, `SET_GEAR`, `SET_SPEED`, `SET_SPEED_UNITS`, `SET_METER_VALUE`, `SET_OUTER_GOAL`, `SET_INNER_GOAL`, `SET_IS_DRIFT_RACE`, `FLASH_OUTER_GOAL`, `FLASH_INNER_GOAL`, `SET_WHEEL_DAMAGE`, `SET_PART_TO_DESTROYED`

**Particle effects** (29) - `scr_sv_drag`, `scr_sv_drift`, `scr_as_trans`, `scr_sv_drag_burnout`, `buildup`, `scr_sum_ow`, `scr_indep_fireworks`, `scr_lowrider`, `core_snow`, `veh_xs_vehicle_mods`, `scr_as_trans_smoke`, `wheel_fric_hard`, `scr_sv_drag_wheel_fric_smoke`, `wheel_spin_snow`, `wheel_fric_grass`, `scr_sv_drag_wheel_fric_sand`, `wheel_fric_sand`, `scr_sr_adversary`, `ent_dst_gen_cardboard`, `scr_hr_lny_races`, `scr_sv_drift_cc_persist`, `scr_sum_ow_race_repair_smoke`, `scr_sr_dst_cardboard`, `scr_sv_drift_cc_trigger`, `scr_xs_pits`, `exp_grd_tankshell`, `scr_xs_props`, `ent_amb_fbi_fire_lg`, `scr_mp_creator`

**Texture dicts** (6) - `CommonMenu`, `MPMissMarkers128`, `MPMissMarkers256`, `BettingBox_Left`, `BettingBox_Centre`, `BettingBox_Right`

**Text labels** (51) - `STRING`, `NUMBER`, `NULL`, `PLYKICKED`, `BLANKALPHA`, `$`, `- $`, `WSBS`, `SKYDIVE_BAG_TICK`, `KITTIC_UNLOCK`, `SKYDIVE_CAN_TICK`, `INVALID`, `OFF`, `HIGROLLUNL`, `ESMINDOLLA`, `ESDOLLA`, `FMMC`, `SSLDID`, `BGDISMISSED`, `WEAPPICK2`, `STRTNM1`, `COPTIMEROFF`, `COPTIMERON`, `CROOKTIMEROFF`, `CROOKTIMERON`, `GBGOONJOINEDC`, `CLOTHES_UNLOCK`, `TICK_LEFT`, `PERCENTAGE`, `FO_NUM`, `FO_TWO_NUM`, `FO_TWO_KM`, `FO_TWO_MI`, `AHD_DIST`, `321GO`, `ERROR_CHECKVEHICLENAME`, `ERROR_CHECKPROFANITY`, `RH_Accel`, `RH_Brake`, `RH_Handle_Air`, `RH_Handle`, `HIDDEN`, `FROZEN`, `INVINCIBLE`, `BAD_SPORT_PERAIR`, `BAD_SPORT_PERVEH`, `BLIP_DEATH`, `FMMCCRTV`, `ERROR_CHECKYACHTNAME`, `CLEAR`, `RH_Speed`

**Decorators** (18) - `MPBitset`, `Player_Vehicle`, `Previous_Owner`, `Player_Field_Duster`, `Player_Bounty_Transporter`, `PV_Slot`, `Veh_Modded_By_Player`, `Player_Avenger`, `PYV_WarpFrom`, `RandomID`, `VehicleList`, `Player_Hacker_Truck`, `Player_Truck`, `Previous_Boss`, `Not_Allow_As_Saved_Veh`, `Player_Acid_Lab`, `Player_Thruster`, `EnableVehLuxeActs`

**Timecycle modifiers** (7) - `Lunar_NewYear_Spectacle`, `Lunar_NewYear_LapOfHonor`, `Lunar_NewYear_TheBigBash`, `DragRaceGearPerf`, `DragRaceGearGood`, `DragRaceGearBad`, `DLC_mp2023_02_Race_AO`

**Interiors and entity sets** (4) - `tr_tuner_car_meet`, `entity_set_test_lights`, `xm_x17dlc_int_02`, `Int02_base_hanger`

**Vehicle mods** (16) - `issi2`, `annihilator`, `hydra`, `tula`, `voltic`, `seashark`, `avenger`, `voltic2`, `oppressor`, `oppressor2`, `toreador`, `vigilante`, `stinger`, `mule`, `dune`, `deathbike2`

**Stats** (27) - `sp0_special_ability_unlocked`, `sp1_special_ability_unlocked`, `sp2_special_ability_unlocked`, `sp0_dist_running`, `sp1_dist_running`, `sp2_dist_running`, `sp0_unarmed_hits`, `sp1_unarmed_hits`, `sp2_unarmed_hits`, `sp0_number_near_miss`, `sp1_number_near_miss`, `sp2_number_near_miss`, `sp0_plane_landings`, `sp1_plane_landings`, `sp2_plane_landings`, `sp0_dist_walk_st`, `sp1_dist_walk_st`, `sp2_dist_walk_st`, `sp0_kills_stealth`, `sp1_kills_stealth`, `sp2_kills_stealth`, `sp0_hits_mission`, `sp0_hits_peds_vehicles`, `sp1_hits_mission`, `sp1_hits_peds_vehicles`, `sp2_hits_mission`, `sp2_hits_peds_vehicles`

**Scripts launched** (14) - `mg_race_to_point`, `am_mp_property_int`, `fm_capture_creator`, `main`, `freemode`, `GB_IE_DELIVERY_CUTSCENE`, `am_mp_smpl_interior_int`, `am_mp_drone`, `am_mp_car_meet_sandbox`, `appinternet`, `appemail`, `appmpemail`, `gb_ie_delivery_cutscene`, `fm_main_menu`

**Hashed names** (13) - `vw_prop_vw_colle_pogo`, `vw_prop_vw_colle_imporage`, `vw_prop_vw_colle_prbubble`, `vw_prop_vw_colle_rsrcomm`, `vw_prop_vw_colle_rsrgeneric`, `vw_prop_vw_colle_alien`, `EARN_REP_TYPE_CAR_MEET_VEHICLE_CLONE_DAILY`, `EARN_REP_TYPE_CAR_MEET_VEHICLE_CLONE_FIRST_TIME`, `fm_content_cerberus`, `vw_prop_vw_lux_card_01a`, `vw_prop_vw_colle_beast`, `vw_prop_vw_colle_sasquatch`, `fm_mission_creator`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (1747), `SET_BIT` (1274), `CLEAR_BIT` (946), `PLAYER_PED_ID` (843), `DOES_ENTITY_EXIST` (617), `GET_EVENT_DATA` (405), `DATADICT_GET_TYPE` (350), `DATADICT_GET_INT` (333), `TO_FLOAT` (314), `DATADICT_SET_INT` (310), `IS_STRING_NULL_OR_EMPTY` (283), `GET_ENTITY_MODEL` (282), `GET_ENTITY_COORDS` (252), `ROUND` (238), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (172), `GET_GAME_TIMER` (163), `ARE_STRINGS_EQUAL` (153), `GET_VEHICLE_PED_IS_IN` (143), `GET_BLIP_SPRITE` (137), `IS_PED_IN_ANY_VEHICLE` (134), `GET_HASH_KEY` (127), `GET_PLAYER_TEAM` (126), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (125), `END_TEXT_COMMAND_SCALEFORM_STRING` (125), `DOES_BLIP_EXIST` (122), `IS_ENTITY_DEAD` (120), `GET_PLAYER_NAME` (120), `PLAY_SOUND_FRONTEND` (117), `SET_ENTITY_COORDS` (105), `SET_PED_COMPONENT_VARIATION` (103)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x88 · `0.1f` x51 · `1.5f` x28 · `0.75f` x26 · `0.25f` x20 · `0.3f` x17 · `-0.5f` x14 · `0.2f` x10 · `0.6f` x10 · `1.32f` x7 · `0.85f` x6 · `0.02f` x6 · `0.9f` x5 · `1.25f` x5 · `2.5f` x4 · `17.4326f` x4 · `1.2f` x4 · `0.95f` x4 · `7.5f` x4 · `4.2f` x4 · `0.4f` x4 · `1.6f` x4 · `0.001388889f` x3 · `0.00078125f` x3

## Other strings

Literals whose consuming native was not classified:

`FMMC_SEL_NO`, `FMMC_SEL_YES`, `FMMC_SEL_OFF`, `deluxo`, `stromberg`, `blazer5`, `pogo_space_monkey`, `impotent_rage`, `princess_robot_bubblegum`, `space_ranger_commander`, `republican_space_ranger`, `ruiner2`, `thruster`, `CrossLine`, `FMMC_SEL_ON`, `fixter`, `oppressor2`, `toreador`, `submersible2`, `FMMC_AB_15`, `submersible`, `FMMC_ER_006`, `FMMC_RC_TG0`, `FMMC_DM_T12`, `oppressor`

---

Source: `decompiled_scripts/fm_race_creator.c`
