# gb_vehicle_export.c

Vehicles script. 1 anim dicts; 89 models; 3 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | Vehicles |
| Total lines | 487,333 |
| Functions | 8,803 (930 unique, 7,873 shared) |
| Unique lines | 86,570 (17.8% of file) |

## Assets

**Animation dictionaries** (1) - `P_cargo_chute_S`

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (89) - `prop_generator_03b`, `g_m_importexport_01`, `g_f_importexport_01`, `s_m_m_highsec_01`, `prop_roadcone01a`, `prop_barrier_work06a`, `s_m_y_xmech_01`, `prop_makeup_trail_01_cr`, `s_m_y_cop_01`, `prop_roadcone02c`, `s_m_y_swat_01`, `prop_tyre_wall_03c`, `g_m_y_korean_01`, `prop_ind_barge_01_cr`, `SET_DATA_SLOT`, `g_m_y_korean_02`, `a_f_y_hipster_02`, `a_m_y_hipster_01`, `prop_barrier_work05`, `s_m_y_sheriff_01`, `s_f_y_cop_01`, `g_m_m_armgoon_01`, `a_m_m_bevhills_01`, `prop_food_van_02`, `prop_container_ld2`, `prop_tyre_wall_02c`, `bkr_prop_weed_bigbag_open_01a`, `g_m_y_lost_01`, `g_m_y_mexgoon_02`, `u_m_m_filmdirector`, `g_m_m_korboss_01`, `s_m_y_marine_03`, `s_m_y_robber_01`, `s_m_y_hwaycop_01`, `s_f_y_hooker_01`, `u_m_y_gunvend_01`, `a_m_m_paparazzi_01`, `a_f_y_beach_01`, `a_m_y_gay_01`, `prop_air_cargo_04a`, `prop_start_gate_01b`, `prop_ghettoblast_02`, `g_m_y_korlieut_01`, `g_m_m_mexboss_01`, `g_m_y_azteca_01`, `a_f_y_genhot_01`, `s_m_m_lifeinvad_01`, `prop_cons_crate`, `prop_container_03mb`, `prop_offroad_tyres02`, `prop_boombox_01`, `prop_security_case_01`, `prop_cs_duffel_01`, `ex_prop_adv_case_sm`, `s_m_m_chemsec_01`, `s_m_y_airworker`, `s_f_y_sheriff_01`, `a_m_y_vindouche_01`, `g_m_m_armboss_01`, `a_m_m_tennis_01` ...

**Audio banks** (3) - `DLC_IMPORTEXPORT/STEAL_STUNT`, `HUD_321_GO`, `DLC_EXEC1/SELL_AIR_DROP`

**Sounds** (27) - `DLC_IE_Steal_Cargobob_Sounds`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Time`, `DLC_IE_Tail_Vehicle_Sounds`, `Speed_Boost`, `DLC_IE_Stunt_Man_Sounds`, `Count_Start`, `Countdown_Loop`, `Ctrl`, `Count_Stop`, `Arming_Countdown`, `Bomb_Armed`, `Bomb_Disarmed`, `Crates_Blipped`, `GTAO_Magnate_Boss_Modes_Soundset`, `Meter_Fill_Loop`, `intensity`, `Meter_Full`, `Hook_Attach`, `Hook_Detach`, `Hook_Engage`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Flyover`, `DLC_Exec_Buy_Air_Drop_Sounds`, `DLC_Exec_Aftermath_Post_Shootout_Area_Scene`

**Scaleform movies** (3) - `SET_DATA_SLOT`, `SET_MESSAGE`, `COUNTDOWN`

**Particle effects** (2) - `scr_ie_export_flare`, `scr_ie_export_package_flare`

**Texture dicts** (2) - `helicopterhud`, `hud_outline`

**Text labels** (12) - `INVALID`, `21ZLW254`, `87DZU328`, `05SBF291`, `NULL`, `25UAB193`, `83CMV565`, `04PVK770`, `83UUC618`, `38UMF829`, `OFF`, `IMPAAUD`

**Decorators** (5) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `ContrabandOwner`, `ContrabandDeliveryType`, `ExportVehicle`

**Scripts launched** (1) - `cellphone_flashhand`

**Hashed names** (1) - `NO_LABEL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`TO_FLOAT` (345), `ROUND` (271), `PLAYER_PED_ID` (203), `PLAYER_ID` (198), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (145), `SET_BIT` (130), `PARTICIPANT_ID` (130), `NET_TO_VEH` (118), `IS_ENTITY_IN_ANGLED_AREA` (93), `NET_TO_PED` (81), `NET_TO_ENT` (80), `IS_ENTITY_DEAD` (74), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (60), `PARTICIPANT_ID_TO_INT` (59), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (53), `GET_ENTITY_COORDS` (51), `SET_PED_COMPONENT_VARIATION` (45), `GET_SCRIPT_TASK_STATUS` (42), `DOES_BLIP_EXIST` (40), `GET_RANDOM_INT_IN_RANGE` (39), `NET_TO_OBJ` (39), `IS_NETWORK_ID_OWNED_BY_PARTICIPANT` (37), `DOES_ENTITY_EXIST` (36), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (36), `SET_PED_COMBAT_ATTRIBUTES` (33), `GET_DISTANCE_BETWEEN_COORDS` (24), `GET_ENTITY_MODEL` (24), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (24), `SET_PED_CONFIG_FLAG` (23), `FLOOR` (23)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x6 · `0.1f` x4 · `36.08694f` x4 · `-1576.5f` x2 · `444.3192f` x2 · `105.9493f` x2 · `-1569.429f` x2 · `372.1915f` x2 · `158.3052f` x2 · `-2756.431f` x2 · `2745.77f` x2 · `0.332401f` x2 · `-2760.088f` x2 · `2693.743f` x2 · `51.3839f` x2 · `796.0793f` x2 · `1197.43f` x2 · `330.4921f` x2 · `838.5543f` x2 · `1247.993f` x2 · `403.0379f` x2 · `456.6269f` x2 · `-1106.045f` x2 · `41.07565f` x2

## Other strings

Literals whose consuming native was not classified:

`dominator`, `sultanrs`, `banshee2`, `mp_g_m_pros_01`, `schafter5`, `police3`, `kuruma`, `futo`, `buccaneer2`, `prototipo`, `virgo2`, `policeb`, `btype3`, `ztype`, `feltzer3`, `D_FMM_2_0`, `tyrus`, `bestiagts`, `t20`, `sheava`, `osiris`, `fmj`, `reaper`, `pfister811`, `alpha`, `mamba`, `tampa`, `tropos`, `entityxf`

---

Source: `decompiled_scripts/gb_vehicle_export.c`
