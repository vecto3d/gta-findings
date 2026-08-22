# Vehicle HUDs, gunner cameras and decorators

**Source:** `heli_gun.c` (9,169 unique lines), `am_mp_vehicle_weapon.c`,
`am_plane_takedown.c`, `am_vehicle_spawn.c`, `fm_content_vehicle_list.c`,
surveyed from unique code.

## The gunner camera look

`heli_gun.c` is the helicopter gunner and news-chopper view. Two things give it its
character:

    SET_TIMECYCLE_MODIFIER("eyeinthesky")
    SET_BLIP_ALPHA(GET_MAIN_PLAYER_BLIP_ID(), 0)

The `eyeinthesky` timecycle is the washed-out surveillance grade, applied for free
with one call. Hiding the player blip while in the gunner view stops the minimap
giving away that you are the helicopter. Both are restored on exit, the blip by
setting alpha back to `255`.

Full list in the [timecycle index](../reference/timecycle-index.md).

## Weapon HUD scaleform

`am_mp_vehicle_weapon.c` drives a targeting overlay through scaleform methods:

| Method | Purpose |
|---|---|
| `SET_HEADING` | Compass heading readout |
| `SET_ALT_FOV_HEADING` | Altitude and field of view |
| `SET_MISSILE_PERCENTAGE` | Lock-on progress |
| `SET_CAM_LOGO` | Corner branding for the camera mode |

Drawn fullscreen with alpha `0` in the call and brightness supplied by the movie
itself, the same convention as the [award shard](../reference/notifications.md).

## Aircraft AI

- `TASK_HELI_MISSION(ped, veh, targetVeh, targetPed, coords, mode, speed, radius, heading, maxHeight, minHeight, slowdown, flags)`
- `TASK_PLANE_MISSION(...)` with the same shape
- `TASK_SUBMARINE_GOTO_AND_STOP` for submarines
- `SET_VEHICLE_DONT_TERMINATE_TASK_WHEN_ACHIEVED(veh)` — keeps the vehicle holding
  station instead of ending the task on arrival, which is what you want for a patrol
  or an escort

## Decorators as vehicle ownership

Decorators are how the game tags a vehicle without a server-side table. Observed
keys, each set with `DECOR_SET_INT` or `DECOR_SET_BOOL`:

| Key | Meaning |
|---|---|
| `Player_Vehicle` | Owner, as `NETWORK_HASH_FROM_PLAYER_HANDLE(player)` |
| `Player_Thruster` | Owner of a deployed thruster |
| `ExportVehicle` | Marked for an export job |
| `VehicleList` | Belongs to a content vehicle list |
| `MPBitset` | Packed flags |

Storing the owner as a hash of the player handle rather than an index is the detail
worth copying — indices are reused when players leave.

Full list in the [decorator index](../reference/decorator-index.md).

## Random but valid colours

    SET_VEHICLE_COLOUR_COMBINATION(veh, GET_RANDOM_INT_IN_RANGE(0, GET_NUMBER_OF_VEHICLE_COLOURS(veh)))

Picks a factory colour combination that actually exists for that model, instead of a
random index that may not.

## Duplication warning

Every `*_carmod.c` — `armory_aircraft_carmod`, `base_carmod`, `business_hub_carmod`,
`car_meet_carmod` and the rest — has **zero unique code**. They are identical
compiled copies. `heli_streaming.c` likewise. There is exactly one mod-shop
implementation in the game and thirteen filenames pointing at it.

## Related

- [../reference/decorator-index](../reference/decorator-index.md)
- [../reference/timecycle-index](../reference/timecycle-index.md)
