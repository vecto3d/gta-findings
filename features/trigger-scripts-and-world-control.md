# Trigger scripts and world control

**Source:** the `launcher_*` family read from logic skeletons — `launcher_minute.c`,
`launcher_omega.c`, `launcher_thelastone.c`, `launcher_pilotschool.c`,
`emergencycalllauncher.c`.

## World-point brains

The [object brain pattern](object-brain-pattern.md) has a sibling that the `ob_*`
prefix hides completely:

    SET_THIS_IS_A_TRIGGER_SCRIPT(true)
    IS_WORLD_POINT_WITHIN_BRAIN_ACTIVATION_RANGE()

Instead of waking near a **prop**, a trigger script wakes near a **coordinate**. Same
lifecycle otherwise: activate in range, run a state machine, terminate when the player
leaves.

That means there are two brain families, and every `launcher_*` script is the second
kind. If you liked the object brain shape but your interaction is not attached to an
object, this is the version you want.

Launchers also register their map markers through
`GET_STANDARD_BLIP_ENUM_ID` and `GET_WAYPOINT_BLIP_ENUM_ID` rather than hardcoding
sprite numbers.

## Render targets work on weapons

`launcher_omega.c` drives the digiscanner screen, and it links a render target to a
**weapon model**:

    REQUEST_SCALEFORM_MOVIE("digiscanner")
    REGISTER_NAMED_RENDERTARGET("digiscanner", false)
    LINK_NAMED_RENDERTARGET(GET_WEAPONTYPE_MODEL("weapon_digiscanner"))
    GET_NAMED_RENDERTARGET_RENDER_ID("digiscanner")

`GET_WEAPONTYPE_MODEL` converts a weapon hash to the model hash the render target
system needs. The movie is driven with `SET_COLOUR` and `SET_DISTANCE`, and paired
with an `IDLE_BEEP` from `EPSILONISM_04_SOUNDSET` that speeds up near the target.

So the [render target recipe](tv-and-channels.md) is not limited to props — any model
works, including weapons a player holds. That opens up scanners, tablets, phones and
detectors as real in-world screens.

## Controlling ambient traffic and parking

Four natives that suppress the ambient world in a region, all used when a launcher
stages a scene:

| Native | Effect |
|---|---|
| `SET_ALL_VEHICLE_GENERATORS_ACTIVE_IN_AREA(...)` | Enable or disable parked-car spawning in a box |
| `REMOVE_VEHICLES_FROM_GENERATORS_IN_AREA(...)` | Clear cars already spawned by generators |
| `SET_ROADS_IN_ANGLED_AREA(...)` | Turn driving traffic off along a stretch |
| `ADD_SCENARIO_BLOCKING_AREA(...)` | Stop scenario peds appearing |

Used together they empty a location without deleting anything the player might be
looking at. Every launcher re-enables them on cleanup — leaving generators disabled is
a permanent, invisible change to the map.

## More attach bones

Beyond the `28422` and `57005` pair from
[random events](random-events.md), the launchers use `18905` and `64729` with small
positional offsets. Bone choice is per-prop and per-pose; there is no single "hand"
bone that works for everything.

## Vehicle staging

Scripted vehicles get a consistent treatment before the player sees them:

`SET_VEHICLE_COLOUR_COMBINATION` · `SET_VEHICLE_DIRT_LEVEL` ·
`SET_VEHICLE_DOORS_LOCKED` · `SET_VEHICLE_ALARM` ·
`SET_DOOR_ALLOWED_TO_BE_BROKEN_OFF` · `SET_VEHICLE_DISABLE_TOWING` ·
`SET_VEHICLE_AUTOMATICALLY_ATTACHES` · `SET_VEHICLE_IS_CONSIDERED_BY_PLAYER` ·
`SET_VEHICLE_MODEL_IS_SUPPRESSED`

`SET_VEHICLE_IS_CONSIDERED_BY_PLAYER(veh, false)` is the interesting one — it removes
a vehicle from the player's "nearest vehicle" consideration, so pressing enter does not
target a prop car parked in a scene.

## Mission gating and stats

    CAN_PLAYER_START_MISSION(player)
    IS_PLAYER_SCRIPT_CONTROL_ON(player)
    IS_THREAD_ACTIVE(threadId)
    SET_INPUT_EXCLUSIVE(group, control)

    PLAYSTATS_ODDJOB_DONE(...)
    PLAYSTATS_MISSION_CHECKPOINT(...)

`CAN_PLAYER_START_MISSION` is a single call covering wanted level, being in a vehicle
mid-air, already being on a mission, and other conditions a home-made check usually
misses.

`SET_INPUT_EXCLUSIVE` reserves one control so a held key triggers only your prompt.

`GET_GROUND_Z_FOR_3D_COORD` finds the surface height below a point — the correct way
to place something on the ground rather than guessing Z.

## Launcher chaining

`emergencycalllauncher.c` is the minimal case: check the thread count for the target
script, request it, wait for it to load, `START_NEW_SCRIPT` with a stack size, done.
This pairs with the argument-passing form in
[networked-scripts](../reference/networked-scripts.md).

## Related

- [object-brain-pattern](object-brain-pattern.md)
- [tv-and-channels](tv-and-channels.md)
- [../reference/networked-scripts](../reference/networked-scripts.md)
