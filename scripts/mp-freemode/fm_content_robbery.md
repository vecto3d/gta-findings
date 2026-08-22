# fm_content_robbery.c

MP freemode script. 3 anim dicts; 13 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 478,635 |
| Functions | 9,799 (282 unique, 9,517 shared) |
| Unique lines | 11,624 (2.4% of file) |

## Assets

**Animation dictionaries** (3) - `anim@scripted@player@freemode@tun_prep_ig1_grab_low@heeled@`, `anim@scripted@player@freemode@tun_prep_ig1_grab_low@male@`, `anim@scripted@player@fix_agy_ig5_handover@male@`

**Models and props** (13) - `s_f_m_fembarber`, `u_m_y_tattoo_01`, `s_m_m_hairdress_01`, `s_f_y_shop_mid`, `s_f_y_shop_low`, `s_f_m_shop_high`, `V_39_ShopRm`, `V_39_StairsRm`, `V_66_ShopRm`, `V_66_BackRm`, `V_68_GasRm`, `V_68_BackRm`, `V_68_Toilets`

**Text labels** (3) - `WT_PIST_CBT`, `NULL`, `WEAPON_UNLOCK`

**Interiors and entity sets** (4) - `v_methlab`, `v_shop_247`, `v_gen_liquor`, `v_gasstation`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (114), `DATADICT_GET_ARRAY` (67), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (11), `GET_ENTITY_COORDS` (8), `DISABLE_CONTROL_ACTION` (7), `IS_STRING_NULL_OR_EMPTY` (7), `GET_SYNCHRONIZED_SCENE_PHASE` (6), `DOES_BLIP_EXIST` (6), `DOES_ENTITY_EXIST` (6), `SET_PED_PROP_INDEX` (6), `CLEAR_PED_TASKS` (5), `SET_ENTITY_VISIBLE` (5), `SET_ENTITY_INVINCIBLE` (5), `NETWORK_IS_PARTICIPANT_ACTIVE` (5), `GET_RANDOM_INT_IN_RANGE` (5), `NET_TO_ENT` (5), `NET_TO_PED` (5), `GET_INTERIOR_AT_COORDS_WITH_TYPE` (5), `SET_BIT` (4), `IS_NEW_LOAD_SCENE_ACTIVE` (4), `IS_ENTITY_DEAD` (3), `REMOVE_BLIP` (3), `SET_ENTITY_COMPLETELY_DISABLE_COLLISION` (3), `FREEZE_ENTITY_POSITION` (3), `GET_ENTITY_MODEL` (3), `DOES_CAM_EXIST` (3), `CREATE_CAMERA` (3), `INT_TO_PARTICIPANTINDEX` (3), `VDIST2` (3), `POW` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x2 · `1.5f` x1 · `0.26f` x1 · `0.62f` x1 · `0.366f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `head`, `int`, `num`, `rot`, `ibs`, `bsa`, `MAX_NUM_SCENARIOS`, `grp`, `veh`, `sprt`, `hclr`, `scl`, `fcs`, `blp`, `fmbs`, `crt`, `MAX_NUM_TRANSITIONS`, `plnkp`, `asi`, `mvmt`, `mrd`, `wpn`

---

Source: `decompiled_scripts/fm_content_robbery.c`
