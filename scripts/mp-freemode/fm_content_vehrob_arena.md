# fm_content_vehrob_arena.c

MP freemode script. 9 anim dicts; 13 models.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 532,341 |
| Functions | 10,651 (379 unique, 10,272 shared) |
| Unique lines | 14,731 (2.8% of file) |

## Assets

**Animation dictionaries** (9) - `anim@scripted@player@mission@tunf_uni_ig1_elevator_pass_p1@male@`, `anim@scripted@player@mission@tunf_uni_ig1_elevator_pass_p1@heeled@`, `anim@heists@keycard@`, `anim@arena@amb@seat_drone_tablet@female@`, `anim@arena@amb@seat_drone_tablet@male@`, `veh@std@ds@base`, `anim@door_trans@elevator@`, `anim@door_trans@hinge_l@`, `anim@scripted@ulp_missions@fibgreet@male@`

**Animations** (2) - `mini@telescope`, `public_exit_front`

**Models and props** (13) - `xs_prop_x18_vip_greeenlight`, `s_m_y_westsec_01`, `g_m_m_casrn_01`, `s_m_y_westsec_02`, `v_ilev_serv_door01`, `prop_hw1_03_gardoor_01`, `v_62_bannersx`, `v_62_fos_props01`, `xs_prop_arena_bigscreen_01`, `xs_prop_arena_tablet_drone_01`, `ig_hao_02`, `a_m_y_motox_01`, `a_m_y_motox_02`

**Audio banks** (3) - `VEHICLE_SHOP_HUD_1`, `VEHICLE_SHOP_HUD_2`, `DLC_23_2/DLC_23_2_Freemode_1`

**Sounds** (4) - `Barge_Door`, `dlc_h4_Prep_FC_Sounds`, `Bomb_Remove`, `Maze_Bank_Arena_Robbery_Finale_Sounds`

**Speech contexts** (1) - `HAO`

**Text labels** (10) - `08TYR162`, `61FZV673`, `29HNM007`, `05JBI289`, `82ADQ636`, `49YOY154`, `64EKR332`, `TELEUSE`, `XM4R3AU`, `BUMP`

**Scenarios** (1) - `WORLD_HUMAN_WINDOW_SHOP_BROWSE_SHOWROOM`

**Interiors and entity sets** (2) - `GtaMloRoom001`, `Arena_Room`

**Hashed names** (2) - `xs_x18intvip_vip_light_dummy`, `xs_propintarena_structure_s_05b`

## Native vocabulary

Most-called natives inside the code unique to this script:

`DATADICT_GET_ARRAY` (91), `IS_STRING_NULL_OR_EMPTY` (13), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (11), `DISABLE_CONTROL_ACTION` (11), `SET_BIT` (11), `SET_ENTITY_VISIBLE` (9), `NET_TO_ENT` (9), `DOES_ENTITY_EXIST` (9), `FREEZE_ENTITY_POSITION` (7), `SET_PED_COMPONENT_VARIATION` (7), `GET_RANDOM_INT_IN_RANGE` (7), `CLEAR_PED_TASKS` (7), `SET_PED_COMBAT_ATTRIBUTES` (7), `GET_ENTITY_COORDS` (6), `DOES_BLIP_EXIST` (6), `CREATE_MODEL_HIDE` (6), `REMOVE_MODEL_HIDE` (6), `GET_SYNCHRONIZED_SCENE_PHASE` (5), `SET_ENTITY_COORDS` (5), `TO_FLOAT` (5), `REQUEST_SCRIPT_AUDIO_BANK` (5), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (4), `IS_NEW_LOAD_SCENE_ACTIVE` (4), `IS_SCREEN_FADED_OUT` (4), `SET_ENTITY_HEADING` (4), `IS_ENTITY_DEAD` (4), `NETWORK_IS_PARTICIPANT_ACTIVE` (4), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (4), `GET_HASH_KEY` (4), `IS_ENTITY_PLAYING_ANIM` (3)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`181.49f` x4 · `-0.85f` x2 · `24.793f` x2 · `523.982f` x2 · `167.7104f` x2 · `100.5962f` x2 · `2800.957f` x2 · `-3930.407f` x2 · `180.493f` x2 · `2799.999f` x2 · `-3915.813f` x2 · `179.9695f` x2 · `2798.84f` x2 · `-3922.86f` x2 · `1.6f` x2 · `2793.65f` x2 · `-3922.83f` x2 · `1.7f` x2 · `-258.24f` x2 · `-2020.554f` x2 · `35.98f` x2 · `-264.332f` x2 · `-2016.439f` x2 · `31.22f` x2

## Other strings

Literals whose consuming native was not classified:

`pos`, `num`, `head`, `int`, `bsa`, `typ`, `sprt`, `hclr`, `scl`, `veh`, `rot`, `rad`, `ibs`, `enter_tablet`, `MAX_NUM_SCENARIOS`, `blp`, `grp`, `GTAO_Bomb_Plant_Sounds`, `enter`, `exit`, `cavalcade3`, `imperator`, `TIMER_TAR`, `MBA_OT_GOBOX`, `HAO_GARAGE`

---

Source: `decompiled_scripts/fm_content_vehrob_arena.c`
