# extreme3.c

SP missions script. 1 anim dicts; 2 models.

| | |
|---|---|
| Category | SP missions |
| Total lines | 109,778 |
| Functions | 712 (39 unique, 673 shared) |
| Unique lines | 1,587 (1.4% of file) |

## Assets

**Animation dictionaries** (1) - `rcmextreme3`

**Animations** (5) - `rcmextreme3`, `idle_frantic`, `jump_fall`, `idle`, `fidget_02`

**Models and props** (2) - `s_m_y_pilot_01`, `a_c_retriever`

**Text labels** (6) - `EXT3AUD`, `DOM`, `FRANKLIN`, `EXT3`, `NULL`, `EXT1HELIPILOT`

**Vehicle recordings** (1) - `Ext3_Truck`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (81), `GET_PED_PARACHUTE_STATE` (15), `GET_GAME_TIMER` (12), `GET_ENTITY_COORDS` (9), `TASK_PLAY_ANIM` (8), `IS_ENTITY_ATTACHED_TO_ENTITY` (6), `ATTACH_ENTITY_TO_ENTITY` (6), `REQUEST_ANIM_DICT` (6), `REQUEST_MODEL` (6), `CLEAR_HELP` (6), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (6), `SET_MODEL_AS_NO_LONGER_NEEDED` (6), `DOES_ENTITY_EXIST` (6), `GET_ENTITY_INDEX_OF_REGISTERED_ENTITY` (6), `PLAYER_ID` (5), `HAS_ANIM_DICT_LOADED` (5), `HAS_MODEL_LOADED` (5), `WAIT` (5), `IS_PLAYBACK_GOING_ON_FOR_VEHICLE` (5), `DOES_CAM_EXIST` (5), `TRIGGER_MUSIC_EVENT` (5), `REPLAY_RECORD_BACK_FOR_TIME` (5), `GET_OFFSET_FROM_ENTITY_GIVEN_WORLD_COORDS` (4), `DETACH_ENTITY` (4), `SKIP_TIME_IN_PLAYBACK_RECORDED_VEHICLE` (4), `REGISTER_ENTITY_FOR_CUTSCENE` (4), `SET_ENTITY_AS_MISSION_ENTITY` (4), `CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY` (4), `SET_ENTITY_INVINCIBLE` (4), `SET_ENTITY_LOAD_COLLISION_FLAG` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.25f` x6 · `0.5f` x6 · `30.3356f` x3 · `-795.6482f` x3 · `44.26f` x3 · `516.254f` x2 · `-163.8118f` x2 · `57.1199f` x2 · `41.3162f` x2 · `0.35f` x1 · `-4.7308f` x1 · `20.6208f` x1 · `6.3419f` x1 · `-4.0898f` x1 · `17.7773f` x1 · `5.632f` x1 · `33.4911f` x1 · `-12.5501f` x1 · `-4.3722f` x1 · `5.6236f` x1 · `-9.8242f` x1 · `-3.8605f` x1 · `4.4802f` x1 · `1.5934f` x1

## Other strings

Literals whose consuming native was not classified:

`Dom`, `DEFAULT_SCRIPTED_CAMERA`, `DOM_Flatbed_truck`, `EXT3_03`, `EXT3_01`, `HAND_SHAKE`, `Franklin`, `EXTREME3_STOP`, `EXT_SKYDIVE`, `EXTREME LAUNCHER RC`, `EXT_NTRUCK`, `EXT_YTRUCK`, `EXT_LAND`, `EXT_LAND2`, `Outro`, `ES_3_MCS_1`, `ES_3_MCS_2`, `EXTREME3_RESTART1`, `flatbed`, `buffalo`, `Force cleanup [TERMINATING]`, `SF_TR`, `EXTREME3_FAIL`, `EXT3_F1`, `EXT3_F2`, `EXT3_F3`, `EXT3_F4`, `EXT3_F5`, `EXT3_F6`, `EXT_COMM`

---

Source: `decompiled_scripts/extreme3.c`
