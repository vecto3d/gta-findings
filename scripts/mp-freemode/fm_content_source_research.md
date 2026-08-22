# fm_content_source_research.c

MP freemode script. 4 models; 2 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 482,987 |
| Functions | 10,061 (196 unique, 9,865 shared) |
| Unique lines | 11,905 (2.5% of file) |

## Assets

**Models and props** (4) - `u_m_y_juggernaut_01`, `s_m_y_swat_01`, `s_m_y_hwaycop_01`, `u_m_y_juggernaut_02`

**Sounds** (3) - `RESEARCH_DATA_JUGGERNAUT_scene`, `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`

**Particle effects** (2) - `scr_vehicle_damage_smoke`, `damage`

**Text labels** (4) - `NULL`, `SM2AGAU`, `AGENT14`, `46BCJ212`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (98), `SET_BIT` (18), `PLAYER_ID` (9), `SET_PED_CONFIG_FLAG` (8), `SET_PED_COMPONENT_VARIATION` (8), `GET_PLAYER_WANTED_LEVEL` (7), `DISABLE_CONTROL_ACTION` (5), `CLEAR_PED_TASKS` (5), `GET_RANDOM_INT_IN_RANGE` (5), `GET_ENTITY_COORDS` (4), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (4), `SET_ENTITY_HEALTH` (4), `IS_PED_IN_ANY_VEHICLE` (3), `STOP_PED_SPEAKING` (3), `NETWORK_IS_PARTICIPANT_ACTIVE` (3), `SET_PED_PROP_INDEX` (3), `SET_PED_COMBAT_ATTRIBUTES` (3), `SET_ENTITY_CAN_BE_DAMAGED_BY_RELATIONSHIP_GROUP` (3), `HIDE_HUD_COMPONENT_THIS_FRAME` (2), `GET_CURRENT_PED_WEAPON` (2), `SET_CURRENT_PED_WEAPON` (2), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (2), `NETWORK_IS_GAME_IN_PROGRESS` (2), `NETWORK_GET_NUM_PARTICIPANTS` (2), `NETWORK_HASH_FROM_PLAYER_HANDLE` (2), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (2), `INT_TO_PARTICIPANTINDEX` (2), `IS_PLAYER_PLAYING` (2), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (2), `PARTICIPANT_ID_TO_INT` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-0.4f` x2 · `0.9f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `bsa`, `sprt`, `hclr`, `scl`, `ibs`, `typ`, `blp`, `rot`, `rad`, `grp`, `veh`, `totyp`, `toid`, `vmx`, `fwd`, `tri`, `ita`, `vce`, `MAX_NUM_TRANSITIONS`, `GEN_`, `fmbs`

---

Source: `decompiled_scripts/fm_content_source_research.c`
