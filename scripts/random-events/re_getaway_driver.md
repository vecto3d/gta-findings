# re_getaway_driver.c

Random events script. 4 anim dicts; 8 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 11,072 |
| Functions | 258 (20 unique, 238 shared) |
| Unique lines | 2,623 (23.7% of file) |

## Assets

**Animation dictionaries** (4) - `random@getawaydriver@thugs`, `combat@gestures@pistol@halt`, `misslamar1ig_20`, `random@getawaydriver`

**Animations** (14) - `random@getawaydriver`, `idle_a`, `idle_2_hands_up`, `hands_up_2_idle`, `random@getawaydriver@thugs`, `gesture_nod_yes_soft`, `base_a`, `base_b`, `base`, `misslamar1ig_20`, `stretch_call_hurry_a`, `combat@gestures@pistol@halt`, `180`, `gesture_nod_yes_hard`

**Models and props** (8) - `s_m_y_cop_01`, `police3`, `picador`, `stanier`, `patriot`, `g_m_y_mexgoon_02`, `a_f_y_soucent_01`, `a_m_m_soucent_01`

**Speech contexts** (2) - `PACKIE_AI_Norm_Part1_Booth`, `A_M_Y_Business_01_CHINESE_MINI_01`

**Text labels** (8) - `REGETAU`, `COP`, `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `PACKIE`, `FEED_CREW_U`

**Scenarios** (2) - `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_MOBILE_FILM_SHOCKING`

**Relationship groups** (3) - `reCriminals`, `reShopKeep`, `reCops`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (169), `IS_PED_INJURED` (121), `GET_PLAYERS_LAST_VEHICLE` (38), `PLAYER_ID` (32), `WAIT` (30), `TASK_SMART_FLEE_PED` (28), `SET_PED_KEEP_TASK` (26), `SET_RELATIONSHIP_BETWEEN_GROUPS` (24), `IS_ENTITY_DEAD` (23), `OPEN_SEQUENCE_TASK` (20), `CLOSE_SEQUENCE_TASK` (20), `TASK_PERFORM_SEQUENCE` (20), `CLEAR_SEQUENCE_TASK` (20), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (20), `IS_ENTITY_AT_ENTITY` (18), `TASK_LOOK_AT_ENTITY` (18), `GET_SCRIPT_TASK_STATUS` (18), `GET_VEHICLE_PED_IS_IN` (17), `GET_GAME_TIMER` (17), `IS_ENTITY_AT_COORD` (17), `DOES_BLIP_EXIST` (17), `IS_PED_IN_ANY_VEHICLE` (16), `GET_VEHICLE_PED_IS_USING` (15), `IS_PED_IN_VEHICLE` (14), `TASK_PLAY_ANIM` (14), `GIVE_WEAPON_TO_PED` (14), `DOES_ENTITY_EXIST` (13), `GET_ENTITY_MODEL` (12), `TASK_LEAVE_ANY_VEHICLE` (11), `IS_PED_IN_GROUP` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`2.5f` x6 · `28.4601f` x5 · `0.2f` x4 · `0.25f` x4 · `-1565.293f` x2 · `61.5891f` x2 · `28.6027f` x2 · `-1.5f` x2 · `0.5f` x2 · `7.3162f` x2 · `-1544.838f` x2 · `28.2558f` x2 · `91.6602f` x2 · `-1541.899f` x2 · `28.3422f` x2 · `32.8029f` x2 · `-1594.4f` x2 · `28.4262f` x2 · `75.3661f` x2 · `-1542.811f` x2 · `43.7035f` x2 · `-1580.28f` x2 · `33.4259f` x2 · `933.83f` x1

## Other strings

Literals whose consuming native was not classified:

`REAWA_COPS`, `REAWA_POLICE`, `bus`, `REAWA_CAR`, `GENERIC_FRIGHTENED_HIGH`, `FIRING_PATTERN_FULL_AUTO`, `REAWA_NDCAR`, `player`, `rhino`, `hc_gunman`, `mp_m_shopkeep_01`, `police3`, `RE_GD`, `REAWA_LOSE`, `REAWA_FKDB`, `REAWA_DEAD1`, `REAWA_THX`, `REAWA_THANKS`, `picador`, `stanier`, `patriot`, `REGETRobber2`, `StoreOwner`, `GENERIC_SHOCKED_HIGH`, `REAWA_DOWN`, `SCRIPTED_SCANNER_REPORT_GETAWAY_01`, `REAWA_COPS2`, `REAWA_HOM`, `REAWA_CULT`, `REAWA_CULT2`

---

Source: `decompiled_scripts/re_getaway_driver.c`
