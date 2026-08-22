# Heist minigames

**Source:** `gb_data_hack.c`, `gb_casino_heist.c`,
`fm_mission_controller_2020.c` (all ~10M, need targeted greps)

The scaleforms behind the vanilla heist minigames are named plainly:

| Scaleform | Mechanic |
|---|---|
| `VAULT_DRILL` | Drilling |
| `VAULT_LASER` | Laser cutting |
| `DIGITAL_SAFE_DISPLAY` | Keypad / safe entry |
| `HACKING_MESSAGE` | Hacking overlay |
| `SECURITY_CAM` | Camera feed |
| `DRONE_CAM` | Drone feed |
| `digiscanner` | Scanner overlay |
| `POWER_PLAY_GENERIC` | |

## Audio banks

Load these or the minigame is silent:
`DLC_MPHEIST\HEIST_FLEECA_DRILL` and `_DRILL_2`,
`DLC_HEIST3\HEIST_FINALE_LASER_DRILL`, `DLC_MPHEIST/HEIST_HACK_SNAKE`,
`DLC_MPHEIST/HEIST_USE_KEYPAD`, `DLC_HEIST3/Door_Hacking`,
`DLC_CHRISTMAS2017/XM_Silo_Laser_Hack`.

## Important caveat

`VAULT_DRILL` and `VAULT_LASER` are requested by nearly every arcade and heist
script as **shared boilerplate**. Grepping for those names will not find the
drilling logic — treat the name as a pointer, not a location.

Related: `mini@biotech@blowtorch_str` / `_def` for blowtorch cutting
(`fbi5a.c`), and [safe-cracking.md](safe-cracking.md).
