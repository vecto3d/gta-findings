# Freemode activities

**Source:** 68 `am_*` scripts (excluding `am_mp_*` and `*_peds`)

Unlike `gb_*`, many of these are small and self-contained. Smallest first:

| Script | Size | Notes |
|---|---|---|
| `am_beach_washup_cinematic.c` | 16K | |
| `am_ga_pickups.c` | 40K | |
| `am_prison.c` | 44K | |
| `am_joyrider.c` | 56K | NPC steals your parked car |
| `am_backup_heli.c` | 80K | Callable support |
| `am_airstrike.c` | 88K | Callable support |
| `am_doors.c` | 104K | Door locking, see [doors.md](doors.md) |
| `am_ammo_drop.c` | 120K | Callable support |
| `am_boat_taxi.c` | 140K | |
| `am_distract_cops.c` | 144K | |
| `am_bru_box.c` | 204K | |
| `am_rollercoaster.c` | 212K | See [rides.md](rides.md) |
| `am_ferriswheel.c` | 232K | See [rides.md](rides.md) |
| `am_taxi.c` | 376K | See [taxi.md](taxi.md) |

The callable-support trio (backup heli, airstrike, ammo drop) are all under 120K
and share a pattern worth copying for any "call in an asset" feature.
