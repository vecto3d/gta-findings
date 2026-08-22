# circuitblockhack.c

Minigames script. 6 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 2,323 |
| Functions | 124 (75 unique, 49 shared) |
| Unique lines | 1,559 (67.1% of file) |

## Assets

**Audio banks** (1) - `DLC_24-2/DLC_24-2_Circuit_Hack`

**Sounds** (12) - `DLC_24-2_Hack_Circuit_Board`, `DLC_24-2_Hacking_Circuit_Scene`, `Fail`, `TimeRemaining`, `Success`, `Move_Circuit_Up`, `Move_Circuit_Down`, `Nav`, `Test`, `Error`, `Background_Loop`, `Timer`

**Scaleform movies** (6) - `GENERIC_INSTRUCTIONAL_BUTTONS`, `TOGGLE_MOUSE_BUTTONS`, `CLEAR_ALL`, `SET_DATA_SLOT`, `SET_MAX_WIDTH`, `DRAW_INSTRUCTIONAL_BUTTONS`

**Text labels** (1) - `NULL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (10), `PLAY_SOUND_FRONTEND` (9), `DRAW_SPRITE` (9), `CLEAR_BIT` (9), `BEGIN_SCALEFORM_MOVIE_METHOD` (7), `END_SCALEFORM_MOVIE_METHOD` (7), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (6), `IS_DISABLED_CONTROL_JUST_PRESSED` (5), `GET_CONTROL_INSTRUCTIONAL_BUTTONS_STRING` (5), `IS_PC_VERSION` (5), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_BOOL` (5), `REQUEST_STREAMED_TEXTURE_DICT` (5), `HAS_STREAMED_TEXTURE_DICT_LOADED` (5), `SET_STREAMED_TEXTURE_DICT_AS_NO_LONGER_NEEDED` (4), `STOP_SOUND` (4), `HAS_SOUND_FINISHED` (4), `HAS_SCALEFORM_MOVIE_LOADED` (4), `BEGIN_TEXT_COMMAND_SCALEFORM_STRING` (4), `ADD_TEXT_COMPONENT_INTEGER` (4), `END_TEXT_COMMAND_SCALEFORM_STRING` (4), `TO_FLOAT` (3), `ROUND` (3), `SET_SCALEFORM_MOVIE_AS_NO_LONGER_NEEDED` (2), `RELEASE_SOUND_ID` (2), `SET_TEXT_SCALE` (2), `SET_TEXT_COLOUR` (2), `SET_TEXT_DROPSHADOW` (2), `SET_TEXT_JUSTIFICATION` (2), `TIMESTEP` (2), `PLAYER_PED_ID` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x8 · `1.788f` x5 · `1.6f` x4 · `0.046875f` x4 · `0.05416667f` x4 · `0.41f` x2 · `0.04296875f` x1 · `0.07638889f` x1

## Other strings

Literals whose consuming native was not classified:

`PCB_Hack_Assets_Foreground`, `MPBeamHack`, `CBH_QUIT`, `PCB_Hack_Assets_Backgrounds`, `CBH_MV_FL`, `fail`, `pass`, `PCB_Hack_OffLight`, `PCB_Hack_RedLight`, `PCB_Hack_GreenLight`, `PCB_Hack_EndSolder_Top`, `PCB_Hack_StartSolder_Bottom`, `PCB_Hack_StartSolder_Middle`, `PCB_Hack_StartSolder_Top`, `PCB_Hack_Selection`, `PCB_Hack_Background`, `CBH_MV_PS`, `CBH_CONFI`, `CBH_MV_UD`, `CBH_MV_LR`, `CBH_MV_HELP`, `CommonMenu`

---

Source: `decompiled_scripts/circuitblockhack.c`
