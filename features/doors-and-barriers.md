# Doors and barriers

**Source:** `am_doors.c`, read from its logic skeleton.

The door system is a registry the engine owns. Scripts do not move doors — they set a
state or an open ratio and the engine animates and syncs it. This is the correct way
to do a door in a networked game, and it is much less code than the usual approach of
animating a prop.

## Ownership first

    DOOR_SYSTEM_GET_DOOR_PENDING_STATE(doorHash)
    DOOR_SYSTEM_GET_DOOR_STATE(doorHash)

    if (NETWORK_HAS_CONTROL_OF_DOOR(doorHash))
        DOOR_SYSTEM_SET_DOOR_STATE(doorHash, state, ...)
    else
        NETWORK_REQUEST_CONTROL_OF_DOOR(doorHash)

The pattern repeats for every door the script touches: **check control, act if you
have it, request it if you do not.** Requesting is not instant, so the script simply
tries again next frame rather than blocking.

Skipping the control check is why community door scripts desync — one client moves the
door locally and nobody else sees it.

Pending state versus current state matters too. A door mid-swing has a pending state
that differs from its current one, and acting on the current state alone fights the
animation.

## Smooth opening with audio

    SET_SCRIPT_UPDATE_DOOR_AUDIO(doorHash, true)
    DOOR_SYSTEM_SET_OPEN_RATIO(doorHash, ratio, ...)

Rather than open/closed, `am_doors.c` drives a continuous ratio scaled by `TIMESTEP`,
with the audio flag set so the engine plays the hinge and latch sounds that match the
motion. A door driven by ratio with audio enabled sounds right for free.

## Registry lifecycle

    IS_DOOR_REGISTERED_WITH_SYSTEM(doorHash)
    REMOVE_DOOR_FROM_SYSTEM(doorHash)

Check before touching, and remove on cleanup. Doors left registered by a terminated
script stay stuck in whatever state they held.

## Race barriers

    OPEN_ALL_BARRIERS_FOR_RACE(...)
    CLOSE_ALL_BARRIERS_FOR_RACE(...)

Two calls that operate on every barrier at once, used when a race starts and ends.
Worth knowing before writing a loop over barrier props.

## Area checks

`am_doors.c` decides who is near a door with `IS_POINT_IN_ANGLED_AREA` and
`IS_ENTITY_IN_ANGLED_AREA` rather than a radius — the same choice the
[beds](beds.md) and [seating](seating.md) make. A doorway has a side; a sphere does
not.

## Related

- [../reference/doors](../reference/doors.md) — the door hash catalogue
- [animated-door-collision](animated-door-collision.md) — for props that are *not*
  registered doors and must be animated by hand
