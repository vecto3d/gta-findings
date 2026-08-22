# Locking down a ped

Surveyed across the heist, random event and job scripts. A scattered set of calls
that share one purpose: stopping the engine from overriding what your script wants a
ped to do.

Most "my animation keeps getting interrupted" problems in FiveM are one of these.

## Stop the ped improvising

    SET_PED_CAN_PLAY_AMBIENT_ANIMS(ped, false)
    SET_PED_CAN_PLAY_AMBIENT_BASE_ANIMS(ped, false)
    SET_PED_CAN_PLAY_GESTURE_ANIMS(ped, false)

The engine layers idle fidgets and conversational gestures on top of whatever a ped
is doing. On a scripted animation this reads as twitching. The heist scripts disable
all three before any staged sequence.

## Stop the ped reacting

    SET_PED_CAN_BE_DRAGGED_OUT(ped, false)
    SET_PED_CAN_RAGDOLL(ped, false)
    SET_PED_CAN_EVASIVE_DIVE(ped, false)
    SET_PED_CAN_BE_KNOCKED_OFF_VEHICLE(ped, 0)
    SET_PED_CAN_RAGDOLL_FROM_PLAYER_IMPACT(ped, false)
    SET_PED_CAN_BE_TARGETTED(ped, false)

Evasive dive is the one that catches people — a ped standing near traffic will throw
itself out of the way mid-animation unless told not to.

## Combat attributes

Set with `SET_PED_COMBAT_ATTRIBUTES(ped, index, bool)`. Indices observed in use,
with behaviour inferred from context rather than confirmed:

| Index | Appears when |
|---|---|
| `0` | armed guards holding position |
| `1` | escorts and drivers, enabled |
| `2` | pursuit vehicles |
| `3` | disabled on peds that must not leave a vehicle |
| `5` | disabled on hired drivers so they do not flee |
| `13` | armed response, shotgun guards |
| `17` | almost every hostile ped in the game — by far the most common |
| `9`, `57`, `58` | shop and delivery guards |

Attribute `17` appearing on nearly every hostile ped makes it the default to copy
when spawning an enemy that should behave normally. The rest are inference from
usage — the numbers are certain, the meanings are not.

## Suppress the ambient world

    CLEAR_PED_NON_CREATION_AREA()
    SET_PED_NON_CREATION_AREA(...)

`carsteal3.c` clears a non-creation area on cleanup, implying one was set to stop
ambient peds spawning into a staged scene. Useful for any set piece where wandering
pedestrians would break the shot.

## Appearance cleanup

    CLEAR_PED_PROP(ped, slot, n)                  // remove hat, glasses
    CLEAR_PED_PARACHUTE_PACK_VARIATION(ped)
    CLEAR_PED_BLOOD_DAMAGE(ped)
    CLEAR_PED_WETNESS(ped)
    CLEAR_PED_DECORATIONS_LEAVE_SCARS(ped)        // remove tattoos, keep scars
    CLEAR_PED_ALTERNATE_MOVEMENT_ANIM(ped, slot, blend)

`CLEAR_PED_DECORATIONS_LEAVE_SCARS` is the one worth knowing — the clothing shops
use it so removing tattoos does not also wipe injury detail.

## Related

- [../reference/task-vocabulary](../reference/task-vocabulary.md)
- [npc-drivers](npc-drivers.md)
- [random-events](random-events.md)
