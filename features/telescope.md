# Telescopes and scripted viewing cameras

**Source:** `ob_telescope.c` (read in full, 1,462 unique lines)

A coin-operated telescope: pay, take control of a fixed camera, pan and zoom, exit.
Worth reading not for telescopes but because it is a complete, careful example of
**taking the camera off the player and giving it to the user**, which is the same
problem as a drone, a security monitor, a sniper scope or a spectator view.

## The one native worth the read

    USE_SCRIPT_CAM_FOR_AMBIENT_POPULATION_ORIGIN_THIS_FRAME(true, false)

Called every frame the telescope camera is active.

Ambient population — pedestrians, traffic — normally spawns around the *player*.
Point a long-range camera somewhere else and you are looking at an empty city, because
nothing spawns where you are looking. This native moves the spawn origin to the
camera.

This is the fix for the "my drone footage has no traffic in it" problem, and it is
close to undiscoverable unless you happen to read a script that needed it.

## Camera setup

    CREATE_CAM_WITH_PARAMS("DEFAULT_SCRIPTED_CAMERA", pos, rot, fov, true, 2)
    SET_CAM_NEAR_CLIP(cam, 0.1)
    SET_CAM_CONTROLS_MINI_MAP_HEADING(cam, true)
    RENDER_SCRIPT_CAMS(true, false, 3000, true, false, 0)

Three details:

- **Near clip at `0.1`** stops the telescope body clipping through the view.
- **`SET_CAM_CONTROLS_MINI_MAP_HEADING`** points the minimap where the camera looks
  instead of where the ped faces. Without it the minimap keeps spinning to the ped
  and the view feels detached.
- **`3000`ms blend** on the way in, and the same call with `false` on the way out,
  so the transition is eased rather than cut.

Zoom is two stored FOV values swapped between, not a continuous range. Panning
writes rotation directly with `SET_CAM_ROT`.

## Exit

`RENDER_SCRIPT_CAMS(false, ...)`, deactivate, `DESTROY_CAM`, then
`SET_GAMEPLAY_CAM_RELATIVE_HEADING(0.0)`. That last call is what stops the gameplay
camera snapping to a stale angle when control returns.

## Positioning the player

Rather than the usual walk-to-a-point, this uses
`script_task_ped_slide_to_coord` and waits for the task status to report finished.
Sliding is the right choice for a short final adjustment where a walk animation would
look wrong.

The brain also handles first-person separately throughout, checking
`GET_FOLLOW_PED_CAM_VIEW_MODE() == 4` and, where needed, forcing
`MotionState_Aiming`. Every safehouse and telescope brain does this. First person is
never an afterthought in Rockstar's own scripts.

## Variants and payment

Three models, branched on throughout: `prop_telescope`, `prop_telescope_01`, and the
arena `xs_prop_arena_telescope_01`, which behaves differently in several places.

Charges run through the standard service transactions `service_spend_telescope` and
`service_spend_arena_spectator_box`. The arena variant also looks for
`ex_prop_office_louvres` nearby, so the view can be blocked by shutters.

## Porting

The camera work transfers directly. The pieces that matter, in order of how easily
they are missed:

1. `USE_SCRIPT_CAM_FOR_AMBIENT_POPULATION_ORIGIN_THIS_FRAME` every frame
2. `SET_CAM_CONTROLS_MINI_MAP_HEADING` so the minimap agrees with the view
3. `SET_GAMEPLAY_CAM_RELATIVE_HEADING(0.0)` on exit
4. Blend times on both transitions, not just the entry

## Related

- [object-brain-pattern](object-brain-pattern.md)
- [../reference/camera-shakes](../reference/camera-shakes.md)
