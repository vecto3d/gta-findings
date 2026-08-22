# player_controller.c

System and infrastructure script. 9 models.

| | |
|---|---|
| Category | System and infrastructure |
| Total lines | 112,464 |
| Functions | 730 (104 unique, 626 shared) |
| Unique lines | 9,086 (8.1% of file) |

## Assets

**Models and props** (9) - `u_m_y_cyclist_01`, `a_c_rabbit_01`, `a_c_boar`, `a_c_deer`, `a_c_mtlion`, `cs_hunter`, `a_m_y_hiker_01`, `a_f_y_hippie_01`, `a_m_m_hillbilly_01`

**Text labels** (21) - `CHAR_SOCIAL_CLUB`, `BLUE`, `ORANGE`, `WHITE`, `BLACK`, `RED`, `YELLOW`, `NULL`, `COP`, `PURPLE`, `GOLD`, `SILVER`, `GRAPHITE`, `CREAM`, `PINK`, `BRONZE`, `CONTENT_TICK`, `AST`, `CHROME`, `GREY`, `GREEN`

**Scenarios** (1) - `BLIMP`

**Vehicle recordings** (1) - `END_MARTIN_1`

**Stats** (3) - `content_hanger_veh`, `content_marina_veh`, `content_heli_veh`

**Scripts launched** (5) - `docks_setup`, `martin1`, `fbi4_prep3amb`, `agency_prep2amb`, `finale_heist_prepeamb`

## Native vocabulary

Most-called natives inside the code unique to this script:

`ADD_DECAL` (63), `PLAYER_PED_ID` (55), `DOES_ENTITY_EXIST` (33), `APPLY_PED_BLOOD_SPECIFIC` (28), `SET_MODEL_AS_NO_LONGER_NEEDED` (26), `SET_BIT` (25), `GET_ENTITY_COORDS` (23), `GET_ENTITY_MODEL` (21), `GET_GAME_TIMER` (19), `HAS_MODEL_LOADED` (17), `IS_PED_INJURED` (14), `ARE_STRINGS_EQUAL` (13), `CLEAR_BIT` (12), `IS_ENTITY_DEAD` (12), `ACTIVATE_PHYSICS` (12), `SET_VEHICLE_DOOR_BROKEN` (12), `VDIST2` (11), `SET_CUTSCENE_PED_PROP_VARIATION` (11), `CREATE_PED` (10), `PLAYER_ID` (9), `DISABLE_PED_PAIN_AUDIO` (9), `SET_ENTITY_HEALTH` (9), `SET_ENTITY_AS_MISSION_ENTITY` (9), `STAT_SET_INT` (9), `IS_VEHICLE_DRIVEABLE` (8), `SET_CUTSCENE_PED_COMPONENT_VARIATION` (8), `WAIT` (7), `IS_PLAYER_SWITCH_IN_PROGRESS` (7), `IS_PED_IN_ANY_VEHICLE` (7), `SET_PED_CONFIG_FLAG` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.196f` x45 · `0.9f` x20 · `0.8f` x18 · `0.19f` x18 · `0.33f` x18 · `0.01f` x17 · `0.7f` x13 · `0.5f` x10 · `1.1f` x9 · `0.6f` x9 · `0.4f` x8 · `0.3f` x7 · `0.688f` x6 · `0.07f` x5 · `0.451f` x4 · `0.542f` x4 · `0.09f` x4 · `0.3798f` x4 · `-0.9251f` x4 · `0.03f` x3 · `0.2f` x3 · `0.174f` x3 · `0.424f` x3 · `0.222f` x3

## Other strings

Literals whose consuming native was not classified:

`ShotgunLargeMonolithic`, `BasicSlash`, `buffalo3`, `dominator2`, `gauntlet2`, `LIME_GREEN`, `MIDNIGHT_BLUE`, `DARK_BLUE`, `MIGHT_PURPLE`, `bodhi2`, `CONT_NEW_V`, `CONTENT_NEW_T`, `til_P_`, `Exec_U`, `xer_Scene`, `B_Mi`, `stab`, `AM_H_SWTCH4`, `AM_H_SWTCH8`, `AM_H_SWTCH7`, `AM_H_SWTCH1`, `AM_H_SWTCH9`, `stalion2`, `BLACK_GRAPHITE`, `CHOCOLATE_BROWN`, `HOT PINK`, `FORMULA_RED`, `ULTRA_BLUE`, `RACING_GREEN`, `RACE_YELLOW`

---

Source: `decompiled_scripts/player_controller.c`
