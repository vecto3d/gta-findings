# Notifications

`BEGIN_TEXT_COMMAND_THEFEED_POST` — 2650 call sites, ended by:

| Ending | Uses |
|---|---|
| `END_TEXT_COMMAND_THEFEED_POST_TICKER` | 1314 |
| `..._MESSAGETEXT` | 868 |
| `..._UNLOCK_TU` | 536 |
| `..._CREWTAG_WITH_GAME_NAME` | 292 |
| `..._CREWTAG` | 167 |
| `..._MESSAGETEXT_SUBTITLE_LABEL` | 89 |
| `..._UNLOCK` | 28 |
| `..._STATS` | 17 |
| `..._AWARD` | 13 |

The award and unlock variants are the achievement-earned popups.

Related HUD scaleform `HUD_AWARDS`, used by the collectible hunts.


## The award shard

Surveyed from `animal_controller.c`, `flyunderbridges.c`, `forsalesigns.c` and
`celebrations.c`, all read via extraction of their unique code.

The big centred banner the game shows on a collectible or milestone is one scaleform
driven the same way everywhere. It is probably the most directly reusable UI pattern
in the corpus, because it needs no assets of your own.

**Movie:** `MIDSIZED_MESSAGE`

**Methods, in order of use:**

| Method | Purpose |
|---|---|
| `SHOW_SHARD_MIDSIZED_MESSAGE` | Set the title and subtitle, then animate in |
| `SHOW_BRIDGES_KNIVES_PROGRESS` | Progress variant, `n of m` style |
| `SHARD_ANIM_OUT` | Animate out; call it rather than just stopping the draw |

Drawn with either `DRAW_SCALEFORM_MOVIE_FULLSCREEN(movie, 100, 100, 100, 255, 0)` or
the positioned `DRAW_SCALEFORM_MOVIE(movie, 0.5, 0.5, 1.0, 1.0, ...)`. Note the
colour components are `100`, not `255` — the shard is drawn dimmed and the movie
supplies its own brightness.

**Always paired with a sound from `HUD_AWARDS`:**

`PEYOTE_COMPLETED` · `COLLECTED` · `UNDER_THE_BRIDGE` · `SIGN_DESTROYED`

Played with `PLAY_SOUND_FRONTEND(-1, name, "HUD_AWARDS", true)`. The sound is what
makes it register as an achievement rather than a message.

The freemode celebration equivalent is a different movie, `MP_BIG_MESSAGE_FREEMODE`,
with `ADD_COMPLETE_MESSAGE_TO_WALL`. `celebrations.c` runs it alongside the
`MP_CELEB_SCREEN_SCENE` audio scene and a `bokeh_removebuzz` timecycle modifier, so
the background blurs while the banner is up.

Full movie list in [../reference/scaleform-index](scaleform-index.md).
