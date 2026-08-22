# mansion_club_bar.c

Properties and venues script. 1 anim dicts; 3 particle effects.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 107,587 |
| Functions | 704 (19 unique, 685 shared) |
| Unique lines | 2,645 (2.5% of file) |

## Assets

**Animation dictionaries** (1) - `ANIM@AMB@NIGHTCLUB@MINI@DRINKING@CHAMPAGNE_DRINKING@BASE@`

**Audio banks** (3) - `SAFEHOUSE_TREVOR_DRINK_WHISKEY`, `DLC_BATTLE/BTL_CHAMPAGNE_MINIGAME`, `DLC_HEI4/DLC_HEI4_Anims_Tequila`

**Sounds** (6) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `ERROR`, `SELECT`, `BACK`, `PICK_UP`

**Particle effects** (3) - `scr_ba_club`, `scr_ba_club_champagne_spray`, `fade`

**Text labels** (3) - `VFX`, `BAR`, `NULL`

**Hashed names** (6) - `Ba_Prop_Battle_Champ_Open`, `Ba_Prop_Battle_Champ_Open_02`, `Ba_Prop_Battle_Champ_Open_03`, `PickupBottle`, `Swap_Bottle_Open`, `BottleDetach`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (104), `NETWORK_HAS_CONTROL_OF_ENTITY` (101), `PLAYER_ID` (80), `NETWORK_REQUEST_CONTROL_OF_ENTITY` (53), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (38), `DOES_ENTITY_EXIST` (34), `SET_BIT` (32), `CLEAR_BIT` (26), `NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE` (26), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (19), `NET_TO_PED` (19), `DISABLE_CONTROL_ACTION` (18), `NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE` (16), `SET_TASK_MOVE_NETWORK_SIGNAL_FLOAT` (15), `NETWORK_CREATE_SYNCHRONISED_SCENE` (14), `NETWORK_START_SYNCHRONISED_SCENE` (14), `PLAY_SOUND_FRONTEND` (14), `GET_SYNCHRONIZED_SCENE_PHASE` (11), `ENABLE_CONTROL_ACTION` (11), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (9), `REQUEST_ANIM_DICT` (9), `HAS_ANIM_DICT_LOADED` (9), `IS_PED_INJURED` (9), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (9), `GET_RANDOM_INT_IN_RANGE` (8), `DOES_PARTICLE_FX_LOOPED_EXIST` (7), `GET_HASH_KEY` (7), `CLEAR_HELP` (7), `IS_ENTITY_ATTACHED_TO_ANY_PED` (7), `IS_TASK_MOVE_NETWORK_ACTIVE` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x9 · `0.01f` x8 · `0.25f` x2 · `2724.799f` x1 · `-380.9069f` x1 · `-49.98798f` x1 · `2724.998f` x1 · `-390.5967f` x1 · `-47.41036f` x1 · `5.75f` x1 · `0.45f` x1 · `2.5f` x1 · `1.5f` x1

## Other strings

Literals whose consuming native was not classified:

`Bartender_Outro_Bottle`, `CHAMP_SHAKE`, `SHAKE_INTENSITY`, `HORIZONTAL_AIM`, `VERTICLE_AIM`, `PRIVATE_BAR`, `intro_bartender`, `idle_a_bartender`, `CHAMP_SPRAY`, `CLU_BAR_PROMPT`, `POD_TOO_MANY`, `outro_bartender`, `Bartender_Intro_Bottle`, `Bartender_Idle`, `intro_bottle`, `intro_shot_glass`, `intro_whiskey`, `outro_shot_glass`, `outro_whiskey`, `Bartender_Intro`, `Bartender_Intro_Cam`, `Champagne_Drinking_Mini_Game`, `IntroFinished`, `BottleHold`, `BottleShake`, `ChampagneSpray`, `Outro`, `OutroFinished`, `Bartender_Outro`, `intro_shotglass`

---

Source: `decompiled_scripts/mansion_club_bar.c`
