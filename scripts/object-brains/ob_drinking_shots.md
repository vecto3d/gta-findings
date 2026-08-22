# ob_drinking_shots.c

Object brains script. 1 anim dicts; 16 models.

| | |
|---|---|
| Category | Object brains |
| Total lines | 97,996 |
| Functions | 481 (25 unique, 456 shared) |
| Unique lines | 2,714 (2.8% of file) |

## Assets

**Animation dictionaries** (1) - `MP_SAFEHOUSEWHISKEY@`

**Models and props** (16) - `prop_radio_01`, `p_tumbler_02_s1`, `p_tumbler_cs2_s`, `p_tumbler_cs2_s_trev`, `p_wine_glass_s`, `prop_cs_beer_bot_01`, `prop_bong_01`, `p_w_grass_gls_s`, `prop_rolled_sock_02`, `p_whiskey_bottle_s`, `ig_8_huff_gas_rag`, `ig_2_wheatgrassdrink_glass`, `ig_2_wheatgrass_drink_michael`, `prop_cigar_03`, `p_cs_joint_01`, `prop_mr_raspberry_01`

**Sounds** (2) - `TREVOR_SAFEHOUSE_ACTIVITIES_SCENE`, `MICHAEL_SAFEHOUSE_ACTIVITIES_SCENE`

**Text labels** (1) - `NULL`

**Stats** (2) - `num_sh_whiskey`, `num_sh_beer_drunk`

**Scripts launched** (1) - `family5`

**Hashed names** (1) - `rm_mid_lounge`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (48), `PLAY_SYNCHRONIZED_ENTITY_ANIM` (21), `DISABLE_CONTROL_ACTION` (16), `PLAYER_ID` (15), `HIDE_HUD_AND_RADAR_THIS_FRAME` (14), `GET_SYNCHRONIZED_SCENE_PHASE` (13), `DOES_ENTITY_EXIST` (11), `CREATE_SYNCHRONIZED_SCENE` (9), `CLEAR_HELP` (9), `TASK_SYNCHRONIZED_SCENE` (8), `FIND_ANIM_EVENT_PHASE` (6), `IS_PED_INJURED` (5), `SET_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (5), `IS_SYNCHRONIZED_SCENE_RUNNING` (5), `IS_CONTROL_JUST_PRESSED` (5), `DOES_ENTITY_HAVE_DRAWABLE` (4), `GET_ENTITY_HEADING` (4), `IS_SYNCHRONIZED_SCENE_HOLD_LAST_FRAME` (4), `IS_ENTITY_VISIBLE` (4), `SET_ENTITY_VISIBLE` (4), `SET_ENTITY_COLLISION` (4), `NETWORK_IS_GAME_IN_PROGRESS` (3), `FREEZE_ENTITY_POSITION` (3), `SET_PLAYER_CONTROL` (3), `SET_PLAYER_CLOTH_PACKAGE_INDEX` (3), `PLAY_FACIAL_ANIM` (3), `SET_SYNCHRONIZED_SCENE_LOOPED` (3), `PLAY_ENTITY_ANIM` (3), `HAS_FORCE_CLEANUP_OCCURRED` (2), `FORCE_ROOM_FOR_ENTITY` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.99f` x5 · `0.75f` x4 · `0.05f` x2 · `0.2f` x1 · `2.5f` x1 · `0.25f` x1

## Other strings

Literals whose consuming native was not classified:

`drink_1_cap`, `drink_2_bottle`, `drink_3_bottle`, `drink_4_bottle`, `drink_3_cap`, `SA_SHOT2`, `drink_4_cap`, `enter_cap`, `first_shot_bot`, `drink_2_cap`, `drink_2_shotglass`, `drink_4_shotglass`, `first_shot_glass`, `drink_1_beer`, `drink_1_bottle`, `drink_2_trevor`, `drink_4_trevor`, `first_shot`, `drink_1`, `drink_1_michael`, `drink_3_michael`, `enter`, `enter_bot`, `WalkInterruptible`, `exit_sober_facial`, `exit_slightly_drunk_facial`, `drink_5_bottle`, `third_shot_bot`, `fourth_shot_bot`, `fifth_shot_bot`

---

Source: `decompiled_scripts/ob_drinking_shots.c`
