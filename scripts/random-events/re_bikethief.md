# re_bikethief.c

Random events script. 6 anim dicts; 2 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 8,261 |
| Functions | 239 (31 unique, 208 shared) |
| Unique lines | 1,262 (15.3% of file) |

## Assets

**Animation dictionaries** (6) - `RANDOM@BICYCLE_THIEF@BASE`, `RANDOM@BICYCLE_THIEF@ASK_HELP`, `RANDOM@BICYCLE_THIEF@IDLE_A`, `RANDOM@BICYCLE_THIEF@GET_OFF_BIKE`, `RANDOM@BICYCLE_THIEF@RETURN_FRONT`, `RANDOM@BICYCLE_THIEF@THANKS`

**Animations** (8) - `IDLE_B`, `IDLE_A`, `IDLE_C`, `RETURNING_FRONT_B`, `RETURNING_FRONT_A`, `THANKS_A`, `BIKE_BACK_NOW_A`, `base`

**Models and props** (2) - `g_m_y_strpunk_01`, `a_m_y_beachvesp_01`

**Sounds** (1) - `RE_CAR_STEAL_SCENE`

**Speech contexts** (2) - `G_M_Y_StreetPunk_01_BLACK_MINI_03`, `A_M_Y_BeachVesp_01_LATINO_MINI_01`

**Text labels** (5) - `REBTHAU`, `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Scenarios** (1) - `WORLD_HUMAN_STAND_MOBILE`

**Vehicle recordings** (1) - `RE_BikeThief2`

**Relationship groups** (2) - `re_bikethief_relGroupVictim`, `re_bikethief_relGroupThief`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (65), `IS_PED_IN_VEHICLE` (16), `GET_GAME_TIMER` (14), `IS_ENTITY_AT_ENTITY` (13), `TASK_PLAY_ANIM` (13), `PLAYER_ID` (8), `IS_PED_INJURED` (7), `SET_PED_KEEP_TASK` (7), `SET_MODEL_AS_NO_LONGER_NEEDED` (7), `IS_PED_RAGDOLL` (6), `SET_VEHICLE_MOD` (6), `SET_PED_CONFIG_FLAG` (6), `REQUEST_ANIM_DICT` (6), `HAS_ANIM_DICT_LOADED` (6), `REMOVE_ANIM_DICT` (6), `TERMINATE_THIS_THREAD` (5), `WAIT` (5), `IS_PED_FACING_PED` (5), `IS_PED_GETTING_UP` (5), `TASK_LOOK_AT_ENTITY` (5), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (5), `GET_PED_BONE_COORDS` (5), `TOGGLE_VEHICLE_MOD` (5), `SET_RELATIONSHIP_BETWEEN_GROUPS` (4), `TASK_ENTER_VEHICLE` (4), `IS_ENTITY_IN_ANGLED_AREA` (4), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (4), `IS_VEHICLE_DRIVEABLE` (4), `VDIST2` (3), `SUPPRESS_CRIME_THIS_FRAME` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x3 · `472.195f` x2 · `-1974.902f` x2 · `18.57787f` x2 · `572.7468f` x2 · `-1921.216f` x2 · `28.68633f` x2 · `421.92f` x1 · `-1930.95f` x1 · `23.18f` x1 · `769.3f` x1 · `-151.66f` x1 · `73.79f` x1 · `-1923.93f` x1 · `254.48f` x1 · `85.7f` x1 · `-1875.858f` x1 · `262.3736f` x1 · `82.96029f` x1 · `-1927.379f` x1 · `234.7951f` x1 · `90.71558f` x1 · `50.25f` x1 · `0.5f` x1

## Other strings

Literals whose consuming native was not classified:

`player`, `scorcher`, `REBTH_RUNSOF`, `REBTH_TAUNT`, `REBTH_THX2`, `REBTH_THX3`, `REBTH_GONE`, `bati`, `REBTH_ATTACK`, `REBTH_HANGAR`, `REBTH_APEBIK`, `REBTH_PLASTE`, `REBTH_GETOFF`, `REBTH_THANKS`, `REBTH_INAIR`, `REBTH_HELP2X`, `REBTH_HELP2`, `REBTH_RESPM`, `REBTH_RESPF`, `REBTH_RESPT`, `REBTH_THX2X`, `REBTH_THX3X`, `REBTH_GONEX`, `RE_CAR_STEAL_STOLEN_VEHICLE`, `BThief`, `BThiefVictim`, `REBTH_HELPX`, `REBTH_HELP`, `I_CANT_CATCH_HIM_ON_FOOT`, `REBTH_HLPBX`

---

Source: `decompiled_scripts/re_bikethief.c`
