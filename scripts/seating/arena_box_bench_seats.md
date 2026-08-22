# arena_box_bench_seats.c

Seating and sitting script. 4 anim dicts; 2 models.

| | |
|---|---|
| Category | Seating and sitting |
| Total lines | 4,727 |
| Functions | 174 (44 unique, 130 shared) |
| Unique lines | 2,181 (46.1% of file) |

## Assets

**Animation dictionaries** (4) - `anim@arena@amb@seat_drone_tablet@female@`, `anim@arena@amb@seat_drone_tablet@male@`, `ANIM@AMB@FACILITY@BRIEFING_ROOM@SEATING`, `ANIM@ARENA@AMB@SEAT_DRONE_TABLET`

**Models and props** (2) - `xs_prop_x18_vip_greeenlight`, `xs_prop_arena_tablet_drone_01`

**Sounds** (10) - `DLC_AW_Spectator_Tablet_Sounds`, `ERROR`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Exit_Menu`, `Enter_Menu`, `Select_Turret`, `Select_Drone`, `Select_RC_Car`, `Select_Trap_Cam`, `Select_Live_Stream`

**Text labels** (4) - `ENTER`, `BASE`, `EXIT`, `NULL`

**Hashed names** (1) - `AM_MP_ARENA_BOX`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (38), `PLAYER_PED_ID` (32), `NET_TO_OBJ` (30), `SET_BIT` (20), `IS_CONTROL_JUST_PRESSED` (19), `CLEAR_BIT` (16), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (14), `NETWORK_HAS_CONTROL_OF_NETWORK_ID` (14), `IS_DISABLED_CONTROL_JUST_PRESSED` (12), `DISABLE_CONTROL_ACTION` (10), `PLAY_SOUND_FROM_ENTITY` (9), `NETWORK_REQUEST_CONTROL_OF_NETWORK_ID` (7), `DETACH_ENTITY` (6), `IS_ENTITY_ATTACHED` (6), `GET_ANIM_INITIAL_OFFSET_ROTATION` (5), `GET_PLAYER_TEAM` (5), `HAS_ANIM_EVENT_FIRED` (5), `PLAY_SOUND_FRONTEND` (5), `GET_ANIM_INITIAL_OFFSET_POSITION` (4), `GET_GAME_TIMER` (4), `DOES_ENTITY_EXIST` (3), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (3), `IS_SYNCHRONIZED_SCENE_RUNNING` (3), `NETWORK_STOP_SYNCHRONISED_SCENE` (3), `IS_NEW_LOAD_SCENE_ACTIVE` (3), `SET_ENTITY_COORDS_NO_OFFSET` (3), `SET_ENTITY_ROTATION` (3), `FREEZE_ENTITY_POSITION` (3), `CREATE_MODEL_HIDE` (3), `NETWORK_CREATE_SYNCHRONISED_SCENE` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x4 · `2797.988f` x2 · `181.0005f` x2 · `2797.949f` x2 · `187.4114f` x2 · `-3954.898f` x1 · `-3930.85f` x1 · `0.05f` x1 · `-1.5f` x1 · `0.25f` x1 · `0.7f` x1 · `-3943.898f` x1 · `-3919.85f` x1

## Other strings

Literals whose consuming native was not classified:

`enter_tablet`, `ARENA_SEAT`, `ARENA_SEAT_PC`, `ARENA_SEAT1`, `ARENA_SEAT_PC1`, `ARENA_SEAT2`, `ARENA_SEAT_PC2`, `ARENA_SEAT3`, `ARENA_SEAT_PC3`, `ARENA_SEAT_EX`, `ARENA_VIP_CASH1`, `ARENA_VIP_CASH2`, `ARENA_VIP_ABIL`, `ARENA_SEAT4`, `ARENA_SEAT_PC4`, `ARENA SPECTATOR BOX TABLETS`, `IDLE_A`, `IDLE_B`, `IDLE_C`, `A_TO_B`, `B_TO_C`, `C_TO_D`, `D_TO_E`, `B_TO_E`, `C_TO_A`, `D_TO_A`, `E_TO_A`, `invalid_clip`, `MPOFSEAT_PCEXIT`, `MPOFSEAT_EXIT`

---

Source: `decompiled_scripts/arena_box_bench_seats.c`
