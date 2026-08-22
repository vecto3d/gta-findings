# Remaining vocabulary

The tail of the sweep. These natives are used across many scripts but did not belong
to any single technique, so they had nowhere else to live.

## Dispatch and police behaviour

| Native | Scripts | Use |
|---|---:|---|
| `SET_DISPATCH_COPS_FOR_PLAYER` | 56 | Turn police dispatch on or off for one player without touching the wanted level |
| `SET_ALL_RANDOM_PEDS_FLEE_THIS_FRAME` | 48 | Empty a street of bystanders for a frame, per-frame so it self-cleans |
| `SET_PED_TARGET_LOSS_RESPONSE` | 53 | What a ped does when it loses sight of its target — search, give up, hold |
| `SET_WANTED_LEVEL_DIFFICULTY` | — | How hard the response is at a given star level |
| `SET_WANTED_LEVEL_MULTIPLIER` | — | Scales how fast stars accumulate |
| `SET_PLAYER_WANTED_LEVEL_NO_DROP` | — | Set a level that cannot fall below that floor |
| `PLAY_POLICE_REPORT` | — | A scripted scanner broadcast, e.g. a named prep-mission report |

`SET_DISPATCH_COPS_FOR_PLAYER` is the clean way to make an area police-free without
the side effects of forcing the wanted level to zero every frame.

`PLAY_POLICE_REPORT` is free flavour — the scanner already has the voice lines.

## Ped durability and behaviour

| Native | Scripts | Use |
|---|---:|---|
| `SET_PED_DIES_WHEN_INJURED` | 64 | Whether a ped drops at zero health or enters an injured state |
| `SET_PED_FLEE_ATTRIBUTES` | — | Flags controlling how a ped runs away |
| `SET_PED_PATH_CAN_DROP_FROM_HEIGHT` | — | Allow pathing off ledges |
| `SET_PED_PATH_CAN_USE_CLIMBOVERS` | — | Allow pathing over obstacles |
| `SET_PED_RANDOM_COMPONENT_VARIATION` | — | Randomise an outfit in one call |

The two path flags matter for any ped that must reach the player. A ped that refuses
to climb or drop will simply stand still if the only route needs it.

## Vehicle condition

| Native | Scripts | Use |
|---|---:|---|
| `SET_VEHICLE_ENGINE_HEALTH` | 71 | Engine damage independently of body |
| `SET_VEHICLE_PETROL_TANK_HEALTH` | 47 | Tank damage — low values make it leak and catch fire |
| `SET_VEHICLE_SEARCHLIGHT` | — | Helicopter spotlight |
| `SET_VEHICLE_SIREN` / `IS_VEHICLE_SIREN_ON` | — | Emergency lights and sound |
| `DETACH_VEHICLE_FROM_TOW_TRUCK` | — | Release a towed vehicle |
| `IS_VEHICLE_TYRE_BURST` | — | Per-wheel tyre state |

Setting engine and tank health separately is how a chase vehicle is made to fail
convincingly rather than simply exploding.

## Networked entity scope

| Native | Scripts | Use |
|---|---:|---|
| `NETWORK_SET_ENTITY_ONLY_EXISTS_FOR_PARTICIPANTS` | 46 | Entity visible only to script participants |
| `NETWORK_DISABLE_LEAVE_REMOTE_PED_BEHIND` | 58 | Stop a remote ped persisting when its owner leaves |
| `SET_PLAYER_LEAVE_PED_BEHIND` | 58 | Same for the local player |
| `CAN_REGISTER_MISSION_OBJECTS` | 53 | Budget check before creating objects |
| `SET_MAX_NUM_PORTABLE_PICKUPS_CARRIED_BY_PLAYER` | 53 | Cap on carryable objectives |
| `NETWORK_END_TUTORIAL_SESSION` | 53 | Move a player out of the isolated tutorial instance |
| `NETWORK_IS_TUTORIAL_SESSION_CHANGE_PENDING` | 80 | Guard while that transition is in flight |

The first one is the interesting one for a server: an entity scoped to participants
only, rather than to everyone in the session.

## Portable pickups

The "carry the objective" system behind bag and case mechanics has its own family,
of which `SET_MAX_NUM_PORTABLE_PICKUPS_CARRIED_BY_PLAYER` is the visible edge. Worth
investigating before hand-building a carryable objective from a prop and an attach.

## Controls you have disabled

    DISABLE_CONTROL_ACTION(group, control, true)
    IS_DISABLED_CONTROL_PRESSED(group, control)
    IS_DISABLED_CONTROL_JUST_PRESSED(group, control)
    GET_DISABLED_CONTROL_NORMAL(group, control)

Disabling a control stops the game acting on it but **not** your ability to read it.
That is how a script takes a key exclusively: disable it so nothing else responds,
then read the disabled state yourself. Reading the normal (non-disabled) variant of a
disabled control returns nothing, which is the usual source of confusion.

`IS_USING_CURSOR` and `IS_USING_KEYBOARD_AND_MOUSE` distinguish input devices.

## Time

`GET_NETWORK_TIME` · `GET_NETWORK_TIME_ACCURATE` · `GET_TIME_DIFFERENCE` ·
`GET_CLOUD_TIME_AS_INT`

Cloud time is a real-world clock shared by all clients, used for daily resets and
timed events. Network time is session time. Neither is `GET_GAME_TIMER`, which is
local and resets.

## Maths primitives

`ROUND` · `FLOOR` · `CEIL` · `ABSF` · `ABSI` · `POW` · `SIN` · `COS` · `ATAN2` ·
`SQRT` · `VDIST` · `VDIST2` · `VMAG` · `VMAG2` · `TO_FLOAT`

`VDIST2` and `VMAG2` are the squared forms — compare against a squared radius and skip
the square root. Used throughout the corpus for distance checks in per-frame loops.

## Related

- [../TECHNIQUES.md](../TECHNIQUES.md)
- [networked-scripts](networked-scripts.md)
- [../features/ped-control-flags](../features/ped-control-flags.md)
