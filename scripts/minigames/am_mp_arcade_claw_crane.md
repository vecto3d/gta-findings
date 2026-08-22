# am_mp_arcade_claw_crane.c

Minigames script. 2 anim dicts; 11 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 88,858 |
| Functions | 683 (78 unique, 605 shared) |
| Unique lines | 2,598 (2.9% of file) |

## Assets

**Animation dictionaries** (2) - `anim_heist@arcade@claw@male@`, `anim_heist@arcade@claw@female@`

**Models and props** (11) - `ch_prop_princess_robo_plush_07a`, `ch_prop_shiny_wasabi_plush_08a`, `ch_prop_master_09a`, `ch_prop_arcade_claw_plush_01a`, `ch_prop_arcade_claw_plush_02a`, `ch_prop_arcade_claw_plush_03a`, `ch_prop_arcade_claw_plush_04a`, `ch_prop_arcade_claw_plush_05a`, `ch_prop_arcade_claw_plush_06a`, `prop_claw_grab`, `prop_plush_grab`

**Sounds** (13) - `dlc_ch_claw_crane_sounds`, `ascend`, `lose`, `descend_impact`, `release_toy`, `rare_win`, `win`, `ascend_win`, `ascend_lose`, `move`, `claw_speed`, `descend`, `start`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_ENTITY_COORDS` (34), `PLAYER_ID` (33), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (20), `DOES_ENTITY_EXIST` (20), `FREEZE_ENTITY_POSITION` (16), `SET_BIT` (15), `PLAY_SOUND_FROM_COORD` (15), `PLAYER_PED_ID` (14), `SET_ENTITY_COORDS` (10), `SET_ENTITY_VISIBLE` (8), `GET_ENTITY_HEADING` (7), `IS_ENTITY_DEAD` (7), `GET_ENTITY_MODEL` (7), `GET_OFFSET_FROM_ENTITY_GIVEN_WORLD_COORDS` (7), `ROUND` (7), `NETWORK_IS_PLAYER_A_PARTICIPANT` (6), `SET_ENTITY_COLLISION` (6), `CLEAR_HELP` (5), `IS_ENTITY_ATTACHED` (5), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (5), `IS_SYNCHRONIZED_SCENE_RUNNING` (5), `CLEAR_BIT` (4), `GET_CAM_VIEW_MODE_FOR_CONTEXT` (4), `DETACH_ENTITY` (4), `SET_ENTITY_COORDS_NO_OFFSET` (4), `TIMESTEP` (4), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (3), `IS_STRING_NULL_OR_EMPTY` (3), `DOES_CAM_EXIST` (3), `IS_ENTITY_ATTACHED_TO_ENTITY` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-0.29f` x13 · `-0.097f` x8 · `1.68f` x8 · `1.723f` x7 · `0.004f` x4 · `-0.1f` x4 · `1.785f` x4 · `0.54f` x3 · `0.05f` x1 · `-0.2f` x1 · `1.41f` x1 · `0.29f` x1 · `0.1f` x1 · `-0.000732422f` x1 · `-0.862213f` x1 · `1.571f` x1 · `-18.6932f` x1 · `50.6788f` x1

## Other strings

Literals whose consuming native was not classified:

`CLAW GAME RP250`, `ARC_CLAW_MO_D`, `ARC_CLAW_MO_F`, `ARC_CLAW_MO_R`, `CLAW_FAIL`, `attach`, `CLAW_MOVING_ARM`, `CLAW_RAREWIN`, `CLAW_WIN`, `CLAW GAME RP5`, `CLAW GAME RP500`, `CLAW GAME RP750`, `CLAW GAME RP1000`, `CLAW_HYPE`, `CLAW_LEAVE`, `CLAW_DESCENDING_ARM`, `CLAW_START_PLAY`, `claw_02`, `DEFAULT_SCRIPTED_CAMERA`, `HAND_SHAKE`, `CLAW_ATTRACT`

---

Source: `decompiled_scripts/am_mp_arcade_claw_crane.c`
