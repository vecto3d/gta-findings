# am_hold_up.c

MP ambient script. 3 anim dicts; 69 models.

| | |
|---|---|
| Category | MP ambient |
| Total lines | 22,531 |
| Functions | 510 (86 unique, 424 shared) |
| Unique lines | 6,486 (28.8% of file) |

## Assets

**Animation dictionaries** (3) - `mp_am_hold_up`, `oddjobs@shop_robbery@rob_till`, `mp_missheist_countrybank@cower`

**Animations** (10) - `mp_am_hold_up`, `oddjobs@shop_robbery@rob_till`, `loop`, `handsup_base`, `cower_intro`, `cower_loop`, `WARY_LOOP`, `enter`, `exit`, `handsup_enter`

**Models and props** (69) - `prop_choc_pq`, `prop_till_01`, `s_f_y_airhostess_01`, `s_f_y_baywatch_01`, `s_f_y_cop_01`, `s_f_y_ranger_01`, `s_f_y_scrubs_01`, `s_f_y_sheriff_01`, `s_m_m_armoured_01`, `s_m_m_armoured_02`, `s_m_m_bouncer_01`, `s_m_m_ciasec_01`, `s_m_m_chemsec_01`, `s_m_m_doctor_01`, `s_m_m_fiboffice_01`, `s_m_m_fiboffice_02`, `s_m_m_highsec_01`, `s_m_m_highsec_02`, `s_m_m_janitor`, `s_m_m_lsmetro_01`, `s_m_m_marine_01`, `s_m_m_marine_02`, `s_m_m_paramedic_01`, `s_m_m_pilot_01`, `s_m_m_pilot_02`, `s_m_m_postal_01`, `s_m_m_postal_02`, `s_m_m_prisguard_01`, `s_m_m_scientist_01`, `s_m_m_security_01`, `s_m_m_ups_01`, `s_m_m_ups_02`, `s_m_y_airworker`, `s_m_y_armymech_01`, `s_m_y_baywatch_01`, `s_m_y_blackops_01`, `s_m_y_blackops_02`, `s_m_y_cop_01`, `s_m_y_doorman_01`, `s_m_y_fireman_01`, `s_m_y_garbage`, `s_m_y_hwaycop_01`, `s_m_y_marine_01`, `s_m_y_marine_02`, `s_m_y_marine_03`, `s_m_y_pilot_01`, `s_m_y_ranger_01`, `s_m_y_sheriff_01`, `s_m_y_swat_01`, `s_m_y_uscg_01`, `s_m_y_valet_01`, `s_m_y_waiter_01`, `u_m_m_jewelsec_01`, `s_m_y_casino_01`, `prop_choc_ego`, `prop_choc_meto`, `prop_ld_fags_01`, `prop_ecola_can`, `prop_amb_beer_bottle`, `prop_ld_can_01b` ...

**Sounds** (11) - `HUD_LIQUOR_STORE_SOUNDSET`, `ERROR`, `PURCHASE`, `CANCEL`, `ROBBERY_MONEY_TOTAL`, `HUD_FRONTEND_CUSTOM_SOUNDSET`, `NAV_UP_DOWN`, `HUD_FRONTEND_DEFAULT_SOUNDSET`, `SELECT`, `BACK`, `HUD_FREEMODE_SOUNDSET`

**Speech contexts** (21) - `SPEECH_PARAMS_FORCE`, `GENERIC_INSULT_HIGH`, `GENERIC_FUCK_YOU`, `SHOP_GREET`, `SHOP_BRAVE`, `SHOP_REMOVE_VEHICLE`, `SHOP_REACT_TO_SHOUT`, `SHOP_HURRYING`, `SHOP_NO_COPS`, `SHOP_THREATENED`, `SHOP_GREET_START`, `SHOP_SCARED_START`, `SHOP_NO_COPS_START`, `SHOP_GREET_END`, `SHOP_SCARED_END`, `SHOP_NO_COPS_END`, `SHOP_COPS_ARRIVED`, `SHOP_SELL`, `SHOP_NO_ENTRY`, `SHOP_STEAL`, `SCREAM_PANIC`

**Text labels** (1) - `NULL`

**Decorators** (1) - `XP_Blocker`

**Interiors and entity sets** (4) - `v_methlab`, `v_shop_247`, `v_gen_liquor`, `v_gasstation`

**Hashed names** (7) - `SNK_ITEM1`, `SNK_ITEM2`, `SNK_ITEM3`, `SNK_ITEM4`, `SNK_ITEM5`, `SNK_ITEM7`, `SNK_ITEM6`

## Native vocabulary

Most-called natives inside the code unique to this script:

`NET_TO_PED` (201), `SET_BIT` (150), `PLAYER_ID` (115), `PLAYER_PED_ID` (106), `PARTICIPANT_ID_TO_INT` (100), `NET_TO_OBJ` (60), `NETWORK_DOES_NETWORK_ID_EXIST` (38), `GET_SCRIPT_TASK_STATUS` (29), `CLEAR_BIT` (26), `PLAY_PED_AMBIENT_SPEECH_WITH_VOICE_NATIVE` (18), `REPORT_CRIME` (17), `GET_WANTED_LEVEL_THRESHOLD` (17), `IS_SYNCHRONIZED_SCENE_RUNNING` (16), `GET_RANDOM_INT_IN_RANGE` (15), `NETWORK_GET_LOCAL_SCENE_FROM_NETWORK_ID` (15), `INT_TO_PARTICIPANTINDEX` (15), `TASK_PLAY_ANIM` (14), `GET_GAME_TIMER` (14), `IS_ENTITY_AT_COORD` (13), `SET_INPUT_EXCLUSIVE` (12), `IS_PED_INJURED` (11), `SET_ENTITY_VISIBLE` (11), `FREEZE_ENTITY_POSITION` (11), `PLAY_SOUND_FRONTEND` (11), `ROUND` (10), `NETWORK_IS_HOST_OF_THIS_SCRIPT` (10), `GIVE_DELAYED_WEAPON_TO_PED` (10), `SET_PED_KEEP_TASK` (10), `GET_SYNCHRONIZED_SCENE_PHASE` (10), `CLEAR_PED_TASKS` (10)

## Tuning constants

Float literals in unique code: distances, timings, blend values.

`1.5f` x9 · `2.5f` x7 · `0.5f` x6 · `0.25f` x4 · `1.2f` x4 · `0.1f` x3 · `0.87f` x2 · `-1.5f` x2 · `0.7f` x2 · `0.68f` x2 · `0.3008f` x2 · `0.75f` x2 · `-0.65f` x1 · `-0.02f` x1 · `0.44f` x1 · `-0.2f` x1 · `0.4f` x1 · `0.95f` x1 · `-0.5f` x1 · `-0.1878f` x1 · `3.0635f` x1 · `-0.0129f` x1 · `0.0927f` x1 · `-1.0346f` x1

## Other strings

Literals whose consuming native was not classified:

`purchase`, `mp_am_hold_up`, `SHR_MENU`, `object`, `FHU_MANR`, `service_spend_cash_drop_holdup`, `mp_m_shopkeep_01`, `StoreHero`, `purchase_chocbar`, `purchase_chocbar_shopkeeper`, `holdup_victim_20s`, `holdup_victim_20s_bag`, `holdup_victim_20s_till`, `RB_12AU`, `HAND_SHAKE`, `SHR_SOLD_OUT`, `mp_m_freemode_01`, `purchase_beer`, `purchase_energydrink`, `purchase_beer_shopkeeper`, `purchase_energydrink_shopkeeper`, `FHU_HELPM`, `service_earn_holdups`, `mp_f_freemode_01`, `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_HUMAN_STAND_MOBILE`, `mp_m_fibsec_01`, `mp_s_m_armoured_01`

---

Source: `decompiled_scripts/am_hold_up.c`
