# Pre-authored paths

Shipped game data, so a FiveM script can play these back without authoring
anything.

## Waypoint recordings

**154 distinct** names via `REQUEST_WAYPOINT_RECORDING` — named vehicle routes,
e.g. `ARM2`, `ARM2_FIRE`, `AccomMarching01`, `BB_JEW_1`, `BB_JEW_2`, `BB_JEW_6`,
`BB_MOLLY_2`, `Eps8EPED`.

Driven with `TASK_VEHICLE_FOLLOW_WAYPOINT_RECORDING` (992 uses).

## Vehicle recordings

**146 distinct** via `REQUEST_VEHICLE_RECORDING` — full playback of a recorded
drive, used for scripted traffic and chases.

Recording tools also ship: `coordinate_recorder.c`, `liverecorder.c`,
`rerecord_recording.c`, `train_create_widget.c`.
