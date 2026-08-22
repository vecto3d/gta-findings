# lesterhandler.c

SP missions script. 1 anim dicts; 3 models; 1 scaleforms.

| | |
|---|---|
| Category | SP missions |
| Total lines | 1,109 |
| Functions | 34 (6 unique, 28 shared) |
| Unique lines | 225 (20.3% of file) |

## Assets

**Animation dictionaries** (1) - `MISSHEIST_JEWEL@HACKING`

**Animations** (3) - `MISSHEIST_JEWEL@HACKING`, `HACK_INTRO`, `HACK_LOOP`

**Models and props** (3) - `prop_laptop_lester2`, `prop_cs_walking_stick`, `prop_laptop_01a`

**Scaleform movies** (1) - `JHPB_02_Laptop`

**Text labels** (3) - `NULL`, `LESTER`, `JHFAUD`

**Relationship groups** (1) - `Lester Group`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_CONFIG_FLAG` (6), `SET_MODEL_AS_NO_LONGER_NEEDED` (5), `SET_BIT` (4), `SET_ENTITY_PROOFS` (3), `FREEZE_ENTITY_POSITION` (3), `PLAYER_PED_ID` (3), `SET_OBJECT_AS_NO_LONGER_NEEDED` (2), `REQUEST_MODEL` (2), `HAS_MODEL_LOADED` (2), `WAIT` (2), `DOES_ENTITY_EXIST` (2), `SET_RELATIONSHIP_BETWEEN_GROUPS` (2), `SET_ENTITY_IS_TARGET_PRIORITY` (2), `TASK_PLAY_ANIM_ADVANCED` (2), `CREATE_OBJECT` (2), `SET_ENTITY_INVINCIBLE` (2), `IS_ENTITY_DEAD` (2), `GET_ENTITY_COORDS` (2), `GET_GAME_TIMER` (2), `SET_TEXT_RENDER_ID` (2), `CLEAR_BIT` (2), `SET_PED_AS_NO_LONGER_NEEDED` (1), `SET_SCRIPT_AS_NO_LONGER_NEEDED` (1), `REMOVE_ANIM_DICT` (1), `REMOVE_MODEL_HIDE` (1), `REMOVE_RELATIONSHIP_GROUP` (1), `TERMINATE_THIS_THREAD` (1), `SET_SCALEFORM_MOVIE_AS_NO_LONGER_NEEDED` (1), `HAS_FORCE_CLEANUP_OCCURRED` (1), `REQUEST_ANIM_DICT` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`707.3041f` x3 · `-967.6456f` x3 · `30.376f` x3 · `706.9874f` x2 · `-967.0945f` x2 · `30.4f` x2 · `183.14f` x1 · `718.0749f` x1 · `-976.0472f` x1 · `22.91482f` x1 · `718.0593f` x1 · `-979.455f` x1 · `27.1191f` x1 · `5.75f` x1 · `0.08f` x1 · `0.17f` x1 · `0.27f` x1 · `0.45f` x1

## Other strings

Literals whose consuming native was not classified:

`tvscreen`, `player`, `re_lured`, `JHF_LEAVE`

---

Source: `decompiled_scripts/lesterhandler.c`
