# Shops and customisation

**Source:** `shop_controller.c` (9.2M), `clothes_shop_sp.c` (7.6M),
`clothes_shop_mp.c` (7.9M), `carmod_shop.c` (8.3M), `tattoo_shop.c` (2.8M),
`hairdo_shop_sp.c` (3.4M), `gunclub_shop.c` (3.9M), `wardrobe_sp.c` /
`wardrobe_mp.c` (11M each)

**Almost no anim dicts.** The mechanics are native-driven.

## Clothing

`SET_PED_COMPONENT_VARIATION` (101 in the SP shop, 104718 repo-wide),
`SET_PED_PROP_INDEX`, `GET_NUMBER_OF_PED_TEXTURE_VARIATIONS`,
`GET_NUMBER_OF_PED_PROP_TEXTURE_VARIATIONS`, `SET_PED_MICRO_MORPH`.
`wardrobe_mp.c` owns the `MP_MENU_GLARE` scaleform.

## Car mods

The best reference for a mod-shop browsing camera:
`GET_NUM_VEHICLE_MODS` (145), `SET_VEHICLE_MOD` (107),
`SET_VEHICLE_MOD_COLOR_` (45), with 39 `SET_CAM_ACTIVE` and 28 `SET_CAM_PARAMS`.

**Warning:** there are **13 near-identical `*_carmod.c` clones** at ~8.3M each
(`arena_`, `base_`, `car_meet_`, `hacker_den_`, `hangar_`, `mansion_`,
`tuner_property_`, `personal_`, `business_hub_`, `fixer_hq_`, `juggalo_hideout_`,
`armory_aircraft_`, `vinewood_premium_garage_`). Read `carmod_shop.c` only.

## Note

`ADD_PED_DECORATION_FROM_HASHES` appears ~200 times in *every* shop script — it
is shared boilerplate, not tattoo-specific.

Only `gunclub_shop.c` has a real anim dict:
`ANIM@SCRIPTED@FREEMODE_NPC@FIX_AGY_IG2_REQUISITIONS@`.

Shop speech contexts: `SHOP_GREET`, `SHOP_GREET_UNUSUAL`, `SHOP_SELL`,
`SHOP_GOODBYE`, `SHOP_BANTER`, `SHOP_TRY_ON_ITEM`, `SHOP_NO_COPS`,
`SHOP_NO_WEAPON`, `SHOP_NO_MESSING`, `SHOP_GIVE_FOR_FREE`,
`SHOP_HAIR_WHAT_WANT`, `WEPSEXPERT_UPGRDSHOPGEN`.

Money stats: `sp0_money_spent_in_clothes`, `_on_hairdos`, `_on_tattoos`,
`_in_buying_guns`, `_car_mods`, `_property`, `_in_strip_clubs`, `_on_taxis`.
