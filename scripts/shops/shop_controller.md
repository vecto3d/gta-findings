# shop_controller.c

Shops script. 34 models; 2 scaleforms; 17 particle effects.

| | |
|---|---|
| Category | Shops |
| Total lines | 453,440 |
| Functions | 7,585 (337 unique, 7,248 shared) |
| Unique lines | 33,310 (7.3% of file) |

## Assets

**Models and props** (34) - `prop_xmas_ext`, `ig_lamardavis_02`, `a_c_rabbit_02`, `p_franklin_02`, `a_c_boar`, `a_c_cat_01`, `a_c_cow`, `a_c_coyote`, `a_c_deer`, `a_c_husky`, `a_c_mtlion`, `a_c_pig`, `a_c_poodle`, `a_c_pug`, `a_c_rabbit_01`, `a_c_retriever`, `a_c_rottweiler`, `a_c_shepherd`, `a_c_westy`, `a_c_chickenhawk`, `a_c_cormorant`, `a_c_crow`, `a_c_hen`, `a_c_pigeon`, `a_c_seagull`, `a_c_dolphin`, `a_c_fish`, `a_c_killerwhale`, `a_c_sharkhammer`, `a_c_sharktiger`, `a_c_stingray`, `ig_orleans`, `a_c_chop`, `a_c_humpback`

**Audio banks** (1) - `SNOW_FOOTSTEPS`

**Sounds** (6) - `HUD_FRONTEND_DEFAULT_SOUNDSET`, `GTAO_Vision_Modes_SoundSet`, `OK`, `CANCEL`, `Nightvision_Loop`, `Thermal_Loop`

**Scaleform movies** (2) - `SET_PLAYER_CHIP_CHANGE`, `SET_PLAYER_CHIPS`

**Particle effects** (17) - `scr_mp_tankbattle`, `scr_xm_orbital`, `scr_weap_bombs`, `core_snow`, `proj_xmas_firework`, `exp_grd_tankshell`, `scr_firework_indep_burst_rwb`, `scr_firework_indep_spiral_burst_rwb`, `scr_firework_indep_repeat_burst_rwb`, `scr_firework_indep_ring_burst_rwb`, `exp_grd_tankshell_mp`, `scr_indep_wheelsmoke`, `scr_indep_parachute`, `scr_firework_xmas_burst_rgw`, `scr_firework_xmas_spiral_burst_rgw`, `scr_firework_xmas_repeat_burst_rgw`, `scr_firework_xmas_ring_burst_rgw`

**Texture dicts** (1) - `MPClubEmblemSmall`

**Text labels** (28) - `MISSION`, `NONE`, `AWARD`, `HEIST5`, `AVI`, `FINALE`, `BAIL`, `CHICKEN`, `SETUP`, `MANSION`, `CTALERT_F_1`, `OFF`, `NULL`, `XMAS`, `KORTZ`, `CAT`, `DOG`, `UNAFFILIATED`, `MCKENZIE`, `MFH`, `PIZZA`, `DISPATCH`, `SELL`, `PREP`, `BRSCRWTEX`, `BRDISTEX`, `BRSHETEX`, `SALVAGE`

**Decorators** (1) - `MPBitset`

**Stats** (1) - `total_shop_time`

**Scripts launched** (6) - `wardrobe_mp`, `AM_ARENA_SHP`, `main`, `creator`, `director_mode`, `animal_controller`

**Hashed names** (2) - `appInternet`, `NO_LABEL`

## Native vocabulary

Most-called natives inside the code unique to this script:

`PLAYER_PED_ID` (364), `PLAYER_ID` (248), `ROUND` (230), `DOES_SHOP_PED_APPAREL_HAVE_RESTRICTION_TAG` (185), `TO_FLOAT` (180), `NETWORK_IS_GAME_IN_PROGRESS` (98), `SET_BIT` (91), `CLEAR_BIT` (64), `LOCK_RADIO_STATION_TRACK_LIST` (47), `GET_NETWORK_TIME` (38), `GET_ENTITY_MODEL` (36), `UNLOCK_RADIO_STATION_TRACK_LIST` (31), `GET_ENTITY_COORDS` (26), `GET_HASH_KEY` (25), `NETWORK_IS_ACTIVITY_SESSION` (24), `GET_DISTANCE_BETWEEN_COORDS` (24), `IS_PED_INJURED` (21), `IS_STRING_NULL_OR_EMPTY` (21), `GET_PED_DRAWABLE_VARIATION` (21), `GET_PED_TEXTURE_VARIATION` (20), `NETWORK_EARN_FROM_AMBIENT_JOB` (20), `SET_PED_COMPONENT_VARIATION` (18), `DOES_ENTITY_EXIST` (17), `LOCK_RADIO_STATION` (17), `SET_PED_CONFIG_FLAG` (16), `GET_GAME_TIMER` (16), `GET_PED_PROP_INDEX` (16), `GET_PED_PROP_TEXTURE_INDEX` (16), `ABSI` (15), `GET_TIME_DIFFERENCE` (15)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`7.5f` x18 · `237.4236f` x3 · `-880.7832f` x3 · `29.4971f` x3 · `2.5f` x3 · `-3.654f` x2 · `-1.348f` x2 · `1.2f` x1 · `0.2f` x1 · `31.617f` x1 · `5.488f` x1 · `28.734f` x1 · `9.619f` x1 · `3.5f` x1 · `-13.272f` x1 · `-12.765f` x1 · `-10.123f` x1 · `-12.74f` x1 · `2.3f` x1

## Other strings

Literals whose consuming native was not classified:

`RADIO_36_AUDIOPLAYER`, `RADIO_09_HIPHOP_OLD`, `money_earn_jobs`, `gunclub_shop`, `_t0_v0`, `player_zero`, `mp_f_freemode_01`, `mp_m_freemode_01`, `RADIO_03_HIPHOP_NEW`, `pilot_suit`, `thermal_vision`, `GunStoreHooks`, `carmod_shop`, `tattoo_shop`, `morph_suit`, `light_up`, `alt_helmet`, `night_vision`, `ClothesLowCHEAP`, `ClothesLowHipster`, `apart_draw_2`, `biker_draw_1`, `weevil`, `toros`, `biker_draw_0`, `arena_draw_5`, `arena_draw_7`, `heist_draw_0`, `stockings`, `RADIO_37_MOTOMAMI`

---

Source: `decompiled_scripts/shop_controller.c`
