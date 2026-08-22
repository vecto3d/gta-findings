# am_mp_arc_cab_manager.c

MP ambient script. 4 anim dicts; 4 models; 7 particle effects.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 392,333 |
| Functions | 7,337 (331 unique, 7,006 shared) |
| Unique lines | 23,434 (6.0% of file) |

## Assets

**Animation dictionaries** (4) - `ANIM_HEIST@ARCADE@LOVE@FEMALE@LEFT@`, `ANIM_HEIST@ARCADE@LOVE@MALE@LEFT@`, `ANIM_HEIST@ARCADE@LOVE@FEMALE@RIGHT@`, `ANIM_HEIST@ARCADE@LOVE@MALE@RIGHT@`

**Animations** (3) - `prop_claw_win`, `anim_heist@arcade@claw@male@`, `anim_heist@arcade@claw@female@`

**Models and props** (4) - `ch_prop_ch_usb_drive01x`, `ch_prop_arcade_claw_01a_c`, `ch_prop_fingerprint_scanner_01a`, `prop_phone_ing`

**Audio banks** (4) - `DLC_HEI4/DLC_HEI4_V_MG`, `DLC_HEI4/DLC_HEI4_FH_MG`, `DLC_HEIST3/Door_Hacking`, `DLC_HEIST3/Fingerprint_Match`

**Sounds** (47) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `DLC_H4_Voltage_Hack_Scene`, `Window_Clear`, `Hack_Failed`, `Disconnect_Wire`, `CANCEL`, `SELECT`, `Minigame_Failure`, `Processing`, `Scramble_Countdown_High`, `Scramble_Countdown_Low`, `Print_Appears`, `NAV_LEFT_RIGHT`, `OS_Draw`, `Success_Bink`, `Fail_Bink`, `Loading_Bink`, `Main_Screen_Draw`, `All_Connected_Correct`, `All_Connected_Incorrect`, `Minigame_Success`, `Background_loop`, `Timebar`, `Voltage_Current`, `Voltage_Target`, `Glitch`, `Hack_Success`, `Print_Match`, `Print_Not_Match`, `Pattern_Shift`, `Pattern_Scramble`, `Scramble_Countdown_MED`, `Cursor_Choose_Good`, `Cursor_Choose_Bad`, `New_Line_Flash`, `Dot_Sequence_Change`, `Dot_Sequence_Choose_Flash`, `Section_Success_Window_Appears`, `Section_Success_Window_Cleared`, `Scramble_Countdown_Med`, `Window_Draw`, `Target_Match`, `No_Match`, `Print_Shuffle`, `Kick_Machine`, `DLC_H3_Arc_Mac_Degen_DotF_Sounds`

**Particle effects** (7) - `scr_ch_finale`, `power`, `scr_ch_finale_laser`, `scr_ch_finale_laser_sparks`, `scr_ch_finale_drill_sparks`, `scr_ch_finale_drill_overheat`, `heat`

**Texture dicts** (12) - `MPIsland_Voltage`, `MPIsland_Voltage_BG`, `MPFClone_Retro`, `MPFClone_Retro_LIFE`, `MPFClone_Retro_BACKGROUND`, `MPFClone_Retro_LOADING`, `MPFClone_Retro_MESSAGES`, `MPFClone_Retro_NUMBERS`, `MPFClone_Retro_SCRAMBLER`, `MPFClone_Retro_CORRECT`, `MPBeamHack`, `Fail`

**Text labels** (2) - `NULL`, `HS3MNAU`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (267), `SET_BIT` (106), `CLEAR_BIT` (86), `DOES_ENTITY_EXIST` (58), `PLAY_SOUND_FRONTEND` (58), `PLAYER_PED_ID` (55), `IS_STRING_NULL_OR_EMPTY` (44), `GET_RANDOM_INT_IN_RANGE` (24), `TO_FLOAT` (21), `REQUEST_STREAMED_TEXTURE_DICT` (21), `HAS_STREAMED_TEXTURE_DICT_LOADED` (21), `SET_ENTITY_VISIBLE` (17), `STOP_SOUND` (17), `NET_TO_OBJ` (15), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (12), `SET_STREAMED_TEXTURE_DICT_AS_NO_LONGER_NEEDED` (12), `FLOOR` (11), `GET_SCRIPT_TASK_STATUS` (10), `IS_CONTROL_JUST_PRESSED` (10), `CLEAR_HELP` (9), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (8), `ROUND` (8), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (8), `IS_ENTITY_VISIBLE` (8), `ENABLE_CONTROL_ACTION` (8), `HIDE_HUD_COMPONENT_THIS_FRAME` (7), `DISABLE_CONTROL_ACTION` (7), `GET_SOUND_ID` (7), `INT_TO_PLAYERINDEX` (6), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x15 · `0.45f` x6 · `1.5f` x5 · `-1.5f` x5 · `0.01f` x5 · `0.7f` x3 · `0.516f` x2 · `1.6f` x2 · `3.141593f` x1 · `0.99f` x1 · `1.778f` x1 · `0.41f` x1 · `2.5f` x1

## Other strings

Literals whose consuming native was not classified:

`mporderunlock`, `MPIsland_Voltage_BG`, `MPIsland_Voltage`, `innercircle_fill`, `correct_circles`, `result_text`, `mphackinggame`, `incorrect_circles`, `VOLTAGE_PIXEL_GRID`, `Main_RM`, `MPIsland_voltage`, `hei_p_m_bag_var22_arm_s`, `ARC_CAB_DEC_4`, `ITEM_SELECT`, `ITEM_BACK`, `MPFClone_Retro_Print`, `MPFClone_Retro_PrintFull`, `MPFClone_Retro_LOADING`, `DLC_H4_Fingerprint_Hack_Minigame_Sounds`, `inner_circles`, `Inner_Circles`, `enter`, `idle`, `exit`, `average_better`, `average_worse`, `bad_better`, `bad_worse`, `friendzoned_perfect`, `friendzoned_worst`

---

Source: `decompiled_scripts/am_mp_arc_cab_manager.c`
