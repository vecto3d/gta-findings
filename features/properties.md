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
[interior-entity-sets.md](../reference/interior-entity-sets.md).

## Warning

There are **~10 near-identical `*_seating.c` clones** at ~8.4M each (`mansion_`,
`fixer_hq_`, `salvage_yard_`, `multistorey_garage_`, `juggalo_hideout_`,
`base_lounge_`). Read one and ignore the rest.


## Survey of all 55 property and venue scripts

### The shared cigar idle

`am_mp_casino_apartment.c` and `am_mp_arena_box.c` both place a ped smoking with the
same three steps: ask the animation where to stand using
`GET_ANIM_INITIAL_OFFSET_POSITION` and its rotation counterpart against the clip
`base_cigar_a`, create a `lux_prop_cigar_01_luxe`, and freeze it.

This is the same alignment technique the beds use, applied to prop placement rather
than player positioning — see
[animation alignment](../reference/animation-alignment.md). It confirms the native is
the general solution, not a bed-specific trick.

### Ownership decorators

Properties tag their spawned vehicles so they are not mistaken for personal ones:

`Player_Vehicle` · `Player_Truck` · `Player_Mansion_Luxury_Vehicle` ·
`Player_Hacker_Truck` · `Not_Allow_As_Saved_Veh` · `MPBitset`

`Not_Allow_As_Saved_Veh` is the useful one for a server — it marks a vehicle as
loaner stock that must never be persisted to a player garage.

### Render targets are everywhere

`am_mp_field_hangar.c`, `am_mp_sb_weed_shop.c` and `am_mp_sb_heli_tours.c` all drive
in-world screens with `SET_TEXT_RENDER_ID`, always restoring
`GET_DEFAULT_SCRIPT_RENDERTARGET_RENDER_ID()` afterwards. Recipe in
[tv-and-channels](tv-and-channels.md).

### Cameras by hash

`am_beach_washup_cinematic.c` calls `CREATE_CAMERA` with a numeric hash rather than
a name string. Worth knowing when a camera type does not appear as a literal
anywhere — the name has been hashed at compile time.

### Venue audio

`GTAO_FM_Events_Soundset` carries `Event_Start_Text`, `Object_Collect_Player` and
`Object_Collect_Remote` — the last pair distinguishing your own pickup from another
player's, which is a detail worth copying for any shared collectible event.
