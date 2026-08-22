# gb_ie_delivery_cutscene.c

Jobs script. 2 anim dicts; 13 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 402,486 |
| Functions | 7,257 (185 unique, 7,072 shared) |
| Unique lines | 22,843 (5.7% of file) |

## Assets

**Animation dictionaries** (2) - `random@atm_robbery@return_wallet_male`, `map_objects`

**Animations** (3) - `map_objects`, `Dock_crane_SLD_unload`, `Dock_crane_SLD_load`

**Models and props** (13) - `v_ilev_csr_garagedoor`, `s_m_m_trucker_01`, `s_m_m_highsec_02`, `imp_prop_flatbed_ramp`, `p_car_keys_01`, `mp_m_freemode_01`, `mp_f_freemode_01`, `prop_facgate_08`, `prop_com_gar_door_01`, `p_dock_crane_sld_s`, `prop_container_ld_d`, `p_dock_crane_cabl_s`, `prop_ld_garaged_01`

**Sounds** (5) - `Crush_Car`, `DLC_IE_Deliver_Vehicle_Scrapyard_Sounds`, `GTAO_EXEC_WH_GARAGE_DOOR_SOUNDS`, `Door_Open`, `Door_Close`

**Text labels** (1) - `NULL`

**Scenarios** (1) - `WORLD_HUMAN_HANG_OUT_STREET`

**Decorators** (2) - `ContrabandOwner`, `ExportVehicle`

**Hashed names** (2) - `v_15_garg_delta_doordown`, `MP_M_WareMech_01`

## Native vocabulary

Most-called natives inside the code unique to this script:

`IS_ENTITY_DEAD` (120), `DOES_ENTITY_EXIST` (90), `SET_BIT` (84), `PLAYER_PED_ID` (45), `PLAYER_ID` (43), `TO_FLOAT` (38), `FREEZE_ENTITY_POSITION` (34), `SET_ENTITY_COLLISION` (28), `SET_ENTITY_VISIBLE` (26), `GET_ENTITY_COORDS` (20), `PARTICIPANT_ID_TO_INT` (16), `GET_ENTITY_MODEL` (15), `SET_ENTITY_COORDS_NO_OFFSET` (15), `IS_PED_IN_ANY_VEHICLE` (15), `CLEAR_BIT` (15), `SET_ENTITY_COORDS` (14), `SET_ENTITY_HEADING` (14), `HAS_MODEL_LOADED` (13), `IS_STRING_NULL_OR_EMPTY` (11), `SET_ENTITY_ROTATION` (10), `GET_VEHICLE_PED_IS_IN` (10), `NETWORK_HAS_CONTROL_OF_ENTITY` (10), `GET_ENTITY_HEADING` (10), `REQUEST_MODEL` (9), `SET_VEHICLE_FORWARD_SPEED` (8), `ATTACH_ENTITY_TO_ENTITY` (8), `SET_ENTITY_CAN_BE_DAMAGED` (8), `GET_PLAYER_PED` (8), `SET_VEHICLE_ENGINE_ON` (6), `SET_VEHICLE_HANDBRAKE` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x52 · `0.15f` x41 · `0.25f` x35 · `0.75f` x18 · `-89.5003f` x18 · `-89.4995f` x12 · `-2.53198f` x10 · `17.5898f` x10 · `312.734f` x10 · `42.6614f` x10 · `-89.4999f` x8 · `-2.4051f` x8 · `-1083.144f` x8 · `27.1674f` x8 · `-0.7046f` x8 · `92.7145f` x8 · `0.05f` x7 · `1396.138f` x6 · `1114.381f` x6 · `114.9562f` x6 · `-1.5759f` x6 · `-81.3031f` x6 · `-1799.939f` x6 · `468.6572f` x6

## Other strings

Literals whose consuming native was not classified:

`est`, `zoom`, `zoom_sustain`, `above`, `birdseye`, `shot_1`, `sky`, `DLC_IE_Door_Sounds`, `shot_2`, `shot_3`, `cargobob`, `cargobob2`, `cargobob3`, `cargobob4`, `truck_in`, `sign`, `lowering`, `Garage_Door_Open_Loop`, `Garage_Door_Close_Loop`, `ramp_in`, `loading`, `going`, `towtruck`, `towtruck2`, `mp_f_freemode_01`, `IE_OFFM_SHRD_T`, `shr_int`, `fakeint`, `handover`, `driveaway`

---

Source: `decompiled_scripts/gb_ie_delivery_cutscene.c`
