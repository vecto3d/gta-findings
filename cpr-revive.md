# CPR / revive

**Source:** `fanatic1.c`

Four dictionaries under `mini@cpr@`:

- `mini@cpr@char_a@cpr_str`
- `mini@cpr@char_a@cpr_def`
- `mini@cpr@char_b@cpr_str`
- `mini@cpr@char_b@cpr_def`

`_str` is struggling, `_def` is default. `char_a` and `char_b` are the two roles,
medic and patient.

Anims: `cpr_intro`, `cpr_pumpchest`.

The paired role structure means medic and patient are driven together — see
[sync-scenes.md](sync-scenes.md).

## Supporting scenarios

`CODE_HUMAN_MEDIC_KNEEL` (82 uses) and `CODE_HUMAN_MEDIC_TIME_OF_DEATH` (16) are
the medic scenarios. Combined with the CPR anims that is a full EMS scene with no
custom animation work.
