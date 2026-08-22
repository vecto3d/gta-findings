# business_battles_sell.c

MP freemode script. 13 anim dicts; 108 models; 1 scaleforms; 6 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 516,199 |
| Functions | 9,294 (1,223 unique, 8,071 shared) |
| Unique lines | 92,941 (18.0% of file) |

## Assets

**Animation dictionaries** (13) - `move_m@bag`, `MOVE_M@TOUGH_GUY@`, `anim@mp_apt_ext@exit_all`, `cellphone@in_car@ps`, `mini@strip_club@idles@dj@idle_01`, `anim@amb@nightclub@dancers@crowddance_facedj@hi_intensity`, `anim@amb@nightclub@dancers@crowddance_facedj@med_intensity`, `veh@van@rps_rear@idle_agitated`, `veh@std@ps@idle_panic`, `cellphone@in_car@ds`, `random@paparazzi@peek`, `timetable@maid@cleaning_window`, `anim@amb@nightclub@poster@`

**Models and props** (108) - `a_m_y_business_03`, `a_f_y_juggalo_01`, `ba_prop_battle_tent_01`, `a_m_y_vinewood_04`, `s_m_y_construct_01`, `a_f_y_hippie_01`, `a_m_y_hipster_01`, `s_m_y_cop_01`, `a_m_y_beach_01`, `a_m_y_hiker_01`, `a_f_y_hipster_02`, `s_m_y_waretech_01`, `ba_prop_battle_tent_02`, `prop_crate_11e`, `a_m_m_paparazzi_01`, `ba_prop_battle_barrier_02a`, `g_m_y_korean_01`, `g_m_y_lost_01`, `g_m_y_mexgoon_02`, `prop_beach_fire`, `s_f_y_clubbar_01`, `s_m_y_clubbar_01`, `s_m_y_doorman_01`, `u_f_y_bikerchic`, `ig_djblamadon`, `a_m_y_soucent_01`, `prop_ghettoblast_02`, `prop_boxpile_02b`, `ba_prop_club_dressing_posters_01`, `ba_prop_club_dressing_posters_02`, `gr_prop_gr_rsply_crate04b`, `s_m_m_ciasec_01`, `ex_prop_adv_case_sm_02`, `ig_englishdave`, `a_m_y_clubcust_01`, `s_m_m_highsec_01`, `ig_dix`, `v_ret_ml_beerpat1`, `a_m_m_hillbilly_01`, `g_m_m_chigoon_02`, `s_m_y_blackops_01`, `prop_skid_tent_01`, `ba_prop_batle_crates_pounder`, `prop_lrggate_01_l`, `prop_lrggate_01_r`, `ig_kerrymcintosh_02`, `u_f_y_poppymich_02`, `s_m_m_trucker_01`, `ig_jimmyboston_02`, `ig_lacey_jones_02`, `a_f_y_soucent_03`, `a_m_y_soucent_04`, `a_f_m_bevhills_01`, `a_f_y_vinewood_02`, `ig_tylerdix_02`, `u_f_m_miranda_02`, `u_f_y_mistress`, `prop_pipes_02b`, `ba_prop_battle_crate_beer_04`, `ba_prop_battle_hinge` ...

**Audio banks** (3) - `SCRIPT/CAR_STEAL_4`, `SCRIPT/DELIVERIES`, `PLANES`

**Sounds** (18) - `DLC_BTL_Collector_Sounds`, `DLC_BTL_Blimp_Promotion_General_Scene`, `Flyer_Drop`, `DLC_BTL_Flyer_Promotion_Sounds`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Crates_Blipped`, `GTAO_Magnate_Boss_Modes_Soundset`, `car_fall`, `package_delivered_success`, `DLC_GR_Generic_Mission_Sounds`, `bottles_loop`, `dlc_btl_stolen_supplies_Sounds`, `blimpheight`, `lock_break`, `stafford_fall`, `ramp_fall`, `DLC_BTL_PBUS2_Music_Boost_Scene`

**Speech contexts** (5) - `KERRY`, `POPPY`, `JIMMYBOSTON`, `MIRANDA`, `A_F_Y_EastSA_03_Latino_FULL_01`

**Scaleform movies** (1) - `PARTY_BUS`

**Particle effects** (6) - `scr_ba_bb`, `scr_ba_bb_leaflet_drop`, `spawn`, `scr_ba_bb_flare`, `scr_ba_bb_package_flare`, `scr_ba_bb_plane_smoke_trail`

**Text labels** (21) - `LACEY`, `JIMMYBOSTON`, `MIRANDA`, `LAZLOW`, `PR2NCE`, `NULL`, `POPPYM15`, `D3X1E`, `89MZD344`, `69RLV051`, `40GZM267`, `21RKK886`, `81AFC815`, `PR1NCE`, `HACK`, `LAZFMAU`, `BATFMAU`, `KERRY`, `OFF`, `FIGHT`, `POPPY`

**Decorators** (5) - `Not_Allow_As_Saved_Veh`, `MPBitset`, `ContrabandOwner`, `ContrabandDeliveryType`, `ExportVehicle`

**Scripts launched** (1) - `am_mp_smpl_interior_int`

**Hashed names** (2) - `ba_prop_battle_pbus_screen`, `Swap_Poster`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (224), `NET_TO_VEH` (149), `DOES_ENTITY_EXIST` (148), `IS_ENTITY_DEAD` (128), `PARTICIPANT_ID` (123), `NET_TO_ENT` (112), `GET_SCRIPT_TASK_STATUS` (102), `SET_BIT` (90), `SET_ALL_VEHICLE_GENERATORS_ACTIVE_IN_AREA` (79), `SET_VEHICLE_DOOR_OPEN` (77), `IS_ENTITY_IN_ANGLED_AREA` (73), `SET_DOOR_ALLOWED_TO_BE_BROKEN_OFF` (72), `NET_TO_PED` (69), `SET_PED_COMPONENT_VARIATION` (69), `PLAYER_ID` (67), `DOES_EXTRA_EXIST` (67), `SET_VEHICLE_EXTRA` (67), `SET_PED_CONFIG_FLAG` (61), `SET_PED_COMBAT_ATTRIBUTES` (57), `GET_ENTITY_COORDS` (49), `SET_VEHICLE_COLOURS` (48), `GET_PLAYER_WANTED_LEVEL` (47), `IS_PED_IN_ANY_VEHICLE` (46), `PARTICIPANT_ID_TO_INT` (44), `GET_ENTITY_MODEL` (44), `GET_RANDOM_INT_IN_RANGE` (41), `SET_ENTITY_VISIBLE` (38), `CLEAR_BIT` (33), `SET_ENTITY_INVINCIBLE` (32), `NETWORK_HAS_CONTROL_OF_ENTITY` (30)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x10 · `0.25f` x9 · `0.9f` x7 · `1.5f` x7 · `0.3f` x4 · `0.2f` x3 · `0.454319f` x3 · `16.5f` x3 · `12.5f` x3 · `0.1f` x3 · `0.8f` x3 · `10.45432f` x2 · `5.454319f` x2 · `0.454318f` x2 · `37.755f` x2 · `30.78754f` x2 · `62.1074f` x2 · `2.5f` x2 · `0.01f` x2 · `24.72731f` x2 · `1334.873f` x2 · `3119.384f` x2 · `39.9832f` x2 · `0.4f` x2

## Other strings

Literals whose consuming native was not classified:

`BTL_DAVE`, `riata`, `BTL_TONY`, `sadler`, `speedo4`, `1st Scene`, `pounder2`, `mule4`, `2nd Scene`, `Nigel1bCelebMale01`, `mule`, `policet`, `kuruma`, `BTL_BLMADONNA`, `BTL_CARMINE`, `BTL_MATEO`, `police4`, `MBS_BM_TP`, `MBB_LIMO`, `MBSOT_ENTER3`, `BTL_MARCEL`, `BTL_CONNIE`, `PBus_Screen`, `schafter3`, `patriot2`, `chassis_dummy`, `speedo`

---

Source: `decompiled_scripts/business_battles_sell.c`
