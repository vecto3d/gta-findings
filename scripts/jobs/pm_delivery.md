# pm_delivery.c

Jobs script. 2 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 5,771 |
| Functions | 143 (18 unique, 125 shared) |
| Unique lines | 1,028 (17.8% of file) |

## Assets

**Models and props** (2) - `s_m_y_cop_01`, `g_m_y_salvagoon_02`

**Audio banks** (1) - `Deliveries`

**Sounds** (4) - `HUD_MINI_GAME_SOUNDSET`, `10_SEC_WARNING`, `BAR_DELIVER_BOOZE_RATTLE_MASTER`, `TIMER_STOP`

**Text labels** (2) - `NULL`, `PMDL`

**Relationship groups** (2) - `rghCriminal`, `rghCop`

**Vehicle mods** (2) - `benson`, `pony2`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_GAME_TIMER` (21), `PLAY_SOUND_FRONTEND` (16), `PLAYER_PED_ID` (12), `IS_PED_INJURED` (9), `IS_VEHICLE_TYRE_BURST` (8), `DOES_BLIP_EXIST` (8), `REMOVE_BLIP` (6), `IS_ENTITY_DEAD` (5), `PLAYER_ID` (5), `DOES_ENTITY_EXIST` (4), `IS_VEHICLE_DRIVEABLE` (4), `CREATE_PED_INSIDE_VEHICLE` (4), `REQUEST_MODEL` (4), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (4), `HAS_MODEL_LOADED` (4), `GET_MILLISECONDS_PER_GAME_MINUTE` (4), `GET_DISTANCE_BETWEEN_COORDS` (4), `ROUND` (4), `GET_ENTITY_HEALTH` (3), `SET_PED_KEEP_TASK` (3), `TASK_LEAVE_ANY_VEHICLE` (3), `IS_ENTITY_AT_ENTITY` (3), `IS_PED_IN_VEHICLE` (3), `SET_PED_COMBAT_ATTRIBUTES` (3), `CREATE_VEHICLE` (2), `SET_VEHICLE_EXTRA` (2), `ADD_RELATIONSHIP_GROUP` (2), `SET_RELATIONSHIP_BETWEEN_GROUPS` (2), `GIVE_WEAPON_TO_PED` (2), `SET_PED_RELATIONSHIP_GROUP_HASH` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`16.5f` x4

## Other strings

Literals whose consuming native was not classified:

`PMDL_TIM`, `player`, `PMDL_DMG`, `police4`, `TIMER_TIME`, `PMDL_REC`, `PMDL_OBJ`, `PMDL_LOC`, `PMDL_BCK`, `PMDL_TRUCK`, `PMDL_BTIM`, `PMDL_BCKT`, `benson`, `pony2`

---

Source: `decompiled_scripts/pm_delivery.c`
