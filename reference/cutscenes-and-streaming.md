# Cutscenes, handoff and forced streaming

**Source:** `abigail1.c` (216 unique lines, read in full), `heist_ctrl_docks.c`,
`player_scene_f_taxi.c`.

The cutscene natives are widely known. What is not is the **handoff** — how the game
gets from a cutscene back to gameplay without a visible jump. `abigail1.c` is short
enough to read end to end and shows the whole recipe.

## Running a cutscene

    REQUEST_CUTSCENE_WITH_PLAYBACK_LIST(name, flags, playbackFlags)
    REGISTER_ENTITY_FOR_CUTSCENE(entity, "ABIGAIL", 0, 0, 0)
    START_CUTSCENE(flags)
    ... IS_CUTSCENE_PLAYING()
    REMOVE_CUTSCENE()

`REGISTER_ENTITY_FOR_CUTSCENE` binds a **live world entity** to a named role in the
cutscene, so the ped standing there is the ped in the scene, carrying its current
state. `heist_ctrl_docks.c` additionally calls
`SET_CUTSCENE_PED_COMPONENT_VARIATION` so a cutscene ped wears what the player last
saw them in.

## The handoff, which is the actual trick

While the cutscene is **still playing**, the script asks permission to set the exit
state and then positions everything for the moment it ends:

    if (CAN_SET_EXIT_STATE_FOR_CAMERA(false))
        SET_CAM_PARAMS(cam, pos, rot, fov, 0, ...)          // where the camera lands
        SET_CAM_PARAMS(cam, pos2, rot2, fov, 10000, ...)    // and where it drifts to

    if (CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY("Michael", 0))
        ... place the player
    if (CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY("Abigail", 0))
        ... place the other ped

Two `SET_CAM_PARAMS` calls back to back, the first with duration `0` and the second
with `10000`, mean the gameplay camera is **already drifting** the instant the cutscene
releases. There is no static frame to notice. That slow drift is why the transitions
feel filmic rather than cut.

The `CAN_SET_EXIT_STATE_*` guards matter: they return true only in the window where the
cutscene will accept the handoff. Setting positions outside it does nothing.

## Force-streaming the destination

Also set up during the cutscene, so the world is present when it ends:

    NEW_LOAD_SCENE_START(x, y, z, rx, ry, rz, radius, flags)
    IS_NEW_LOAD_SCENE_ACTIVE()
    NEW_LOAD_SCENE_STOP()

`abigail1.c` streams a `300` unit radius around the exit position while the cutscene
plays. Without it the player is dropped into an unstreamed world and watches it pop in.

This is the native to reach for whenever a player is **moved somewhere they were not**
— a teleport, a spawn, a property exit, a spectator jump. Start the load scene, wait
for it, then move. Always stop it afterwards; it holds streaming resources.

`heist_ctrl_docks.c` uses the related streaming-volume family, `STREAMVOL_IS_VALID`
and `STREAMVOL_DELETE`, for the same purpose over a region.

## Persistent injury as story state

An aside from `heist_ctrl_docks.c` worth recording: it calls
`APPLY_PED_DAMAGE_DECAL` with a `bruise` decal more than twenty times to mark
characters as beaten up, so story state is visible on the character rather than tracked
only in variables.

For a server this is a cheap way to show injury, arrest history or a fight without any
UI.

## Character switch animations

`player_scene_f_taxi.c` and `heist_ctrl_docks.c` reference the switch dictionaries —
`SWITCH@TREVOR@BED`, `SWITCH@TREVOR@WATCHING_TV`, `SWITCH@TREVOR@FLOYD_CRYING`. These
are the "what the character was doing while you were away" idles. There is a full set
per character, and they are ready-made ambient idles for any spawn-in.

`DOES_ENTITY_BELONG_TO_THIS_SCRIPT(entity)` appears here too — the correct guard before
touching an entity another script may own.

## Related

- [sync-scenes](sync-scenes.md)
- [animation-alignment](animation-alignment.md)
