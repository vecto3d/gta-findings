# Random events

**Source:** 38 `re_*` scripts

Ambient world events with exact ped and vehicle models, scenario strings and
branching outcomes. The best templates for populating a map with incidents.

## Notable ones

| Script | Anim dicts | Notes |
|---|---|---|
| `re_paparazzi` | `random@paparazzi@pap_anims`, `@peek`, `@trans`, `@wait` | Full pursue-and-flee loop, panic passenger `veh@std@ps@idle_panic` |
| `re_drunkdriver` | `random@drunk_driver_1`, `_2` | Uses the drunk movement clipsets |
| `re_atmrobbery` | `random@atmrobberygen@male` / `@female` | |
| `re_shoprobbery` | `random@robbery`, `random@shop_robbery` | |
| `re_hitch_lift` | `random@hitch_lift`, `facials@gen_female@base` | |
| `re_gang_intimidation` | `random@gang_intimidation@` | |
| `re_burials` | `random@burial` | |
| `re_domestic` | `random@domestic`, `random@security_van` | |
| `re_securityvan` | `random@security_van` | |
| `re_prisonvanbreak` | `random@countrysiderobbery` | |
| `re_getaway_driver` | `random@getawaydriver`, `@thugs` | |
| `re_homeland_security` | `random@homelandsecurity` | |
| `re_stag_do` | `re@stag_do@`, `@idle_a` | |
| `re_cartheft` | `RANDOM@CAR_THIEF@WAITING_IG_4` | |
| `re_lured` | `random@mugging5` | |
| `re_snatched` | `random@kidnap_girl` | |
| `re_gangfight` | `random@countryside_gang_fight` | |
| `re_accident` | `re@construction` | |
| `re_abandonedcar` | `random@train_tracks` | |

Others: `re_armybase`, `re_arrests`, `re_bikethief`, `re_border`, `re_bus_tours`,
`re_chasethieves`, `re_crashrescue`, `re_cultshootout`, `re_dealgonewrong`,
`re_duel`, `re_lossantosintl`, `re_monkey`, `re_mountdance`, `re_muggings`,
`re_prison`, `re_prisonerlift`, `re_rescuehostage`, `re_seaplane`,
`re_yetarian`.

Common scenarios used: `WORLD_HUMAN_SMOKING`, `WORLD_HUMAN_STAND_MOBILE`,
`WORLD_HUMAN_HANG_OUT_STREET`, `WORLD_VEHICLE_DRIVE_SOLO`,
`WORLD_VEHICLE_PARK_PERPENDICULAR_NOSE_IN`.
