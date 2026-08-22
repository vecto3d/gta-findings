# Pause menu pages and button hints

**Source:** all 16 `ui-menus` scripts surveyed from unique code, chiefly
`pausemenu_map.c`, `pausemenu_multiplayer.c`, `pausemenu_sp_repeat.c`,
`mp_gameplay_menu.c`, `pausemenu.c`.

## Driving the pause menu without owning it

The pause menu is a frontend movie the game already has loaded. Scripts do not
request it — they call methods on it directly:

    BEGIN_SCALEFORM_MOVIE_METHOD_ON_FRONTEND("SET_DATA_SLOT")

The call returns a bool, so scripts wrap it in an `if` and only push arguments when
the frontend accepted the method. That guard is in every use and is not optional —
the frontend rejects methods when the menu is not in a state to receive them.

Confirmed methods:

| Method | Purpose |
|---|---|
| `SET_DATA_SLOT` | Write a row into a column |
| `SET_DATA_SLOT_EMPTY` | Clear a row |
| `SET_COLUMN_TITLE` | Header text for a column |
| `SET_COLUMN_SCROLL` | Scroll position |
| `SHOW_COLUMN` | Reveal a column |
| `FOCUS_CONTENT` | Move focus into content |
| `SHOW_WARNING_MESSAGE` | The full-screen confirm or warning overlay |

`pausemenu.c` and `pausemenu_example.c` are both tiny — 54 and 74 unique lines. R*
shipped a worked example next to the real thing, and it is the shortest description
of the contract available.

`SHOW_WARNING_MESSAGE` is the reusable one: it is the standard confirm dialog, and
calling it costs no assets of your own.

## Instructional buttons

The button hint bar along the bottom is a separate movie, requested as an
**instance** so several can coexist:

    REQUEST_SCALEFORM_MOVIE_INSTANCE("GENERIC_INSTRUCTIONAL_BUTTONS")
    BEGIN_SCALEFORM_MOVIE_METHOD(movie, "CLEAR_ALL")
    BEGIN_SCALEFORM_MOVIE_METHOD(movie, "TOGGLE_MOUSE_BUTTONS")

Both `INSTRUCTIONAL_BUTTONS` and `GENERIC_INSTRUCTIONAL_BUTTONS` are in use across
the corpus. Always `CLEAR_ALL` before repopulating, or rows accumulate.

## Scale

`am_pi_menu.c` — the interaction menu — is 110,027 unique lines across 1,221 unique
functions, one of the largest scripts in the game. `wardrobe_sp.c` is 55,554 and
`pausemenu_multiplayer.c` 34,239. Menus are among the most expensive things R*
built, which is worth remembering before hand-rolling one.

`timershud.c` has 145 unique functions and **zero** distinct mechanical calls — it is
pure layout and arithmetic driving the mission timer HUD.

## Related

- [../reference/scaleform-index](../reference/scaleform-index.md)
- [../reference/notifications](../reference/notifications.md)
