# Collectible hunts

**Source:** `letterscraps.c` and `spaceshipparts.c` (both read in full),
`underwaterpickups.c`, `photographywildlife.c`, `murdermystery.c`, `shrinkletter.c`

Two complete implementations of the same idea, sharing one engine. Between them
they are the cleanest template in the corpus for "hide N things on the map and track
which ones the player has".

## One engine, two skins

Both scripts do the same three calls on startup and differ only in their arguments:

| | `letterscraps.c` | `spaceshipparts.c` |
|---|---|---|
| Prop | `prop_ld_scrap` | `prop_power_cell` |
| Collect label | `LETTERS_COLLECT` | `SSHIP_COLLECT` |
| Backing stat | `num_hidden_packages_0` | `num_hidden_packages_1` |
| Magic numbers | `705`, `50` | `755`, `50` |

Register the set with a model and a label, bind it to a stat slot, then let the
shared code place and track everything. Adding a third hunt means one more call with
one more stat slot.

## The pieces worth taking

**Pickups, not objects.** Collectibles spawn as pickups of type
`pickup_custom_script` rather than as props with a distance check. That gets the
float, spin, glow and collection sound from the engine for free.

**Interior pickups need registering.** A pickup placed inside an interior is
invisible until it is added to the room:

    ADD_PICKUP_TO_INTERIOR_ROOM_BY_NAME(pickup, "GtaMloRoomTun5")

This is easy to miss and the failure looks like the pickup silently not spawning.

**Progress lives in a stat, not in script state.** Collected count and total are read
back from the stat, so progress survives without the script owning it. Completion is
just count equalling total, which then fires the reward path.

**Singleton guard.** Both scripts terminate immediately if more than one thread of
their own hash is already running. Cheap, and worth copying for any resource that
must not double-start.

## The document viewer

`letterscraps.c` carries a second, separately useful thing: a **fullscreen readable
document**, built on the `LETTER_SCRAPS` scaleform.

It requests the movie, pushes page text through a `SET_LETTER_TEXT` method, and
draws it with `DRAW_SCALEFORM_MOVIE_FULLSCREEN`. Four pages, `LETTERS_PAGE_ONE`
through `LETTERS_PAGE_FOUR`, paged with the left and right controls and closed with
the cancel control.

Two details make it feel right:

- It calls `SET_GAME_PAUSED(true)` and hides the radar while the document is open,
  and draws with `SET_SCRIPT_GFX_DRAW_BEHIND_PAUSEMENU` so the page sits under the
  pause menu rather than over it.
- Page turns are **debounced with a latch** — the input sets a flag that only clears
  once the control is released, so a held button turns one page, not forty.

For FiveM this is a ready-made pattern for any in-world readable: notes, newspapers,
case files, letters. The pause is the part to reconsider, since pausing is
single-player behaviour; freeze input and blur instead.

## The rest

- `underwaterpickups.c` — same engine, underwater placement
- `photographywildlife.c` and `photographymonkey.c` — photograph-the-target variant,
  scored through the phone camera rather than pickups
- `murdermystery.c` — clue hunt, has its own `vintage_filmcan` prop
- `shrinkletter.c` — owns the `PSYCHOLOGY_REPORT` scaleform, another document viewer
- `prop_drop.c` — 4 lines, empty stub

## Related

- [../reference/pickups](../reference/pickups.md)
- [../reference/scaleform-catalogue](../reference/scaleform-catalogue.md)


## One stat series for every hunt

Confirmed across the whole category: all collectible hunts write into the same
numbered stat family.

| Stat | Hunt |
|---|---|
| `num_hidden_packages_0` | Letter scraps |
| `num_hidden_packages_1` | Spaceship parts |
| `num_hidden_packages_6` | Monkey photographs |

So adding a hunt means claiming the next index, not inventing storage. A server
porting this can keep the same shape: one counter series, one shared completion
check.

## A second document viewer

`shrinkletter.c` owns the `PSYCHOLOGY_REPORT` scaleform and drives it with
`SET_PLAYER_NAME` alongside the same `SET_LETTER_TEXT` method the letter scraps use.
Two different movies, one text-setting convention — useful if you want a second
readable style without building anything.

## Pickup creation, both forms

`underwaterpickups.c` uses both:

    CREATE_PICKUP(type, x, y, z, flags, amount, ...)
    CREATE_PICKUP_ROTATE(type, x, y, z, rx, ry, rz, flags, amount, ..., customModel)

The lifetime argument is either a millisecond timeout or `-1` to persist. The rotate
form is the one that accepts a custom display model, as covered in
[random-events](random-events.md).

## Filters as feedback

`murdermystery.c` plays `"ON"` from the `NOIR_FILTER_SOUNDS` soundset when its
black-and-white investigation filter engages. Pairing a timecycle or filter change
with its own sound is a small touch that makes a mode change read as deliberate.
