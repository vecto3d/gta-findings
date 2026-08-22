# Casino table games

**Source:** `blackjack.c` (608K), `casinoroulette.c` (7.7M),
`casino_lucky_wheel.c` (1.5M), `bigwheel.c` (660K)

Both blackjack and roulette use only `instructional_buttons` /
`GENERIC_INSTRUCTIONAL_BUTTONS` — table state is data-driven and the dealer
animation lives in `am_casino_peds.c`, not in the game script.

`casinoroulette.c` is 7.7M but most of that is shared boilerplate; it also
carries unrelated props (`gr_prop_gr_basepart`, `prop_golf_ball`).

`casino_lucky_wheel.c` and `bigwheel.c` request no scaleform at all.

Ambient casino population, including brawl reactions, is documented in
[street-characters.md](street-characters.md) territory but lives in
`am_casino_peds.c` (9.5M) under `ANIM@AMB@CASINO@`:
`HANGOUT@PED_FEMALE@STAND@01A@BASE` / `@IDLES` / `@IDLES_CONVO` (numbered
variants), `BAR@SPECIAL_PEDS@LAUREN@01A@BASE@`,
`BAR@SPECIAL_PEDS@TAYLOR@01A@BASE@`, and `BRAWL@REACTS@BAR@` / `@SLOTS@` /
`@STANDING@`.
