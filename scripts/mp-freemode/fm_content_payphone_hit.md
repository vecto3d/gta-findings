# fm_content_payphone_hit.c

MP freemode script. 10 anim dicts; 12 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 520,239 |
| Functions | 11,236 (942 unique, 10,294 shared) |
| Unique lines | 28,096 (5.4% of file) |

## Assets

**Animation dictionaries** (10) - `amb@world_human_gardener_plant@male@enter`, `anim@heists@narcotics@funding@horny_biker`, `ANIM@SCRIPTED@PAYPHONE_HITS@MALE@`, `move_M@TOUGH_GUY@`, `move_f@scared`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `ANIM@SCRIPTED@PAYPHONE_HITS@GONE_GOLFING@`, `MOVE_M@GOLFER@`, `anim@door_trans@hinge_l@`, `move_m@drunk@a`

**Animations** (2) - `anim@heists@narcotics@funding@horny_biker`, `horny_biker_loop`

**Models and props** (12) - `sf_prop_sf_phonebox_01b_s`, `a_f_y_juggalo_01`, `a_m_y_juggalo_01`, `a_m_m_rurmeth_01`, `a_m_m_salton_04`, `a_m_m_skater_01`, `a_m_y_beachvesp_01`, `a_m_y_eastsa_01`, `a_m_y_ktown_01`, `a_f_y_hippie_01`, `a_f_y_tourist_02`, `prop_golf_iron_01`

**Audio banks** (1) - `DLC_SECURITY/DLC_Sec_Payphone_Hit_Golf`

**Sounds** (2) - `Crush_Car`, `DLC_IE_Deliver_Vehicle_Scrapyard_Sounds`

**Texture dicts** (1) - `FIXER_MENU_BANNERS`

**Text labels** (12) - `STRING`, `CLO_SBM_B_6_1`, `46QOF421`, `NULL`, `89FNN447`, `14DAV022`, `10LUD998`, `BTRSW33T`, `65PZS928`, `MASKS_UNLOCK`, `FXFRAUD`, `68IEZ001`

**Scenarios** (1) - `WORLD_HUMAN_STAND_IMPATIENT`

**Decorators** (2) - `bombowner`, `bombdec`

**Hashed names** (1) - `A_F_Y_EASTSA_02_WHITE_PVG`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (105), `SET_PED_COMPONENT_VARIATION` (86), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (38), `NET_TO_PED` (36), `DOES_ENTITY_EXIST` (35), `IS_PED_IN_ANY_VEHICLE` (35), `GET_ENTITY_COORDS` (35), `SET_BIT` (34), `NET_TO_ENT` (26), `SET_PED_CONFIG_FLAG` (22), `IS_STRING_NULL_OR_EMPTY` (19), `IS_VEHICLE_SEAT_FREE` (18), `IS_PED_DEAD_OR_DYING` (17), `SET_PED_PROP_INDEX` (15), `DOES_BLIP_EXIST` (15), `NET_TO_VEH` (13), `IS_ENTITY_DEAD` (13), `SET_ENTITY_HEALTH` (11), `SET_PED_COMBAT_ATTRIBUTES` (11), `CLEAR_PED_TASKS` (11), `CLEAR_BIT` (11), `IS_PED_INJURED` (11), `GET_PLAYER_WANTED_LEVEL` (10), `SET_CURRENT_PED_WEAPON` (10), `GET_DISTANCE_BETWEEN_COORDS` (9), `VDIST2` (9), `GET_PED_CAUSE_OF_DEATH` (9), `SET_VEHICLE_DOOR_OPEN` (9), `SET_VEHICLE_RADIO_ENABLED` (9), `DISABLE_CONTROL_ACTION` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x3 · `0.7f` x2 · `-0.5f` x2 · `0.99f` x2 · `0.4f` x1 · `-0.2f` x1 · `-0.3f` x1 · `0.8f` x1 · `0.28f` x1 · `0.3f` x1 · `-416.1596f` x1 · `-1712.02f` x1 · `18.5053f` x1 · `253.225f` x1 · `0.1f` x1 · `1.5f` x1 · `0.5f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `bsa`, `sprt`, `hclr`, `scl`, `rad`, `typ`, `ibs`, `name`, `FXR_OT_LEAVE`, `GROUP_SNIPER`, `blp`, `veh`, `rot`, `FXR_BLIP_TAR`, `taxi`, `caddy`, `caddy2`, `MAX_NUM_SCENARIOS`, `grp`, `FXR_ENDS_BOX`, `					`

---

Source: `decompiled_scripts/fm_content_payphone_hit.c`
