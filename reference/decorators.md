# Decorators — entity state

R* attaches persistent state to entities with decorators, which survive
ownership migration between clients.

| Native | Call sites |
|---|---|
| `DECOR_EXIST_ON` | 23399 |
| `DECOR_GET_INT` | 16133 |
| `DECOR_SET_INT` | 5671 |
| `DECOR_GET_BOOL` | 1589 |
| `DECOR_SET_BOOL` | 1285 |
| `DECOR_REGISTER` | 115 |
| `DECOR_SET_TIME` | 15 |
| `DECOR_SET_FLOAT` | 2 |

## Named decorators

`MPBitset` (9814), `Player_Vehicle` (5764), `Veh_Modded_By_Player` (2301),
`PV_Slot` (2282), `IgnoredByQuickSave` (2051), `Not_Allow_As_Saved_Veh` (1810),
`ContrabandOwner` (1775), `Player_Thruster` (1592), `MLJ` (1536),
`ExportVehicle` (1507), `Creator_Trailer` (1285), `bombdec` (1178),
`bombowner` (1135), `Player_Hacker_Truck` (1114).

FiveM has state bags now, but decorators still work and are how vanilla marks
personal vehicles and ownership.
