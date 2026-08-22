# Developer state labels

Debug strings Rockstar left in the shipped scripts. They name internal states, so they are the closest thing to a written specification of how a script is structured.

**105 distinct values** across 1156 scripts. Sorted by how many scripts use each: widely-shared values first, one-off values last.

A value used by exactly one script is that script's own; a value used by hundreds is shared plumbing.

| Value | Scripts | Used by |
|---|---:|---|
| `[VehSwap] VS_PROCESS_IDLE - Blocking inputs due to ciVEHSWAPBS_BLOCK_ROTATE_INPUT` | 4 | `fm_mission_controller.c`, `fm_mission_controller_2020.c`, `fm_mission_controller_v3.c`, `public_mission_controller.c` |
| `UPDATE_FMMC_YACHT_WARPING` | 4 | `fm_mission_controller.c`, `fm_mission_controller_2020.c`, `fm_mission_controller_v3.c`, `public_mission_controller.c` |
| `Arena is loading...` | 2 | `fm_deathmatch_creator.c`, `fm_race_creator.c` |
| `CHECK_FOR_LOADED_CONVERSATION` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `controlledByAnim` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `CONVERSATION STILL RUNNING` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `conversationAlreadyOngoing` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `Disabling First Person Cam` | 2 | `tennis.c`, `tennis_network_mp.c` |
| `do_monologue = FALSE` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `enter` | 2 | `atm_trigger.c`, `laptop_trigger.c` |
| `grabPlayer` | 2 | `ob_vend1.c`, `ob_vend2.c` |
| `HAS_ANIM_DICT_LOADED` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `iBlockObject OFF` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `iBlockObject ON` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `IDLE` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `idle_a` | 2 | `atm_trigger.c`, `laptop_trigger.c` |
| `idle_b` | 2 | `atm_trigger.c`, `laptop_trigger.c` |
| `idle_c` | 2 | `atm_trigger.c`, `laptop_trigger.c` |
| `idle_d` | 2 | `atm_trigger.c`, `laptop_trigger.c` |
| `idle_XXX` | 2 | `atm_trigger.c`, `laptop_trigger.c` |
| `MONOLOGUE` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `MOVE_TO_NEXT_MONOLOGUE` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `NEWSTATE` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `NOT controlledByAnim` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `NOT conversationAlreadyOngoing` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `NOT IS_ANIM_PLAYING_ON_PED` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `PLAY_MONOLOGUE` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `playerOutOfRange` | 2 | `ob_vend1.c`, `ob_vend2.c` |
| `PRE_PLAY_MONOLOGUE` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `resetVend` | 2 | `ob_vend1.c`, `ob_vend2.c` |
| `runVendingMachine` | 2 | `ob_vend1.c`, `ob_vend2.c` |
| `SET_IDLING` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `SET_IDLING SET_PED_IDLING` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `START_CONVERSATION` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `START_IDLING` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `START_LOADING_CONVERSATION` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `START_MOVE_BACK_TO_INITIAL_POSITION` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `WAIT_FOR_ANIM_TO_BE_LOADED` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `WAIT_FOR_CONVERSATION_SECTION_OVER` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `WAIT_FOR_CONVERSATION_TO_END` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `WAIT_MOVE_BACK_TO_INITIAL_POSITION` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `WAIT_MOVE_BACK_TO_INITIAL_POSITION TASK_PLAY_ANIM` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `WAIT_TO_START_CONVERSATION` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `waitForPlayer` | 2 | `ob_vend1.c`, `ob_vend2.c` |
| `WAITING TO CLEAN UP` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `WAITING_TO_BLEND_INTO_IDLE_BEFORE_FLEEING` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `WAITING_TO_BLEND_INTO_IDLE_BEFORE_WANDERING` | 2 | `gpb_clinton.c`, `gpb_superhero.c` |
| `walk` | 2 | `atm_trigger.c`, `laptop_trigger.c` |
| `ABLE_TO_RETRIEVE_DROPPED_BAG` | 1 | `re_muggings.c` |
| `AMBIENT LINE` | 1 | `re_bus_tours.c` |
| `ASK_PLAYER_FOR_HELP` | 1 | `re_muggings.c` |
| `At_Point_Of_Interest TRUE` | 1 | `re_bus_tours.c` |
| `base` | 1 | `atm_trigger.c` |
| `Bomb Football Sudden Death` | 1 | `fm_mission_controller.c` |
| `bPlayerHasBumpedJimmy` | 1 | `family2.c` |
| `bPlayerHasCheated` | 1 | `family2.c` |
| `Checking for warp` | 1 | `re_snatched.c` |
| `copChasesCriminal` | 1 | `re_arrests.c` |
| `copChasesCriminal TIMERA() < 2000` | 1 | `re_arrests.c` |
| `criminal_thanks 0` | 1 | `re_arrests.c` |
| `criminal_thanks 1` | 1 | `re_arrests.c` |
| `criminal_thanks 2` | 1 | `re_arrests.c` |
| `criminal_thanks 3` | 1 | `re_arrests.c` |
| `criminal_thanks 4` | 1 | `re_arrests.c` |
| `criminal_thanks 5` | 1 | `re_arrests.c` |
| `criminal_thanks 6` | 1 | `re_arrests.c` |
| `criminal_thanks 7` | 1 | `re_arrests.c` |
| `criminal_thanks 8` | 1 | `re_arrests.c` |
| `criminal_thanks 9` | 1 | `re_arrests.c` |
| `GYN_CS_END` | 1 | `taxi_gotyounow.c` |
| `INITIAL_MUGGING_SEQ` | 1 | `re_muggings.c` |
| `IS_ANY_CONVERSATION_ONGOING_OR_QUEUED` | 1 | `re_bus_tours.c` |
| `Jimmy in front` | 1 | `family2.c` |
| `Jimmy take over line should fire` | 1 | `family2.c` |
| `LPOP_STATE_CLEANUP` | 1 | `localpopulator.c` |
| `Michael take over line should fire` | 1 | `family2.c` |
| `MIKE WIN CUTSCENE SET TO LOAD` | 1 | `rural_bank_setup.c` |
| `MUGGING_INTERACTION` | 1 | `re_muggings.c` |
| `Not drawing timer cos on holding rule` | 1 | `fm_mission_controller.c` |
| `Not drawing timer cos timer has expired` | 1 | `fm_mission_controller.c` |
| `Not drawing timer cos we're in a transition period` | 1 | `fm_mission_controller.c` |
| `NOT PLAY_SINGLE_LINE_FROM_CONVERSATION` | 1 | `re_bus_tours.c` |
| `pedGuy1` | 1 | `range_modern.c` |
| `pedGuy2` | 1 | `range_modern.c` |
| `pedGuy3` | 1 | `range_modern.c` |
| `PLAYER HAS PROJECTILE WEAPON` | 1 | `re_securityvan.c` |
| `Player in front` | 1 | `family2.c` |
| `Player INSIDE of vehicle` | 1 | `taxi_gotyounow.c` |
| `Player INSIDE of vehicle adjusted` | 1 | `taxi_gotyounow.c` |
| `PLAYER IS BEHIND VAN` | 1 | `re_securityvan.c` |
| `PLAYER IS CLOSE TO VAN` | 1 | `re_securityvan.c` |
| `Player OUTSIDE of vehicle` | 1 | `taxi_gotyounow.c` |
| `Player OUTSIDE of vehicle adjusted` | 1 | `taxi_gotyounow.c` |
| `PLAYER_HAS_BAG` | 1 | `re_muggings.c` |
| `PROCESS_FMMC_YACHT - ciMYACHT__LOADED` | 1 | `fm_mission_controller.c` |
| `PROCESS_FMMC_YACHT - Requesting Yacht assets` | 1 | `fm_mission_controller.c` |
| `PROCESS_FMMC_YACHT - UPDATE_YACHT_FOR_MISSION_CREATOR` | 1 | `fm_mission_controller.c` |
| `SCOPE FALLEN` | 1 | `ob_telescope.c` |
| `SCOPE UPRIGHT` | 1 | `ob_telescope.c` |
| `Shooting Disabled` | 1 | `range_modern_mp.c` |
| `SKIP IS ACTIVE` | 1 | `rural_bank_setup.c` |
| `TREVOR WIN CUTSCENE SET TO LOAD` | 1 | `rural_bank_setup.c` |
| `VIC_CRY_OUT` | 1 | `re_muggings.c` |
| `WAITING FOR: bTVTurnedOn` | 1 | `lester1.c` |
| `WAITING FOR: cutscene` | 1 | `lester1.c` |
