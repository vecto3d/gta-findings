# Networked script architecture

**Source:** the `am_*` family, read from logic skeletons — `am_doors.c`,
`am_ga_pickups.c`, `am_prison.c`, `am_prostitute.c`, `am_car_mod_tut.c`,
`am_joyrider.c`.

Every `am_*` script is built the same way. FiveM inverts the authority model, but the
structure is still the best available reference for splitting shared state from local
presentation.

## Broadcast variables

The mechanism that syncs state, and it appears in essentially every networked script:

    NETWORK_REGISTER_HOST_BROADCAST_VARIABLES(count)
    NETWORK_REGISTER_PLAYER_BROADCAST_VARIABLES(count)

Two blocks of variables with different ownership:

- **Host broadcast** — written only by the host, read by everyone. The authoritative
  event state.
- **Player broadcast** — each participant writes its own slot, everyone reads all
  slots. Per-player status.

Registration happens once at startup, before the main loop, alongside
`SET_THIS_SCRIPT_CAN_BE_PAUSED(false)`.

That split maps cleanly onto a FiveM design: host broadcast becomes server state,
player broadcast becomes per-client state the server aggregates.

## The standard preamble

Nearly every `am_*` script opens with the same guards:

    NETWORK_IS_GAME_IN_PROGRESS()
    NETWORK_IS_IN_TUTORIAL_SESSION()          -> bail out
    NETWORK_GET_PLAYER_TUTORIAL_SESSION_INSTANCE()
    NETWORK_SET_THIS_SCRIPT_IS_NETWORK_SCRIPT(maxParticipants, ...)
    NETWORK_SET_SCRIPT_IS_SAFE_FOR_NETWORK_GAME()

Tutorial sessions are isolated instances; scripts that ignore them spawn events a new
player cannot interact with.

## Iterating participants

    NETWORK_GET_MAX_NUM_PARTICIPANTS()
    NETWORK_IS_PARTICIPANT_ACTIVE(INT_TO_PARTICIPANTINDEX(i))
    GET_PLAYER_PED(NETWORK_GET_PLAYER_INDEX(INT_TO_PARTICIPANTINDEX(i)))
    PARTICIPANT_ID_TO_INT()

Participant index and player index are different things, and the conversion is
explicit. `PARTICIPANT_ID_TO_INT()` is how a script finds its own slot.

## Entity control

    NETWORK_HAS_CONTROL_OF_ENTITY(entity)
    NETWORK_REQUEST_CONTROL_OF_DOOR(doorHash)
    CAN_REGISTER_MISSION_ENTITIES(peds, vehicles, objects, pickups)

`CAN_REGISTER_MISSION_ENTITIES` is a budget check — ask before creating, because the
networked entity pool is finite and a failed spawn is worse than a delayed one.

Every conversion from a network id is guarded, as covered in
[scripted-scene-hygiene](../features/scripted-scene-hygiene.md).

## Launching another script with arguments

`am_prostitute.c` shows how one script starts another and passes it data:

    REQUEST_SCRIPT("pb_prostitute")
    HAS_SCRIPT_LOADED("pb_prostitute")
    NETWORK_IS_SCRIPT_ACTIVE(...)                 // do not double-start
    START_NEW_SCRIPT_WITH_ARGS("pb_prostitute", args, argCount, stackSize)
    SET_SCRIPT_AS_NO_LONGER_NEEDED("pb_prostitute")

This is the mechanism behind the parameterised
[results screen](../features/results-screen.md) — a general service launched with a
payload. The guard combination matters: `GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH`
plus `NETWORK_IS_SCRIPT_ACTIVE` prevents both local and remote duplicates.

## Suppressing the ambient world

    ADD_SCENARIO_BLOCKING_AREA(x1, y1, z1, x2, y2, z2, ...)
    REMOVE_SCENARIO_BLOCKING_AREA(...)

From `am_prison.c`. Stops scenario peds spawning inside a volume, so a staged area
does not fill with people leaning on walls. Paired with
`CLEAR_PED_NON_CREATION_AREA` covered in
[ped-control-flags](../features/ped-control-flags.md).

## Wanted level as an API

`am_prison.c` does not set the wanted level directly. It reports:

    REPORT_CRIME(player, crimeType, GET_WANTED_LEVEL_THRESHOLD(n))
    REPORT_POLICE_SPOTTED_PLAYER(player)

Reporting a crime lets the engine decide the response, including witnesses and
escalation. Forcing a wanted level bypasses all of that and is why manually-set stars
behave oddly.

## Screen effects

The heist cinematics drive post effects by name:

    ANIMPOSTFX_PLAY(name, duration, looped)
    ANIMPOSTFX_STOP(name) / ANIMPOSTFX_STOP_ALL()
    ANIMPOSTFX_IS_RUNNING(name)
    ANIMPOSTFX_GET_CURRENT_TIME(name)

Seen with camera-flash effects during a cutscene, and `CamPushInNeutral` on a
transition. `HAS_ANIM_EVENT_FIRED` triggers them from tags embedded in the animation
rather than from a timer — the same event-tag idea as
[animation alignment](animation-alignment.md).

## Two small ones worth stealing

    FORCE_PED_AI_AND_ANIMATION_UPDATE(ped)

Forces an immediate update so a ped is in the right pose on the frame a scene starts,
instead of one frame late.

    SIMULATE_PLAYER_INPUT_GAIT(player, mode, duration, ...)

Makes the player walk out of a scene under simulated input rather than snapping to
idle. Used at the end of the beach cinematic to hand control back while already
moving.

`SET_FACIAL_IDLE_ANIM_OVERRIDE(ped, name)` and its clear counterpart hold a facial
expression across a scene — the reason characters keep an expression between clips.
