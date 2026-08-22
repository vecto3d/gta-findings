# launcher_fanatic.c

System and infrastructure script. 1 anim dicts; 7 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 12,522 |
| Functions | 301 (10 unique, 291 shared) |
| Unique lines | 579 (4.6% of file) |

## Assets

**Animation dictionaries** (1) - `rcm_fanatic2`

**Animations** (2) - `rcm_fanatic2`, `ef_2_rcm__maryann_biking_cyclist`

**Models and props** (7) - `prop_beach_towel_01`, `prop_energy_drink`, `prop_freeweight_01`, `prop_freeweight_02`, `u_m_y_cyclist_01`, `prop_facgate_03_l`, `prop_facgate_03_r`

**Text labels** (5) - `MARYANN`, `NULL`, `FAN1AU`, `FAN2AU`, `FAN3AUD`

**Doors** (2) - `prop_facgate_03_l`, `prop_facgate_03_r`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (10), `SET_ENTITY_ROTATION` (5), `FREEZE_ENTITY_POSITION` (5), `GET_GAME_TIMER` (5), `TERMINATE_THIS_THREAD` (4), `SET_ENTITY_COORDS_NO_OFFSET` (4), `CREATE_OBJECT` (4), `PLAYER_PED_ID` (4), `REQUEST_MODEL` (3), `SET_ENTITY_QUATERNION` (3), `SET_MODEL_AS_NO_LONGER_NEEDED` (3), `WAIT` (2), `SET_PED_COMPONENT_VARIATION` (2), `DOES_OBJECT_OF_TYPE_EXIST_AT_COORDS` (2), `SET_STATE_OF_CLOSEST_DOOR_OF_TYPE` (2), `GET_STANDARD_BLIP_ENUM_ID` (1), `GET_WAYPOINT_BLIP_ENUM_ID` (1), `SET_THIS_IS_A_TRIGGER_SCRIPT` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (1), `CLEAR_AREA` (1), `CAN_REQUEST_ASSETS_FOR_CUTSCENE_ENTITY` (1), `SET_CUTSCENE_PED_COMPONENT_VARIATION_FROM_PED` (1), `SET_CUTSCENE_PED_PROP_VARIATION` (1), `CLEAR_AREA_OF_PEDS` (1), `ADD_SCENARIO_BLOCKING_AREA` (1), `GET_GROUND_Z_FOR_3D_COORD` (1), `SET_PED_PROP_INDEX` (1), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (1), `SET_PED_LOD_MULTIPLIER` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-915.6f` x2 · `6139.192f` x2 · `5.525f` x2 · `111.24f` x2 · `801.7148f` x2 · `1270.138f` x2 · `359.2855f` x2 · `802.9195f` x2 · `1280.92f` x2 · `360.7272f` x2 · `816.3f` x1 · `1275.61f` x1 · `359.5f` x1 · `744.7144f` x1 · `1254.726f` x1 · `357.0291f` x1 · `847.8754f` x1 · `1342.243f` x1 · `370.0352f` x1 · `2.52f` x1 · `-916.6389f` x1 · `6137.046f` x1 · `4.7157f` x1 · `1.7f` x1

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `FANATIC LAUNCHER RC`, `MaryAnnes_Friend`, `FAN1_AMB`, `FAN2_AMB`, `FAN3_AMB`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `Player out of range [TERMINATING]`, `Trying to set Mary Ann boyfriend component variation`, `rcmfanatic1`, `ef_1_rcm_mary_ann_streching_base`, `EF_1_RCM`, `Created initial scene`, `EF_3_RCM_CONCAT`, `rcmfanatic3`, `ef_3_rcm_loop_maryann`, `PUSHUP_BREATH`, `scorcher`, `EF_2_RCM`, `rcm_fanatic2`, `ef_2_rcm__maryann_biking_maryann`, `Playing Mary Ann's friend anim...`, `SCRIPT TERMINATING: Ending off-mission cutscene request`

---

Source: `decompiled_scripts/launcher_fanatic.c`
