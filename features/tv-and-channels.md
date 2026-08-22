# TVs, channels and render targets

**Source:** `ob_tv.c` (read in full), `ob_franklin_tv.c` (read in full)

The most reusable thing in the object brains after the interaction skeleton. This is
a working recipe for **drawing anything onto a surface in the world**, which is the
same machinery behind custom screens, menu boards, adverts and cinema.

## The render target recipe

The sequence matters and every step is load-bearing:

1. `REGISTER_NAMED_RENDERTARGET("tvscreen", false)`
2. `LINK_NAMED_RENDERTARGET(modelHash)` — binds the target to a **model**, not an
   instance. Every object of that model shows what you draw.
3. Poll `IS_NAMED_RENDERTARGET_LINKED(modelHash)` and re-register plus re-link if
   the check fails. `ob_tv.c` retries in a loop rather than assuming success —
   linking is not reliable on the first attempt.
4. `GET_NAMED_RENDERTARGET_RENDER_ID("tvscreen")` for the id you draw into.

To draw a frame:

    SET_TEXT_RENDER_ID(renderId)
    ... draw calls, here DRAW_TV_CHANNEL(0.5, 0.5, width, 1.0, 0.0, 255,255,255,255)
    SET_TEXT_RENDER_ID(GET_DEFAULT_SCRIPT_RENDERTARGET_RENDER_ID())

**Always restore the default render id.** Leaving it pointed at the target sends the
rest of the frame's drawing to the TV instead of the screen. Cleanup releases the
target with `RELEASE_NAMED_RENDERTARGET` and restores the id again.

Draw coordinates are `0..1` across the target surface, so `0.5, 0.5` is centred.

## The TV channel system

Independent of render targets and easy to miss — the game ships a full broadcast
system:

- `SET_TV_CHANNEL(n)` / `GET_TV_CHANNEL()`, and `SET_TV_CHANNEL(-1)` turns it off
- `SET_TV_CHANNEL_PLAYLIST(channel, playlistName, flag)` builds a channel from a
  named playlist
- `SET_TV_VOLUME(v)`
- `SET_TV_AUDIO_FRONTEND(false)` then `ATTACH_TV_AUDIO_TO_ENTITY(screen)` makes the
  sound positional instead of 2D
- `SET_TV_PLAYER_WATCHING_THIS_FRAME(ped)` must be called **every frame** while
  watching, or playback stalls
- `ENABLE_MOVIE_SUBTITLES(true)` while watching, off on exit

Channel choice is written back into a global array per TV, so each set remembers what
it was tuned to across visits. Cheap trick, worth copying.

## Screen models

`ob_tv.c` handles several and branches on model:

- `v_ilev_mm_screen2` — the on state, and `v_ilev_mm_scre_off` for off. The script
  **swaps one object for the other** rather than toggling a state
- `v_ilev_mm_screen2_vl` — a second object created alongside
- `prop_tv_03`, `prop_trev_tv_01`, `prop_tv_flat_01` — each with its own offsets

The off-model swap is the detail to note. A TV that is off is a different prop, not
the same prop with a black texture.

## The remote control gate

`ob_franklin_tv.c` will not let the player watch unless the remote is physically
present:

    DOES_OBJECT_OF_TYPE_EXIST_AT_COORDS(coords, 3.0, joaat("prop_cs_remote_01"), false)

A small piece of world logic that costs nothing and reads as intentional. The same
brain also refuses to start while the player is wanted, outside an interior, or on a
phone call, and it runs the `FRANKLIN_SAFEHOUSE_ACTIVITIES_SCENE` audio scene with
help label `TV_HLP0` and anim dict `safe@franklin@ig_14`.

Approach validation uses `IS_PED_HEADING_TOWARDS_POSITION(ped, coords, 90.0)` — a
90-degree facing cone rather than a distance check, so you cannot start it with your
back to the screen.

## FiveM notes

Render targets work unchanged and are the standard route for NUI-free in-world
screens. Two things that catch people:

- The link is per **model**, so every instance of that prop displays the same thing.
  Distinct content per screen needs distinct models.
- The re-link retry loop is not defensive padding. Register and link genuinely fail
  when the model is not streamed in yet.

## Related

- [../reference/render-targets](../reference/render-targets.md) — every registered
  target name in the corpus
- [object-brain-pattern](object-brain-pattern.md)
- [cinema](cinema.md)
