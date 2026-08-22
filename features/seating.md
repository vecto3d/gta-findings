# Seating and sitting

**Source:** all 52 seating scripts, surveyed from unique code. 176,620 unique lines.

## A correction

An earlier pass in this repo dismissed these as duplicate clones. That was wrong on
both counts.

They are **not** duplicates — all 52 have unique code, and `am_mp_boardroom_seating.c`
alone carries 13,892 unique lines across 79 unique functions. And they are not low
value: they are the **best reference in the entire corpus** for placing a ped exactly
where an animation expects.

What misled the earlier pass was the asset count. These scripts average four distinct
assets each, the lowest of any category, because they reference almost nothing by
name — the anim dictionaries and clips arrive through helper functions rather than as
literals. A string-scanning sweep sees empty files. They are not empty; they are
opaque to that method.

## Why they matter

Every seating script positions the player the same way, and it is the technique
described in [animation alignment](../reference/animation-alignment.md):

    GET_ANIM_INITIAL_OFFSET_POSITION(dict, clip, sceneOrigin, sceneRot, 0.0, 2)
    GET_ANIM_INITIAL_OFFSET_ROTATION(dict, clip, sceneOrigin, sceneRot, 0.0, 2)

Then walk there and start the scene:

    TASK_GO_STRAIGHT_TO_COORD(ped, alignedPos, 1.0, 500, alignedHeading, ...)
    GET_SCRIPT_TASK_STATUS(ped, joaat("script_task_go_straight_to_coord"))

Not one of the 52 hardcodes an approach offset. Every chair in the game is aligned by
asking the animation. Given that a chair is exactly the case where clipping is most
obvious, that is a strong endorsement of the method.

Note the `500`ms walk timeout — much shorter than the `5000` the beds use, because
the player is already standing at the chair.

## Clip naming

Enter clips follow a convention, chosen by what the seat is for:

`enter_chair` · `enter` · `enter_tablet`

`arena_box_bench_seats.c` uses `enter_tablet` for a seat where the ped is holding a
tablet, so the entry animation and the prop match. Props are created and frozen
alongside, the same approach the casino cigar idle uses.

## Context extras

- `arcade_seating.c` runs the `dlc_ch_arcade_Watch_TV_Scene` audio scene while seated
- `SET_CAM_VIEW_MODE_FOR_CONTEXT(0, 1)` forces a view mode for the seated context
- Hashed exit states `BREAK_OUT` and `BREAKOUT_FINISH` appear as the standing-up path
- `weapon_unarmed` is forced on entry, as in every other interaction in the game

## Porting

If you are building any sit-down interaction, read `arena_box_bench_seats.c` (2,181
unique lines) rather than the boardroom one. It is the smallest complete example that
still covers enter, prop, scene and exit.

Do not copy the coordinates — copy the alignment call. That is the whole lesson of
this category.

## Related

- [../reference/animation-alignment](../reference/animation-alignment.md)
- [beds](beds.md)
- [object-brain-pattern](object-brain-pattern.md)
