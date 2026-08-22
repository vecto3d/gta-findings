# Chop — companion dog / K9

**Source:** `chop.c` (212K)

The richest single animal find in the repo. Full rottweiler AI:

| Dict | Purpose |
|---|---|
| `creatures@rottweiler@move` | Locomotion |
| `creatures@rottweiler@tricks@` | Trick animations |
| **`creatures@rottweiler@indication@`** | Scent indication pose |
| `creatures@rottweiler@melee@streamed_taunts@` | Attack |
| `creatures@rottweiler@amb@world_dog_barking@enter` / `@idle_a` / `@exit` | Barking |
| `creatures@rottweiler@amb@sleep_in_kennel@` | Sleeping |
| `creatures@rottweiler@in_vehicle@std_car` | Riding in a car |
| `misschop_vehicleenter_exit` | Getting in and out |

The indication pose is the one most police K9 scripts fake with a generic sit.
Everything a K9 unit or companion pet needs is here.

Scenario `WORLD_DOG_SITTING_RETRIEVER` for static dogs.
