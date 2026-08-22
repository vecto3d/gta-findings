# hunting_ambient.c

Jobs script. 8 anim dicts; 10 models; 4 scaleforms; 1 particle effects.

| | |
|---|---|
| Category | Jobs |
| Total lines | 114,474 |
| Functions | 863 (160 unique, 703 shared) |
| Unique lines | 10,806 (9.4% of file) |

## Assets

**Animation dictionaries** (8) - `oddjobs@hunterOutro`, `oddjobs@hunterIntro`, `creatures@deer@amb@world_deer_grazing@enter`, `creatures@deer@amb@world_deer_grazing@idle_a`, `creatures@deer@amb@world_deer_grazing@exit`, `creatures@deer@amb@world_deer_grazing@base`, `creatures@cougar@melee@`, `facials@p_m_one@variations@elkcall`

**Animations** (17) - `creatures@deer@amb@world_deer_grazing@idle_a`, `creatures@deer@amb@world_deer_grazing@base`, `base`, `creatures@deer@amb@world_deer_grazing@enter`, `enter`, `idle_b`, `creatures@deer@amb@world_deer_grazing@exit`, `exit`, `_Trevor`, `idle_a`, `idle_c`, `oddjobs@hunterOutro`, `creatures@cougar@melee@`, `growling`, `facials@p_m_one@variations@elkcall`, `mood_elkcal_1`, `oddjobs@hunterIntro`

**Models and props** (10) - `a_c_mtlion`, `a_c_deer`, `a_c_coyote`, `a_c_boar`, `blazer`, `a_c_chickenhawk`, `a_c_cormorant`, `a_c_crow`, `a_c_pigeon`, `a_c_seagull`

**Audio banks** (4) - `SCRIPT\HUNTING_2_ELK_CALLS`, `SCRIPT\HUNTING_2_ELK_VOCALS`, `SCRIPT\HUNTING_MAIN_A`, `HUD_AWARDS`

**Sounds** (24) - `HUNTING_02_SETTINGS`, `ELK_PAIN_MASTER`, `HUD_AWARDS`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `Concentration`, `ELK_BREY_MASTER`, `CHALLENGE_UNLOCKED`, `NAV_UP_DOWN`, `LEADERBOARD_SCENE`, `SELECT`, `AMBIENT_HUNTING_MIX`, `MEDAL_GOLD`, `LOSER`, `CANCEL`, `Heart_Breathing`, `Breathing`, `PLAYER_CALLS_ELK_MASTER`, `MEDAL_BRONZE`, `MEDAL_SILVER`, `LEADER_BOARD`, `BACK`, `QUIT_WHOOSH`, `HUD_MINI_GAME_SOUNDSET`, `HUD_FRONTEND_MP_SOUNDSET`

**Speech contexts** (1) - `TREVOR_NORMAL`

**Scaleform movies** (4) - `CLEAR_ALL_SLOTS`, `MP_BIG_MESSAGE_FREEMODE`, `RESET_MOVIE`, `STRING`

**Particle effects** (1) - `ent_amb_insect_plane`

**Texture dicts** (4) - `CommonMenu`, `Hunting`, `MPLeaderboard`, `MPHud`

**Text labels** (19) - `HCONT`, `HRETRY`, `HLEADR`, `Hunting`, `HUD_MED_UNLKED`, `HUNT`, `NULL`, `AHT_RTIT`, `Hunting_Gold_128`, `HLEFT1`, `HWANTED`, `HCHEND`, `HLEFT`, `HWRONG`, `HNOTIME`, `LATE`, `Hunting_Bronze_128`, `Hunting_Silver_128`, `AMBHT`

**Decorators** (7) - `hunt_score`, `doe_elk`, `hunt_weapon`, `hunt_kill_time`, `hunt_chal_weapon`, `hunt_undetected`, `hunt_nocall`

**Relationship groups** (1) - `Elk Group`

**Hashed names** (4) - `AR_knife_low_kick_far`, `AR_knife_low_kick_close`, `ACT_low_kick_close`, `ACT_low_kick_far`

## Native vocabulary

Most-called natives inside the code unique to this script:

`GET_GAME_TIMER` (133), `PLAYER_PED_ID` (91), `DOES_ENTITY_EXIST` (42), `SET_BIT` (40), `GET_ENTITY_COORDS` (35), `GET_RANDOM_INT_IN_RANGE` (33), `GET_SHOP_PED_APPAREL_FORCED_COMPONENT_COUNT` (31), `GET_FORCED_COMPONENT` (31), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (30), `GET_RANDOM_FLOAT_IN_RANGE` (24), `LEADERBOARDS2_READ_GET_ROW_DATA_INT` (23), `PLAYER_ID` (21), `TASK_PLAY_ANIM` (20), `IS_ENTITY_DEAD` (20), `CLEAR_BIT` (17), `IS_PED_INJURED` (17), `PLAY_SOUND_FROM_ENTITY` (17), `PLAY_SOUND_FRONTEND` (16), `LEADERBOARDS2_READ_GET_ROW_DATA_FLOAT` (13), `SET_BLIP_ALPHA` (13), `DECOR_EXIST_ON` (12), `HAS_ENTITY_BEEN_DAMAGED_BY_WEAPON` (12), `GET_DISTANCE_BETWEEN_COORDS` (11), `IS_SPHERE_VISIBLE` (11), `SET_ENTITY_AS_MISSION_ENTITY` (11), `LEADERBOARDS2_READ_GET_ROW_DATA_INFO` (11), `HIDE_HUD_AND_RADAR_THIS_FRAME` (10), `GET_ITEMSET_SIZE` (10), `DOES_BLIP_EXIST` (10), `LEADERBOARDS2_READ_GET_ROW_DATA_END` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`-1707.434f` x6 · `4666.563f` x6 · `22.1095f` x6 · `1.5f` x3 · `0.99f` x3 · `323.2491f` x2 · `0.1f` x2 · `0.5f` x2 · `-1705.311f` x1 · `4664.68f` x1 · `38.8278f` x1 · `10.2934f` x1 · `-1.8316f` x1 · `-85.2144f` x1 · `42.79f` x1 · `0.25f` x1 · `359.9f` x1 · `-1702.695f` x1 · `4666.941f` x1 · `22.7091f` x1 · `-1708.517f` x1 · `4663.869f` x1 · `44.9329f` x1 · `6.5082f` x1

## Other strings

Literals whose consuming native was not classified:

`MinigameTransitionIn`, `MinigameTransitionOut`, `vest_shirt`, `open_collar`, `tie`, `HUNT_RESULT`, `AHT_MEDAL_EARN`, `FMMC_COR_SCLB5`, `FMMC_COR_SCLB6`, `SCLB_C_RANK`, `HUNTUI_RANKUP`, `HUNTUI_COMPLETE`, `AHT_MISS`, `AMMO_SNIPER`, `_Trevor_cam`, `_Trevor_journey`, `blazer`, `open_short`, `tux_vest`, `loose_tie`, `loose_bowtie`, `HUNTING_MISSED`, `HUNTING_SPOT_ANIMAL`, `AHT_CALL`, `GROUP_SNIPER`, `AHT_PHOTO`, `AHT_HIGHSCORE`, `HT_BACK_PMT`, `SCLB_PROFILE`

---

Source: `decompiled_scripts/hunting_ambient.c`
