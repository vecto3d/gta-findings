# gb_contraband_buy.c

MP gang ops script. 1 anim dicts; 52 models.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 458,925 |
| Functions | 8,464 (646 unique, 7,818 shared) |
| Unique lines | 43,883 (9.6% of file) |

## Assets

**Animation dictionaries** (1) - `P_cargo_chute_S`

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (52) - `g_m_y_lost_01`, `g_m_m_armgoon_01`, `g_m_m_mexboss_01`, `g_m_y_azteca_01`, `prop_barrier_work05`, `g_m_y_korean_01`, `s_m_y_cop_01`, `s_m_m_chemsec_01`, `a_m_y_hipster_01`, `s_m_m_fibsec_01`, `s_m_y_swat_01`, `s_m_m_autoshop_02`, `s_f_y_cop_01`, `g_m_y_mexgoon_02`, `ex_prop_exec_crashedp`, `g_m_m_armboss_01`, `a_f_y_business_04`, `a_m_y_busicas_01`, `a_m_y_business_03`, `g_f_y_vagos_01`, `a_f_y_hipster_02`, `a_f_y_runner_01`, `v_ilev_garageliftdoor`, `a_m_m_tramp_01`, `a_m_y_epsilon_01`, `a_m_y_musclbeac_01`, `ex_prop_adv_case_sm`, `s_m_m_highsec_01`, `g_m_m_chiboss_01`, `g_m_m_chigoon_02`, `a_f_y_beach_01`, `g_m_m_korboss_01`, `prop_box_wood04a`, `a_m_o_tramp_01`, `a_f_y_epsilon_01`, `a_f_m_bodybuild_01`, `s_m_m_doctor_01`, `s_f_y_scrubs_01`, `s_m_m_paramedic_01`, `s_m_m_movspace_01`, `u_m_y_pogo_01`, `u_m_y_zombie_01`, `ex_prop_adv_case_sm_03`, `ex_prop_adv_case_sm_02`, `a_m_m_genfat_02`, `a_m_y_gay_01`, `a_f_y_hippie_01`, `s_m_y_construct_01`, `prop_const_fence02a`, `prop_road_memorial_02`, `prop_box_wood03a`, `prop_box_wood01a`

**Audio banks** (2) - `ALARM_BELL_01`, `DLC_EXEC1/SELL_AIR_DROP`

**Sounds** (21) - `DLC_Exec_Aftermath_Post_Shootout_Area_Scene`, `DLC_Exec_Aftermath_Sounds`, `GTAO_Magnate_Boss_Modes_Soundset`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `Deliver_Item`, `MP_PROPERTIES_ELEVATOR_DOORS`, `Bell_01`, `ALARMS_SOUNDSET`, `Crashed_Plane_Ambience`, `DLC_Exec_Crash_Site_SoundSet`, `Crow_Caw`, `Fly_Buzz`, `Car_Creak`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Flyover`, `DLC_Exec_Buy_Air_Drop_Sounds`, `Crates_Blipped`, `OPENING`, `OPENED`

**Text labels** (4) - `NULL`, `CONTRAVALUE`, `CONTRAVALUES`, `EXCALAU`

**Decorators** (2) - `MPBitset`, `Not_Allow_As_Saved_Veh`

**Scripts launched** (1) - `cellphone_flashhand`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NET_TO_PED` (231), `PLAYER_ID` (167), `PLAYER_PED_ID` (150), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (149), `NET_TO_ENT` (111), `NET_TO_VEH` (95), `PARTICIPANT_ID` (90), `SET_MODEL_AS_NO_LONGER_NEEDED` (87), `IS_ENTITY_DEAD` (77), `GET_ENTITY_COORDS` (71), `IS_ENTITY_IN_ANGLED_AREA` (71), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (67), `PARTICIPANT_ID_TO_INT` (58), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (46), `NET_TO_OBJ` (44), `DOES_ENTITY_EXIST` (38), `SET_BIT` (36), `GET_SCRIPT_TASK_STATUS` (34), `DOES_BLIP_EXIST` (34), `IS_NETWORK_ID_OWNED_BY_PARTICIPANT` (33), `GET_CLOUD_TIME_AS_INT` (29), `SET_PED_COMBAT_ATTRIBUTES` (26), `IS_VEHICLE_DRIVEABLE` (24), `SET_PED_CONFIG_FLAG` (22), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (21), `GET_RANDOM_INT_IN_RANGE` (20), `GET_DISTANCE_BETWEEN_COORDS` (18), `SET_ENTITY_INVINCIBLE` (18), `SET_BLIP_ROUTE` (18), `GIVE_WEAPON_TO_PED` (17)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x8 · `2.5f` x4 · `0.001f` x4 · `0.9f` x3 · `7.5f` x3 · `6.5f` x3 · `14.9f` x2 · `0.8f` x2 · `3.5f` x2 · `1.5f` x2 · `23.25f` x2 · `29.40535f` x2 · `33.22042f` x2 · `1508.385f` x2 · `-2101.052f` x2 · `74.91064f` x2 · `1541.564f` x2 · `-2100.845f` x2 · `86.20255f` x2 · `799.0624f` x2 · `1284.498f` x2 · `366.0732f` x2 · `778.8398f` x2 · `1285.482f` x2

## Other strings

Literals whose consuming native was not classified:

`BYCB_TITLE`, `buccaneer`, `speedo`, `mule`, `kuruma`, `gburrito`, `cavalcade2`, `BYCB_CLT_CNT0b`, `BYCB_CLT_CNT0`, `rumpo3`, `stockade`, `paradise`, `BYCB_NM`, `boxville`, `burrito`, `journey`, `policet`, `surfer`, `daemon`, `phoenix`, `schafter2`, `emperor`, `huntley`, `GB_CONT_OVER`, `BYCB_TXTMSG23a1`, `pony`, `youga`, `manana`, `fugitive`, `hexer`

---

Source: `decompiled_scripts/gb_contraband_buy.c`
