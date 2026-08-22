# Native call counts

Rough measure of how heavily R* leans on each area.

## Namespaces

| Namespace | Calls |
|---|---|
| `PLAYER` | 2.76M |
| `MISC` | 1.42M |
| `ENTITY` | 1.36M |
| `FILES` | 1.20M |
| `PED` | 1.14M |
| `SYSTEM` | 736K |
| `VEHICLE` | 699K |
| `PAD` | 691K |
| `NETWORK` | 582K |
| `HUD` | 367K |
| `GRAPHICS` | 194K |
| `TASK` | 188K |
| `STREAMING` | 188K |
| `CAM` | 186K |
| `OBJECT` | 127K |
| `AUDIO` | 124K |
| `DATAFILE` | 105K |
| `STATS` | 80K |
| `DECORATOR` | 69K |
| `SCRIPT` | 56K |

## Ped natives

`SET_PED_COMPONENT_VARIATION` (104718), `SET_PED_CONFIG_FLAG` (37034),
`SET_PED_CAN_SWITCH_WEAPON` (16305), `SET_PED_CAN_BE_KNOCKED_OFF_VEHICLE`
(14255), `SET_PED_RESET_FLAG` (10314), `SET_PED_COMBAT_ATTRIBUTES` (8092),
`SET_PED_PROP_INDEX` (6843), `SET_PED_STEALTH_MOVEMENT` (5544),
`SET_PED_MAX_MOVE_BLEND_RATIO` (5014), `SET_PED_DEFAULT_COMPONENT_VARIATION`
(3606), `SET_PED_INTO_VEHICLE` (3302), `SET_PED_KEEP_TASK` (2306),
`SET_PED_HEAD_BLEND_DATA` (2226), `SET_PED_CAN_BE_TARGETTED` (1903).

## Vehicle natives

`SET_VEHICLE_DOORS_LOCKED_FOR_ALL_PLAYERS` (18680), `SET_VEHICLE_MOD` (14049),
`SET_VEHICLE_DISABLE_TOWING` (13475), `SET_VEHICLE_ON_GROUND_PROPERLY` (13114),
`SET_VEHICLE_DOORS_LOCKED` (13103), `SET_VEHICLE_COLOURS` (12628),
`SET_VEHICLE_EXTRA` (10442), `SET_VEHICLE_EXTRA_COLOURS` (10106),
`SET_VEHICLE_ENGINE_ON` (9028), `SET_VEHICLE_WEAPON_RESTRICTED_AMMO` (7174),
`SET_VEHICLE_DOORS_LOCKED_FOR_PLAYER` (5955), `SET_VEHICLE_MOD_KIT` (4078).

## Weapons

`weapon_unarmed` (9679) leads by a wide margin — it is used constantly to stash
the equipped weapon during an interaction, exactly as the vending machine does.
Then `weapon_pistol` (8008), `weapon_carbinerifle` (5015),
`weapon_assaultrifle` (4455), `weapon_smg` (4386), `weapon_heavysniper` (4156),
`weapon_pumpshotgun` (3817), `weapon_heavysniper_mk2` (3778).

## Explosions and fire

`ADD_EXPLOSION` (562), `ADD_OWNED_EXPLOSION` (66), `START_SCRIPT_FIRE` (17).

## Cutscenes

246 distinct cutscenes requested via `REQUEST_CUTSCENE`.
