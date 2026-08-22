# launcher_racing.c

System and infrastructure script. 1 anim dicts; 4 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 9,586 |
| Functions | 233 (40 unique, 193 shared) |
| Unique lines | 2,405 (25.1% of file) |

## Assets

**Animation dictionaries** (1) - `random@street_race`

**Animations** (2) - `random@street_race`, `_streetracer_wait_loop`

**Models and props** (4) - `a_m_y_hipster_02`, `a_m_y_jetski_01`, `A_M_Y_RACER_01_WHITE_MINI_01`, `a_f_y_hipster_02`

**Text labels** (2) - `SPRACE`, `NULL`

**Scenarios** (2) - `WORLD_VEHICLE_PARK_PERPENDICULAR_NOSE_IN`, `WORLD_VEHICLE_PARK_PARALLEL`

**Scripts launched** (2) - `mission_Race`, `appinternet`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (38), `DOES_ENTITY_EXIST` (25), `GET_GAME_TIMER` (19), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (9), `IS_PLAYER_PLAYING` (9), `SET_BIT` (9), `HAS_MODEL_LOADED` (9), `PLAYER_ID` (8), `IS_ENTITY_DEAD` (8), `SET_PED_KEEP_TASK` (7), `GET_RADIO_STATION_NAME` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `IS_PED_IN_VEHICLE` (6), `TASK_VEHICLE_DRIVE_WANDER` (6), `WAIT` (6), `GET_ENTITY_MODEL` (6), `IS_VEHICLE_TYRE_BURST` (6), `OPEN_SEQUENCE_TASK` (5), `CLOSE_SEQUENCE_TASK` (5), `TASK_PERFORM_SEQUENCE` (5), `SET_BOAT_ANCHOR` (5), `SET_INPUT_EXCLUSIVE` (5), `GET_ENTITY_COORDS` (5), `TASK_PLAY_ANIM` (5), `CREATE_VEHICLE` (5), `SET_VEHICLE_ENGINE_ON` (5), `TASK_PAUSE` (4), `TASK_WANDER_STANDARD` (4), `IS_PED_INJURED` (4), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`374.0083f` x1 · `279.5919f` x1 · `102.3306f` x1 · `0.5f` x1

## Other strings

Literals whose consuming native was not classified:

`seashark`, `dm_test_20`, `dm_test_18`, `dm_test_2`, `dm_test_4`, `dm_test_5`, `dm_test_16`, `dm_test_13`, `dm_test_15`, `dm_test_24`, `STREET_NA_BIKE`, `STREET_NA_CAR`, `_car_b_chatting_female`, `_car_b_chatting_male`, `feltzer2`, `qLp8OsaeTkCjzhK0SZoRVA`, `JhV_7Ir4ekSQLafj22vFkg`, `Fuc2Yl2sukOrORoMo1YJ1A`, `aNlcpqEkhUytgK-8IMbTYQ`, `9aLp9VEnME25Mp_6XZaw0A`, `lT9gI2mfrkGDhiW1lSlhbw`, `YxiNucGMGEu4lCKqizI2lA`, `szYNFSberECI5goiWsh1bw`, `nZ4p_4_F0EOFyZa2yKEHGA`, `bati`, `SEA_NA_VEH`, `SEA_NA_VEH2`, `STREET_NA_COP`, `ambulance`

---

Source: `decompiled_scripts/launcher_racing.c`
