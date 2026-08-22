# fm_content_tuner_robbery.c

MP freemode script. 23 anim dicts; 15 models; 1 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 556,081 |
| Functions | 12,407 (1,675 unique, 10,732 shared) |
| Unique lines | 44,770 (8.1% of file) |

## Assets

**Animation dictionaries** (23) - `anim@door_trans@hinge_l@`, `anim@apt_trans@garage`, `anim@apt_trans@buzzer`, `amb@world_human_hang_out_street@female_arms_crossed@enter`, `amb@world_human_hang_out_street@male_c@enter`, `anim@door_trans@hinge_r@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@mp_corona_idles@female_a@idle_c`, `anim@scripted@robbery@tun_prep_pris_ig1_handover@`, `anim_heist@hs4f@ig14_open_car_trunk@male@`, `anim_heist@hs4f@ig14_open_car_trunk@female@`, `anim@scripted@heist@ig9_control_tower@male@`, `anim@scripted@player@mission@tun_prep_plant_ig1@heeled@`, `anim@scripted@player@mission@tun_prep_plant_ig1@male@`, `mini@safe_cracking`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@heeled@`, `mini@strip_club@throwout_d@`, `amb@code_human_cross_road@male@idle_a`, `anim@amb@code_human_patrol@male@1h@idle_a`, `anim@mp_corona_idles@male_d@idle_a`, `amb@code_human_cross_road@female@idle_a`, `mp_corona_idles@female_a@idle_a`, `anim@scripted@robbery@tun_prep_uni_ig1_couple@`

**Animations** (4) - `DOOR_OPEN_SUCCEED_STAND_SAFE`, `throwout_d_bouncer_a`, `throwout_d_bouncer_b`, `throwout_d_victim`

**Models and props** (15) - `prop_map_door_01`, `prop_drug_package`, `v_16_ap_mid_pants5`, `v_16_ap_mid_pants4`, `s_m_y_casino_01`, `vw_prop_casino_wine_glass_01a`, `hei_prop_hei_paper_bag`, `prop_cs_ciggy_01`, `v_ilev_mm_doorw`, `prop_tv_flat_01`, `v_ilev_mp_mid_frontdoor`, `g_f_importexport_01`, `g_m_importexport_01`, `SET_REMAINING_PHOTOS`, `a_f_y_business_03`

**Audio banks** (5) - `SCRIPT/ALARM_KLAXON_03`, `SCRIPT/LIFTS`, `DLC_TUNER/DLC_Tuner_Prep_Inside_Man`, `DLC_HEI4/DLCHEI4_GENERIC_01`, `DLC_TUNER/DLC_Tuner_Generic`

**Sounds** (25) - `Signal_Jammers_Unlock_Trunk_Scene`, `Push`, `dlc_h4_Prep_FC_Sounds`, `TAIL_HELICOPTER_SCENE`, `GTAO_GUNFIRE_DUCKING_SCENE`, `GTAO_APT_DOOR_DOWNSTAIRS_GENERIC_SOUNDS`, `dlc_xm_facility_entry_exit_sounds`, `LIFT_NORMAL_SOUNDSET`, `Alarm_Tripped`, `Attach`, `Prep_Signal_Jammers_Sounds`, `Barge_Door_Glass`, `Collect_Pass`, `Prep_Elevator_Pass_Sounds`, `Barge_Door_Metal`, `Barge_Door`, `GTAO_APT_DOOR_DOWNSTAIRS_WOOD_SOUNDS`, `dlc_xm_facility_enter_in_vehicle_interior_scene`, `dlc_xm_facility_enter_on_foot_interior_scene`, `hangar_doors_close`, `elevator_descend_loop`, `Door_Close`, `Tone`, `Camera_Shoot`, `Phone_Soundset_Franklin`

**Scaleform movies** (1) - `camera_gallery`

**Particle effects** (2) - `scr_tn_pr`, `scr_tn_pr_cig_smoke`

**Texture dicts** (2) - `helicopterhud`, `hud_outline`

**Text labels** (30) - `TNRPAUD`, `25NSH619`, `65PIU143`, `23MDW274`, `NULL`, `TNHEAUD`, `LI1DEE`, `44BRB073`, `28QNA156`, `25GXP027`, `06YUZ637`, `00NOU624`, `88RNP540`, `21RQL186`, `88NGJ146`, `03YBC659`, `05SBF291`, `68KWK927`, `06NZQ185`, `84TFX949`, `86CVG072`, `15HBW365`, `46PAC408`, `40DSE854`, `KP1`, `40WJK483`, `28UNJ774`, `41PPV138`, `69HDR495`, `65VEE035`

**Decorators** (1) - `RandomID`

**Interiors and entity sets** (2) - `xm_x17dlc_int_02`, `Int02_base_hanger`

**Vehicle mods** (9) - `mamba`, `bodhi2`, `chino`, `voltic`, `buccaneer`, `buccaneer2`, `chino2`, `faction`, `faction2`

**Hashed names** (2) - `V_FakeBoatPO1SH2A`, `v_fakeboatpo1sh1`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (121), `PLAYER_ID` (116), `DATADICT_GET_ARRAY` (115), `SET_BIT` (96), `GET_RANDOM_INT_IN_RANGE` (93), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (71), `NET_TO_ENT` (62), `DOES_ENTITY_EXIST` (59), `GET_ENTITY_COORDS` (43), `VDIST` (30), `IS_PED_IN_ANY_VEHICLE` (29), `CLEAR_BIT` (29), `PLAYER_PED_ID` (28), `GET_PLAYER_WANTED_LEVEL` (26), `NET_TO_PED` (25), `NET_TO_VEH` (25), `DISABLE_CONTROL_ACTION` (23), `GET_ENTITY_MODEL` (23), `SET_ENTITY_VISIBLE` (22), `VMAG` (20), `SET_PED_COMBAT_ATTRIBUTES` (19), `VDIST2` (18), `NET_TO_OBJ` (17), `GET_RANDOM_FLOAT_IN_RANGE` (17), `DOES_BLIP_EXIST` (16), `GET_SYNCHRONIZED_SCENE_PHASE` (16), `REQUEST_SCRIPT_AUDIO_BANK` (15), `IS_ENTITY_DEAD` (15), `FREEZE_ENTITY_POSITION` (15), `TO_FLOAT` (15)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x14 · `0.2f` x14 · `0.3f` x6 · `0.6f` x4 · `0.1f` x4 · `-0.2947f` x4 · `33.2472f` x4 · `0.15f` x3 · `-3.5f` x3 · `0.8f` x3 · `0.99f` x3 · `-2.5f` x2 · `-1104.657f` x2 · `-1638.481f` x2 · `4.675f` x2 · `0.5125f` x2 · `0.03f` x2 · `-0.5f` x2 · `0.274f` x2 · `350.583f` x2 · `-994.424f` x2 · `-100.171f` x2 · `350.369f` x2 · `-997.683f` x2

## Other strings

Literals whose consuming native was not classified:

`enter`, `GTAO_SCRIPT_DOORS_SOUNDS`, `TNRP_GN_5A`, `TUN_SESSANTA`, `walk_cam_left`, `walk_player1`, `GTAO_Script_Doors_Faded_Screen_Sounds`, `gar_open_1_left`, `TUNER_DELIVERING_START`, `pos`, `TUNER_SUSPENSE`, `walk_cam_right`, `buzz_short`, `DOOR_BUZZ_ONESHOT_MASTER`, `TUNER_MED_INTENSITY`, `GTAO_APT_DOOR_DOWNSTAIRS_GLASS_SOUNDS`, `Garage_Door_Close`, `num`, `polmav`, `TUNER_GUNFIGHT`, `head`, `FMCOT_GOTO`, `TUNER_DELIVERING`, `GENERIC_DOOR_PUSH`, `GENERIC_DOOR_LIMIT`, `int`, `typ`, `ibs`, `ROB_ENTER_THE`

---

Source: `decompiled_scripts/fm_content_tuner_robbery.c`
