# hunting1.c

Jobs script. 2 anim dicts; 8 models.

| | |
|---|---|
| Category | Jobs |
| Total lines | 49,603 |
| Functions | 559 (115 unique, 444 shared) |
| Unique lines | 4,991 (10.1% of file) |

## Assets

**Animation dictionaries** (2) - `special_ped@cletus@base`, `ODDJOBS@HUNTER`

**Animations** (13) - `ODDJOBS@HUNTER`, `BINOCULARS_OUTRO`, `BINOCULARS_LOOP`, `binoculars_intro`, `enter_call`, `enter`, `idle_a`, `exit`, `idle_a_call`, `point_fwd`, `BINOCULARS_INTRO`, `special_ped@cletus@base`, `cletus_base`

**Models and props** (8) - `a_m_y_hippy_01`, `a_m_m_salton_01`, `prop_satdish_l_02b`, `a_c_coyote`, `prop_binoc_01`, `prop_npc_phone`, `a_m_m_hillbilly_01`, `p_cletus_necklace_s`

**Audio banks** (1) - `SCRIPT\HUNTING_1_COYOTE_VOCALS`

**Sounds** (2) - `COYOTE_BARK_MASTER`, `COYOTE_CRY_MASTER`

**Text labels** (6) - `HUNT1AU`, `TREVOR`, `CLETUS`, `NULL`, `HUNT1`, `NONE`

**Scenarios** (3) - `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_DRINKING`, `WORLD_HUMAN_SMOKING`

**Relationship groups** (1) - `FRIENDLIES`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (159), `DOES_ENTITY_EXIST` (52), `IS_ENTITY_DEAD` (30), `GET_GAME_TIMER` (28), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (27), `CLEAR_PED_TASKS` (26), `GET_ENTITY_COORDS` (26), `IS_ENTITY_IN_ANGLED_AREA` (25), `SET_MODEL_AS_NO_LONGER_NEEDED` (17), `REQUEST_MODEL` (17), `TASK_FOLLOW_NAV_MESH_TO_COORD` (16), `HAS_MODEL_LOADED` (16), `IS_PED_IN_ANY_VEHICLE` (16), `SET_FORCE_OBJECT_THIS_FRAME` (14), `IS_ENTITY_AT_COORD` (13), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (12), `WAIT` (11), `SET_VEHICLE_DENSITY_MULTIPLIER_THIS_FRAME` (11), `SET_PED_CAN_RAGDOLL_FROM_PLAYER_IMPACT` (11), `PLAYER_ID` (10), `TASK_PLAY_ANIM` (10), `IS_BULLET_IN_AREA` (9), `IS_PED_INJURED` (9), `SET_PED_KEEP_TASK` (9), `CLEAR_ENTITY_LAST_DAMAGE_ENTITY` (9), `GET_SCRIPT_TASK_STATUS` (9), `IS_SCREEN_FADED_OUT` (8), `CLEAR_PED_TASKS_IMMEDIATELY` (8), `DOES_BLIP_EXIST` (8), `GET_PROFILE_SETTING` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x17 · `1.5f` x15 · `0.5f` x4 · `3.5f` x4 · `2.5f` x3 · `359.9f` x3 · `3533.135f` x2 · `33.9186f` x2 · `36.6333f` x2 · `359.8644f` x2 · `1.25f` x2 · `0.75f` x1 · `7.5f` x1 · `0.7f` x1 · `4.5f` x1 · `1155.058f` x1 · `34.9236f` x1 · `1655.803f` x1 · `3492.451f` x1 · `35.5714f` x1 · `105.5303f` x1 · `1516.076f` x1 · `3376.604f` x1 · `1140.058f` x1

## Other strings

Literals whose consuming native was not classified:

`HT_BKHTER`, `HT_SHDISH`, `HT_NXTLOC`, `HT_FOLL`, `player`, `HT_SHTYRE`, `HUNT1_DISH`, `HUNT1_LAREA`, `AMMO_SNIPER`, `Player has finished shooting the coyote`, `HT_SHCOY`, `Player has finished shooting all the car tyres`, `Player has finished shooting all the satellite dishes`, `Player has reached the satellite dishes`, `Daves_Rifle`, `HUNT1_DISH_1`, `HUNT1_TYRE`, `HUNT1_NOVEH`, `HUNT1_DIIN`, `HUNT_TYIN`, `dune`, `emperor2`, `surfer2`, `Trevor`, `Cletus`, `HUNT1_BANTER_1`, `Force cleanup [TERMINATING]`, `SF_TP`, `HT_2MORE`, `HT_1MORE`

---

Source: `decompiled_scripts/hunting1.c`
