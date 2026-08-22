# hairdo_shop_mp.c

Shops script. 4 anim dicts; 7 models; 7 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | Shops |
| Total lines | 209,060 |
| Functions | 1,379 (213 unique, 1,166 shared) |
| Unique lines | 24,428 (11.7% of file) |

## Assets

**Animation dictionaries** (4) - `amb@prop_human_seat_chair@male@generic@react_cowering`, `misshair_shop@hair_dressers`, `anim@amb@luxury_suite@spa@barbers`, `misshair_shop@barbers`

**Animations** (11) - `player_base`, `player_exitchair`, `player_intro`, `amb@prop_human_seat_chair@male@generic@react_cowering`, `idle_front`, `keeper_idle_a`, `keeper_idle_b`, `keeper_exitchair`, `player_enterchair`, `keeper_enterchair`, `customer_tutorial`

**Models and props** (7) - `p_cs_scissors_s`, `v_ilev_bs_door`, `s_m_m_hairdress_01`, `a_f_y_business_01`, `a_m_m_business_01`, `s_f_m_fembarber`, `a_m_y_stbla_02`

**Sounds** (8) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `NAV_UP_DOWN`, `SELECT`, `CANCEL`, `Barber_Sounds`, `Scissors`, `Makeup`, `CONTINUOUS_SLIDER`

**Speech contexts** (10) - `SPEECH_PARAMS_FORCE`, `SHOP_HAIR_WHAT_WANT`, `SHOP_CUTTING_HAIR`, `S_M_M_HAIRDRESSER_01_BLACK_MINI_01`, `S_F_M_FEMBARBER_BLACK_MINI_01`, `SHOP_NO_COPS`, `SHOP_GREET_UNUSUAL`, `KIFFLOM_GREET`, `SHOP_GREET`, `SHOP_GOODBYE`

**Scaleform movies** (7) - `SET_IS_PC`, `SET_TITLE`, `SET_DATA_SLOT_EMPTY`, `SET_DATA_SLOT`, `DISPLAY_VIEW`, `SET_HIGHLIGHT`, `SHOW_OPACITY`

**Particle effects** (1) - `scr_barbers_haircut`

**Texture dicts** (2) - `MPShops`, `ShopUI_Title_Graphics_SALE`

**Text labels** (3) - `NONE`, `NULL`, `HAIRDRESSER`

**Scenarios** (2) - `PROP_HUMAN_SEAT_CHAIR_MP_PLAYER`, `WORLD_HUMAN_STAND_IMPATIENT_UPRIGHT`

**Hashed names** (11) - `v_hairdresser`, `v_barbers`, `vw_dlc_casino_apart`, `m25_2_int_mansion`, `wardrobe_mp`, `hairdo_shop_mp`, `torsoDecal`, `Hair_room`, `V_38_BarberRM`, `Apart_Bedroom_Room`, `RM_POOL_SPA`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (264), `ROUND` (256), `TO_FLOAT` (212), `NETWORK_IS_GAME_IN_PROGRESS` (176), `SET_BIT` (115), `PLAYER_ID` (74), `IS_PED_INJURED` (74), `GET_HASH_KEY` (60), `GET_ENTITY_MODEL` (57), `GET_GAME_TIMER` (52), `SET_PED_COMPONENT_VARIATION` (51), `PLAY_SOUND_FRONTEND` (46), `GET_NETWORK_TIME` (41), `DOES_ENTITY_EXIST` (38), `IS_CONTROL_JUST_PRESSED` (38), `GET_PED_DRAWABLE_VARIATION` (34), `IS_STRING_NULL_OR_EMPTY` (33), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (26), `IS_CONTROL_PRESSED` (24), `NET_TO_ENT` (19), `ARE_STRINGS_EQUAL` (19), `CLEAR_PED_TASKS` (18), `BEGIN_SCALEFORM_MOVIE_METHOD` (18), `END_SCALEFORM_MOVIE_METHOD` (18), `SET_PED_CONFIG_FLAG` (17), `GET_SCRIPT_TASK_STATUS` (15), `TASK_PLAY_ANIM_ADVANCED` (13), `GET_PED_TEXTURE_VARIATION` (13), `SET_FORCE_FOOTSTEP_UPDATE` (13), `FORCE_PED_AI_AND_ANIMATION_UPDATE` (12)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.1f` x8 · `0.5f` x6 · `36.5689f` x6 · `-815.86f` x4 · `-183.75f` x4 · `132.08f` x4 · `2.5f` x3 · `0.113f` x2 · `0.255f` x2 · `0.5972f` x2 · `28.2916f` x2 · `1.6f` x1 · `1.777778f` x1 · `1.333333f` x1 · `0.112f` x1 · `0.045f` x1 · `1.5f` x1 · `0.2f` x1 · `0.7181f` x1 · `2.75f` x1 · `0.7525f` x1 · `0.792f` x1 · `0.911f` x1 · `0.883f` x1

## Other strings

Literals whose consuming native was not classified:

`mp_m_freemode_01`, `mp_f_freemode_01`, `ITEM_BACK`, `ITEM_MOV_CAM`, `ITEM_SELECT`, `ITEM_BUY`, `multi_decal`, `CSHOP_FAIL`, `ITEM_ZOOM`, `keeper_base`, `HAIR_UNLOCK`, `MotionState_Walk`, `keeper_idle_a`, `HAIR_UNLOCK_M`, `HAIR_LOCK`, `HAIR_BEARD`, `HAIR_OPTION_2`, `keeper_hair_cut_a`, `keeper_enterchair`, `keeper_exitchair`, `player_base`, `HAIR_LCKPC`, `ITEM_B_OPACITY`, `ITEM_COST`, `player_zero`, `keeper_idle_b`, `keeper_hair_cut_b`, `HAIR_SOFA_STAND`, `casino_item`

---

Source: `decompiled_scripts/hairdo_shop_mp.c`
