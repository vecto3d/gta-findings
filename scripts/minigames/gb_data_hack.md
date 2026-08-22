# gb_data_hack.c

Minigames script. 1 anim dicts; 7 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 483,299 |
| Functions | 8,742 (203 unique, 8,539 shared) |
| Unique lines | 19,533 (4.0% of file) |

## Assets

**Animation dictionaries** (1) - `anim@mp_apt_ext@exit_all`

**Models and props** (7) - `ex_prop_adv_case_sm_02`, `s_m_m_highsec_01`, `s_m_m_highsec_02`, `hei_prop_carrier_crate_01b`, `gr_prop_gr_rsply_crate04b`, `prop_box_wood04a`, `ba_prop_batle_crates_pounder`

**Sounds** (6) - `dlc_xm_deluxos_hacking_Hacking_Sounds`, `Hack_Stop`, `Hack_Start`, `Hack_Complete`, `Hack_Loop`, `percentageComplete`

**Text labels** (3) - `NULL`, `PAIFMAU`, `PAIGE`

**Decorators** (2) - `MPBitset`, `Not_Allow_As_Saved_Veh`

**Scripts launched** (2) - `am_mp_smpl_interior_int`, `appsecurohack`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PARTICIPANT_ID` (60), `PLAYER_ID` (36), `DOES_ENTITY_EXIST` (31), `PARTICIPANT_ID_TO_INT` (24), `GET_ENTITY_MODEL` (21), `SET_BIT` (21), `PLAYER_PED_ID` (20), `NETWORK_HAS_CONTROL_OF_ENTITY` (17), `CLEAR_HELP` (16), `GET_SCRIPT_TASK_STATUS` (16), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (15), `GET_ENTITY_COORDS` (14), `INT_TO_PARTICIPANTINDEX` (13), `GET_RANDOM_INT_IN_RANGE` (10), `GET_PED_IN_VEHICLE_SEAT` (10), `IS_ENTITY_DEAD` (10), `SET_ENTITY_VISIBLE` (10), `CLEAR_BIT` (9), `DOES_BLIP_EXIST` (9), `NETWORK_GET_PLAYER_INDEX` (9), `IS_PED_IN_VEHICLE` (8), `IS_ENTITY_A_PED` (8), `GET_PED_INDEX_FROM_ENTITY_INDEX` (8), `VEHICLE_SET_JET_WASH_FORCE_ENABLED` (8), `SET_VEHICLE_ON_GROUND_PROPERLY` (8), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (8), `NETWORK_DOES_NETWORK_ID_EXIST` (7), `SET_ENTITY_COLLISION` (7), `NETWORK_GET_PLAYER_INDEX_FROM_PED` (6), `SET_ALL_VEHICLE_GENERATORS_ACTIVE_IN_AREA` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x4 · `0.25f` x2 · `2.5f` x1 · `0.3f` x1

## Other strings

Literals whose consuming native was not classified:

`1st Scene`, `2nd Scene`, `speedo`, `cognoscenti2`, `schafter6`, `baller6`, `BB_DH_OBJ_023`, `BB_DH_OBJ_025`, `BB_DH_OBJ_022`, `BB_DH_OBJ_020`, `BB_DH_OBJ_021`, `BB_DH_OBJ_024`, `mule`, `mule2`, `mule3`, `mule4`, `pounder2`, `speedo2`, `speedo4`, `BB_DH_HMT_00`, `BB_DH_HMT_01`, `BB_DH_BMT_02`, `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_GUARD_STAND`, `BB_DH_OBJ_05`, `pounder`, `BB_DH_OBJ_04`, `MBB_DATA_DRIVES`, `HACK_WORK_END`

---

Source: `decompiled_scripts/gb_data_hack.c`
