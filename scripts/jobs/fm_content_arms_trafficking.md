# fm_content_arms_trafficking.c

Jobs script. 2 anim dicts; 6 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 493,108 |
| Functions | 10,636 (471 unique, 10,165 shared) |
| Unique lines | 14,926 (3.0% of file) |

## Assets

**Animation dictionaries** (2) - `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`

**Animations** (2) - `P_cargo_chute_S_crumple`, `P_cargo_chute_S_deploy`

**Models and props** (6) - `prop_plant_group_06b`, `prop_fnc_farm_01c`, `prop_fnc_farm_01f`, `prop_bush_lrg_01b`, `prop_bush_med_03`, `prop_lrggate_02_ld`

**Sounds** (5) - `DLC_MP2023_1_Small_And_Agile_Sounds`, `Delivery_Success`, `Deliver_Parcel`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`

**Text labels** (2) - `X24OAU`, `MISSION`

**Vehicle mods** (1) - `ratel`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (97), `PLAYER_ID` (66), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (27), `SET_BIT` (26), `NET_TO_OBJ` (23), `GET_RANDOM_FLOAT_IN_RANGE` (13), `VMAG` (11), `GET_ENTITY_COORDS` (10), `NET_TO_VEH` (10), `GET_RANDOM_INT_IN_RANGE` (10), `IS_PED_IN_ANY_VEHICLE` (8), `PLAYER_PED_ID` (7), `GET_ID_OF_THIS_THREAD` (7), `NET_TO_ENT` (7), `CREATE_MODEL_HIDE` (6), `REMOVE_MODEL_HIDE` (6), `FREEZE_ENTITY_POSITION` (6), `IS_PLAYER_DEAD` (6), `VDIST` (6), `SET_ENTITY_INVINCIBLE` (6), `DISABLE_CONTROL_ACTION` (5), `CLEAR_PED_TASKS` (5), `NETWORK_GET_PLAYER_INDEX` (5), `SET_ACTIVATE_OBJECT_PHYSICS_AS_SOON_AS_IT_IS_UNFROZEN` (5), `SET_ENTITY_SHOULD_FREEZE_WAITING_ON_COLLISION` (5), `SET_ENTITY_LOD_DIST` (5), `GET_ENTITY_HEADING` (5), `IS_ENTITY_IN_AIR` (4), `IS_STRING_NULL_OR_EMPTY` (4), `GET_NETWORK_TIME` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-0.2f` x3 · `1598.252f` x2 · `2131.283f` x2 · `79.692f` x2 · `1597.958f` x2 · `2152.719f` x2 · `79.201f` x2 · `2809.568f` x2 · `4713.501f` x2 · `45.3285f` x2 · `2817.241f` x2 · `4718.372f` x2 · `45.5141f` x2 · `2815.76f` x2 · `4737.744f` x2 · `45.7198f` x2 · `0.5f` x2 · `2808.863f` x2 · `4703.41f` x2 · `45.2998f` x2 · `3.5f` x1 · `14.9f` x1 · `-2.88f` x1 · `0.65f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `AT_BM_SS`, `rot`, `bsa`, `ibs`, `sprt`, `hclr`, `scl`, `MP242_MED_INTENSITY`, `MP242_DELIVERING`, `veh`, `rad`, `X24_OSCAR`, `peyote`, `MP242_GUNFIGHT`, `MAX_NUM_SCENARIOS`, `blp`, `grp`, `ATR_OBJ_ENT`, `MP242_SUSPENSE`, `MAX_NUM_TRANSITIONS`, `TIMER_TAR`, `totyp`

---

Source: `decompiled_scripts/fm_content_arms_trafficking.c`
