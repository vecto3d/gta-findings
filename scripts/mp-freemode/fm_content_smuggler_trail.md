# fm_content_smuggler_trail.c

MP freemode script. 4 anim dicts.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 472,224 |
| Functions | 9,616 (141 unique, 9,475 shared) |
| Unique lines | 9,796 (2.1% of file) |

## Assets

**Animation dictionaries** (4) - `AMB@MEDIC@STANDING@TENDTODEAD@ENTER`, `AMB@MEDIC@STANDING@TENDTODEAD@EXIT`, `ANIM@SCRIPTED@PLAYER@FREEMODE@TUN_PREP_IG1_GRAB_LOW@HEELED@`, `ANIM@SCRIPTED@PLAYER@FREEMODE@TUN_PREP_IG1_GRAB_LOW@MALE@`

**Sounds** (2) - `PICKUP_DEFAULT`, `HUD_FRONTEND_STANDARD_PICKUPS_SOUNDSET`

**Text labels** (3) - `NULL`, `ENTER`, `EXIT`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (67), `DISABLE_CONTROL_ACTION` (5), `CLEAR_PED_TASKS` (5), `NETWORK_IS_PARTICIPANT_ACTIVE` (4), `GET_RANDOM_INT_IN_RANGE` (4), `GET_DISTANCE_BETWEEN_COORDS` (4), `DOES_PARTICLE_FX_LOOPED_EXIST` (4), `STOP_PARTICLE_FX_LOOPED` (4), `SET_BIT` (3), `INT_TO_PARTICIPANTINDEX` (3), `GET_ENTITY_COORDS` (3), `PLAYER_PED_ID` (3), `DOES_ENTITY_EXIST` (3), `IS_ENTITY_PLAYING_ANIM` (3), `GET_ENTITY_ANIM_CURRENT_TIME` (3), `NETWORK_IS_GAME_IN_PROGRESS` (2), `CLEAR_BIT` (2), `NETWORK_HASH_FROM_PLAYER_HANDLE` (2), `IS_MODEL_A_VEHICLE` (2), `NETWORK_GET_MAX_NUM_PARTICIPANTS` (2), `NETWORK_GET_PLAYER_INDEX` (2), `IS_PLAYER_PLAYING` (2), `NETWORK_IS_PLAYER_A_PARTICIPANT` (2), `NETWORK_GET_NUM_PARTICIPANTS` (2), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (2), `PARTICIPANT_ID_TO_INT` (2), `IS_PED_IN_ANY_VEHICLE` (2), `PLAY_SOUND_FRONTEND` (2), `DELETE_OBJECT` (2), `HIDE_HUD_COMPONENT_THIS_FRAME` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.95f` x1 · `0.32f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `head`, `int`, `num`, `veh`, `rot`, `bsa`, `ibs`, `grp`, `sprt`, `hclr`, `scl`, `MAX_NUM_TRANSITIONS`, `blp`, `fcs`, `fmbs`, `crt`, `wpn`, `scen`, `anim`, `asi`, `mvmt`, `mrd`

---

Source: `decompiled_scripts/fm_content_smuggler_trail.c`
