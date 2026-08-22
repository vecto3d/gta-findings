# The results screen

**Source:** `minigame_stats_tracker.c` (173 unique lines, read in full),
`minigame_ending_stinger.c`

A small script that is worth more than its size. It is the **mission complete /
medal screen**, and it is built as a reusable service rather than as part of any one
minigame.

## It takes its payload as script parameters

The script is launched as its own thread with a struct describing what to show:
title, colour, medal, total, and an array of rows. It owns no game logic at all.

That means any activity can show a proper results screen by launching this with
data — no UI code of its own. For a FiveM port the same split is worth keeping: one
results resource, an event carrying the payload, every minigame calling it.

## The movie

**`mission_complete`**, driven with:

| Method | Purpose |
|---|---|
| `SET_MISSION_TITLE` | Title and subtitle |
| `SET_MISSION_TITLE_COLOUR` | Title tint |
| `SET_TOTAL` | The summary line |
| `SET_MEDAL` | Gold / silver / bronze |
| `SET_SOCIAL_CLUB_INFO` | Social club footer |
| `SET_DATA_SLOT` | One result row, called per row |

## One-call scaleform methods

Most code uses `BEGIN_SCALEFORM_MOVIE_METHOD`, then pushes parameters, then
`END_SCALEFORM_MOVIE_METHOD`. For simple calls there are single-call variants that
skip all of it:

    CALL_SCALEFORM_MOVIE_METHOD_WITH_STRING(movie, method, s0, s1, s2, s3, s4)
    CALL_SCALEFORM_MOVIE_METHOD_WITH_NUMBER(movie, method, f0, f1, f2, f3, f4)
    CALL_SCALEFORM_MOVIE_METHOD_WITH_NUMBER_AND_STRING(movie, method, ...)

Unused slots are `-1.0` for numbers and `0` for strings. Worth knowing — it removes a
lot of boilerplate from UI code.

## Pushing formatted text into a scaleform

The genuinely non-obvious part. A scaleform parameter cannot take a formatted value
directly, so text commands are used to build one:

    BEGIN_TEXT_COMMAND_SCALEFORM_STRING("STRING")
    ADD_TEXT_COMPONENT_SUBSTRING_TIME(milliseconds, 6)
    END_TEXT_COMMAND_SCALEFORM_STRING()

The block between begin and end becomes the next parameter. Three formats are used:

- **Times** — `ADD_TEXT_COMPONENT_SUBSTRING_TIME(ms, 6)` with the `"STRING"` command.
  Format `6` is minutes, seconds and hundredths.
- **Player names** — `ADD_TEXT_COMPONENT_SUBSTRING_PLAYER_NAME(name)` against a
  supplied label, so user-supplied text is never treated as a text key.
- **Decimals** — `ADD_TEXT_COMPONENT_FLOAT(value, 2)` with the `"NUMBER"` command.

Rows are typed by a code carried in the payload: type `4` is a time, type `8` is a
player name, anything else is numeric.

There is a small optimisation worth copying: whole numbers are pushed straight as
floats, and only non-whole values go through the two-decimal text formatting. It
avoids showing `3.00` where `3` is meant.

## Related

- [../reference/scaleform-index](../reference/scaleform-index.md)
- [../reference/notifications](../reference/notifications.md)
- [minigames-toolkit](minigames-toolkit.md)
