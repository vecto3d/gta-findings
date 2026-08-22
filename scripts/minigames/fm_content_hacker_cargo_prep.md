# fm_content_hacker_cargo_prep.c

Minigames script. 4 anim dicts; 6 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 493,270 |
| Functions | 10,484 (374 unique, 10,110 shared) |
| Unique lines | 10,484 (2.1% of file) |

## Assets

**Animation dictionaries** (4) - `anim@scripted@freemode@ig7_sonar_equip@male@`, `anim@scripted@player@freemode@tun_prep_grab_midd_ig3@male@`, `anim@scripted@player@mission@tun_control_tower@heeled@`, `anim@scripted@player@mission@tun_control_tower@male@`

**Models and props** (6) - `v_ret_gc_ammo4`, `prop_barier_conc_05b`, `prop_barier_conc_05a`, `prop_pile_dirt_06`, `prop_rub_pile_02`, `prop_pile_dirt_03`

**Audio banks** (1) - `DLC_HEI4/DLCHEI4_GENERIC_01`

**Sounds** (4) - `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`, `Attach`, `Prep_CPPD_Sounds`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (105), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (14), `SET_BIT` (11), `NET_TO_ENT` (9), `SET_PED_COMBAT_ATTRIBUTES` (9), `SET_PED_CONFIG_FLAG` (9), `GET_RANDOM_INT_IN_RANGE` (8), `SET_ENTITY_INVINCIBLE` (7), `GET_ENTITY_COORDS` (6), `FREEZE_ENTITY_POSITION` (6), `SET_PED_PROP_INDEX` (6), `DOES_ENTITY_EXIST` (5), `IS_STRING_NULL_OR_EMPTY` (5), `DISABLE_CONTROL_ACTION` (5), `SET_CURRENT_PED_WEAPON` (5), `CLEAR_PED_TASKS` (5), `GET_DISTANCE_BETWEEN_COORDS` (5), `SET_PED_COMPONENT_VARIATION` (5), `CREATE_MODEL_HIDE` (5), `REMOVE_MODEL_HIDE` (5), `GET_PLAYER_WANTED_LEVEL` (5), `SET_ENTITY_ROTATION` (4), `GET_EVENT_DATA` (4), `NETWORK_GET_PLAYER_INDEX` (4), `SET_BOAT_ANCHOR` (4), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (4), `GET_VEHICLE_DOOR_ANGLE_RATIO` (4), `PLAYER_PED_ID` (3), `NETWORK_IS_PARTICIPANT_ACTIVE` (3), `GET_ENTITY_ROTATION` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`4.895f` x4 · `830.338f` x2 · `-3350.06f` x2 · `978.102f` x2 · `-3350.101f` x2 · `0.01f` x2 · `213.582f` x2 · `-2182.649f` x2 · `8.487f` x2 · `212.503f` x2 · `-2177.785f` x2 · `8.759f` x2 · `219.555f` x2 · `-2178.047f` x2 · `8.384f` x2 · `0.03f` x2 · `0.4f` x1 · `1.2f` x1 · `0.35f` x1 · `-0.2f` x1 · `-1276.027f` x1 · `-2448.211f` x1 · `73.3519f` x1 · `-1278.97f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `ibs`, `sprt`, `hclr`, `scl`, `bsa`, `rad`, `typ`, `CP_OT_WAITARO1`, `blp`, `veh`, `rot`, `X24_PAVEL`, `HF_BMT_4`, `MAX_NUM_SCENARIOS`, `grp`, `MP242_DELIVERING_START`, `MP242_SUSPENSE`, `MP242_DELIVERING`, `X24_JODI`, `MAX_NUM_TRANSITIONS`, `TIMER_TAR`, `CP_OT_WAITARM1`

---

Source: `decompiled_scripts/fm_content_hacker_cargo_prep.c`
