# Heist planning boards

**Source:** `gb_casino_heist_planning.c`, `heist_island_planning.c`,
`kortz_planning.c`, `tuner_planning.c`, `vehrob_planning.c`

Each drives a corkboard interface for choosing approach, crew and equipment.

Casino heist scaleforms come in three stages:
`CASINO_HEIST_BOARD_PREP`, `CASINO_HEIST_BOARD_SETUP`,
`CASINO_HEIST_BOARD_FINALE`.

Also `BANK_JOB_LOGIN` in `gb_bank_job.c`.

The planning-board pattern generalises well to any multi-stage job selection UI.
