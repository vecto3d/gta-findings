# The hotwire minigame

**Source:** `am_mp_hotwire.c` (934 unique lines, read in full)

The most self-contained interactive minigame in the corpus, and the best template for
any skill-check overlay — lockpicking, hacking, wiring, safe dials. It is
**sprite-drawn**, not scaleform, which makes it far easier to port.

## Drawn with sprites, not a movie

The whole UI is `DRAW_SPRITE` calls against the texture dictionary **`MPHotwire`**,
with sprite names such as `HWSF_QT`. No scaleform movie, no NUI, no assets of your
own — request the texture dictionary and draw.

For FiveM this matters: a sprite-drawn minigame is a few dozen lines of draw calls
and needs no HTML, no message passing, and no focus handling.

## Input handled twice, on purpose

    IS_USING_KEYBOARD_AND_MOUSE(2)

Appears eleven times. The script runs **two input paths** and picks per frame, not at
startup, so a player switching between pad and keyboard mid-minigame is handled.

Analog input comes from `GET_CONTROL_NORMAL`, which returns a normalised axis value
rather than a pressed/not-pressed bool. That is what allows a gradual dial rather than
a button mash. `IS_CONTROL_JUST_PRESSED` handles the discrete confirmations, and
`DISABLE_CONTROL_ACTION` suppresses everything else while the overlay is up.

## Frame-rate independence

    SYSTEM::TIMESTEP()

Used to scale movement per frame. Anything that moves continuously must multiply by
timestep, or the minigame is easier at high frame rates and harder at low ones — an
extremely common bug in community minigames.

`GET_FRAME_TIME` serves the same purpose elsewhere in the corpus, for example in the
[animated door](animated-door-collision.md).

## Audio that tracks the state

    SET_VARIABLE_ON_SOUND(soundId, name, value)

The minigame holds a looping sound and writes a variable into it as the state changes,
so the tone follows how close you are rather than firing discrete beeps. It is the
same principle as [audio scene variables](../reference/audio.md) — a driven value
instead of a triggered event — applied to a single sound.

It runs inside the `DLC_XM17_IAA_Hack_Minigame_Scene` audio scene.

## Network-safe timing

    GET_NETWORK_TIME()
    GET_TIME_DIFFERENCE(a, b)

Rather than `GET_GAME_TIMER`. Network time is consistent between machines, so a timed
challenge cannot be won by a client with a different local clock. Worth adopting for
anything timed that a server will validate.

## State in bit flags

`SET_BIT` and `CLEAR_BIT` on a single integer rather than a struct of bools — used
throughout this script and the heist controllers. Compact, and trivially syncable as
one number.

## Related

- [minigames-toolkit](minigames-toolkit.md)
- [../reference/move-networks](../reference/move-networks.md) — for minigames where the
  *animation* must respond, rather than an overlay
- [../reference/texture-dict-index](../reference/texture-dict-index.md)
