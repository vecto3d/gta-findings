# finalec2.c

Heists script. 3 anim dicts; 16 models; 1 particle effects.

| | |
|---|---|
| Category | Heists |
| Total lines | 138,828 |
| Functions | 1,119 (202 unique, 917 shared) |
| Unique lines | 16,218 (11.7% of file) |

## Assets

**Animation dictionaries** (3) - `veh@bike@police@front@base`, `reaction@gunfire@intro_v1`, `reaction@gunfire@runs_v1`

**Animations** (7) - `Death_Steve`, `Death_CamMan`, `veh@bike@police@front@base`, `still`, `LOUNGE_LOOP_DEV`, `LOUNGE_OUTRO_BOX`, `LOUNGE_OUTRO_DEV`

**Models and props** (16) - `cs_devin`, `p_devin_box_01_s`, `cs_stevehains`, `s_m_y_grip_01`, `a_f_y_hipster_04`, `prop_v_cam_01`, `g_m_y_ballaorig_01`, `s_m_y_cop_01`, `s_m_y_blackops_01`, `prop_phone_ing_02`, `prop_bskball_01`, `prop_ld_ferris_wheel`, `prop_ferris_car_01`, `prop_devin_box_dummy_01`, `g_m_m_chigoon_02`, `prop_cs_tablet`

**Sounds** (7) - `1st_Person_Transition`, `PLAYER_SWITCH_CUSTOM_SOUNDSET`, `FINALE_C2_SOUNDS`, `FINALE_C2_DEVIN_INSIDE_TRUNK_MASTER`, `CAR_WHEELS`, `END_CREDITS_SCENE`, `Car_Push_Flex`

**Particle effects** (1) - `scr_finale2_blood_entry`

**Text labels** (23) - `FRANKLIN`, `MICHAEL`, `FINC1AU`, `DEVIN`, `CREDIT`, `MERRYGUARD2`, `TREVOR`, `GANGBANGER1`, `CAMERAMAN`, `LAMAR`, `CHATCAU`, `NULL`, `TORNADO`, `LESTER`, `FINC`, ` M0NIED `, `F3TRIAD1`, `CHENGSR`, `GANGBANGER2`, `TEAMMATE`, `STRETCH`, `STEVE`, `BADSTRING`

**Scenarios** (1) - `WORLD_HUMAN_SMOKING`

**Waypoint recordings** (1) - `finc24`

**Relationship groups** (4) - `player`, `Triad group`, `Merryweather group`, `Gangster group`

**Timecycle modifiers** (1) - `scanline_cam_cheap`

**Vehicle mods** (13) - `tornado2`, `tornado3`, `tornado4`, `voodoo2`, `baller`, `baller2`, `granger`, `cavalcade2`, `landstalker`, `police`, `police2`, `police3`, `policeb`

**Hashed names** (4) - `HIDE_PHONE`, `THROW_BBALL`, `DROP_BALL`, `DRAW_GUN`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (292), `IS_PED_INJURED` (170), `GET_GAME_TIMER` (147), `DOES_ENTITY_EXIST` (114), `IS_VEHICLE_DRIVEABLE` (83), `PLAYER_ID` (68), `GET_ENTITY_COORDS` (59), `DOES_BLIP_EXIST` (42), `WAIT` (38), `IS_ENTITY_AT_ENTITY` (36), `REMOVE_BLIP` (28), `DELETE_PED` (24), `ENABLE_DISPATCH_SERVICE` (22), `IS_SYNCHRONIZED_SCENE_RUNNING` (21), `SET_PED_COMPONENT_VARIATION` (21), `IS_PED_IN_ANY_VEHICLE` (20), `REGISTER_ENTITY_FOR_CUTSCENE` (20), `IS_ENTITY_AT_COORD` (20), `SET_VEHICLE_MODEL_IS_SUPPRESSED` (20), `DELETE_OBJECT` (19), `FREEZE_ENTITY_POSITION` (19), `SET_PED_CONFIG_FLAG` (18), `DISABLE_CONTROL_ACTION` (17), `SET_ENTITY_COORDS` (17), `IS_PED_IN_VEHICLE` (16), `GET_DISTANCE_BETWEEN_COORDS` (16), `SET_PED_INTO_VEHICLE` (16), `GET_SYNCHRONIZED_SCENE_PHASE` (15), `SET_ENTITY_HEADING` (15), `GET_PLAYER_WANTED_LEVEL` (14)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.98f` x7 · `-1577.772f` x7 · `5157.833f` x7 · `18.7777f` x7 · `0.4f` x4 · `-2649.059f` x4 · `1872.454f` x4 · `159.7203f` x4 · `-1663.9f` x3 · `0.3f` x3 · `-202.7803f` x3 · `-1509.742f` x3 · `30.61494f` x3 · `-1878.221f` x2 · `-1214.366f` x2 · `-100.0166f` x2 · `-1479.246f` x2 · `-977.3813f` x2 · `100.1158f` x2 · `159.1507f` x2 · `-0.25f` x2 · `3.5f` x2 · `2.5f` x2 · `0.89f` x2

## Other strings

Literals whose consuming native was not classified:

`Devin`, `AllowScriptedSpeechInSlowMo`, `LOSE_WANTED`, `Trevor`, `Michael`, `Franklin`, `player`, `CamPushInNeutral`, `ferris_finale_Anim`, `FC2_KIDDEV`, `FC2_KILLTRI`, `error`, `Steve_FBI`, `Grip_beside_director`, `FC2_KILLSTE`, `FC2_KILLSTR`, `Trevor_Cliff_Car`, `seat_dside_f`, `HAND_SHAKE`, `FINC2_OUTSIDE_DEVINS`, `thisSwitchCam`, `FINC1_WF`, `FINC1_WT`, `FINC1_WM`, `BLIP_VEH`, `finc23`, `finc22`, `finc21`, `FINC1_CHGF`, `FC2_ESCTRI`

---

Source: `decompiled_scripts/finalec2.c`
