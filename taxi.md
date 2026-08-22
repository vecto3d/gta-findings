# Taxi

**Source:** `am_taxi.c` (376K), `taxiservice.c` (272K), `taxilauncher.c`,
`taxitutorial.c`, plus ten `taxi_*` mission variants

The two scripts together cover a complete taxi job with no UI to write:

- **`am_taxi.c`** — scaleform **`TAXI_HAIL`** (the hailing prompt) and anim dict
  **`ODDJOBS@TAXI@DRIVER`**
- **`taxiservice.c`** — scaleform **`taxi_display`**, the fare meter
- Render target **`taxi`** for the in-car screen
- Relationship group `TAXI_Passenger`

Mission variants (`taxi_clowncar`, `taxi_deadline`, `taxi_followcar`,
`taxi_gotyourback`, `taxi_needexcitement`, `taxi_procedural`, `taxi_takeiteasy`,
`taxi_taketobest`, `taxi_cutyouin`, `taxi_gotyounow`) are individual fare
scenarios and show how R* varies a repeated job.

Stat: `sp0_money_spent_on_taxis`.
