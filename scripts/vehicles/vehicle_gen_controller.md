# vehicle_gen_controller.c

Vehicles script. 1 anim dicts; 13 models; 3 scaleforms.

| | |
|---|---|
| Category | Vehicles |
| Total lines | 37,796 |
| Functions | 600 (108 unique, 492 shared) |
| Unique lines | 8,459 (22.4% of file) |

## Assets

**Animation dictionaries** (1) - `ANIM@APT_TRANS@GARAGE`

**Models and props** (13) - `v_ilev_uvline`, `v_garagem_sp`, `u_m_y_cyclist_01`, `a_c_rabbit_01`, `a_c_boar`, `a_c_deer`, `a_c_mtlion`, `cs_hunter`, `a_m_y_hiker_01`, `a_f_y_hippie_01`, `a_m_m_hillbilly_01`, `prop_forsale_dyn_01`, `prop_airport_sale_sign`

**Sounds** (10) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `BACK`, `SELECT`, `GARAGE_DOOR_SCRIPTED_CLOSE`, `hold`, `PROPERTY_PURCHASE_MEDIUM`, `HUD_PROPERTY_SOUNDSET`, `UNDER_THE_BRIDGE`, `HUD_AWARDS`

**Scaleform movies** (3) - `MIDSIZED_MESSAGE`, `SHOW_SHARD_MIDSIZED_MESSAGE`, `SHARD_ANIM_OUT`

**Text labels** (11) - `HANGAR`, `HELIPAD`, `MARINA`, `TWOSTRINGS`, `EAS`, `ALLS`, `SQUAT`, `PVEHICLE`, `NULL`, `AST`, `UNSET`

**Interiors and entity sets** (3) - `v_garagem_sp`, `GtaMloRoom001`, `v_chopshop`

**Scripts launched** (4) - `startup_positioning`, `taxi_procedural`, `michael1`, `exile2`

**Hashed names** (1) - `vehicle_gen_controller`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (194), `DOES_ENTITY_EXIST` (84), `ADD_DECAL` (63), `IS_VEHICLE_DRIVEABLE` (49), `PLAYER_ID` (47), `DISABLE_CONTROL_ACTION` (40), `GET_GAME_TIMER` (37), `CLEAR_BIT` (34), `SET_BIT` (29), `IS_PED_INJURED` (28), `APPLY_PED_BLOOD_SPECIFIC` (28), `GET_ENTITY_MODEL` (27), `DOES_CAM_EXIST` (27), `GET_ENTITY_COORDS` (25), `SET_PLAYER_CONTROL` (24), `IS_PED_IN_ANY_VEHICLE` (24), `SET_ENTITY_COORDS` (24), `SET_MODEL_AS_NO_LONGER_NEEDED` (21), `HAS_MODEL_LOADED` (20), `ENABLE_CONTROL_ACTION` (20), `SET_ENTITY_HEADING` (20), `PLAY_SOUND_FRONTEND` (19), `IS_ENTITY_IN_ANGLED_AREA` (19), `FREEZE_ENTITY_POSITION` (18), `GET_VEHICLE_PED_IS_IN` (17), `SET_CAM_ACTIVE` (16), `DESTROY_CAM` (16), `SETTIMERA` (16), `TIMERA` (16), `SET_VEHICLE_AS_NO_LONGER_NEEDED` (15)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.196f` x45 · `0.9f` x20 · `0.33f` x19 · `0.8f` x18 · `0.19f` x18 · `0.01f` x17 · `0.7f` x13 · `0.5f` x10 · `1.1f` x9 · `0.6f` x9 · `0.4f` x8 · `471.48f` x8 · `0.3f` x7 · `431.4f` x6 · `-997.33f` x6 · `24.76f` x6 · `0.688f` x6 · `0.07f` x5 · `-89.377f` x5 · `92.6583f` x5 · `71.2349f` x5 · `-62.0307f` x5 · `-1839.859f` x5 · `25.6787f` x5

## Other strings

Literals whose consuming native was not classified:

`ShotgunLargeMonolithic`, `monster`, `BasicSlash`, `marshall`, `rhino`, `HANGAR_NO`, `MARINA_NO`, `HELIPAD_NO`, `WEB_VEH_INV`, `WEB_VEH_FULL`, `gar_open_1_left`, `gar_open_1_right`, `ITEM_SELECT`, `ITEM_EXIT`, `submersible2`, `ITEM_YES`, `ITEM_NO`, `MARINA_NAME`, `CAR_GAR`, `gar_open_2_left`, `gar_open_2_right`, `CAR_GAR_05`, `CAR_GAR_06`, `CAR_GAR_EXIT`, `til_P_`, `Exec_U`, `xer_Scene`, `B_Mi`, `stab`, `Cannot be created: Same player vehicle cleaned up within the last 3 hours`

---

Source: `decompiled_scripts/vehicle_gen_controller.c`
