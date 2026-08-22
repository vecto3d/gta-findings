# launcher_nigel.c

System and infrastructure script. 1 anim dicts; 18 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 15,584 |
| Functions | 325 (23 unique, 302 shared) |
| Unique lines | 1,366 (8.8% of file) |

## Assets

**Animation dictionaries** (1) - `mini@golf`

**Animations** (18) - `base`, `idle_speedo`, `rcmnigel1`, `swing_a_mark`, `swing_b_mark`, `idle_a_friend_watching`, `dexy_stay_there`, `price_tag`, `such_a_good`, `this_looks`, `who_would`, `Swimming_Idle`, `base_girl`, `idle_gardener`, `BASE_02_Willie`, `BASE_02_GIRL`, `base_nigel`, `base_mrs_thornhill`

**Models and props** (18) - `u_m_m_aldinapoli`, `a_f_y_bevhills_03`, `s_m_y_doorman_01`, `s_m_m_bouncer_01`, `prop_golf_wood_01`, `s_m_m_highsec_01`, `u_m_m_markfost`, `a_m_y_golfer_01`, `prop_golf_bag_01`, `ig_kerrymcintosh`, `a_c_rottweiler`, `ig_tylerdix`, `a_f_y_beach_01`, `s_m_m_gardener_01`, `prop_nigel_bag_pickup`, `u_m_m_willyfist`, `a_m_y_vinewood_04`, `a_m_y_gay_01`

**Audio banks** (1) - `CAR_TRUNK_THUMPS`

**Sounds** (1) - `TRUNK_THUMPS`

**Speech contexts** (2) - `NIGE3_CXAA`, `DINAPOLI`

**Text labels** (7) - `NIGEL`, `28BNT310`, `NULL`, `NIG1AAU`, `MRSTHORNHILL`, `NIG2AUD`, `NIGE3AU`

**Scenarios** (3) - `WORLD_HUMAN_GUARD_STAND`, `WORLD_HUMAN_CLIPBOARD`, `WORLD_VEHICLE_DRIVE_SOLO`

**Interiors and entity sets** (1) - `v_rockclub`

**Vehicle mods** (1) - `gauntlet`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (40), `TASK_PLAY_ANIM` (15), `DOES_ENTITY_EXIST` (9), `SET_SCENARIO_TYPE_ENABLED` (9), `PLAYER_PED_ID` (8), `CREATE_PED` (8), `HAS_ANIM_DICT_LOADED` (8), `GET_RANDOM_INT_IN_RANGE` (7), `REQUEST_MODEL` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `REQUEST_ANIM_DICT` (7), `GET_GAME_TIMER` (6), `SET_VEHICLE_COLOURS` (6), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (6), `CLEAR_AREA` (5), `SET_VEHICLE_DOORS_LOCKED` (5), `REMOVE_SCENARIO_BLOCKING_AREA` (5), `CLEAR_PED_NON_CREATION_AREA` (5), `ADD_SCENARIO_BLOCKING_AREA` (5), `SET_PED_NON_CREATION_AREA` (5), `SET_PED_MODEL_IS_SUPPRESSED` (5), `SET_ALL_VEHICLE_GENERATORS_ACTIVE_IN_AREA` (5), `TASK_SYNCHRONIZED_SCENE` (5), `TERMINATE_THIS_THREAD` (4), `SET_DOOR_ALLOWED_TO_BE_BROKEN_OFF` (4), `ATTACH_ENTITY_TO_ENTITY` (4), `CLEAR_AREA_OF_PEDS` (4), `SET_ENTITY_ONLY_DAMAGED_BY_PLAYER` (4), `SET_VEHICLE_NUMBER_PLATE_TEXT` (3), `SET_VEHICLE_NUMBER_PLATE_TEXT_INDEX` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-577.274f` x5 · `270.6505f` x5 · `-543.1793f` x5 · `315.2973f` x5 · `-1073.19f` x5 · `342.05f` x5 · `63.32832f` x5 · `-966.24f` x5 · `411.05f` x5 · `84.82043f` x5 · `0.5f` x3 · `-1100.5f` x3 · `789.8f` x3 · `164.34f` x3 · `-1035.73f` x3 · `365.44f` x3 · `68.91f` x3 · `-1096.855f` x3 · `67.6858f` x3 · `52.952f` x3 · `-1289.86f` x2 · `29.16f` x2 · `-1.8f` x2 · `0.2f` x2

## Other strings

Literals whose consuming native was not classified:

`SCRIPT TERMINATED`, `base_nigel`, `NIG1A_AMB`, `RC NIGEL`, `rcmnigel1`, `base_mrs_thornhill`, `premier`, `Force cleanup [TERMINATING]`, `Relinquishing candidate id...`, `Player out of range [TERMINATING]`, `Nigel 2 : set Di Napoli's cutscene trousers variation in launcher`, `NIG2_AMB`, `NIGEL3_AMB`, `Player damaged the N1D peds but it's not safe to trigger the mission!`, `Player killed a N1D ped but it's not safe to trigger the mission!`, `start conversation`, `conversation ended`, `pause conversation`, `unpause conversation`, `Al_DiNapoli`, `Created initial scene`, `NMT_3_RCM`, `rcmnigel3`, `base`, `NI3_LNCH_CELEB`, `dubsta`, `NMT_2_RCM`, `rcmnigel2`, `caddy`, `rcmnigel1d`

---

Source: `decompiled_scripts/launcher_nigel.c`
