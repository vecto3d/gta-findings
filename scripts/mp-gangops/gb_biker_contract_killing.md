# gb_biker_contract_killing.c

MP gang ops script. 1 anim dicts; 13 models.

| | |
|---|---|
| Category | MP gang ops |
| Total lines | 486,447 |
| Functions | 8,869 (170 unique, 8,699 shared) |
| Unique lines | 17,502 (3.6% of file) |

## Assets

**Animation dictionaries** (1) - `mini@prostitutes@sexnorm_veh`

**Models and props** (13) - `g_m_y_lost_01`, `a_m_y_beachvesp_02`, `a_f_m_beach_01`, `s_m_m_highsec_02`, `prop_woodpile_03a`, `prop_boombox_01`, `PROP_HUMAN_MOVIE_STUDIO_LIGHT`, `u_f_y_bikerchic`, `u_m_y_prisoner_01`, `u_m_m_filmdirector`, `prop_to_sit_alt_prostitute`, `prop_to_sit_male`, `prop_to_sit_prostitute`

**Text labels** (4) - `COP`, `NULL`, `MALCOLM`, `BPMALAU`

**Scenarios** (1) - `WORLD_HUMAN_HANG_OUT_STREET`

**Decorators** (2) - `MPBitset`, `Not_Allow_As_Saved_Veh`

**Relationship groups** (1) - `relContractKiller`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (56), `PLAYER_ID` (28), `GET_SCRIPT_TASK_STATUS` (18), `SET_BIT` (17), `SET_PED_DEFAULT_COMPONENT_VARIATION` (16), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (14), `GET_ENTITY_COORDS` (14), `PLAYER_PED_ID` (14), `PARTICIPANT_ID` (14), `SET_RELATIONSHIP_BETWEEN_GROUPS` (14), `PARTICIPANT_ID_TO_INT` (13), `SET_PED_PROP_INDEX` (13), `NET_TO_PED` (12), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (11), `DOES_BLIP_EXIST` (10), `SET_PED_COMBAT_ATTRIBUTES` (9), `VDIST2` (8), `IS_PED_INJURED` (7), `NET_TO_VEH` (7), `CLEAR_PED_TASKS` (6), `REMOVE_BLIP` (6), `NETWORK_IS_PARTICIPANT_ACTIVE` (5), `GET_PLAYER_PED` (5), `IS_ENTITY_PLAYING_ANIM` (5), `CLEAR_HELP` (5), `TASK_PLAY_ANIM` (5), `SET_BLIP_NAME_FROM_TEXT_FILE` (5), `IS_VEHICLE_DRIVEABLE` (4), `NETWORK_DOES_NETWORK_ID_EXIST` (4), `CLEAR_AREA` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.7f` x2 · `0.01f` x1 · `7.5f` x1

## Other strings

Literals whose consuming native was not classified:

`WORLD_HUMAN_DRINKING`, `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_GUARD_STAND`, `BLIP_BAT`, `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_STAND_IMPATIENT`, `coach`, `cognoscenti`, `BCK_OBJ0b`, `WORLD_HUMAN_SEAT_LEDGE`, `WORLD_HUMAN_PARTYING`, `mp_m_g_vagfun_01`, `caddy`, `BKR_CONTRACT_KILL_TARGET`, `BKR_CONTRACT_KILL_START`, `DisableFlightMusic`, `INVALID WEAPON!`, `INVALID TARGET!`, `BK_WINNER`, `BCK_SH_BIG`, `BCK_SH_PASSE`, `BK_OVER`, `BK_TIME`, `BCK_BL_TAR`, `WORLD_HUMAN_WINDOW_SHOP_BROWSE`, `WORLD_HUMAN_STRIP_WATCH_STAND`, `WORLD_HUMAN_GOLF_PLAYER`, `WORLD_HUMAN_SMOKING_POT`, `CODE_HUMAN_MEDIC_KNEEL`, `WORLD_HUMAN_CLIPBOARD`

---

Source: `decompiled_scripts/gb_biker_contract_killing.c`
