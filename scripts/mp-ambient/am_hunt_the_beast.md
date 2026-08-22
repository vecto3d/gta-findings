# am_hunt_the_beast.c

MP ambient script. 2 anim dicts; 7 scaleforms.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 184,286 |
| Functions | 2,203 (118 unique, 2,085 shared) |
| Unique lines | 7,396 (4.0% of file) |

## Assets

**Animation dictionaries** (2) - `ANIM@MP_FM_EVENT@INTRO`, `move_m@GEneric`

**Animations** (5) - `ANIM@MP_FM_EVENT@INTRO`, `BEAST_TRANSFORM`, `move_m@GEneric`, `wstop_l_0`, `rstop_quick_l`

**Audio banks** (1) - `DLC_SFX1/BEAST`

**Sounds** (16) - `FM_Events_Sasquatch_Sounds`, `FM_Event_Beast_Transform_Sequence_Scene`, `FM_Event_Beast_Fade_White_Scene`, `FM_Event_Beast_Screen_Freeze_Scene`, `Frontend_Beast_Fade_Screen`, `Event_Start_Text`, `GTAO_FM_Events_Soundset`, `Frontend_Beast_Transform_Back`, `Beast_Calls`, `Checkpoint_Beast_Hit`, `Radar_Beast_Blip`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `Frontend_Beast_Freeze_Screen`, `Frontend_Beast_Frozen_Screen_Loop`, `Frontend_Beast_Text_Hit`

**Scaleform movies** (7) - `STRING`, `CREATE_STAT_WALL`, `ADD_BACKGROUND_TO_WALL`, `ADD_WINNER_TO_WALL`, `MP_CELEBRATION`, `MP_CELEBRATION_BG`, `MP_CELEBRATION_FG`

**Text labels** (3) - `LOSER`, `WINNER`, `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PARTICIPANT_ID_TO_INT` (122), `PLAYER_ID` (120), `PLAYER_PED_ID` (111), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (23), `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME` (23), `END_TEXT_COMMAND_SCALEFORM_STRING` (23), `CLEAR_HELP` (19), `GET_ENTITY_COORDS` (16), `CLEAR_BIT` (16), `SET_BIT` (16), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (15), `ANIMPOSTFX_IS_RUNNING` (13), `DOES_ENTITY_EXIST` (12), `ROUND` (12), `ARE_STRINGS_EQUAL` (12), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (10), `PLAY_SOUND_FRONTEND` (10), `DOES_BLIP_EXIST` (10), `END_SCALEFORM_MOVIE_METHOD` (9), `BEGIN_SCALEFORM_MOVIE_METHOD` (9), `IS_HELP_MESSAGE_BEING_DISPLAYED` (9), `REMOVE_ANIM_DICT` (9), `IS_PED_IN_ANY_VEHICLE` (8), `SET_CAM_COORD` (8), `POINT_CAM_AT_ENTITY` (8), `ANIMPOSTFX_STOP` (8), `GET_PLAYER_TEAM` (8), `GET_RANDOM_INT_IN_RANGE` (7), `HAS_SCALEFORM_MOVIE_LOADED` (7), `NETWORK_IS_PARTICIPANT_ACTIVE` (7)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x16 · `0.125f` x8 · `0.1f` x4 · `0.3f` x3 · `0.2f` x2 · `2.5f` x2 · `0.05f` x2 · `-1.11f` x2 · `1.5f` x1 · `2.25f` x1 · `0.122f` x1 · `0.28f` x1 · `0.6f` x1

## Other strings

Literals whose consuming native was not classified:

`BeastIntroScene`, `BeastTransition`, `BeastLaunch`, `AMHB_OVERTTL`, `DEFAULT_SCRIPTED_CAMERA`, `AMHB_LNDLBL`, `AMHB_BSTHLP0`, `AMHB_BSTHLP1`, `AMHB_BSTHLP2`, `AMHB_BSTHLP3`, `AMHB_HTRHLP0`, `AMHB_HTRHLP1`, `AMHB_HTRHLP2`, `AMHB_HTRHLP3`, `AMHB_OPTHELP`, `BEAST_TRANSFORM`, `HUD_COLOUR_FREEMODE`, `HAND_SHAKE`, `BEAST_TRANSFORM_CAM`, `AMHB_PASSIVE`, `AMHB_HELIGUN`, `AMHB_LUXOR`, `AMHB_BOB`, `AMHB_HKR`, `AMHB_PLANE`, `AMHB_NOCLCT`, `AMHB_NOCLCT2`, `AMHB_OPTTCKR`, `AMHB_PHINTSH1`, `BST_STOP`

---

Source: `decompiled_scripts/am_hunt_the_beast.c`
