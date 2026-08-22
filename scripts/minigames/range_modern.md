# range_modern.c

Minigames script. 3 developer state labels recovered; 2 anim dicts; 11 models; 3 scaleforms.

| | |
|---|---|
| Category | Minigames |
| Total lines | 117,837 |
| Functions | 907 (191 unique, 716 shared) |
| Unique lines | 10,897 (9.2% of file) |

## Developer state labels

Debug strings left in the shipped script. They name its own internal states:

`pedGuy1` · `pedGuy2` · `pedGuy3`

## Assets

**Animation dictionaries** (2) - `mini@shoot_range`, `mini@ears_defenders`

**Animations** (5) - `mini@shoot_range`, `shoot_range_tutorial_plyr`, `shoot_range_tutorial_npc1`, `shoot_range_tutorial_npc2`, `shoot_range_tutorial_npc3`

**Models and props** (11) - `prop_target_backboard`, `prop_target_arm`, `prop_target_comp_wood`, `prop_target_arm_b`, `v_ilev_gc_door01`, `prop_ear_defenders_01`, `prop_target_arm_long`, `prop_target_arm_sm`, `prop_target_backboard_b`, `prop_target_comp_metal`, `prop_safety_glasses`

**Audio banks** (3) - `SCRIPT\TARGET_PRACTICE`, `SCRIPT\HUD_321_GO`, `HUD_AWARDS`

**Sounds** (11) - `TARGET_PRACTICE_FLIP_MASTER`, `HUD_AWARDS`, `TARGET_PRACTICE_SLIDE_MASTER`, `LOSER`, `SHOOTING_RANGE_ROUND_OVER`, `MEDAL_BRONZE`, `MEDAL_SILVER`, `MEDAL_GOLD`, `TARGET_PRACTICE_STOP_MASTER`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `HUD_MINI_GAME_SOUNDSET`

**Scaleform movies** (3) - `RESET_MOVIE`, `STRING`, `SHR_CHALL_NAME`

**Texture dicts** (8) - `SRange_Gen`, `SRange_Chal`, `SRange_Chal2`, `SRange_Weap`, `SRange_Weap2`, `MPMedals_FEED`, `Shared`, `CommonMenu`

**Text labels** (17) - `NUMBER`, `BACK`, `SELECT`, `SHR_CHALL_NAME`, `MPMedals_FEED`, `Feed_Medal_ShootingRange`, `HUD_MED_UNLKED`, `SMG`, `LMG`, `MULTIPLIER`, `NULL`, `NONE`, `HVY`, `QUIT`, `SCLB`, `PIS`, `SHO`

**Interiors and entity sets** (1) - `V_7_ShootRm`

**Doors** (1) - `v_ilev_gc_door01`

**Stats** (48) - `sp0_weap_purch_0`, `sp1_weap_purch_0`, `sp2_weap_purch_0`, `sp0_weap_purch_1`, `sp1_weap_purch_1`, `sp2_weap_purch_1`, `sp0_weap_purch_2`, `sp1_weap_purch_2`, `sp2_weap_purch_2`, `sp0_cmbtpistol_heldtime`, `sp1_cmbtpistol_heldtime`, `sp2_cmbtpistol_heldtime`, `sp0_appistol_heldtime`, `sp1_appistol_heldtime`, `sp2_appistol_heldtime`, `sp0_microsmg_heldtime`, `sp1_microsmg_heldtime`, `sp2_microsmg_heldtime`, `sp0_smg_heldtime`, `sp1_smg_heldtime`, `sp2_smg_heldtime`, `sp0_asltrifle_heldtime`, `sp1_asltrifle_heldtime`, `sp2_asltrifle_heldtime`, `sp0_crbnrifle_heldtime`, `sp1_crbnrifle_heldtime`, `sp2_crbnrifle_heldtime`, `sp0_advrifle_heldtime`, `sp1_advrifle_heldtime`, `sp2_advrifle_heldtime`, `sp0_pump_heldtime`, `sp1_pump_heldtime`, `sp2_pump_heldtime`, `sp0_sawnoff_heldtime`, `sp1_sawnoff_heldtime`, `sp2_sawnoff_heldtime`, `sp0_asltshtgn_heldtime`, `sp1_asltshtgn_heldtime`, `sp2_asltshtgn_heldtime`, `sp0_mg_heldtime`, `sp1_mg_heldtime`, `sp2_mg_heldtime`, `sp0_cmbtmg_heldtime`, `sp1_cmbtmg_heldtime`, `sp2_cmbtmg_heldtime`, `sp0_miniguns_heldtime`, `sp1_miniguns_heldtime`, `sp2_miniguns_heldtime`

**Hashed names** (2) - `PROP_TARGET_FRAG_BOARD`, `BONEMASK_HEAD_NECK_AND_L_ARM`

## Native vocabulary

Most-called natives inside the code unique to this script:

`STAT_GET_INT` (49), `PLAYER_PED_ID` (48), `DOES_ENTITY_EXIST` (35), `GET_GAME_TIMER` (30), `PLAYER_ID` (23), `PLAY_SOUND_FROM_ENTITY` (17), `ATTACH_ENTITY_TO_ENTITY` (17), `IS_ENTITY_DEAD` (14), `GET_ENTITY_COORDS` (14), `HAS_MODEL_LOADED` (14), `DISABLE_CONTROL_ACTION` (13), `CLEAR_PED_PROP` (13), `HAS_PED_GOT_WEAPON` (13), `SET_ENTITY_AS_MISSION_ENTITY` (12), `DELETE_OBJECT` (11), `IS_CONTROL_JUST_RELEASED` (11), `REQUEST_MODEL` (11), `CLEAR_HELP` (10), `SET_STATIC_EMITTER_ENABLED` (10), `DRAW_DEBUG_TEXT_2D` (10), `IS_BULLET_IN_ANGLED_AREA` (10), `IS_WEAPON_VALID` (10), `RENDER_SCRIPT_CAMS` (9), `SET_PLAYER_CONTROL` (9), `CLEAR_ENTITY_LAST_WEAPON_DAMAGE` (9), `STOP_SOUND` (8), `SET_BIT` (8), `CREATE_OBJECT_NO_OFFSET` (8), `HAS_STREAMED_TEXTURE_DICT_LOADED` (8), `REQUEST_STREAMED_TEXTURE_DICT` (8)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.007f` x13 · `0.5f` x7 · `0.25f` x6 · `-2160.619f` x6 · `0.15f` x6 · `-0.76f` x5 · `0.73333f` x5 · `0.05f` x4 · `28.79702f` x4 · `-2161.619f` x4 · `-0.45f` x4 · `-1.117f` x4 · `24.657f` x3 · `34.657f` x3 · `-1.5f` x2 · `42.3427f` x2 · `28.619f` x2 · `-0.04f` x2 · `-0.41f` x2 · `0.75f` x2 · `829.375f` x2 · `813.625f` x2 · `0.01f` x2 · `0.8f` x1

## Other strings

Literals whose consuming native was not classified:

`SRange_Gen`, `Hit_Cross`, `SRange_Chal`, `NAV_UP_DOWN`, `CommonMenu`, `Chal_Mini_Target_64`, `Shared`, `SHR_ENDASH`, `SHR_X_HITS`, `RNG_XSCORE`, `Common_Medal`, `Icon_Target_32`, `LOS_SANTOS_AMMUNATION_GUN_RANGE`, `SE_AMMUNATION_CYPRESS_FLATS_GUN_RANGE`, `FE_HLP3`, `Locked_Icon_32`, `IB_QUIT`, `SHR_GEN_REQ`, `DEFAULT_SCRIPTED_CAMERA`, `MenuPlus_32`, `HUD_MULTSMAL`, `SCLB_PROFILE`, `shop_NEW_Star`, `WT_RAILGUN`, `Shooting_Bronze_128`, `Shooting_Silver_128`, `Shooting_Gold_128`, `WTT_PIST`

---

Source: `decompiled_scripts/range_modern.c`
