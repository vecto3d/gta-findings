# Telescope

**Source:** `ob_telescope.c` (1.6M)

Dict `MINI@TELESCOPE`, three variants for the different models:

- `ENTER_FRONT` / `IDLE` / `EXIT_FRONT`
- `UPRIGHT_ENTER_FRONT` / `UPRIGHT_IDLE` / `UPRIGHT_EXIT_FRONT`
- `PUBLIC_ENTER_FRONT` / `PUBLIC_IDLE` / `PUBLIC_EXIT_FRONT`

Props `prop_telescope`, `prop_telescope_01`.
Sound sets `TELESCOPE_COIN_OP`, `TELESCOPE_High_End`, `TELESCOPE_DOMESTIC` — the
coin-op one is a paid interaction like the vending machine.
GXT labels `TELEHOME`, `TELEHLP`, `TELEHLP2`.

Adds a camera with FOV zoom (`SET_CAM_FOV`), a `SET_TIMECYCLE_MODIFIER`, and two
scaleforms for the viewfinder overlay. Good tourist-spot money sink.
