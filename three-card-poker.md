# Three card poker

**Source:** `three_card_poker.c` (568K)

A casino game that the `casino_*` prefix sweep missed entirely — worth noting as
a lesson about relying on filename prefixes.

Uses only `instructional_buttons` and `GENERIC_INSTRUCTIONAL_BUTTONS`, so the
card rendering and table state are handled elsewhere, likely in code and props
rather than a dedicated scaleform.
