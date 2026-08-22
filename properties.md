# Properties and interiors

**Source:** `am_mp_property_int.c` (18M), `am_mp_property_ext.c`,
`am_mp_car_meet_property.c` (14M), `am_mp_auto_shop.c` (14M),
`am_mp_submarine.c` (13M), `am_mp_arcade.c` (9.7M), `am_mp_mansion.c`,
`am_mp_fixer_hq.c`, `am_mp_nightclub.c`

**Low yield overall** — these are large and boilerplate-heavy. What is worth
extracting:

## Named sign and board scaleforms

`CLUBHOUSE_NAME`, `ORGANISATION_NAME`, `AUTO_SHOP_CREW_NAME`,
`BIKER_MISSION_WALL`, `SECURITY_CAM` (used across nightclub, submarine, auto
shop and property interiors).

`am_mp_car_meet_property.c` carries `SC_LEADERBOARD` for test-track times.

## Interior entity sets

Property upgrades and decorations are toggled with `ENABLE_INTERIOR_PROP` rather
than by loading a different interior — see
[interior-entity-sets.md](interior-entity-sets.md).

## Warning

There are **~10 near-identical `*_seating.c` clones** at ~8.4M each (`mansion_`,
`fixer_hq_`, `salvage_yard_`, `multistorey_garage_`, `juggalo_hideout_`,
`base_lounge_`). Read one and ignore the rest.
