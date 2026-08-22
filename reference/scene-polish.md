# Scene polish

**Source:** `re_mountdance.c`, `sb_heli_tours_seating.c`, `randomchar_controller.c`,
`restrictedareas.c`, read from logic skeletons.

The small calls that separate a scene that works from one that looks finished.

## Synchronised audio, properly

[Synchronised scenes](sync-scenes.md) have a matching audio API, and
`re_mountdance.c` uses all of it:

    INIT_SYNCH_SCENE_AUDIO_WITH_ENTITY("MNT_DNC", entity)
    PREPARE_SYNCHRONIZED_AUDIO_EVENT_FOR_SCENE("MNT_DNC", sceneId)
    PLAY_SYNCHRONIZED_AUDIO_EVENT(sceneId)
    STOP_SYNCHRONIZED_AUDIO_EVENT(sceneId)

Initialise against the entity, prepare for the scene, then play. The audio is locked to
scene phase, so if the scene is paused or scrubbed the sound follows. Starting a sound
on a timer alongside a scene drifts; this cannot.

Note the stop call fires when the dance is interrupted, not only when it completes.

## IK targets

    SET_IK_TARGET(ped, part, targetEntity, boneIndex, offX, offY, offZ, ...)

Inverse kinematics: point a hand or the head at something while another animation
plays. `re_mountdance.c` sets two, so the dancer keeps contact with the tape player
regardless of the loop's exact hand position.

This is what fixes "the animation is close but the hand does not quite touch the
object" without authoring a new clip.

## Detecting violence near a scene

    IS_BULLET_IN_AREA(x, y, z, radius, ...)
    IS_PROJECTILE_IN_AREA(x1, y1, z1, x2, y2, z2, ...)

The dance breaks when either fires. Cleaner than watching health or waiting for a ped
to react, and it triggers on a near miss rather than only on a hit.

`IS_ENTITY_OCCLUDED(entity)` answers whether something is actually visible to the
camera, useful before starting an animation the player would not see.

## Constraining the third-person camera

    SET_THIRD_PERSON_CAM_RELATIVE_PITCH_LIMITS_THIS_UPDATE(min, max)
    SET_THIRD_PERSON_CAM_ORBIT_DISTANCE_LIMITS_THIS_UPDATE(min, max)
    INVALIDATE_IDLE_CAM()

Rather than taking the camera with a scripted cam, the helicopter tour **limits** the
normal one — the player still looks around, but only within a sensible range. Much
lighter than a full camera takeover and it keeps player agency.

`INVALIDATE_IDLE_CAM` stops the idle camera drifting in during a long passive
sequence.

## HUD suppression

    HIDE_HUD_COMPONENT_THIS_FRAME(component)
    HUD_FORCE_WEAPON_WHEEL(bool)
    HUD_SUPPRESS_WEAPON_WHEEL_RESULTS_THIS_FRAME()
    DISPLAY_AMMO_THIS_FRAME(bool)
    THEFEED_HIDE_THIS_FRAME()

All per-frame, so they need re-asserting in a loop and clean up automatically when the
loop stops. That is a deliberate design — a script that dies cannot leave the HUD
broken.

## Blips owned by other scripts

    SET_THIS_SCRIPT_CAN_REMOVE_BLIPS_CREATED_BY_ANY_SCRIPT(true)

Normally a script may only remove its own blips. `randomchar_controller.c` takes this
permission to clean up stranger blips left by launchers it manages, then hands it back.

It also uses `GET_MINIMAP_FOW_COORDINATE_IS_REVEALED` — the minimap fog-of-war state
for a coordinate, used so a stranger is not blipped in an area the player has not
explored.

## Re-arming world brains

    REACTIVATE_NAMED_WORLD_BRAINS_WAITING_TILL_OUT_OF_RANGE("launcher_MrsPhilips")

A world brain that has fired stays dormant until the player leaves its range. This
re-arms it by name, which is how the stranger controller recycles encounters. It
confirms that [trigger scripts](../features/trigger-scripts-and-world-control.md) are
a managed system, not just a convention.

## Wanted level control

`restrictedareas.c` uses the full set rather than only setting stars:

    SET_PLAYER_WANTED_LEVEL(player, level, delayed)
    SET_PLAYER_WANTED_LEVEL_NOW(player, ...)
    SUPPRESS_LOSING_WANTED_LEVEL_IF_HIDDEN_THIS_FRAME(player)

`SET_PLAYER_WANTED_LEVEL` alone does not apply until confirmed with `_NOW`. The
suppress call stops a player escaping a restricted zone by hiding, which is exactly
what a secure-area resource needs.

Compare with `REPORT_CRIME` in
[networked-scripts](networked-scripts.md) — reporting is better when you want the
engine to judge severity; setting directly is right when the zone dictates it.

## Related

- [sync-scenes](sync-scenes.md)
- [hint-camera-and-music](hint-camera-and-music.md)
- [../features/trigger-scripts-and-world-control](../features/trigger-scripts-and-world-control.md)
