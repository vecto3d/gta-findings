# Arcade cabinets

**Source:** ten self-contained scripts, which makes them unusually good ports.

| Script | Size | Notes |
|---|---|---|
| `am_mp_arcade_fortune_teller.c` | 60K | Smallest activity in the repo |
| `grid_arcade_cabinet.c` | 276K | Full texture set, below |
| `photographymonkey.c` | 460K | Uses `MIDSIZED_MESSAGE` |
| `am_mp_arcade_claw_crane.c` | 1.8M | Claw machine |
| `am_mp_arcade_love_meter.c` | 1.8M | |
| `am_mp_arcade_strength_test.c` | 1.8M | Own scaleform **`AXE_OF_FURY`** |
| `degenatron_games.c` | 1.9M | |
| `camhedz_arcade.c` | 2.1M | |
| `gunslinger_arcade.c` | 2.1M | |
| `ggsm_arcade.c` | 2.2M | |

Plus `am_mp_arcade.c` (the property), `am_mp_arcade_peds.c`, `arcade_seating.c`,
`apparcadebusiness.c`.

## How the screen works

**Not render targets and not scaleform.** The cabinets draw with `DRAW_SPRITE`
from streamed texture dictionaries. `grid_arcade_cabinet.c` exposes the whole
set: `MPArcadeCabinetGrid`, `MPArcadeCabinetGridHUD`, `MPArcadeCabinetGridTiles`,
and per-player sprites `MPArcadeCabinetGridPlayerBlue`, `Green`, `Purple`,
`Yellow`.

So a cabinet game is: draw sprites each frame from a texture dict, read controls,
keep score. The same approach works for any custom minigame drawn over a screen
prop.

**Caution:** every arcade script also requests `VAULT_DRILL` and `VAULT_LASER`
as shared boilerplate. Those names do not indicate cabinet logic.
