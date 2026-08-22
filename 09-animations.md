# Animations and scenes

Part of the [GTA V decompiled script findings](README.md).

## Activity anim dictionaries (`mini@` / `oddjobs@`)

Listing every `mini@` and `oddjobs@` dict repo-wide is a better sweep than the
rare-name trick for animations, because these prefixes are activity-specific by
convention. The high-value results, with the script that implements each:

### `mini@cpr@` — CPR / revive (`fanatic1.c`)

Four dicts: `mini@cpr@char_a@cpr_str`, `char_a@cpr_def`, `char_b@cpr_str`,
`char_b@cpr_def` (`_str` = struggling, `_def` = default; `char_a`/`char_b` are
the two roles — medic and patient).

Anims: `cpr_intro`, `cpr_pumpchest`.

A two-person synced revive animation, exactly what an EMS script needs. The
paired `char_a`/`char_b` structure means medic and patient can be driven
together as a sync scene.

### `mini@safe_cracking` — full safe-cracking minigame

Used by `business_battles.c` and all three `fm_mission_controller*` variants.
The complete anim set is present:

- `step_into` — approach
- `idle_base`, `idle_look_around`, `idle_heavy_breathe` — waiting states
- `dial_turn_clock_fast`, `dial_turn_anti_fast` — the dial in both directions
- `DOOR_OPEN_SUCCEED_STAND`, `DOOR_OPEN_SUCCEED_STAND_SAFE` — success

Everything needed for a dial-turning safe minigame, including nervous idles.
`gb_biker_safecracker.c` is the other implementation.

### `mini@repair` — vehicle repair (`fbi4_prep2.c`)

Single anim `fixing_a_ped`. The mechanic-job animation.

### `mini@biotech@blowtorch_str` / `_def` — cutting

`fbi5a.c`, `fm_mission_controller_2020.c`, `public_mission_controller.c`.
Blowtorch/cutting for break-ins.

### Others

- `mini@racing@bike@`, `mini@racing@quad@` — `offroad_races.c`
- `mini@ears_defenders` — `range_modern.c`, ear defenders at the range
- `mini@arm_wrestling`, `mini@darts` (+ `dartsintro`, `dartsintro_alt1`,
  `dartsoutro`), `mini@golf` (+ `golfclub_bag`, `golfclubhouse`),
  `mini@tennis` (+ `@female`, `tennisexit@male`/`@female`), `mini@shoot_range`

## Sync scenes — the most-used mechanic in the repo

`TASK_SYNCHRONIZED_SCENE` (7998), `CREATE_SYNCHRONIZED_SCENE` (4747),
`NETWORK_CREATE_SYNCHRONISED_SCENE` (1991).

R* coordinates almost every multi-ped animation this way rather than with
separate `TASK_PLAY_ANIM` calls. Anything where two entities must move together
— the CPR pair, a ped opening a door for you, any cutscene-like set piece — is a
sync scene. The networked variant keeps it consistent for other players.
**This is the single most transferable technique in the codebase.**

## Camera shakes

`HAND_SHAKE` (1903, plus 380 more in other casings), `SMALL_EXPLOSION_SHAKE`
(260), `JOLT_SHAKE` (251), `ROAD_VIBRATION_SHAKE` (102), `DRUNK_SHAKE` (72),
`VIBRATE_SHAKE` (29), `SKY_DIVING_SHAKE` (29), `MEDIUM_EXPLOSION_SHAKE`,
`LARGE_EXPLOSION_SHAKE`, `GAMEPLAY_EXPLOSION_SHAKE`.

Casing is inconsistent in the originals; the names are case-insensitive.

## Scenario types

Most-used `TASK_START_SCENARIO_*` strings: `WORLD_HUMAN_CLIPBOARD` (104),
`CODE_HUMAN_MEDIC_KNEEL` (82), `WORLD_HUMAN_SMOKING` (50),
`WORLD_HUMAN_STAND_MOBILE_UPRIGHT` (47), `WORLD_HUMAN_STAND_MOBILE` (45),
`WORLD_HUMAN_GUARD_STAND` (44), `WORLD_HUMAN_HANG_OUT_STREET` (38),
`WORLD_HUMAN_WELDING` (35), `WORLD_HUMAN_STAND_IMPATIENT` (35),
`WORLD_HUMAN_SMOKING_POT` (33), `WORLD_HUMAN_DRINKING` (25),
`WORLD_HUMAN_LEANING` (16), `WORLD_HUMAN_AA_SMOKE` (16),
`CODE_HUMAN_MEDIC_TIME_OF_DEATH` (16), `WORLD_HUMAN_SIT_UPS` (15),
`WORLD_HUMAN_CLIPBOARD_FACILITY` (15), `WORLD_HUMAN_GUARD_STAND_ARMY` (11),
`WORLD_HUMAN_MOBILE_FILM_SHOCKING` (8), `WORLD_HUMAN_BINOCULARS` (6),
`WORLD_DOG_SITTING_RETRIEVER` (5), `WORLD_HUMAN_SECURITY_SHINE_TORCH` (4),
`WORLD_HUMAN_PAPARAZZI` (4).

`CODE_HUMAN_MEDIC_KNEEL` and `CODE_HUMAN_MEDIC_TIME_OF_DEATH` are the medic
scenarios — pair them with the `mini@cpr@` anims for a full EMS scene.
