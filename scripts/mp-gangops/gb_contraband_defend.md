# gb_contraband_defend.c

MP gang ops script. 15 models.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 416,902 |
| Functions | 7,631 (143 unique, 7,488 shared) |
| Unique lines | 17,139 (4.1% of file) |

## Assets

**Models and props** (15) - `g_m_m_armgoon_01`, `g_m_m_mexboss_01`, `g_m_y_korean_02`, `s_m_y_cop_01`, `s_f_y_cop_01`, `s_m_y_swat_01`, `s_m_m_fiboffice_01`, `s_m_y_sheriff_01`, `s_f_y_sheriff_01`, `s_m_y_ranger_01`, `s_f_y_ranger_01`, `s_m_y_blackops_01`, `s_m_m_armoured_01`, `s_m_y_pilot_01`, `s_m_m_fibsec_01`

**Audio banks** (1) - `ALARM_BELL_02`

**Sounds** (2) - `Bell_02`, `ALARMS_SOUNDSET`

**Text labels** (3) - `COP`, `NULL`, `EXCALAU`

**Relationship groups** (2) - `relDefendPlayer`, `relDefendAI`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (114), `PARTICIPANT_ID_TO_INT` (83), `NET_TO_PED` (69), `PLAYER_ID` (56), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (51), `NET_TO_VEH` (41), `PLAYER_PED_ID` (23), `ADD_SCENARIO_BLOCKING_AREA` (22), `INT_TO_PLAYERINDEX` (19), `CLEAR_BIT` (14), `DOES_BLIP_EXIST` (14), `SET_RELATIONSHIP_BETWEEN_GROUPS` (14), `GET_ENTITY_COORDS` (13), `TO_FLOAT` (12), `CLEAR_HELP` (9), `IS_PED_INJURED` (8), `REMOVE_BLIP` (8), `SET_PED_COMBAT_ATTRIBUTES` (8), `NETWORK_IS_PLAYER_ACTIVE` (8), `GET_PED_INDEX_FROM_ENTITY_INDEX` (8), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (7), `INT_TO_PARTICIPANTINDEX` (7), `NETWORK_IS_PLAYER_A_PARTICIPANT` (7), `TRIGGER_MUSIC_EVENT` (7), `DOES_ENTITY_EXIST` (7), `GET_SCRIPT_TASK_STATUS` (7), `NETWORK_IS_GAME_IN_PROGRESS` (6), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (6), `IS_STRING_NULL_OR_EMPTY` (6), `ARE_STRINGS_EQUAL` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.6f` x2 · `0.01f` x2 · `31.1862f` x1 · `-2594.657f` x1 · `68.0247f` x1 · `-2551.956f` x1 · `-1109.664f` x1 · `-1297.61f` x1 · `-1074.653f` x1 · `-1223.725f` x1 · `859.394f` x1 · `-1082.382f` x1 · `914.3219f` x1 · `-1008.526f` x1 · `240.8218f` x1 · `-1997.975f` x1 · `243.8696f` x1 · `-1933.894f` x1 · `-451.6602f` x1 · `171.9769f` x1 · `-397.3188f` x1 · `222.9419f` x1 · `-1059.294f` x1 · `-2044.054f` x1

## Other strings

Literals whose consuming native was not classified:

`DCONTRA_OBJ2`, `DCONTRA_OBJ`, `DCONTRA_OBJ4`, `DCONTRA_OBJ3`, `DCONTRA_TOBJ3`, `DCONTRA_WOBJ`, `BIGM_DEFEND`, `BIGM_DCLOST`, `DCONTRA_HLP1`, `DCONTRA_HLP2`, `DCONTRA_HLPCR`, `DCONTRA_HLPVCR`, `mule`, `GB_WORK_END`, `DCONTRA_TOBJ2`, `BIGM_CONTRALS`, `DisableFlightMusic`, `WantedMusicDisabled`, `DCONTRA_HUD2`, `DCONTRA_TOBJ`, `BIGM_DEFEND3`, `BIGM_SECURED`, `speedo`, `burrito3`, `gburrito2`, `EXEC1_UNDER_ATTACK_START`, `EXEC1_DEFEND_FLEEING_START`, `EXEC1_UNDER_ATTACK_ARRIVE_SMA`, `EXEC1_UNDER_ATTACK_STOP`

---

Source: `decompiled_scripts/gb_contraband_defend.c`
