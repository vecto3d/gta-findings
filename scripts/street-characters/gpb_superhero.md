# gpb_superhero.c

Street characters script. 32 developer state labels recovered; 3 anim dicts; 1 models.

| | |
|---|---|
| Category | Street characters |
| Total lines | 3,339 |
| Functions | 119 (6 unique, 113 shared) |
| Unique lines | 891 (26.7% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`controlledByAnim` · `NOT controlledByAnim` · `iBlockObject OFF` · `iBlockObject ON` · `MONOLOGUE` · `IDLE` · `SET_IDLING` · `SET_IDLING SET_PED_IDLING` · `WAIT_FOR_ANIM_TO_BE_LOADED` · `conversationAlreadyOngoing` · `NOT conversationAlreadyOngoing` · `START_MOVE_BACK_TO_INITIAL_POSITION` · `WAIT_MOVE_BACK_TO_INITIAL_POSITION` · `WAIT_MOVE_BACK_TO_INITIAL_POSITION TASK_PLAY_ANIM` · `START_IDLING` · `PRE_PLAY_MONOLOGUE` · `PLAY_MONOLOGUE` · `MOVE_TO_NEXT_MONOLOGUE` · `CONVERSATION STILL RUNNING` · `NEWSTATE` · `WAIT_TO_START_CONVERSATION` · `START_LOADING_CONVERSATION` · `CHECK_FOR_LOADED_CONVERSATION` · `START_CONVERSATION` · `WAIT_FOR_CONVERSATION_SECTION_OVER` · `HAS_ANIM_DICT_LOADED` · `NOT IS_ANIM_PLAYING_ON_PED` · `WAIT_FOR_CONVERSATION_TO_END` · `WAITING_TO_BLEND_INTO_IDLE_BEFORE_FLEEING` · `WAITING_TO_BLEND_INTO_IDLE_BEFORE_WANDERING` · `do_monologue = FALSE` · `WAITING TO CLEAN UP`

## Assets

**Animation dictionaries** (3) - `Special_Ped@Impotent_Rage`, `special_ped@Impotent_Rage@base`, `special_ped@Impotent_Rage@intro`

**Animations** (1) - `idle_intro`

**Models and props** (1) - `u_m_y_imporage`

**Speech contexts** (2) - `GENERIC_CURSE_MED`, `SPEECH_PARAMS_FORCE`

**Text labels** (4) - `NULL`, `AUD`, `PBSH`, `IMPORAGE`

**Scripts launched** (2) - `director_mode`, `context_controller`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DRAW_DEBUG_TEXT_2D` (38), `PLAYER_PED_ID` (22), `TASK_PLAY_ANIM` (8), `GET_THIS_SCRIPT_NAME` (6), `WAIT` (5), `IS_PED_INJURED` (5), `PLAYER_ID` (4), `GET_GAME_TIMER` (4), `REQUEST_ANIM_DICT` (4), `HAS_ANIM_DICT_LOADED` (4), `GET_ENTITY_COORDS` (3), `DOES_BLIP_EXIST` (3), `GET_HASH_KEY` (3), `IS_PLAYER_PLAYING` (2), `HAS_MODEL_LOADED` (2), `SET_BLOCKING_OF_NON_TEMPORARY_EVENTS` (2), `IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE` (2), `SET_IK_TARGET` (2), `GET_MISSION_FLAG` (2), `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH` (2), `IS_BULLET_IN_AREA` (2), `HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY` (2), `GET_SCRIPT_TASK_STATUS` (2), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (2), `REMOVE_ANIM_DICT` (2), `DISABLE_PED_PAIN_AUDIO` (2), `IS_ENTITY_DEAD` (2), `HAS_FORCE_CLEANUP_OCCURRED` (1), `VMAG2` (1), `GET_ENTITY_VELOCITY` (1)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.02f` x35 · `0.1f` x18 · `0.5f` x3 · `0.8f` x3 · `0.6f` x2 · `0.65f` x2 · `0.2f` x2 · `0.3f` x2 · `0.9f` x2 · `0.81f` x1 · `0.82f` x1 · `0.83f` x1 · `0.11f` x1 · `0.15f` x1 · `0.25f` x1 · `0.26f` x1 · `0.03f` x1

## Other strings

Literals whose consuming native was not classified:

`Grr_Im_Impotent_Rage`, `Im_Really_Pretty_Mad`, `Im_Completely_Crazy_Here`, `This_Is_Just_Insanity`, `Im_So_Damn_Mad`, `Dont_Get_Me_Excited`, `Ill_Find_The_Doughnut`, `America_Im_The_Hero`, `I_Am_The_Ultimate`, `I_Will_Defeat_The`, `Really_Very_Unhappy`, `You_Cant_Stop_My`, `I_Am_White_Male`, `Youll_Not_Stop_me`, `Newest_Superhero`, `_RAND_`, `conversation_offset `, `max_conversation_offset `, `conversation_split_offset `, `max_conversation_split_offsets[conversation_offset] `, `talking offset:`, `MAG_2_RAGE_PED_GROUP`, `Base`, `PBSH_INTERACT`, `PBSH_CONV_M1`, `PBSH_CONV_T1`, `PBSH_CONV_F1`, `Im_An_Actor`, `I_Wanna_Do_Hamlet`, `Having_About_as_Much`

---

Source: `decompiled_scripts/gpb_superhero.c`
