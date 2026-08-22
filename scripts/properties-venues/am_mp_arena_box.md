# am_mp_arena_box.c

Properties and venues script. 14 anim dicts; 10 models; 4 scaleforms; 6 particle effects.

| | |
|---|---|
| Category | Properties and venues |
| Total lines | 399,509 |
| Functions | 7,424 (266 unique, 7,158 shared) |
| Unique lines | 20,156 (5.0% of file) |

## Assets

**Animation dictionaries** (14) - `anim@amb@nightclub@mini@drinking@bar@drink@base`, `anim@amb@nightclub@mini@drinking@bar@drink@idle_a`, `ANIM@AMB@NIGHTCLUB@MINI@DRINKING@CHAMPAGNE_DRINKING@BASE@`, `anim@amb@nightclub@mini@drinking@bar@drink@beer`, `anim@amb@nightclub@mini@drinking@bar@drink@one`, `anim@amb@nightclub@mini@drinking@bar@drink@two`, `anim@amb@nightclub@mini@drinking@bar@drink@three`, `anim@amb@nightclub@mini@drinking@bar@drink@four`, `anim@arena@amb@seating@seat_a@`, `anim@arena@amb@seating@seat_b@`, `anim@arena@amb@seating@seat_c@`, `anim@arena@amb@seating@seat_d@`, `ANIM@ARENA@PRIZE_WHEEL@FEMALE`, `ANIM@ARENA@PRIZE_WHEEL@MALE`

**Animations** (9) - `BASE`, `IDLE_A`, `IDLE_B`, `WIN_1`, `WIN_2`, `WIN_3`, `LOSE_1`, `LOSE_2`, `LOSE_3`

**Models and props** (10) - `lux_prop_cigar_01_luxe`, `lux_prop_ashtray_luxe_01`, `prop_cs_beer_bot_01`, `ex_prop_exec_lighter_01`, `xs_prop_arena_roulette`, `ba_prop_battle_decanter_02_s`, `p_whiskey_bottle_s`, `p_cs_shot_glass_2_s`, `ba_prop_battle_shot_glass_01`, `xs_prop_arena_champ_closed`

**Audio banks** (4) - `DLC_BATTLE/BTL_CHAMPAGNE_MINIGAME`, `SAFEHOUSE_TREVOR_DRINK_WHISKEY`, `SAFEHOUSE_FRANKLIN_SOFA`, `SCRIPT/SAFEHOUSE_TREVOR_DRINK_WHISKEY`

**Sounds** (8) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `ERROR`, `SELECT`, `BACK`, `PICK_UP`, `Wheel_Spin_Start`, `DLC_AW_Arena_Spin_Wheel_Game_Sounds`

**Speech contexts** (1) - `SPEECH_PARAMS_FORCE`

**Scaleform movies** (4) - `SPIN_THE_WHEEL`, `SPIN_WHEEL`, `SET_SEGMENT`, `SET_WHEEL_STYLE`

**Particle effects** (6) - `scr_safehouse`, `scr_sh_lighter_sparks`, `scr_sh_lighter_flame`, `scr_sh_cig_smoke`, `scr_sh_cig_exhale_mouth`, `scr_sh_cig_exhale_nose`

**Text labels** (5) - `BASE`, `NULL`, `BUMP`, `SPIN`, `ENTER`

**Interiors and entity sets** (1) - `VIP_ROOM`

**Scripts launched** (1) - `arena_box_bench_seats`

**Hashed names** (10) - `xs_propintarena_structure_s_05b`, `SNK_ITEM6`, `vfx_xs_cig_smoke_exhale`, `xs_x18intvip_vip_light_dummy`, `AM_MP_DRONE`, `vfx_xs_lighter_sparks`, `vfx_xs_lighter_flame_start`, `vfx_xs_lighter_flame_stop`, `vfx_xs_cig_smoke_start`, `vfx_xs_cig_smoke_stop`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_BIT` (171), `PLAYER_PED_ID` (117), `PLAYER_ID` (117), `CLEAR_BIT` (111), `DISABLE_CONTROL_ACTION` (92), `CLEAR_HELP` (38), `DOES_ENTITY_EXIST` (33), `HAS_ANIM_DICT_LOADED` (24), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (24), `NETWORK_HAS_CONTROL_OF_ENTITY` (24), `REMOVE_ANIM_DICT` (24), `GET_PLAYER_PED` (24), `REQUEST_ANIM_DICT` (23), `IS_ENTITY_PLAYING_ANIM` (22), `GET_ANIM_INITIAL_OFFSET_POSITION` (21), `GET_ANIM_INITIAL_OFFSET_ROTATION` (21), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (20), `GET_SYNCHRONIZED_SCENE_PHASE` (19), `NET_TO_PED` (18), `ENABLE_CONTROL_ACTION` (18), `REQUEST_MODEL` (18), `HAS_MODEL_LOADED` (18), `SET_MODEL_AS_NO_LONGER_NEEDED` (18), `SET_ENTITY_CAN_BE_DAMAGED` (18), `SET_ENTITY_CAN_ONLY_BE_DAMAGED_BY_SCRIPT_PARTICIPANTS` (18), `SET_ENTITY_COORDS_NO_OFFSET` (18), `IS_SYNCHRONIZED_SCENE_RUNNING` (18), `IS_PED_INJURED` (17), `GET_HASH_KEY` (17), `CREATE_OBJECT` (17)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.01f` x16 · `1.5f` x9 · `182.6357f` x8 · `184.6357f` x8 · `0.99f` x7 · `0.05f` x4 · `0.96f` x4 · `183.4106f` x3 · `2799.999f` x3 · `-3915.813f` x3 · `179.9695f` x3 · `0.15f` x3 · `0.75f` x2 · `-0.025f` x2 · `2800.957f` x2 · `-3930.407f` x2 · `180.493f` x2 · `2802.511f` x2 · `-3936.38f` x2 · `187.7886f` x2 · `-26.8913f` x2 · `-3919.735f` x2 · `184.5086f` x2 · `-40.7704f` x2

## Other strings

Literals whose consuming native was not classified:

`lux_prop_cigar_01_luxe`, `lux_prop_ashtray_luxe_01`, `WS_IC_V_FSPIN`, `WS_IC_V_PAY`, `WS_V_INVALID`, `WS_IC_EXIT`, `WS_CTRL1`, `WS_CTRL2`, `WS_CTRL3`, `WS_CTRL4`, `SNK_AFFORD`, `purchase`, `WS_AP_HELP`, `WS_IC_PAY`, `WS_INVALID`, `WS_IC_FREESPIN`, `WS_COOLDOWN`, `LOSE_2`, `WIN_1`, `WIN_2`, `WIN_3`, `idle_a_bartender`, `arena_roulette`, `WS_BLOCKED`, `LOSE_3`, `LOSE_1`, `service_spend_arena_spectator_box`, `base_ashtray_ab`, `base_ashtray_cd`, `base_cigar_a`

---

Source: `decompiled_scripts/am_mp_arena_box.c`
