# Pickups

Most-referenced pickup types:

| Pickup | Uses |
|---|---|
| `pickup_weapon_advancedrifle` | 399 |
| `pickup_health_standard` | 324 |
| `pickup_weapon_grenade` | 302 |
| `pickup_armour_standard` | 280 |
| `pickup_weapon_rpg` | 274 |
| `pickup_weapon_pistol` | 250 |
| **`pickup_vehicle_custom_script`** | 245 |
| `pickup_weapon_combatmg` | 240 |
| `pickup_weapon_microsmg` | 237 |
| **`pickup_custom_script`** | 226 |
| `pickup_weapon_assaultshotgun` | 224 |
| `pickup_weapon_stickybomb` | 221 |
| `pickup_vehicle_health_standard` | 219 |
| `pickup_ammo_pistol` | 201 |
| `pickup_vehicle_health_standard_low_glow` | 189 |

**For custom collectibles use `pickup_custom_script` and
`pickup_vehicle_custom_script`** — the generic script-defined types — rather than
repurposing a weapon pickup.

## Money pickups

`pickup_money_variable`, `pickup_money_case`, `pickup_money_wallet`,
`pickup_money_purse`, `pickup_money_dep_bag`, `pickup_money_med_bag`,
`pickup_money_paper_bag`, `pickup_money_security_case`,
`pickup_gang_attack_money`, `pickup_vehicle_money_variable`.

Always place with `GET_SAFE_PICKUP_COORDS` so they do not land inside geometry —
see [cash-register.md](../features/cash-register.md).
