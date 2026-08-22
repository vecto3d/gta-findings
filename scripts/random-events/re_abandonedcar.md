# re_abandonedcar.c

Random events script. 2 anim dicts; 6 models.

| | |
|---|---|
| Category | Random events |
| Total lines | 36,522 |
| Functions | 316 (19 unique, 297 shared) |
| Unique lines | 1,154 (3.2% of file) |

## Assets

**Animation dictionaries** (2) - `random@train_tracks`, `amb@world_human_guard_patrol@male@idle_b`

**Animations** (9) - `random@train_tracks`, `frontseat_carsex_loop_low_guy`, `on_back_c`, `frontseat_carsex_loop_top_guy`, `amb@world_human_guard_patrol@male@idle_b`, `idle_e`, `frontseat_carsex_death_exit_top_guy`, `frontseat_carsex_outro_low_guy`, `frontseat_carsex_outro_top_guy`

**Models and props** (6) - `a_m_m_hillbilly_01`, `a_m_y_acult_01`, `freight`, `freightcar`, `freightgrain`, `freightcont1`

**Audio banks** (1) - `Train_Horn`

**Sounds** (4) - `RE_ABANDONED_VEHICLE_SCENE`, `Warning_Once`, `TRAIN_HORN`, `SUSPENSION_SCRIPT_FORCE`

**Speech contexts** (3) - `A_M_M_HillBilly_02_WHITE_MINI_01`, `A_M_M_HillBilly_02_WHITE_MINI_02`, `A_M_M_HillBilly_01_WHITE_MINI_02`

**Text labels** (8) - `COP`, `MICHAEL`, `FRANKLIN`, `TREVOR`, `INCESTBRO1`, `INCESTBRO2`, `NULL`, `RAPIST`

**Relationship groups** (1) - `Redneck`

**Timecycle modifiers** (1) - `Drug_deadman`

**Vehicle mods** (1) - `surfer`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (89), `IS_PED_INJURED` (36), `GET_ENTITY_ANIM_CURRENT_TIME` (18), `IS_ENTITY_DEAD` (15), `IS_ENTITY_AT_ENTITY` (14), `PLAYER_ID` (13), `WAIT` (11), `SET_PED_COMPONENT_VARIATION` (10), `GET_ENTITY_COORDS` (10), `DOES_BLIP_EXIST` (10), `SET_PED_KEEP_TASK` (8), `REMOVE_BLIP` (8), `TASK_PLAY_ANIM` (7), `IS_PED_IN_ANY_VEHICLE` (7), `TASK_LOOK_AT_ENTITY` (7), `REQUEST_MODEL` (6), `HAS_MODEL_LOADED` (6), `SET_PED_COMBAT_ATTRIBUTES` (6), `IS_ENTITY_AT_COORD` (5), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (5), `TASK_COMBAT_PED` (5), `SETTIMERB` (5), `IS_SPHERE_VISIBLE` (5), `IS_EXPLOSION_IN_AREA` (4), `GET_PLAYERS_LAST_VEHICLE` (4), `ENABLE_DISPATCH_SERVICE` (4), `SET_RELATIONSHIP_BETWEEN_GROUPS` (4), `IS_PED_IN_WRITHE` (4), `IS_PED_BEING_STUNNED` (4), `OPEN_SEQUENCE_TASK` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`8.8f` x4 · `0.1f` x3 · `923.5159f` x2 · `3203.386f` x2 · `40.173f` x2 · `-5.2078f` x2 · `-15.2963f` x2 · `280.1253f` x1 · `1063.595f` x1 · `3227.571f` x1 · `39.3899f` x1 · `0.95f` x1 · `0.075f` x1 · `0.25f` x1 · `0.225f` x1 · `0.38f` x1 · `0.355f` x1 · `0.53f` x1 · `0.505f` x1 · `0.638f` x1 · `0.613f` x1 · `0.7f` x1 · `0.675f` x1 · `0.833f` x1

## Other strings

Literals whose consuming native was not classified:

`re_acau`, `reac2au`, `Dont_tazeme_bro`, `player`, `reac2_attac1`, `re_ac_attac2`, `re_ac_attac1`, `re_ac_rambl`, `reac2_attac3`, `RE_ABANDONED_VEHICLE_MOTORHOME`, `surfer`, `RE8A_TASERED`, `journey`, `RE8B_CAUGHT`, `reac2_attacM`, `reac2_attacF`, `reac2_attacT`, `RE_AV`, `re_ac_approM`, `re_ac_approF`, `re_ac_approT`, `reac2_approM`, `reac2_approF`, `reac2_approT`, `DEATH_FAIL_IN_EFFECT_SHAKE`, `freight`, `freightcar`, `freightgrain`, `freightcont1`, `re_ac_awakeM`

---

Source: `decompiled_scripts/re_abandonedcar.c`
