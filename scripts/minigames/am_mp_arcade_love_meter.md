# am_mp_arcade_love_meter.c

Minigames script. 10 models; 1 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 91,045 |
| Functions | 711 (69 unique, 642 shared) |
| Unique lines | 3,313 (3.6% of file) |

## Assets

**Models and props** (10) - `ch_prop_arc_love_btn_ice`, `ch_prop_arc_love_btn_cold`, `ch_prop_arc_love_btn_thaw`, `ch_prop_arc_love_btn_gett`, `ch_prop_arc_love_btn_burn`, `ch_prop_arc_love_btn_hot`, `ch_prop_arc_love_btn_sizz`, `ch_prop_arc_love_btn_clam`, `ch_prop_arc_love_btn_warm`, `ch_prop_arc_love_btn_flush`

**Audio banks** (3) - `DLC_HEIST3\HEIST_FINALE_LASER_DRILL`, `DLC_MPHEIST\HEIST_FLEECA_DRILL`, `DLC_MPHEIST\HEIST_FLEECA_DRILL_2`

**Sounds** (23) - `DLC_H3_LoveMachine_Sounds`, `dlc_ch_heist_finale_laser_drill_sounds`, `Outcome_BuzzKill`, `Outcome_PerfectMatch`, `DrillState`, `DrillHeat`, `laser_power_down`, `Outcome_Nemesis`, `Outcome_Chillin`, `Outcome_Not`, `Outcome_Schwing`, `Outcome_Pimpin`, `Outcome_Hype`, `Outcome_Sweet`, `Outcome_LoveSick`, `Outcome_SoFine`, `laser_power_up`, `laser_drill`, `laser_overheat`, `Drill_Jam`, `DLC_HEIST_FLEECA_SOUNDSET`, `Calculate_Outcome`, `Time`

**Scaleform movies** (1) - `RESET`

**Text labels** (1) - `NULL`

**Hashed names** (2) - `AM_MP_DRONE`, `NO_LABEL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (72), `SET_BIT` (51), `CLEAR_BIT` (22), `GET_ENTITY_COORDS` (17), `PLAY_SOUND_FROM_COORD` (14), `NET_TO_OBJ` (14), `SET_ENTITY_VISIBLE` (13), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (11), `IS_TASK_MOVE_NETWORK_ACTIVE` (10), `TIMESTEP` (7), `STOP_SOUND` (7), `DOES_ENTITY_EXIST` (6), `PLAYER_PED_ID` (6), `GET_PLAYER_NAME` (6), `IS_SYNCHRONIZED_SCENE_RUNNING` (6), `DISPLAY_HELP_TEXT_THIS_FRAME` (6), `PLAY_SOUND_FROM_ENTITY` (6), `ROUND` (6), `RELEASE_SOUND_ID` (5), `GET_SYNCHRONIZED_SCENE_PHASE` (5), `SET_VARIABLE_ON_SOUND` (5), `GET_GAME_TIMER` (5), `SET_CONTROL_SHAKE` (5), `GET_OFFSET_FROM_ENTITY_IN_WORLD_COORDS` (4), `FREEZE_ENTITY_POSITION` (4), `HAS_SOUND_FINISHED` (4), `DISABLE_CONTROL_ACTION` (4), `NETWORK_ADD_SYNCHRONISED_SCENE_CAMERA` (4), `HIDE_HUD_AND_RADAR_THIS_FRAME` (4), `THEFEED_HIDE_THIS_FRAME` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x4 · `-1.5f` x2 · `0.2f` x2 · `0.728f` x1 · `0.36f` x1 · `0.16f` x1 · `0.4f` x1 · `0.38f` x1 · `0.8f` x1 · `0.9f` x1 · `0.35f` x1

## Other strings

Literals whose consuming native was not classified:

`Arc_Love_01a`, `ARC_CAB_LOVE_WAIT`, `Cutting`, `ARCCAB_LOVE_P2`, `ARCCAB_LOVE_P3`, `ARCCAB_LOVE_P4`, `ARCCAB_LOVE_P5`, `ARCCAB_LOVE_P6`, `ARCCAB_LOVE_P7`, `ARCCAB_LOVE_P8`, `ARCCAB_LOVE_P9`, `ARCCAB_LOVE_P10`, `ARCCAB_LOVE_P11`, `Heist3_minigame_drill_vault`, `bag_intro`, `intro_cam`, `intro_nobag_cam`, `MC_LASER_3`, `MC_DRILL_3`, `z_axis`, `LOVETEST_HYPE`, `LOVETEST_NEMESIS`, `ARCCAB_LOVE_P1`, `LOVE METER NEMESIS RP800`, `LOVETEST_ICE_COLD`, `LOVETEST_COLD_SHOULDER`, `LOVETEST_THAW_OUT`, `LOVETEST_CLAMMY`, `LOVETEST_WARMER`, `LOVETEST_FLUSHED`

---

Source: `decompiled_scripts/am_mp_arcade_love_meter.c`
