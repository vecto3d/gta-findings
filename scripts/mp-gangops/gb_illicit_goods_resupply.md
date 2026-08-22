# gb_illicit_goods_resupply.c

MP gang ops script. 1 anim dicts; 147 models; 1 scaleforms; 2 particle effects.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 492,548 |
| Functions | 8,822 (946 unique, 7,876 shared) |
| Unique lines | 99,209 (20.1% of file) |

## Assets

**Animation dictionaries** (1) - `P_cargo_chute_S`

**Animations** (3) - `P_cargo_chute_S`, `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (147) - `prop_box_wood02a_pu`, `g_m_y_lost_01`, `g_m_y_mexgoon_02`, `prop_box_wood04a`, `g_m_y_azteca_01`, `bkr_prop_meth_table01a`, `g_f_y_vagos_01`, `a_m_m_hillbilly_02`, `prop_boxpile_02b`, `g_m_y_ballaorig_01`, `g_m_y_korean_01`, `g_m_y_ballaeast_01`, `bkr_prop_weed_lrg_01b`, `g_m_m_mexboss_01`, `g_m_m_armgoon_01`, `s_m_m_lathandy_01`, `g_m_m_chigoon_02`, `bkr_prop_weed_table_01a`, `prop_barrel_pile_01`, `bkr_prop_weed_med_01b`, `a_m_y_methhead_01`, `a_m_y_hippy_01`, `g_f_y_lost_01`, `g_m_y_salvagoon_01`, `prop_boxpile_04a`, `prop_barrier_work05`, `s_m_y_cop_01`, `prop_meth_setup_01`, `s_m_m_security_01`, `a_f_y_business_04`, `a_m_m_hillbilly_01`, `prop_box_wood03a`, `prop_pot_plant_05c`, `bkr_prop_meth_phosphorus`, `a_m_y_hipster_01`, `SET_DATA_SLOT`, `s_m_m_chemsec_01`, `s_m_y_construct_01`, `s_m_m_fibsec_01`, `prop_box_guncase_02a`, `prop_pipes_conc_01`, `prop_cratepile_07a`, `prop_box_wood02a_mws`, `prop_boxpile_07a`, `prop_barier_conc_01a`, `prop_cs_duffel_01`, `s_m_m_autoshop_02`, `s_m_y_swat_01`, `s_m_y_airworker`, `a_m_y_busicas_01`, `a_m_y_business_03`, `g_m_m_chiboss_01`, `s_f_y_cop_01`, `prop_offroad_barrel01`, `ex_prop_exec_crashedp`, `g_m_y_mexgoon_01`, `g_m_m_chigoon_01`, `g_m_y_strpunk_01`, `a_f_y_hippie_01`, `g_m_m_armboss_01` ...

**Audio banks** (2) - `ALARM_BELL_01`, `DLC_EXEC1/SELL_AIR_DROP`

**Sounds** (27) - `GTAO_Biker_Modes_Soundset`, `DLC_Exec_Aftermath_Post_Shootout_Area_Scene`, `DLC_Exec_Aftermath_Sounds`, `5s`, `MP_MISSION_COUNTDOWN_SOUNDSET`, `MP_PROPERTIES_ELEVATOR_DOORS`, `Bell_01`, `ALARMS_SOUNDSET`, `DLC_Biker_Resupply_Meet_Contact_Sounds`, `OPENING`, `OPENED`, `Pickup_Standard`, `PICKUP_AMMO_BULLET_MP`, `PICKUP_DEFAULT`, `Crates_Blipped`, `Crashed_Plane_Ambience`, `DLC_Exec_Crash_Site_SoundSet`, `Crow_Caw`, `Fly_Buzz`, `Car_Creak`, `Deliver_Item`, `Parachute_Land`, `DLC_Exec_Air_Drop_Sounds`, `Flyover`, `DLC_Exec_Buy_Air_Drop_Sounds`, `Sniper_Fire`, `Sniper_Bullet_Hit`

**Scaleform movies** (1) - `SET_DATA_SLOT`

**Particle effects** (2) - `scr_bike_contact`, `scr_contact_sniper_kill`

**Text labels** (3) - `NULL`, `LJT`, `BPLESAU`

**Decorators** (5) - `MPBitset`, `Not_Allow_As_Saved_Veh`, `ContrabandOwner`, `ContrabandDeliveryType`, `ExportVehicle`

**Hashed names** (1) - `NO_LABEL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (351), `PLAYER_PED_ID` (341), `TO_FLOAT` (333), `ROUND` (278), `NET_TO_PED` (238), `IS_ENTITY_IN_ANGLED_AREA` (211), `PARTICIPANT_ID` (185), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (183), `NET_TO_ENT` (140), `NET_TO_VEH` (102), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (99), `IS_ENTITY_DEAD` (95), `PARTICIPANT_ID_TO_INT` (88), `SET_MODEL_AS_NO_LONGER_NEEDED` (86), `GET_ENTITY_COORDS` (83), `SET_BIT` (82), `SET_PED_CONFIG_FLAG` (61), `NET_TO_OBJ` (60), `SET_PED_COMPONENT_VARIATION` (60), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (59), `DOES_ENTITY_EXIST` (54), `GET_CLOUD_TIME_AS_INT` (50), `DOES_BLIP_EXIST` (50), `SET_PED_COMBAT_ATTRIBUTES` (45), `IS_NETWORK_ID_OWNED_BY_PARTICIPANT` (43), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (41), `GET_SCRIPT_TASK_STATUS` (41), `GET_RANDOM_INT_IN_RANGE` (38), `GIVE_WEAPON_TO_PED` (36), `SET_PED_KEEP_TASK` (34)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.2f` x6 · `0.1f` x5 · `10.25f` x5 · `2.5f` x5 · `4.5f` x5 · `30.62671f` x5 · `7.5f` x4 · `0.5f` x4 · `0.001f` x4 · `-0.2947f` x4 · `33.2472f` x4 · `8.5f` x4 · `32.87672f` x4 · `0.25f` x3 · `14.9f` x3 · `1.5f` x3 · `6.5f` x3 · `9.75f` x3 · `3.5f` x3 · `37.73138f` x3 · `40.52014f` x3 · `5.25f` x3 · `-3.57f` x2 · `1.04f` x2

## Other strings

Literals whose consuming native was not classified:

`daemon`, `pcj`, `mp_g_m_pros_01`, `fugitive`, `stockade`, `gburrito`, `speedo`, `enduro`, `huntley`, `hakuchou`, `contender`, `double`, `journey`, `boxville3`, `nemesis`, `D_FMM_2_0`, `BRS_NMRESUP`, `burrito2`, `burrito`, `tampa`, `picador`, `D_FMM_1_0`, `paradise`, `REW_RS`, `REW_LSB`, `REW_REDSK`, `BRS_BM0`, `BBS_VANa1`, `BBS_VANa0`

---

Source: `decompiled_scripts/gb_illicit_goods_resupply.c`
