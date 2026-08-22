# Scaleform returns, text drawing and timers

**Source:** the phone app family read from logic skeletons — `appsettings.c`,
`appsidetask.c`, `apptrackify.c`, `appvlsi.c`, `appzit.c`, `apporganiser.c`.

Small mechanisms that appear everywhere once you know them.

## Scaleform return values are asynchronous

The single most useful thing in this group, and a common source of bugs.

Reading a value back out of a scaleform movie is **not** a function call that returns.
It is a request, a poll, and a fetch:

    BEGIN_SCALEFORM_MOVIE_METHOD(movie, "GET_CURRENT_SELECTION")
    handle = END_SCALEFORM_MOVIE_METHOD_RETURN_VALUE()

    ... later frames ...
    if (IS_SCALEFORM_MOVIE_METHOD_RETURN_VALUE_READY(handle))
        value = GET_SCALEFORM_MOVIE_METHOD_RETURN_VALUE_INT(handle)

Note the different terminator: `END_SCALEFORM_MOVIE_METHOD_RETURN_VALUE` instead of
the usual `END_SCALEFORM_MOVIE_METHOD`. The result is not available on the same frame,
so treating it as synchronous reads stale data — usually the previous selection, which
looks like an off-by-one in the menu.

There are `_INT`, `_BOOL` and `_STRING` fetch variants.

## Parameter push types

Between begin and end, each parameter has its own call:

`SCALEFORM_MOVIE_METHOD_ADD_PARAM_INT` · `..._FLOAT` · `..._BOOL` ·
plus the text-command block for formatted strings described in
[the results screen](../features/results-screen.md).

The one-call `CALL_SCALEFORM_MOVIE_METHOD_WITH_*` variants skip all of this when the
call is simple.

## The two built-in timers

Scripts do not generally do arithmetic on `GET_GAME_TIMER`. They use two per-script
timers the engine maintains:

    SETTIMERA(0)        // reset
    if (TIMERA() > 3000) ...

    SETTIMERB(0)
    if (TIMERB() > 500) ...

Two independent timers per script, `A` and `B`, which is usually enough for a
"debounce plus timeout" pair. `appsettings.c` uses both at once — one for a ringtone
preview timeout, one for input debounce.

Cleaner than storing timestamps, and it survives the script being paused.

## Drawing text by hand

For the apps that draw their own UI rather than pushing into a movie, the full
sequence appears in `appsidetask.c`:

    SET_TEXT_FONT(font)
    SET_TEXT_SCALE(x, y)
    SET_TEXT_COLOUR(r, g, b, a)
    SET_TEXT_DROPSHADOW(distance, r, g, b, a)
    SET_TEXT_EDGE(...)
    SET_TEXT_PROPORTIONAL(bool)
    SET_TEXT_WRAP(start, end)
    DRAW_RECT(x, y, w, h, r, g, b, a)

`SET_TEXT_WRAP` is the one people miss — without it long strings run off the screen
edge instead of wrapping into a column.

## Loading text on demand

    REQUEST_ADDITIONAL_TEXT(block, slot)
    HAS_ADDITIONAL_TEXT_LOADED(slot)

Text blocks are streamed like any other asset. A label from an unloaded block resolves
to nothing, which is why [`DOES_TEXT_LABEL_EXIST`](../features/scripted-scene-hygiene.md)
matters.

## Odds and ends worth knowing

| Native | Use |
|---|---|
| `SET_CONTROL_SHAKE(pad, duration, frequency)` | Controller rumble |
| `PLAY_PED_RINGTONE` / `STOP_PED_RINGTONE` / `IS_PED_RINGTONE_PLAYING` | Phone ringing on a ped |
| `NETWORK_CLAN_GET_EMBLEM_TXD_NAME` | Crew emblem as a streamable texture dict |
| `REQUEST_SCRIPT_AUDIO_BANK("DLC_MPHEIST/HEIST_HACK_SNAKE")` | DLC banks use a path form |
| `GET_CLOCK_HOURS` / `_DAY_OF_WEEK` / `_DAY_OF_MONTH` / `_MONTH` | In-game calendar, used by the organiser app |
| `GET_PROFILE_SETTING(id)` | Read a user preference |

`apptrackify.c` is the only app doing real maths — `COS`, `ATAN2` and `SQRT` to turn a
position difference into a bearing and distance for its tracker display.

## Related

- [../features/results-screen](../features/results-screen.md)
- [../features/pause-menu-and-buttons](../features/pause-menu-and-buttons.md)
- [../features/phone](../features/phone.md)
