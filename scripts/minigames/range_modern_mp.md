# range_modern_mp.c

Minigames script. 1 developer state labels recovered; 8 models; 2 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 161,254 |
| Functions | 1,845 (180 unique, 1,665 shared) |
| Unique lines | 10,083 (6.3% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`Shooting Disabled`

## Assets

**Models and props** (8) - `prop_target_ora_purp_01`, `prop_target_red_cross`, `prop_target_backboard_b`, `prop_target_frame_01`, `prop_ear_defenders_01`, `prop_safety_glasses`, `prop_target_arm`, `prop_target_arm_sm`

**Audio banks** (2) - `TARGET_PRACTICE`, `HUD_321_GO`

**Sounds** (16) - `10_SEC_WARNING`, `HUD_MINI_GAME_SOUNDSET`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `MP_CELEB_SCREEN_SCENE`, `BACK`, `TARGET_PRACTICE_FLIP_MASTER`, `NAV_UP_DOWN`, `TIMER_STOP_MASTER`, `Hit_1`, `LONG_PLAYER_SWITCH_SOUNDS`, `SHOOTING_RANGE_ROUND_OVER`, `HUD_AWARDS`, `TARGET_PRACTICE_SLIDE_MASTER`, `TARGET_PRACTICE_STOP_MASTER`, `LEADER_BOARD`, `SELECT`

**Scaleform movies** (2) - `RESET_MOVIE`, `STRING`

**Texture dicts** (8) - `MPHUD`, `MPSRange`, `SRange_Gen`, `SRange_Chal`, `SRange_Chal2`, `SRange_Weap`, `SRange_Weap2`, `Shared`

**Text labels** (11) - `NUMBER`, `SUMMARY`, `SR_SPEC_WAITING`, `SCLB`, `STRING`, `NULL`, `MULTIPLIER`, `GRID`, `RANDOM`, `COVERED`, `WINNER`

**Interiors and entity sets** (2) - `V_Gun`, `V_7_ShootRm`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_ID` (72), `SET_BIT` (68), `IS_ENTITY_DEAD` (49), `PLAYER_PED_ID` (49), `DISABLE_CONTROL_ACTION` (40), `PLAY_SOUND_FRONTEND` (34), `CLEAR_BIT` (32), `DELETE_ENTITY` (28), `SET_ENTITY_ROTATION` (25), `TO_FLOAT` (20), `SET_ENTITY_HEADING` (17), `SET_ENTITY_COORDS` (16), `GET_GAME_TIMER` (16), `IS_CONTROL_JUST_RELEASED` (16), `PARTICIPANT_ID_TO_INT` (14), `INT_TO_PARTICIPANTINDEX` (13), `CLEAR_HELP` (13), `ATTACH_ENTITY_TO_ENTITY` (13), `NETWORK_GET_PLAYER_INDEX` (12), `SET_PLAYER_CONTROL` (12), `SET_CAM_PARAMS` (12), `CREATE_OBJECT_NO_OFFSET` (12), `RENDER_SCRIPT_CAMS` (10), `CLEAR_ENTITY_LAST_DAMAGE_ENTITY` (10), `GET_PLAYER_NAME` (10), `GET_FRAME_TIME` (9), `HAS_PED_GOT_WEAPON` (9), `IS_SCREEN_FADED_OUT` (8), `HAS_STREAMED_TEXTURE_DICT_LOADED` (8), `REQUEST_STREAMED_TEXTURE_DICT` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x16 · `-0.41f` x8 · `0.73333f` x5 · `-0.03f` x4 · `-0.04f` x2 · `0.007f` x2 · `0.1f` x2 · `0.03f` x2 · `-0.1f` x2 · `-1.2f` x2 · `0.24f` x1 · `-0.76f` x1 · `0.25f` x1 · `6.594f` x1 · `-1100.162f` x1 · `28.797f` x1 · `0.05f` x1 · `0.9f` x1 · `-0.45f` x1 · `0.22f` x1 · `0.0125f` x1 · `1.75f` x1

## Other strings

Literals whose consuming native was not classified:

`MPSRange`, `PanelBack`, `IB_QUIT`, `CommonMenu`, `Common_Medal`, `SHR_ENDASH`, `RANGE_OVER`, `U_CHOOSE`, `SHR_SC_CONT`, `SR_SPEC_WAITING`, `SHR_MP_MATCHOV`, `SHR_MP_NRND`, `FE_HLP4`, `O_CHOOSE`, `FE_HLP3`, `SHR_QUIT_RANGE`, `SHR_QUIT_DET`, `SHR_SPEC_RND`, `BM_R2P_WIN`, `BM_R2P_LOSS`, `SHR_MP_OSCORE_C`, `SRange_Gen`, `Shared`, `SRange_Weap2`, `SRange_Chal`, `SC_COM_TIMEUP`, `SHR_MP_Q_LV`, `XPT_RANGE`, `CELL_286`, `SHR_MP_WAITSC`

---

Source: `decompiled_scripts/range_modern_mp.c`
