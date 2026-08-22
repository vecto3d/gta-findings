# Small world systems

Individually small scripts, each doing one thing.

| Script | Size | What it does |
|---|---|---|
| `restrictedareas.c` | 40K | Restricted-zone enforcement |
| `flyunderbridges.c` | 52K | Tracks flying under bridges; generalises to any stunt detector |
| `forsalesigns.c` | | Property for-sale signs |
| `vehicle_plate.c` | 1K | Licence plates |
| `vehicle_stealth_mode.c` | 28K | Toggle with audio `STEALTH_ON` / `STEALTH_OFF` (+ `_P` / `_S`) |
| `save_anywhere.c`, `savegame_bed.c` | | Save points |
| `wp_partyboombox.c` | 4K | Boombox as a carried prop |
| `mp_player_damage_numbers.c` | 1K | Floating damage numbers |
| `mp_awards.c`, `mp_unlocks.c` | | Award and unlock systems |
| `shrinkletter.c` | 40K | Owns the `PSYCHOLOGY_REPORT` scaleform |
| `ufo.c` | 68K | Larger than `ambient_ufos.c` |
| `photographywildlife.c` | | Wildlife photography objectives |
| `murdermystery.c` | | Has its own `prop_vintage_filmcan` |
| `emergencycall.c` | 16K | 911 calls, routed via `cellphone_flashhand` |
| `emergencycalllauncher.c` | 24K | |
| `minigame_stats_tracker.c` | 12K | Owns the generic `mission_complete` screen |
| `minigame_ending_stinger.c` | | Shared activity ending |
| `dont_cross_the_line.c` | 164K | Own scaleform `dont_cross_the_line` |
| `fake_interiors.c` | 20K | |
| `prop_drop.c`, `pickupvehicles.c`, `vehiclespawning.c` | | Spawning helpers |
| `dialogue_handler.c`, `localpopulator.c`, `spawn_activities.c`, `walking_ped.c`, `idlewarper.c` | | Population and dialogue plumbing |
| `buddydeathresponse.c` | 12K | |
| `charactergoals.c` | 32K | |
| `heli_gun.c`, `turret_cam_script.c`, `missioniaaturret.c` | | Mounted weapons |

## Thin ambient scripts

`ambient_ufos.c` is **12K, the smallest script in the repo** — sound only, with
`SPECIAL_EVIL_UFO_DEATH_RAY`. `ambient_diving.c` (52K) uses
`ADD_BLIP_FOR_RADIUS` search areas. `ambient_sonar.c` (80K) is minimal.
`animal_controller.c` (2.1M) is the animal spawning brain.

Note: `prop_bought_*` models in these are shared property boilerplate, not
collectibles.
