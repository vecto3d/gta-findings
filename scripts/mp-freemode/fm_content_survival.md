# fm_content_survival.c

MP freemode script. 7 anim dicts; 19 models; 23 particle effects.

| | |
|---|---|
| Category | MP freemode |
| Total lines | 542,153 |
| Functions | 10,962 (519 unique, 10,443 shared) |
| Unique lines | 15,398 (2.8% of file) |

## Assets

**Animation dictionaries** (7) - `clipset@anim@ingame@move_m@zombie@core`, `anim@scripted@surv@ig2_zombie_spawn@shambler@`, `move_characters@orleans@core@`, `get_up@standard`, `get_up@directional@movement@from_knees@action`, `GET_UP@DIRECTIONAL@TRANSITION@PRONE_TO_KNEES@INJURED`, `ANIM@SCRIPTED@FREEMODE@IG2_GHOST@`

**Animations** (3) - `front`, `walk`, `action_01`

**Models and props** (19) - `ig_orleans`, `u_m_y_rsranger_01`, `u_m_y_pogo_01`, `s_m_m_movalien_01`, `u_m_y_imporage`, `prop_rub_pile_01`, `prop_laptop_01a`, `prop_skip_05b`, `u_m_m_yulemonster`, `xs_prop_hamburgher_wl`, `prop_gate_cult_01_l`, `prop_gate_cult_01_r`, `xs_prop_nacho_wl`, `u_m_m_yeti`, `s_m_m_movspace_01`, `ig_furry`, `s_m_y_clown_01`, `mp_m_freemode_01`, `s_m_m_fiboffice_01`

**Audio banks** (4) - `DLC_24-1/GH_DM_01`, `DLC_25-1/DLC_25-1_GH_JN_01`, `DLC_MP2023_1/DLC_MP2023_1_GH`, `DLC_CM2022/CM2022_DAX_1_4`

**Sounds** (23) - `DLC_CM2022_DRUG_TRIP_SCENE`, `dlc_vw_hidden_collectible_sounds`, `BARRY_01_SOUNDSET`, `DLC_VW_Survival_Sounds`, `DESPAWN`, `Screen_Fade_White`, `Tripping_Sounds`, `space_ranger_commander`, `impotent_rage`, `pogo_space_monkey`, `Survival_Passed`, `Payment_Player`, `DLC_HEISTS_GENERIC_SOUNDS`, `Damage`, `Round_Passed`, `Attack_Grunt`, `MIND_CONTROL`, `DrugsEffect`, `DrugsEffectSpeech`, `Death_Roar`, `Die`, `scr_powerplay_beast_appear`, `Spawn`

**Speech contexts** (2) - `CLOWNS`, `ALIENS`

**Particle effects** (23) - `muz_clown`, `eject_clown`, `scr_clown_bul`, `scr_rcbarry2`, `scr_man_surv_actfig_muz`, `scr_alien_impact`, `scr_alien_teleport`, `smoke`, `scr_man_surv_hippy_muz`, `scr_man_surv_hippy_eject`, `scr_man_surv_hippy_impact`, `scr_man_surv_food_muz`, `scr_man_surv_food_eject`, `scr_man_surv_food_impact`, `scr_man_surv_actfig_eject`, `scr_man_surv_actfig_impact`, `scr_man_surv_alien_muz`, `scr_man_surv_alien_eject`, `scr_man_surv_alien_impact`, `scr_man_surv_zombie_muz`, `scr_man_surv_zombie_eject`, `scr_man_surv_zombie_impact`, `scr_alien_charging`

**Text labels** (7) - `NULL`, `CLEAR`, `CLOUDS`, `THUNDER`, `FOGGY`, `HALLOWEEN`, `ALIENS`

## Native vocabulary

Most-called natives inside the code unique to this script:

`SET_PED_COMPONENT_VARIATION` (148), `DATADICT_GET_ARRAY` (74), `SET_BIT` (32), `NETWORK_DOES_ENTITY_EXIST_WITH_NETWORK_ID` (32), `SET_PED_COMBAT_ATTRIBUTES` (20), `GET_ENTITY_COORDS` (19), `SET_PED_CONFIG_FLAG` (19), `SET_ENTITY_INVINCIBLE` (17), `RESET_PARTICLE_FX_OVERRIDE` (16), `SET_PARTICLE_FX_OVERRIDE` (16), `CLEAR_BIT` (13), `HAS_NAMED_PTFX_ASSET_LOADED` (12), `USE_PARTICLE_FX_ASSET` (12), `PLAYER_PED_ID` (12), `RELEASE_NAMED_SCRIPT_AUDIO_BANK` (11), `GET_RANDOM_INT_IN_RANGE` (10), `REQUEST_SCRIPT_AUDIO_BANK` (10), `REQUEST_NAMED_PTFX_ASSET` (10), `SET_ENTITY_HEALTH` (9), `IS_ENTITY_PLAYING_ANIM` (8), `SET_PED_RESET_FLAG` (8), `START_NETWORKED_PARTICLE_FX_NON_LOOPED_AT_COORD` (8), `REMOVE_NAMED_PTFX_ASSET` (8), `PLAY_SOUND_FRONTEND` (7), `FREEZE_ENTITY_POSITION` (7), `REQUEST_ANIM_DICT` (7), `REMOVE_ANIM_DICT` (7), `NETWORK_OVERRIDE_CLOCK_TIME` (7), `NETWORK_FADE_IN_ENTITY` (6), `IS_PED_IN_ANY_VEHICLE` (6)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`0.5f` x5 · `0.8f` x2 · `41.782f` x2 · `3649.56f` x2 · `38.693f` x2 · `0.1f` x2 · `2352.481f` x2 · `2613.051f` x2 · `46.4705f` x2 · `51.2455f` x2 · `3688.939f` x2 · `38.6804f` x2 · `0.125f` x2 · `0.85f` x2 · `0.3f` x1 · `-1041.233f` x1 · `4906.101f` x1 · `209.2f` x1 · `-1044.749f` x1 · `4914.972f` x1 · `209.193f` x1 · `0.7f` x1 · `0.25f` x1 · `2331.616f` x1

## Other strings

Literals whose consuming native was not classified:

`pos`, `GTAO_Bomb_Plant_Sounds`, `head`, `num`, `int`, `mp_m_freemode_01`, `rot`, `ibs`, `Ghost_Hunt_Sounds`, `xmas25_420_3`, `Arm`, `Detonate`, `Explode`, `Remote_Vehicle_Bomb_Sounds`, `xmas25_420_4`, `xmas25_420_2`, `bsa`, `typ`, `Male_Ghost`, `speedo2`, `scramjet`, `weevil`, `grp`, `veh`, `sprt`, `hclr`, `scl`

---

Source: `decompiled_scripts/fm_content_survival.c`
