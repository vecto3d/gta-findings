# Minigame toolkit

**Source:** all 75 `minigames` scripts surveyed from unique code, including
`am_darts.c`, `bj.c`, `blackjack.c`, `bigwheel.c`, `cablecar.c`,
`am_rollercoaster.c`, `am_mp_arcade_*.c`, `camhedz_arcade.c`.

The category holds 1,166,312 unique lines, far too much to read. What follows is the
shared toolkit that shows up across all of them.

## Interactive animation: MoVE networks

The most important find in the category, documented separately in
[move-networks](../reference/move-networks.md). Arm wrestling and the arcade love
meter both run named animation state machines that report their state as a string
and respond to input while playing. The love meter reuses the casino heist's vault
drilling network, which means these are generic and repurposable.

## Scaleform in world space

`am_darts.c` draws its scoreboard with:

    DRAW_SCALEFORM_MOVIE_3D(movie, x, y, z, rx, ry, rz, scaleX, scaleY, scaleZ, 2)

A scaleform rendered onto a plane in the world rather than over the screen. This is
the alternative to a [render target](tv-and-channels.md) when the surface is not a
model you can link to — scoreboards, floating signs, machine displays.

## Camera transitions

`bj.c` moves between two cameras without a cut:

    SET_CAM_ACTIVE_WITH_INTERP(newCam, oldCam, 10000, 1, 1)

The engine interpolates over the duration. Creating a second camera and interpolating
to it is much smoother than repositioning one camera per frame, and it is what the
casino games use throughout.

`am_mp_arcade_claw_crane.c` forces a view mode for its context with
`SET_CAM_VIEW_MODE_FOR_CONTEXT(0, 4)`, which is how a cabinet locks you to first
person while playing.

`bigwheel.c` drives its camera as an offset from the player's own rotation —
`SET_CAM_ROT(cam, GET_ENTITY_ROTATION(ped, 2) + offset, 2)` — so the view rides the
ride without the script tracking orientation itself.

## Riding a moving platform

`cablecar.c` attaches passengers and props directly to the moving car with
`ATTACH_ENTITY_TO_ENTITY` on bone index `0`, offset per seat, some rotated `180` to
face the other way. `am_rollercoaster.c` does the same and waits for scene phase past
`0.99` before releasing.

That is the whole trick for any moving vehicle interior: attach, do not chase.

## Audio soundsets

Each ride and cabinet ships its own soundset, which saves authoring any audio:

| Soundset | Sounds seen |
|---|---|
| `DLC_IND_ROLLERCOASTER_SOUNDS` | `Ride_Stop`, `Bar_Unlock_And_Raise` |
| `CABLE_CAR_SOUNDS` | `Leave_Station` |
| `dlc_ch_nazar_speaks_sounds` | `fortune_bell`, `fortune_mech_loop` |
| `HUD_FRONTEND_DEFAULT_SOUNDSET` | `SELECT`, `CANCEL`, `NAV_LEFT_RIGHT`, `NAV_UP_DOWN` |

The frontend set is the one to reuse for any menu — players already read those
sounds as navigation.

## Randomness that avoids repeats

A recurring idiom is `GET_RANDOM_INT_IN_RANGE(0, 65535) % n` rather than
`GET_RANDOM_INT_IN_RANGE(0, n)`. Several scripts also **cycle** a variant index
after use instead of re-rolling, so the same clip cannot appear twice in a row. The
safehouse activities do the same thing.

## Casino ped population

`am_casino_peds.c` is enormous — 1,023 unique functions, 116,523 unique lines, more
than any other minigame script — and almost all of it is ambient patrons. It leans
entirely on `TASK_PLAY_ANIM_ADVANCED` with explicit world coordinates and packed
flag values such as `786433`, `786945` and `135004161`.

`TASK_PLAY_ANIM_ADVANCED` is worth knowing generally: it plays a clip at an exact
position and rotation without needing a synchronised scene, which is the cheap way to
place a single ambient animation precisely.

## Related

- [../reference/move-networks](../reference/move-networks.md)
- [darts](darts.md) · [casino-table-games](casino-table-games.md) ·
  [arcade-cabinets](arcade-cabinets.md) · [slot-machine](slot-machine.md)
