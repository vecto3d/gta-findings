# Rides — cable car, rollercoaster, ferris wheel

**Source:** `cablecar.c` (632K), `rollercoaster.c` (596K), `bigwheel.c` (660K),
`am_rollercoaster.c` (212K), `am_ferriswheel.c` (232K)

No anim dicts at all. Rides are built from entity attachment plus cameras:

- `cablecar.c` — 19 `ATTACH_ENTITY_TO_ENTITY`, 15 `SET_ENTITY_COORDS`,
  14 `PLAY_SOUND_FROM_ENTITY`, 5 `SET_CAM_ACTIVE`, 4 `SET_CAM_PARAMS`
- `rollercoaster.c` — `SET_ENTITY_COORDS` with `FREEZE_ENTITY_POSITION`, plus
  `SET_CAM_ROT` and `SET_CAM_PARAMS`

The pattern is: freeze the player, attach to a moving carrier entity, drive a
scripted camera. Directly reusable for any custom ride, lift or elevator.

`fairgroundhub.c` coordinates the fairground attractions.
