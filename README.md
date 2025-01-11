# lcpp_gas_pumps_props

Adds GTAV modern fuel pump props to the map for the Liberty City Preservation Project: https://worldtravel.dev/

Thanks to hrdbdyz and his LegacyFuel for LC script edit, for easier access to where each gas station was: https://discord.com/channels/1297057471034167369/1323872021293306007/1323872021293306007

Includes all LC native gas stations and includes two custom fueling scenes at the Airport and Airdock landing pads for Helicopters. Includes an edited prop_gas_pump_old2 prop for the Terroroil pump as I couldn't get a modern version of the RON pump working with a replaced texture for branding.

WARNING: This includes two replacement YMAP files that replace the original LPCC files, these are to hide the native pump props under the ground as sometimes they were spawning in fine and causing duplication visual glitches, etc. I've included backups of the original files also e.g. `nj_01_stream4.ymapBACKUP` and `queens_w_stream10.ymapBACKUP`
If LCPP does a FiveM patch in the future, you MUST check that they have not added these two files to the patch, if they have, I need to release an update. The chance that they change anything on the ymap is very low however.

## How To Install:
1. Place the `lcpp_gas_pumps` folder into your FiveM/RP Framework resources folder, e.g., `[defaultmaps]` or whatever you use**.
**No need to edit `server.cfg` as `[defaultmaps]` will be in there by default. If you dumped the folder into the `resources` folder on its own, add `ensure lcpp_gas_pumps` to your `server.cfg` towards the bottom of your resources list.
2. Cut `Ctrl+X` the `libertycity` folder from within `lcpp_gas_pumps` and then paste `Ctrl+V` into the folder that has your `libertycity` folder from the LCPP map files. This will automatically place the files into the right subfolders.
3. Click ok to replace files.

## TP Coordinates:
- `/tp 6641.7 -1542.51 16.34`
- `/tp 3875.58 -1520.38 27.92`
- `/tp 3796.84 -3226.81 6.49`
- `/tp 6959.92 -2419.01 16.43`
- `/tp 6312.12 -2927.31 29.35`
- `/tp 6518.56 -2356.8 13.87`
- `/tp 6317.24 -3614.51 18.54`
- `/tp 4708.29 -3465.96 7.28`
- `/tp 4753.28 -3275.91 9.39`
- `/tp 5297.15 -2120.05 14.08`
- `/tp 5962.52 -3060.82 6.18`
- `/tp 7429.24 -2527.97 5.81` (Airport)
- `/tp 5595.31 -3905.29 4.69` (Dock Heliport)

## Pump Models for Fuel Scripts:
- `prop_gas_pump_1a`
- `prop_gas_pump_1b`
- `prop_gas_pump_old2`
- `prop_air_fueltrail1`
- `prop_air_fueltrail2`
