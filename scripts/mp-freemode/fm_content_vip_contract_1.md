# fm_content_vip_contract_1.c

MP freemode script. 13 anim dicts; 124 models; 3 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 543,494 |
| Functions | 11,995 (1,168 unique, 10,827 shared) |
| Unique lines | 30,228 (5.6% of file) |

## Assets

**Animation dictionaries** (13) - `anim@door_trans@hinge_l@`, `anim@apt_trans@garage`, `anim@amb@warehouse@laptop@`, `amb@world_human_janitor@male@idle_a`, `anim@scripted@player@fix_club_ig1_hdd_remove@heeled@`, `anim@scripted@player@fix_club_ig1_hdd_remove@male@`, `anim@heists@keypad@`, `anim@scripted@player@freemode@tun_prep_ig3_grab_high@male@`, `anim@GangOps@Facility@Servers@BodySearch@`, `anim@gangops@morgue@office@laptop@`, `anim@scripted@player@mission@tun_bunk_ig1_hdd_server@male@`, `move_m@brave`, `random@arrests`

**Models and props** (124) - `v_ilev_fib_door1`, `sf_prop_ap_port_text`, `sf_prop_ap_starb_text`, `sf_prop_ap_stern_text`, `prop_secdoor_01`, `set_crane_tint`, `set_lighting_tint_props`, `set_modarea`, `set_tint_shell`, `prop_drug_package`, `prop_tool_broom`, `prop_monitor_01b`, `prop_cs_keyboard_01`, `v_corp_offchair`, `set_bedroom_blinds_open`, `set_bedroom_clutter`, `set_bedroom_modern`, `set_bedroom_tint`, `set_floor_1`, `set_floor_decal_7`, `set_lighting_hangar_a`, `set_lighting_wall_neutral`, `set_lighting_wall_tint05`, `set_office_modern`, `set_pent_arcade_modern`, `set_pent_bar_party_1`, `set_pent_bar_party_after`, `set_pent_clutter_01`, `set_pent_clutter_02`, `set_pent_clutter_03`, `set_pent_dealer`, `set_pent_media_bar_open`, `Set_Pent_Pattern_03`, `set_pent_spa_bar_open`, `set_pent_tint_shell`, `set_plan_setup`, `set_int_mod2_b_tint`, `set_int_mod2_b1`, `set_car_lift_01_up`, `set_car_lift_02_up`, `set_mechanic_upgrade`, `set_safe_upgrade`, `set_tint_b`, `prop_skip_02a`, `prop_laptop_01a`, `ba_prop_door_club_glam_generic`, `ba_prop_door_elevator_1l`, `ba_prop_door_elevator_1r`, `ba_prop_door_club_glass`, `prop_lrggate_02_ld`, `hei_prop_hst_usb_drive`, `set_floor_2`, `set_floor_decal_9`, `set_lighting_hangar_c`, `set_lighting_wall_tint09`, `set_office_traditional`, `set_up`, `v_fib03_door_light`, `v_fib03_set_ah3a`, `set_plan_garage` ...

**Audio banks** (1) - `DLC_TUNER/DLC_Tuner_Generic`

**Sounds** (16) - `GTAO_Script_Doors_Faded_Screen_Sounds`, `DLC_Ba_NightClub_NoFlies_Scene`, `Barge_Door_Metal`, `DLC_Security_Door_Barge_Sounds`, `Metal_Door_Push`, `GTAO_Script_Doors_Sounds`, `Garage_Door_Open`, `Garage_Door_Close`, `DLC_Security_Investigations_Setup_Sounds`, `Air_Defences_Disabled`, `DLC_Security_Investigation_The_Yacht_Sounds`, `Upload_Complete`, `DLC_Security_Investigations_The_Limo_Sounds`, `Alarm_Tripped`, `Software_Installing_Loop`, `Software_Installing_Success`

**Speech contexts** (1) - `A_M_M_SOUCENT_01_R2PVG`

**Scaleform movies** (3) - `SET_YACHT_NAME`, `YACHT_NAME`, `YACHT_NAME_STERN`

**Text labels** (18) - `FXFRAUD`, `FXIMAUD`, `63DYR448`, `APAIR`, `FXDL2AU`, `YACHTCAPTAIN`, ` L1T1G8 `, `87KBG840`, `84FCT218`, `87PMM977`, `NULL`, `ACTION`, `68TBS953`, `FXFAAUD`, `88ELC593`, `41XZE016`, `FXBAAUD`, `1875`

**Timecycle modifiers** (1) - `mp_battle_int01_dancefloor_OFF`

**Interiors and entity sets** (45) - `entity_set_tint_options`, `set_tint_shell`, `set_crane_tint`, `set_modarea`, `set_lighting_tint_props`, `set_car_lift_01_up`, `set_car_lift_02_up`, `set_mechanic_upgrade`, `set_safe_upgrade`, `set_tint_b`, `apa_mpapa_yacht`, `V_FIB03_atr_hall`, `set_floor_1`, `set_bedroom_tint`, `set_floor_decal_7`, `set_floor_2`, `set_floor_decal_9`, `set_pent_arcade_modern`, `set_pent_bar_party_1`, `set_pent_bar_party_after`, `set_pent_clutter_01`, `set_pent_clutter_02`, `set_pent_clutter_03`, `set_pent_dealer`, `set_pent_media_bar_open`, `Set_Pent_Pattern_03`, `set_pent_spa_bar_open`, `set_pent_tint_shell`, `decorative_02`, `furnishings_02`, `lower_walls_default`, `mod_booth`, `mural_09`, `no_gun_locker`, `walls_01`, `entity_set_style_5`, `set_int_mod_shell_def`, `set_mod1_style_01`, `set_int_mod_booth_combo`, `set_office_standard`, `int_03_ba_bikemod`, `int_03_ba_design_02`, `int_03_ba_drone`, `int_03_ba_light_rig9`, `int_03_ba_tint`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (113), `SET_INTERIOR_ENTITY_SET_TINT_INDEX` (57), `SET_PED_COMPONENT_VARIATION` (52), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (49), `SET_BIT` (46), `SET_PED_COMBAT_ATTRIBUTES` (28), `DOES_ENTITY_EXIST` (28), `NET_TO_ENT` (26), `SET_PED_CONFIG_FLAG` (24), `IS_ENTITY_DEAD` (22), `NET_TO_PED` (22), `GET_SYNCHRONIZED_SCENE_PHASE` (21), `GET_ENTITY_COORDS` (18), `DISABLE_CONTROL_ACTION` (17), `SET_ENTITY_VISIBLE` (14), `SET_TINT_INDEX_CLOSEST_BUILDING_OF_TYPE` (14), `SET_STATIC_EMITTER_ENABLED` (13), `POW` (11), `VDIST2` (10), `CLEAR_BIT` (10), `SET_ENTITY_INVINCIBLE` (10), `IS_STRING_NULL_OR_EMPTY` (10), `IS_ENTITY_AT_COORD` (9), `HIDE_HUD_COMPONENT_THIS_FRAME` (9), `GET_PLAYER_WANTED_LEVEL` (9), `SET_PED_CAN_BE_TARGETTED` (8), `NET_TO_VEH` (8), `CLEAR_PED_TASKS` (8), `ROUND` (8), `PLAY_SOUND_FRONTEND` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x12 · `523.038f` x11 · `4750.548f` x11 · `-67.6263f` x11 · `258.302f` x9 · `0.6f` x4 · `0.99f` x4 · `0.1f` x4 · `-762.38f` x4 · `-0.5f` x3 · `0.35f` x3 · `-0.8f` x2 · `-76.20504f` x2 · `-74.20504f` x2 · `0.01f` x2 · `1.01f` x2 · `151.434f` x2 · `-766.347f` x2 · `258.052f` x2 · `151.103f` x2 · `-766.204f` x2 · `258.069f` x2 · `150.938f` x2 · `-766.15f` x2

## Other strings

Literals whose consuming native was not classified:

`FIX_FAML1`, `pos`, `num`, `FIX_FRANKLIN`, `FXR_OT_EXTSECRM`, `head`, `int`, `FIXER_SUSPENSE`, `typ`, `ibs`, `FIX_BALLASL1`, `sprt`, `hclr`, `scl`, `entity_set_style_1`, `bsa`, `rad`, `FIX_IMANI`, `entity_set_style_2`, `entity_set_style_3`, `entity_set_style_4`, `entity_set_style_5`, `entity_set_tint_options`, `FIXER_DELIVERING_START`, `FIXER_DELIVERING`, `FIXER_MED_INTENSITY`, `FXR_OT_EXTBRDG`, `FXR_OT_BRDYACHT`

---

Source: `decompiled_scripts/fm_content_vip_contract_1.c`
