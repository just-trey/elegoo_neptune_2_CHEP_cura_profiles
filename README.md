# Elegoo Neptune 2 "CHEP" Cura 4.10 Profiles

For those using Toylerrr's Cura custom profile for the Neptune 2 from here (https://www.thingiverse.com/thing:4899915) or here (https://github.com/Toylerrr/ELEGOO_Neptune2_Cura). I figured out how to modify the popular [CHEP printer profile settings](https://www.chepclub.com/cura-profiles.html) so you can add them in Cura 4.10. NOTE:  I did make some minor changes noted below to the configuraitons. 

To download them: 
1. Click the green "Code" button on this page and then click "Download ZIP" to a location on your computer. 
1. Extract the fils on your computer
1. Open Cura then and click on the "Preferences" menu and select "Contfigure Cura"
1. Select the "Profiles" option on the Preferences screen.
1. Click import and select each profile you unzipped to your computer. (Note: you have to do one at a time)

## My modifications

### All profiles
Changed the naming of the files to make them clearer

### neptune_2_cura_4.10_0.12(best).curaprofile
- Set `adaptive_layer_height_enabled` to`true`
- Set `support_enable` to `false`
- Set `coasting_enable` to `True`
- Set `skirt_line_count` to  `2`
- Set a few items to be calculated rather than a hard coded value 
  - `infill_pattern`
  - `skirt_brim_speed`
  - `speed_layer_0`
  ` `travel_compensate_overlapping_walls_0_enabled`

### neptune_2_cura_4.10_0.2(good).curaprofile
- Set `adaptive_layer_height_enabled` to`true`
- Set `coasting_enable` to `True`
- Set `infill_sparse_density` to `25`
- Set `skirt_line_count` to  `2`
- Removed `xy_offset_layer_0` setting
- Set a few items to be calculated rather than a hard coded value 
  - `cool_fan_speed`
  - `infill_pattern`
  - `skirt_brim_speed`
  - `speed_layer_0`
  ` `travel_compensate_overlapping_walls_0_enabled`

### neptune_2_cura_4.10_0.28(rough).curaprofile
- Set `adaptive_layer_height_enabled` to`true`
- Set `skirt_line_count` to  `2`
  - Set a few items to be calculated rather than a hard coded value 
  - `infill_pattern`
  - `skirt_brim_speed`
  - `speed_layer_0`
