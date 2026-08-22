# puzzle.c

Minigames script. 2 anim dicts; 1 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 382,076 |
| Functions | 6,869 (135 unique, 6,734 shared) |
| Unique lines | 18,305 (4.8% of file) |

## Assets

**Animation dictionaries** (2) - `ANIM_HEIST@ARCADE@QUB3D@`, `ANIM_HEIST@ARCADE@QUB3D`

**Models and props** (1) - `sum_prop_ac_qub3d_grid`

**Audio banks** (2) - `DLC_SUM20/sum20_qub3d_sfx`, `DLC_SUM20/sum20_qub3d_music`

**Sounds** (7) - `MusicMix`, `Music_Dynamic_Banked`, `sum20_am_Qub3d_sounds`, `Slowmo`, `Menu_Navigate`, `Menu_Back`, `MENU_SELECT`

**Texture dicts** (6) - `MPArcadeGamesFX03`, `MPArcadeGamesFX04`, `MPArcadeGamesFX00`, `MPArcadeGamesFX01`, `MPArcadeGamesFX02`, `MPArcadeGamesFX05`

**Text labels** (3) - `NULL`, `CLEAR`, `QUB3D`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DOES_ENTITY_EXIST` (75), `TO_FLOAT` (69), `GET_GAME_TIMER` (67), `SET_VARIABLE_ON_SOUND` (36), `DELETE_OBJECT` (34), `PLAY_SOUND_FRONTEND` (32), `IS_DISABLED_CONTROL_PRESSED` (26), `HAS_STREAMED_TEXTURE_DICT_LOADED` (19), `SET_ENTITY_COLLISION` (19), `FREEZE_ENTITY_POSITION` (19), `SET_ENTITY_HEADING` (18), `PLAYER_ID` (17), `GET_SOUND_ID` (14), `IS_DISABLED_CONTROL_JUST_PRESSED` (14), `GET_RANDOM_INT_IN_RANGE` (12), `RELEASE_SOUND_ID` (10), `CLEAR_HELP` (10), `SET_ENTITY_VISIBLE` (10), `SET_CAM_ACTIVE` (8), `FLOOR` (8), `POW` (8), `REQUEST_STREAMED_TEXTURE_DICT` (8), `IS_CONTROL_PRESSED` (7), `SET_BIT` (7), `PLAYER_PED_ID` (5), `GET_ENTITY_MODEL` (5), `IS_USING_KEYBOARD_AND_MOUSE` (5), `CLEAR_PRINTS` (5), `SET_CAM_ACTIVE_WITH_INTERP` (4), `TIMESTEP` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.85f` x5 · `-0.85f` x4 · `0.01f` x2 · `0.02f` x2 · `0.2f` x1

## Other strings

Literals whose consuming native was not classified:

`DEG_GAME_QUIT`, `NO_BIG_2`, `NO_BIG_3`, `PZ_RETURN`, `LET_X`, `NO_BIG_`, `NO_BIG_1`, `LABEL_SPECIAL`, `LABEL_POWER`, `sum_prop_ac_qub3d_grid`, `scr_sum_q3`, `scr_sum_q3_block_destroy`, `scr_sum_q3_block_destroy_charge`, `blockXPos`, `blockYPos`, `blocksCleared`, `QUB3D_CLEAR_BLOCK`, `QUB3D_ROTATE_BLOCK`, `QUB3D_MOVE_BLOCK`, `QUB3D_GLOM_BLOCK`, `QUB3D_LAND_BLOCK`, `QUB3D_GOT_POWERUP`, `QUB3D_USE_POWERUP`, `QUB3D_GAME_OVER`, `[BAZ][QUB3D] `, `_Pixtro_Intro_80s_2`, `Facade`, `MENU_LABEL_QUIT`, `YellowSpecial`, `LABEL_SCORE`

---

Source: `decompiled_scripts/puzzle.c`
