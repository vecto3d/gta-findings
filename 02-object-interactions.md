# Object interactions and random events

Part of the [GTA V decompiled script findings](README.md).

## The goldmine: `ob_*` and `re_*`

26 object-interaction scripts and 38 random events, each a self-contained worked
example of one mechanic.

`ob_*` scripts run as **object brains**: attached to a prop model and woken by
`IS_OBJECT_WITHIN_BRAIN_ACTIVATION_RANGE` when a player approaches. That maps
cleanly onto a target/interact system in FiveM.

### Extracted anim data

| Script | Dict | Anims / props |
|---|---|---|
| `ob_vend1/2` | `MINI@SPRUNK@FIRST_PERSON` | `PLYR_BUY_DRINK_PT1/PT2/PT3` |
| `ob_mp_bed_*` | `mp_bedmid` | `f_getin_l_bighouse`, `f_sleep_l_loop_bighouse`, `f_getout_l_bighouse` (`_r` variants in bed_high) |
| `ob_mp_shower_med` | `ANIM@MP_YACHT@SHOWER@MALE@` / `@FEMALE@` | `male_shower_enter_into_idle`, `male_shower_idle_a`–`d`, `Male_Shower_Exit_To_Idle`, prop `p_mp_showerdoor_s` |
| `ob_telescope` | `MINI@TELESCOPE` | `ENTER_FRONT`/`IDLE`/`EXIT_FRONT`, plus `UPRIGHT_*` and `PUBLIC_*` variants; props `prop_telescope`, `prop_telescope_01` |
| `ob_jukebox` | `anim@amb@clubhouse@jukebox@` | scaleform track menu |
| `ob_poledancer` | `MISSSTRIP_CLUB` | `Poledance_01` |
| `ob_mp_stripper` | `mini@strip_club@lap_dance_2g@*` | `ld_2g_intro_m/_s1/_s2` + `_face` variants |
| drinking family | `MP_SAFEHOUSEBEER@`, `MP_SAFEHOUSEWINE@`, `MP_SAFEHOUSEWHISKEY@`, `mp_safehousewheatgrass@`, `mp_safehousebong@` | enter/idle/exit **plus drunk-state exits**: `exit_sober_bot`, `exit_slightly_drunk_bot`, `exit_moderately_drunk_bot`, `exit_drunk_bot`, with matching facials and named cameras |
| `ob_tv` / `ob_franklin_tv` | — | channel list `PL_STD_CNT`, `PL_LO_WZL`, `PL_MP_WEAZEL`, `PL_LES1_FAME_OR_SHAME`, … |

Drunk movement clipsets: `MOVE_M@DRUNK@SLIGHTLYDRUNK`,
`MOVE_M@DRUNK@MODERATEDRUNK_HEAD_UP`. A complete sober→drunk progression exists.

Drink/consume props: `prop_cs_beer_bot_01`, `p_wine_glass_s`, `prop_bong_01`,
`p_cs_joint_01`, `prop_cigar_03`, `p_whiskey_bottle_s`, `p_w_grass_gls_s`.

### `ob_cashregister` — smallest useful script (~170 lines)

No animation. Polls `HAS_OBJECT_BEEN_BROKEN` on the register prop, then spawns
cash via `GET_SAFE_PICKUP_COORDS` so it never lands inside geometry.
SP drops 70–120 (`pickup_money_med_bag`), MP 50–100 scaled by a global
multiplier (`prop_cash_pile_01`).

### `ob_poledancer` — ambient performer template (~170 lines)

Freeze prop, spawn ped at its coords, loop anim, and call
`SET_ENTITY_ANIM_CURRENT_TIME` with a random 0–1 float so multiple dancers do
not move in lockstep. Watches for player proximity, shooting or touching, then
bails into `TASK_COWER`.

### `re_*` random events — spawn recipes with exact models

Notable ones and their anim dicts:

- `re_paparazzi` — `random@paparazzi@pap_anims/@peek/@trans/@wait`, plus panic
  passenger `veh@std@ps@idle_panic`. Full pursue-and-flee AI loop.
- `re_drunkdriver` — `random@drunk_driver_1/_2` + the drunk movement clipsets.
- `re_atmrobbery` — `random@atmrobberygen@male` / `@female`.
- `re_shoprobbery` — `random@robbery`, `random@shop_robbery`.
- `re_hitch_lift` — `random@hitch_lift`, facials `facials@gen_female@base`.
- `re_gang_intimidation`, `re_lured`, `re_muggings`, `re_burials`,
  `re_domestic`, `re_prisonvanbreak`, `re_getaway_driver`, `re_securityvan`,
  `re_homeland_security`, `re_stag_do`, `re_cartheft`, `re_bikethief`.

Each carries its ped and vehicle model list, scenario strings
(`WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_STAND_MOBILE`, `WORLD_HUMAN_HANG_OUT_STREET`,
`WORLD_VEHICLE_DRIVE_SOLO`) and branching outcomes.
