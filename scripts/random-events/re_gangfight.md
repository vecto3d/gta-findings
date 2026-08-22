# re_gangfight.c

Random events script. 3 anim dicts; 5 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 6,462 |
| Functions | 155 (15 unique, 140 shared) |
| Unique lines | 1,356 (21.0% of file) |

## Assets

**Animation dictionaries** (3) - `move_m@gangster@var_i`, `random@countryside_gang_fight`, `veh@drivebystd_ds_grenades`

**Animations** (6) - `random@countryside_gang_fight`, `veh@drivebystd_ds_grenades`, `drop_grenade`, `biker_02_stickup_loop`, `gangmember_stickup_loop`, `biker_01_stickup_loop`

**Models and props** (5) - `g_m_y_lost_01`, `g_m_y_lost_02`, `hexer`, `a_m_m_skidrow_01`, `picador`

**Sounds** (1) - `RE_COUNTRYSIDE_GANG_FIGHT_SCENE`

**Speech contexts** (1) - `A_M_M_TRAMP_01_BLACK_MINI_01`

**Text labels** (5) - `RECGFAU`, `NULL`, `MICHAEL`, `FRANKLIN`, `TREVOR`

**Relationship groups** (1) - `rghLost`

**Vehicle mods** (2) - `picador`, `hexer`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (78), `IS_PED_INJURED` (66), `IS_ENTITY_DEAD` (32), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (14), `IS_ENTITY_AT_ENTITY` (14), `DOES_ENTITY_EXIST` (14), `DOES_BLIP_EXIST` (12), `SET_PED_KEEP_TASK` (11), `OPEN_SEQUENCE_TASK` (11), `CLOSE_SEQUENCE_TASK` (11), `TASK_PERFORM_SEQUENCE` (11), `CLEAR_SEQUENCE_TASK` (11), `GET_GAME_TIMER` (9), `PLAYER_ID` (9), `TASK_SMART_FLEE_PED` (8), `REMOVE_BLIP` (8), `IS_PED_IN_ANY_VEHICLE` (8), `REQUEST_MODEL` (8), `HAS_MODEL_LOADED` (8), `SET_MODEL_AS_NO_LONGER_NEEDED` (8), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (7), `CREATE_VEHICLE` (7), `IS_ENTITY_AT_COORD` (6), `SHOW_HEIGHT_ON_BLIP` (6), `ENABLE_DISPATCH_SERVICE` (6), `IS_PED_IN_VEHICLE` (6), `GET_PLAYERS_LAST_VEHICLE` (6), `TASK_COMBAT_PED` (5), `TASK_LOOK_AT_ENTITY` (5), `WAIT` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`417.901f` x3 · `3578.002f` x3 · `31.176f` x3 · `1305.897f` x3 · `3604.306f` x3 · `40.1064f` x3 · `100.0625f` x3 · `3.3f` x3 · `973.053f` x3 · `3616.738f` x3 · `916.5764f` x2 · `3602.146f` x2 · `31.9262f` x2 · `0.25f` x2 · `916.3351f` x2 · `3602.048f` x2 · `31.9209f` x2 · `2.5f` x2 · `916.4631f` x2 · `3601.261f` x2 · `31.9327f` x2 · `32.6181f` x2 · `915.7905f` x2 · `3603.449f` x2

## Other strings

Literals whose consuming native was not classified:

`hexer`, `RECGF_SHOOT`, `RECGF_SHUTUP`, `RECGF_PAYUP`, `player`, `RECGF_REPEAT`, `RE_CGF`, `RECGF_BIKERS`, `RECGF_REWARD`, `RECGF_END`, `RECGF_END2`, `RECGF_THX`, `RECGF_JABM`, `RECGF_JABF`, `RECGF_JABBER`, `RECGF_STASH`, `RECGF_STASHM`, `RECGF_STASHF`, `RECGF_HIDE`, `RECGF_GANG`, `RECGFLost3`, `RE_COUNTRYSIDE_GANG_BIKES`, `GENERIC_FRIGHTENED_HIGH`, `RECGF_COMM`, `RECGF_COMF`, `RECGF_COMT`, `RECGF_HELP`, `RECGF_GETLOS`, `RECGF_BEGONE`, `RECGF_BIKES`

---

Source: `decompiled_scripts/re_gangfight.c`
