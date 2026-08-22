# Hint cameras, music events and the feed

**Source:** the Epsilon and stranger scripts read from logic skeletons —
`epsilon2.c`, `epsilon5.c`, `epsdesert.c`, `epsilontract.c`.

Three systems that are widely available and almost never used outside Rockstar's own
scripts.

## The gameplay hint camera

The best find in this group. When the game wants you to *notice* something — a
character, a door, a vehicle — it does not take the camera. It nudges it:

    SET_GAMEPLAY_ENTITY_HINT(entity, offX, offY, offZ, controlOn, duration, blendIn, blendOut)
    IS_GAMEPLAY_HINT_ACTIVE()
    STOP_GAMEPLAY_HINT(immediate)

The player keeps control. The camera drifts toward the target and returns. There are
coord and ped variants alongside the entity one.

It is fully tunable while running:

| Native | Effect |
|---|---|
| `SET_GAMEPLAY_HINT_FOV` | Zoom of the hint |
| `SET_GAMEPLAY_HINT_FOLLOW_DISTANCE_SCALAR` | How far back it sits |
| `SET_GAMEPLAY_HINT_BASE_ORBIT_PITCH_OFFSET` | Look up or down at the target |
| `SET_GAMEPLAY_HINT_CAMERA_RELATIVE_SIDE_OFFSET` | Shift left or right |
| `SET_GAMEPLAY_HINT_CAMERA_RELATIVE_VERTICAL_OFFSET` | Shift up or down |
| `SET_GAMEPLAY_HINT_CAMERA_BLEND_TO_FOLLOW_PED_MEDIUM_VIEW_MODE` | How it hands back |
| `STOP_GAMEPLAY_HINT_BEING_CANCELLED_THIS_UPDATE` | Keep it alive while the player moves |

That last one matters — a hint is cancelled by player input by default, so a hint that
must persist through movement needs it re-asserted each frame.

**Why this is worth having.** The usual FiveM answer to "look at this" is a scripted
camera, which takes control away and feels heavy. A hint costs nothing, cannot trap
the player, and is what the game itself uses for every objective reveal.

## Music events

The score is event-driven, not a track you play:

    PREPARE_MUSIC_EVENT("EPS2_FAIL")
    TRIGGER_MUSIC_EVENT("EPS2_FAIL")

Prepare first, trigger when it should land — preparing loads the stems so the
transition happens on the beat rather than after a load. Event names seen include
start, stop and fail variants per mission.

The engine handles the musical transition between states. This is how mission music
swells and cuts cleanly instead of cross-fading.

## The notification feed

    BEGIN_TEXT_COMMAND_THEFEED_POST(label)
    ... optional ADD_TEXT_COMPONENT_* calls
    END_TEXT_COMMAND_THEFEED_POST_TICKER(...)

The ticker variant is the plain top-left notification. `THEFEED_HIDE_THIS_FRAME`
suppresses the whole feed during a cinematic.

## Reading doors without a hash

    GET_STATE_OF_CLOSEST_DOOR_OF_TYPE(modelHash, x, y, z, &locked, &heading)

Useful when you know the door model and roughly where it is but not its registered
hash. `DOES_OBJECT_OF_TYPE_EXIST_AT_COORDS` serves the same purpose for props.

## Ped state predicates

A fuller set than most scripts use, all seen in `epsdesert.c`:

`IS_PED_FLEEING` · `IS_PED_RAGDOLL` · `IS_PED_PRONE` · `IS_PED_ON_FOOT` ·
`IS_PED_FALLING` · `IS_PED_SWIMMING` · `IS_PED_WALKING` · `IS_PED_STILL` ·
`IS_PED_SPRINTING`

Combined, these answer "is this ped in a state where I can safely start an
interaction" far better than a health-and-distance check.

`GET_PED_NEARBY_PEDS(ped, &array, flags)` enumerates neighbours into an array —
cheaper and more correct than iterating all peds and filtering by distance.

`SET_BLOCKING_OF_NON_TEMPORARY_EVENTS(ped, true)` makes a ped ignore distractions
entirely, which is what keeps a scripted character from reacting to passing traffic.

`SET_PED_MONEY(ped, amount)` sets what a ped drops when killed — the hook a
pickpocketing or mugging resource wants.

## Cutscene odds and ends

`WAS_CUTSCENE_SKIPPED` · `GET_CUTSCENE_TIME` · `HAS_CUTSCENE_FINISHED` ·
`IS_CUTSCENE_ACTIVE`

After a cutscene the Epsilon scripts set `SET_GAMEPLAY_CAM_RELATIVE_PITCH` and
`SET_GAMEPLAY_CAM_RELATIVE_HEADING` so the gameplay camera resumes facing the right
way — the same concern as the telescope's heading reset.

They branch on `WAS_CUTSCENE_SKIPPED`, because a skipped cutscene needs different exit
placement from one that played through. Skipping is a separate code path, not an early
return.

## Debug names left in

`SET_PED_NAME_DEBUG(ped, "POSTTOM")` survives in the shipped scripts. Like the
[developer state labels](developer-state-labels.md), these name things the developers
cared about and occasionally reveal intent.

## Related

- [cutscenes-and-streaming](cutscenes-and-streaming.md)
- [../features/ped-control-flags](../features/ped-control-flags.md)
- [audio](audio.md)
