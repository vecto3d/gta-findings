# Safehouse drinking and smoking

**Source:** `ob_drinking_shots.c`, `ob_franklin_beer.c`, `ob_franklin_wine.c`,
`ob_wheatgrass.c`, `ob_bong.c`, `ob_mr_raspberry_jam.c`, `ob_huffing_gas.c`,
`ob_sofa_michael.c`, `ob_sofa_franklin.c` (1.8–1.9M each, heavy shared boilerplate)

## Dictionaries

`MP_SAFEHOUSEBEER@`, `MP_SAFEHOUSEWINE@`, `MP_SAFEHOUSEWHISKEY@`,
`mp_safehousewheatgrass@`, `mp_safehousebong@`, plus character-specific
`safe@michael@ig_1`–`ig_5`, `safe@franklin@ig_9`–`ig_14`, `safe@trevor@ig_5`–`ig_8`.

## The useful part: drunk-state exits

Each activity has enter and idle clips plus **separate exits per drunk state**:

- `exit_sober_bot`, `exit_slightly_drunk_bot`, `exit_moderately_drunk_bot`,
  `exit_drunk_bot`
- Glass variants: `exit_sober_glass`, `exit_drunk_glass`, `exit_shotglass`
- Bottle counts: `exit_1_bottle` through `exit_4_bottle`, `exit_1_beer`,
  `exit_2_beer`
- Matching facial anims, e.g. `exit_sober_trevor_facial`,
  `exit_moderately_drunk_trevor_facial`
- Named cameras: `bong_cam`, `short_cam`, `enter_cam`, `drinking_wine_cam2`/`3`,
  `ig_8_huff_gas_cam`, `ig_2_wheatgrassdrink_cam`

## Props

`prop_cs_beer_bot_01`, `prop_wine_bot_01`, `p_wine_glass_s`,
`p_whiskey_bottle_s`, `p_tumbler_02_s1`, `p_tumbler_cs2_s`,
`p_tumbler_cs2_s_trev`, `prop_bong_01`, `p_cs_joint_01`, `prop_cigar_03`,
`p_w_grass_gls_s`, `prop_mr_raspberry_01`, `prop_bottle_cap_01`.

Audio: `SAFEHOUSE_FRANKLIN_USE_BONG`, `SAFEHOUSE_MICHAEL_SIT_SOFA`,
`SAFEHOUSE_TREVOR_DRINK_WHISKEY`. Speech labels `SA_BEER`, `SA_WINE`,
`SA_WHSKY`, `SA_SHOT2`, `SA_BONG`, `SA_BONG2`, `SA_CIGAR`, `SA_SPLFF`, `SA_GAS`,
`SA_MRJAM`, `SA_WHEAT`.

See also [drunk-system.md](drunk-system.md).
