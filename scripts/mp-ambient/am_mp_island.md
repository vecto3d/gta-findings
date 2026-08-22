# am_mp_island.c

MP ambient script. 17 anim dicts; 3 particle effects.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 299,410 |
| Functions | 3,795 (259 unique, 3,536 shared) |
| Unique lines | 10,835 (3.6% of file) |

## Assets

**Animation dictionaries** (17) - `MOVE_M@DANCING@VERY_SLOW`, `MOVE_F@DANCING@VERY_SLOW`, `MOVE_M@DANCING`, `MOVE_F@DANCING`, `MOVE_M@DANCING@SLOW`, `MOVE_F@DANCING@SLOW`, `ANIM@AMB@NIGHTCLUB@MINI@DRINKING@CHAMPAGNE_DRINKING@BASE@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_A@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_B@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_D@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_E@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_F@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_H@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_J@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_K@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_L@`, `ANIM@AMB@NIGHTCLUB@MINI@DANCE@DANCE_PAIRED@DANCE_M@`

**Audio banks** (4) - `SAFEHOUSE_TREVOR_DRINK_WHISKEY`, `DLC_BATTLE/BTL_CLUB_OPEN_TRANSITION_CROWD`, `DLC_BATTLE/BTL_CHAMPAGNE_MINIGAME`, `DLC_HEI4/DLC_HEI4_Anims_Tequila`

**Sounds** (2) - `PICK_UP`, `HUD_FRONTEND_DEFAULT_SOUNDSET`

**Particle effects** (3) - `scr_ba_club`, `scr_ba_club_champagne_spray`, `fade`

**Text labels** (4) - `VFX`, `NULL`, `BUMP`, `EXTRASUNNY`

**Timecycle modifiers** (1) - `h4_beachparty_day`

**Scripts launched** (3) - `beach_exterior_seating`, `am_mp_peds`, `spawn_activities`

**Hashed names** (7) - `beach_exterior_seating`, `Ba_Prop_Battle_Champ_Open`, `Ba_Prop_Battle_Champ_Open_02`, `Ba_Prop_Battle_Champ_Open_03`, `PickupBottle`, `Swap_Bottle_Open`, `BottleDetach`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (145), `NETWORK_HAS_CONTROL_OF_ENTITY` (101), `PLAYER_ID` (99), `DISABLE_CONTROL_ACTION` (68), `GET_RANDOM_INT_IN_RANGE` (61), `NETWORK_REQUEST_CONTROL_OF_ENTITY` (53), `SET_CONTROL_SHAKE` (39), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (38), `DOES_ENTITY_EXIST` (36), `SET_BIT` (28), `CLEAR_BIT` (27), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (26), `ROUND` (23), `GET_PLAYER_PED` (19), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (19), `NET_TO_PED` (19), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (18), `IS_ENTITY_IN_ANGLED_AREA` (17), `NETWORK_START_SYNCHRONISED_SCENE` (15), `NETWORK_CREATE_SYNCHRONISED_SCENE` (15), `SET_TASK_MOVE_NETWORK_SIGNAL_FLOAT` (15), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (14), `GET_HASH_KEY` (13), `IS_STRING_NULL_OR_EMPTY` (12), `GET_ENTITY_COORDS` (12), `ARE_STRINGS_EQUAL` (11), `GET_SYNCHRONIZED_SCENE_PHASE` (11), `TO_FLOAT` (10), `HAS_ANIM_DICT_LOADED` (10), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (9)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x9 · `0.01f` x8 · `0.25f` x4 · `4894.948f` x2 · `-4900.73f` x2 · `5.211586f` x2 · `4893.2f` x2 · `-4938.884f` x2 · `2.375023f` x2 · `25.25f` x2 · `2.3619f` x2 · `3.2695f` x2 · `0.5f` x2 · `4791.023f` x1 · `-4958.36f` x1 · `6.490686f` x1 · `4826.247f` x1 · `-4896.496f` x1 · `-5.38957f` x1 · `4893.244f` x1 · `-4907.34f` x1 · `4.6251f` x1 · `-27.0617f` x1 · `-1.5099f` x1

## Other strings

Literals whose consuming native was not classified:

`Bartender_Outro_Bottle`, `CHAMP_SHAKE`, `SHAKE_INTENSITY`, `HORIZONTAL_AIM`, `VERTICLE_AIM`, `beach_exterior_seating`, `intro_bartender`, `idle_a_bartender`, `CHAMP_SPRAY`, `UseQuietSceneSoftVersion`, `track`, `timems`, `DUAL_DANCE_BLOCK`, `SM26_GREET`, `SM26_BYE`, `CLU_BAR_PROMPT`, `POD_TOO_MANY`, `outro_bartender`, `Bartender_Intro_Bottle`, `Bartender_Idle`, `am_mp_peds`, `BP_RESTRICTION`, `intype`, `PED_A_DANCE_INTRO`, `PED_A_STANDING_INTRO`, `PED_A_DANCE_IDLE`, `PED_A_DANCE_EXIT`, `PED_A_STANDING_EXIT`, `PED_B_DANCE_INTRO`, `PED_B_STANDING_INTRO`

---

Source: `decompiled_scripts/am_mp_island.c`
