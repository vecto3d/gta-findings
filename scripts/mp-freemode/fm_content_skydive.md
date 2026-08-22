# fm_content_skydive.c

MP freemode script. 3 anim dicts; 4 scaleforms.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 481,423 |
| Functions | 9,997 (252 unique, 9,745 shared) |
| Unique lines | 10,627 (2.2% of file) |

## Assets

**Animation dictionaries** (3) - `oddjobs@basejump@ig_15`, `oddjobs@basejump@`, `anim@door_trans@hinge_l@`

**Animations** (3) - `oddjobs@basejump@`, `Heli_jump`, `Heli_door_loop`

**Audio banks** (1) - `DLC_MPSUM2/Junk_Energy_Skydive`

**Sounds** (13) - `Junk_Energy_Skydive_Soundset`, `Deploy_Parachute`, `PUSH`, `GTAO_APT_DOOR_DOWNSTAIRS_GLASS_SOUNDS`, `Checkpoint_Missed`, `Checkpoint`, `Checkpoint_Count`, `Countdown_Go`, `Countdown_123`, `Finish_Gold`, `Finish`, `Free_Fall_Loop`, `Jump`

**Scaleform movies** (4) - `SET_MESSAGE`, `COUNTDOWN`, `STRING`, `NUMBER`

**Text labels** (1) - `24BUE439`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (72), `PLAYER_ID` (68), `DISABLE_CONTROL_ACTION` (16), `SET_BIT` (13), `GET_RANDOM_FLOAT_IN_RANGE` (12), `VMAG` (11), `PLAY_SOUND_FRONTEND` (10), `SET_ENTITY_VISIBLE` (9), `DOES_ENTITY_EXIST` (8), `DOES_CAM_EXIST` (8), `RENDER_SCRIPT_CAMS` (8), `GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS` (8), `CLEAR_PED_TASKS` (7), `GET_SYNCHRONIZED_SCENE_PHASE` (7), `IS_STRING_NULL_OR_EMPTY` (7), `GET_ID_OF_THIS_THREAD` (7), `IS_PLAYER_DEAD` (7), `VDIST` (6), `SET_PED_COMPONENT_VARIATION` (6), `SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` (6), `PLAYER_PED_ID` (5), `GET_ENTITY_MODEL` (5), `IS_SCREEN_FADED_IN` (5), `SET_CAM_ACTIVE` (5), `SET_CAM_FOV` (5), `GET_GAMEPLAY_CAM_FOV` (5), `SET_CAM_COORD` (5), `POINT_CAM_AT_COORD` (5), `HIDE_HUD_COMPONENT_THIS_FRAME` (4), `IS_NEW_LOAD_SCENE_ACTIVE` (4)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x2 · `3.5f` x1 · `0.99f` x1 · `0.6f` x1 · `0.92f` x1 · `0.271f` x1 · `1.5f` x1 · `0.2f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `reh_p_para_bag_reh_s_01a`, `puton_parachute_cam`, `puton_parachute`, `puton_parachute_bag`, `head`, `int`, `num`, `ibs`, `rot`, `bsa`, `veh`, `grp`, `hclr`, `scl`, `sprt`, `MAX_NUM_TRANSITIONS`, `visr`, `corc`, `chvc`, `vcst`, `hcst`, `vmn`, `vmx`, `fwd`, `look`, `dur`

---

Source: `decompiled_scripts/fm_content_skydive.c`
