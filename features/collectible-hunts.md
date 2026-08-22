# Collectible hunts

Two complete, independent implementations to compare — both small.

## `spaceshipparts.c` (36K)

The better template. Scaleforms `MIDSIZED_MESSAGE` and `HUD_AWARDS`, GXT labels
`SSHIP_COLLECT`, `COLLECTED`, `PEYOTE_COMPLETED`, and a `SHARD_ANIM_OUT`
transition. Progress tracking, award popup and completion state in one file.

Giver scripts `omega1.c` and `omega2.c`.

## `letterscraps.c` (48K)

Own scaleform **`LETTER_SCRAPS`**. Same idea, different presentation.

## `underwaterpickups.c` (32K)

Seabed pickup placement. Straight list of standard pickup hashes:
`pickup_health_standard`, `pickup_armour_standard`, `pickup_money_case`,
`pickup_weapon_crowbar`, `pickup_weapon_grenade`, `pickup_weapon_grenadelauncher`,
`pickup_weapon_assaultrifle`.

## For custom collectibles

Use `pickup_custom_script` and `pickup_vehicle_custom_script` — the generic
script-defined types — rather than repurposing a weapon pickup.
See [pickups.md](../reference/pickups.md).
