# am_mp_arcade_peds.c

Minigames script. 69 anim dicts; 26 models.

| | |
|---|---|
| Category | Minigames |
| Total lines | 6,576 |
| Functions | 192 (132 unique, 60 shared) |
| Unique lines | 5,032 (76.5% of file) |

## Assets

**Animation dictionaries** (69) - `world_human_seat_wall_tablet@_male@_idle_a`, `PED_MALE@_STAND_WITHDRINK@_01B@_IDLES_IDLE_A`, `WORLD_HUMAN_STAND_MOBILE@_MALE@_TEXT@_idle_a`, `ANIM@AMB@RANGE@ASSEMBLE_GUNS@Base_W_AR_CarbineRifleMK2`, `ANIM@AMB@RANGE@WEAPON_TEST@Weapon_Test_Busrt_01_W_AR_AssaultRifleMK2`, `JIMMY@_SMOKING_BASE_P_CS_Ciggy_01b_S`, `JIMMY@_SMOKING_IDLE_01_P_CS_Ciggy_01b_S`, `JIMMY@_SMOKING_IDLE_02_P_CS_Ciggy_01b_S`, `JIMMY@_SMOKING_IDLE_03_P_CS_Ciggy_01b_S`, `JIMMY@_DRINKING@_BEER_BASE`, `JIMMY@_DRINKING@_BEER_IDLE_A`, `JIMMY@_DRINKING@_BEER_IDLE_B`, `JIMMY@_DRINKING@_BEER_IDLE_C`, `JIMMY@_DRINKING@_BEER_IDLE_D`, `JIMMY@_DRINKING@_BEER_IDLE_E`, `JIMMY@_DRINKING@_BEER_IDLE_F`, `world_human_stand_mobile@_female@_standing@_call@_idle_a`, `world_human_clipboard@_male@_idle_d`, `WORLD_HUMAN_AA_SMOKE@_MALE@_IDLE_A`, `SWITCH@_MICHAEL@_ON_SOFA_BASE_JIMMY`, `male@_standing@_call@_idle_a`, `AMB@WORLD_HUMAN_LEANING@MALE@WALL@BACK@MOBILE@IDLE_A`, `AMB@WORLD_HUMAN_CLIPBOARD@MALE@IDLE_A_IDLE_A`, `prop_human_seat_computer@_male@_idle_a`, `AMB@WORLD_HUMAN_LEANING@MALE@COFFEE@IDLE_A_IDLE_A`, `ANIM@AMB@RANGE@ASSEMBLE_GUNS@Base_AMY_Skater_01`, `AMB@PROP_HUMAN_SEAT_BAR@MALE@ELBOWS_ON_BAR@IDLE_A`, `JIMMY@_SMOKING_BASE`, `JIMMY@_SMOKING_IDLE_01`, `JIMMY@_SMOKING_IDLE_02`, `JIMMY@_SMOKING_IDLE_03`, `JIMMY@_DRINKING@_BASE`, `JIMMY@_DRINKING@_IDLE_A`, `JIMMY@_DRINKING@_IDLE_B`, `JIMMY@_DRINKING@_IDLE_C`, `JIMMY@_DRINKING@_IDLE_D`, `JIMMY@_DRINKING@_IDLE_E`, `JIMMY@_DRINKING@_IDLE_F`, `PED_MALE@_STAND_WITHDRINK@_01A@_IDLES_IDLE_A`, `PED_MALE@_STAND_WITHDRINK@_01A@_IDLES_IDLE_B`, `PED_MALE@_STAND_WITHDRINK@_01A@_IDLES_IDLE_C`, `PED_MALE@_STAND_WITHDRINK@_01A@_IDLES_IDLE_D`, `PED_MALE@_STAND_WITHDRINK@_01B@_IDLES_IDLE_B`, `PED_MALE@_STAND_WITHDRINK@_01B@_IDLES_IDLE_C`, `PED_MALE@_STAND_WITHDRINK@_01B@_IDLES_IDLE_D`, `PED_FEMALE@_STAND@_03A@_IDLES_IDLE_A`, `PED_FEMALE@_STAND@_03A@_IDLES_IDLE_B`, `PED_FEMALE@_STAND@_03A@_IDLES_IDLE_C`, `PED_FEMALE@_STAND@_03A@_IDLES_IDLE_D`, `PED_FEMALE@_STAND@_03B@_IDLES_IDLE_A`, `PED_FEMALE@_STAND@_03B@_IDLES_IDLE_B`, `PED_FEMALE@_STAND@_03B@_IDLES_IDLE_C`, `PED_FEMALE@_STAND@_03B@_IDLES_IDLE_D`, `PED_FEMALE@_STAND@_02A@_IDLES_CONVO_IDLE_A`, `PED_FEMALE@_STAND@_02A@_IDLES_CONVO_IDLE_B`, `PED_FEMALE@_STAND@_02A@_IDLES_CONVO_IDLE_C`, `PED_FEMALE@_STAND@_02A@_IDLES_CONVO_IDLE_D`, `PED_FEMALE@_STAND_WITHDRINK@_01B@_IDLES_IDLE_A`, `PED_FEMALE@_STAND_WITHDRINK@_01B@_IDLES_IDLE_B`, `PED_FEMALE@_STAND_WITHDRINK@_01B@_IDLES_IDLE_C` ...

**Models and props** (26) - `ex_prop_offchair_exec_03`, `a_m_y_hipster_01`, `prop_tool_broom`, `prop_amb_beer_bottle`, `prop_cs_ciggy_01`, `prop_cs_tablet`, `prop_amb_phone`, `p_cs_clipboard`, `p_amb_coffeecup_01`, `w_ar_carbinerifle`, `w_ar_assaultrifle`, `prop_pencil_01`, `bkr_prop_fakeid_clipboard_01a`, `u_m_m_edtoh`, `s_m_y_xmech_02`, `s_m_y_waretech_01`, `ig_money`, `ig_paige`, `u_m_y_smugmech_01`, `a_f_y_hipster_02`, `a_f_y_hipster_04`, `a_f_y_skater_01`, `a_m_y_beachvesp_01`, `a_m_y_skater_01`, `a_m_y_skater_02`, `a_m_y_stwhi_02`

**Sounds** (1) - `PedDensity`

**Text labels** (15) - `WEPSEXP`, `NULL`, `JIMMY`, `KARIM`, `TALINA`, `EDDIE`, `LIENGINEER`, `CHRISTIAN`, `AVI`, `PAIGE`, `KARL`, `GUSTAVO`, `AIRMECH`, `PACKIE`, `BUMP`

**Hashed names** (3) - `ig_jimmydisanto2`, `ig_wendy`, `AM_MP_ARCADE`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (64), `CLEAR_BIT` (38), `SET_BIT` (30), `DOES_ENTITY_EXIST` (26), `GET_ENTITY_COORDS` (21), `PLAYER_PED_ID` (20), `GET_RANDOM_INT_IN_RANGE` (16), `GET_DISTANCE_BETWEEN_COORDS` (11), `IS_STRING_NULL_OR_EMPTY` (10), `PLAYER_ID` (9), `SET_PED_DEFAULT_COMPONENT_VARIATION` (9), `SET_ENTITY_VISIBLE` (8), `GET_SCRIPT_TASK_STATUS` (6), `SET_ENTITY_ALPHA` (6), `SET_PED_PROP_INDEX` (6), `INT_TO_PARTICIPANTINDEX` (4), `GET_HASH_KEY` (4), `DELETE_OBJECT` (4), `IS_STREAM_PLAYING` (3), `TO_FLOAT` (3), `GET_NETWORK_TIME` (3), `IS_ENTITY_TOUCHING_ENTITY` (3), `CREATE_OBJECT_NO_OFFSET` (3), `SET_ENTITY_COORDS_NO_OFFSET` (3), `SET_ENTITY_ROTATION` (3), `SET_ENTITY_INVINCIBLE` (3), `SET_ENTITY_CAN_BE_DAMAGED` (3), `FREEZE_ENTITY_POSITION` (3), `SET_MODEL_AS_NO_LONGER_NEEDED` (3), `STOP_STREAM` (2)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-55.587f` x4 · `2733.13f` x2 · `-387.578f` x2 · `-49.33f` x2 · `2712.377f` x2 · `-352.966f` x2 · `2714.403f` x2 · `-355.905f` x2 · `2729.589f` x1 · `-383.9195f` x1 · `-48.9951f` x1 · `0.5f` x1 · `0.7f` x1

## Other strings

Literals whose consuming native was not classified:

`ARCADE_LOITER`, `ARCADE_HI`, `ARCADE_BYE`, `ARCADE_BUMP`, `ARCADE_DRIVING`, `hc_gunman`, `amb_world_human_hang_out_street_female_hold_arm_idle_b`, `ARCADE_PHONE`, `ARCADE_TEXTING`, `ARCADE_NOVEHICLE`, `hc_driver`, `mp_m_weapexp_01`, `hc_hacker`, `stockade`, `Walla_Normal`, `DLC_H3_Arcade_Walla_Sounds`, `Inspecting_HIGH_Idle_01_inspector`, `stand_phone_lookaround_nowork`, `amb_world_human_hang_out_street_male_c_base`, `HS3_WENDY`, `BIKE_MECHANIC`, `BTL_YOHAN`, `ARCADE_TV_TURNEDOFF`, `ARCADE_HOWSITGOING`, `ARCADE_TV_OFF`, `ARCADE_WATCHING_TV`, `ARCADE_SMOKING`, `ARCADE_SETUP`, `ARCADE_LOW`, `ARCADE_HIGH`

---

Source: `decompiled_scripts/am_mp_arcade_peds.c`
