# gb_delivery.c

Jobs script. 7 anim dicts; 56 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 447,755 |
| Functions | 7,981 (661 unique, 7,320 shared) |
| Unique lines | 62,803 (14.0% of file) |

## Assets

**Animation dictionaries** (7) - `anim@amb@facility@hanger_doors`, `anim@amb@waving@male`, `anim@amb@facility@hangerdoors@base@enter_exit@female@`, `anim@amb@facility@hangerdoors@base@enter_exit@male@`, `anim@apt_trans@garage`, `anim@scripted@player@fix_agy_ig5_handover@male@`, `ANIM@CASINO@ANIMATED_CAMS@`

**Animations** (6) - `map_objects`, `Dock_crane_SLD_load`, `Dock_crane_SLD_unload`, `anim@amb@waving@male`, `air_wave`, `control_operation`

**Models and props** (56) - `prop_v_hook_s`, `a_m_y_busicas_01`, `s_m_y_dealer_01`, `gr_prop_gr_rsply_crate04b`, `prop_mb_crate_01a`, `sm_prop_smug_crate_s_narc`, `bkr_prop_coke_doll_bigbox`, `bkr_prop_money_counter`, `prop_golf_ball`, `prop_gd_ch2_08`, `asbo`, `prop_lrggate_01c_r`, `prop_lrggate_01c_l`, `a_f_y_business_01`, `g_f_y_lost_01`, `a_m_y_hipster_01`, `a_m_y_stwhi_02`, `a_m_m_bevhills_02`, `g_m_m_korboss_01`, `a_m_y_ktown_02`, `a_m_m_eastsa_02`, `g_m_y_mexgoon_02`, `g_m_y_mexgoon_01`, `g_m_y_lost_02`, `p_dock_crane_sld_s`, `p_dock_crane_cabl_s`, `prop_container_ld_d`, `u_m_m_edtoh`, `vw_prop_vw_garagedoor_01a`, `xm_prop_auto_salvage_stromberg`, `g_m_m_casrn_01`, `g_m_y_strpunk_02`, `g_m_y_ballaorig_01`, `g_m_y_korlieut_01`, `a_f_m_bevhills_01`, `s_m_m_highsec_04`, `a_m_m_salton_02`, `a_m_m_salton_01`, `g_m_y_ballasout_01`, `g_m_y_lost_03`, `m23_1_prop_m31_emp_01a`, `ig_lildee`, `s_m_y_xmech_02`, `ch_prop_arcade_collect_01a`, `ch_prop_boring_machine_01b`, `sm_prop_smug_rsply_crate02a`, `a_f_m_genbiker_01`, `a_f_y_genhot_01`, `a_f_y_vinewood_04`, `a_m_m_genbiker_01`, `a_m_y_carclub_01`, `g_f_importexport_01`, `flatbed`, `p_parachute1_mp_dec`, `a_f_y_hipster_02`, `a_f_y_soucent_03`

**Audio banks** (1) - `DLC_CHRISTMAS2017/XM_FACILITY_ENTRY_EXIT`

**Sounds** (15) - `Garage_Door_Close`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `Door_Knock_Normal`, `dlc_btl_deliver_goods_sounds`, `DLC_H3_FM_Sewer_Tunnel_Drill_Delivery_Scene`, `dlc_xm_facility_enter_in_vehicle_exterior_scene`, `dlc_xm_facility_enter_on_foot_exterior_scene`, `dlc_xm_facility_entry_exit_sounds`, `DLC_SM_Precision_Delivery_Sounds`, `hangar_doors_limit`, `hangar_doors_loop`, `Air_Drop_Package`, `DLC_SM_Generic_Mission_Sounds`, `flatbed_delivery`, `flatbed_delivery_impact`

**Text labels** (2) - `NULL`, `LAM`

**Decorators** (6) - `FMDeliverableID`, `MPBitset`, `FMCVehicle`, `CSHVehicle`, `GBCVehicle`, `BBCarrier`

**Scripts launched** (2) - `am_mp_smpl_interior_int`, `am_mp_defunct_base`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (233), `PLAYER_PED_ID` (185), `DOES_ENTITY_EXIST` (169), `SET_BIT` (153), `GET_ENTITY_MODEL` (101), `SET_PED_COMPONENT_VARIATION` (68), `GET_ENTITY_COORDS` (52), `FREEZE_ENTITY_POSITION` (52), `IS_ENTITY_DEAD` (51), `SET_ENTITY_COLLISION` (46), `IS_PED_IN_ANY_VEHICLE` (43), `TO_FLOAT` (43), `GET_VEHICLE_PED_IS_IN` (34), `SET_ENTITY_COORDS_NO_OFFSET` (33), `SET_ENTITY_VISIBLE` (32), `SET_ENTITY_HEADING` (32), `GET_SHOP_PED_APPAREL_FORCED_COMPONENT_COUNT` (31), `GET_FORCED_COMPONENT` (31), `GET_NETWORK_TIME` (31), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (30), `IS_SCREEN_FADED_OUT` (26), `GET_PED_IN_VEHICLE_SEAT` (24), `SET_ENTITY_COORDS` (22), `VMAG` (22), `GET_ENTITY_HEADING` (21), `ATTACH_ENTITY_TO_ENTITY` (21), `SET_ENTITY_INVINCIBLE` (21), `REGISTER_ENTITY_FOR_CUTSCENE` (20), `SET_PED_CONFIG_FLAG` (19), `SET_MODEL_AS_NO_LONGER_NEEDED` (17)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x10 · `0.5f` x9 · `0.3f` x9 · `0.25f` x7 · `79.7545f` x6 · `1.6f` x6 · `711.6924f` x5 · `144.674f` x5 · `35.752f` x4 · `35.889f` x4 · `3.5f` x3 · `984.455f` x3 · `-2883.53f` x3 · `29.8977f` x3 · `7.5f` x3 · `0.2f` x3 · `-0.4106f` x3 · `-4.5f` x3 · `1.5f` x3 · `-0.098f` x2 · `0.003f` x2 · `998.971f` x2 · `-52.554f` x2 · `73.956f` x2

## Other strings

Literals whose consuming native was not classified:

`chassis_dummy`, `trailersmall2`, `GO_HELI_DELIV`, `h4_prop_h4_crates_full_01a`, `insurgent3`, `mp_m_freemode_01`, `avenger`, `Descent`, `Bounty_Female_Flats`, `Bounty_Female_Heels`, `mp_f_freemode_01`, `MP_1`, `sum_prop_ac_drinkglobe_01a`, `sum_prop_ac_sarcophagus_01a`, `sum_prop_ac_tigerrug_01a`, `h4_prop_h4_p_boat_01a`, `h4_prop_h4_box_delivery_01a`, `h4_prop_h4_box_delivery_01b`, `xm3_prop_xm3_bdl_meth_01a`, `xm3_prop_xm3_box_pspt_01a`, `xm3_prop_xm3_product_box_01`, `TD Veh Exit`, `thruster`, `Garage door`, `vest_shirt`, `open_collar`, `TUN_CUSTO1`, `Bounty_Male`, `tula`

---

Source: `decompiled_scripts/gb_delivery.c`
