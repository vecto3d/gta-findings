# carwash1.c

Jobs script. 9 models; 1 particle effects.

| | |
|---|---|
| Category | Jobs |
| Total lines | 40,202 |
| Functions | 410 (105 unique, 305 shared) |
| Unique lines | 4,194 (10.4% of file) |

## Assets

**Models and props** (9) - `prop_ld_test_01`, `prop_carwash_roller_vert`, `prop_carwash_roller_horz`, `prop_dumpster_01a`, `prop_dumpster_02a`, `prop_dumpster_02b`, `prop_dumpster_3a`, `prop_dumpster_4a`, `prop_dumpster_4b`

**Audio banks** (1) - `SCRIPT\CARWASH`

**Sounds** (8) - `CAR_WASH_SCENE`, `CARWASH_SOUNDS`, `BRUSHES_SPINNING`, `BRUSHES_MOVE`, `SPRAY`, `DRYER`, `SPRAY_CAR`, `BRUSHES_HIT_CAR`

**Particle effects** (1) - `ent_amb_car_wash`

**Text labels** (1) - `NULL`

**Scenarios** (2) - `DRIVE`, `WORLD_VEHICLE_DRIVE_SOLO`

**Decorators** (1) - `Carwash_Vehicle_Decorator`

**Scripts launched** (1) - `carwash1`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (98), `GET_GAME_TIMER` (40), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (39), `NETWORK_IS_GAME_IN_PROGRESS` (27), `GET_VEHICLE_PED_IS_IN` (26), `GET_ENTITY_MODEL` (26), `PLAYER_ID` (22), `GET_PED_IN_VEHICLE_SEAT` (18), `ABSF` (17), `DISABLE_CONTROL_ACTION` (17), `IS_PED_IN_ANY_VEHICLE` (15), `GET_ENTITY_COORDS` (14), `NETWORK_HAS_CONTROL_OF_ENTITY` (14), `IS_VEHICLE_EXTRA_TURNED_ON` (13), `SET_ENTITY_COLLISION` (12), `DOES_ENTITY_EXIST` (12), `SET_ENTITY_NO_COLLISION_ENTITY` (12), `GET_ENTITY_FORWARD_VECTOR` (12), `WAIT` (11), `SET_ENTITY_HEADING` (10), `GET_SHAPE_TEST_RESULT` (10), `PLAY_SOUND_FROM_ENTITY` (10), `GET_VEHICLE_MOD` (10), `START_PARTICLE_FX_LOOPED_ON_ENTITY` (9), `TIMESTEP` (9), `GET_SOUND_ID` (9), `SET_ENTITY_COORDS` (8), `DOES_VEHICLE_HAVE_ROOF` (8), `GET_MODEL_DIMENSIONS` (8), `TO_FLOAT` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x16 · `0.75f` x8 · `0.1f` x7 · `1.25f` x4 · `0.8f` x4 · `1.2f` x4 · `1.5f` x3 · `0.25f` x3 · `2.5f` x3 · `0.325f` x2 · `-2.16f` x2 · `-2.5f` x2 · `0.06625f` x2 · `1.48884f` x2 · `0.3f` x1 · `51.6073f` x1 · `-1401.665f` x1 · `28.4046f` x1 · `344.3805f` x1 · `0.05f` x1 · `-1.96f` x1 · `1.96f` x1 · `0.0625f` x1 · `0.03125f` x1

## Other strings

Literals whose consuming native was not classified:

`ent_amb_car_wash_jet`, `seat_dside_f`, `ent_amb_car_wash_steam`, `ent_amb_car_wash_jet_soap`, `SCRIPT\CARWASH`, `service_spend_carwash`, `zeno`, `btype`, `btype3`, `regina`, `banshee`, `peyote`, `coquette`, `manana`, `mesa`, `voltic`, `bobcatxl`, `ruiner`, `yosemite3`, `rt3000`, `brioso3`, `zr350`, `driftzr350`, `krieger`, `entity3`, `boor`, `ambulance`, `armytrailer`, `airtug`, `bifta`

---

Source: `decompiled_scripts/carwash1.c`
