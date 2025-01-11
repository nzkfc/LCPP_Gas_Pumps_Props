# LCPP Gas Pumps Props

Adds GTAV modern fuel pump props to the map for the Liberty City Preservation Project: [Liberty City Preservation Project](https://worldtravel.dev/)

Thanks to hrdbdyz and his LegacyFuel for LC script edit, for easier access to where each gas station was: [LegacyFuel Discord Message](https://discord.com/channels/1297057471034167369/1323872021293306007/1323872021293306007)

## Features
- Adds all LC native gas stations with modern pumps.
- Includes two custom fueling scenes at the Airport and Airdock landing pads for helicopters.
- Edited `prop_gas_pump_old2` to create a Terroroil-branded pump since the RON pump could not be replaced with a modern texture.

## Important Notes
- Includes **two replacement YMAP files** (`nj_01_stream4.ymap` and `queens_w_stream10.ymap`) to hide the native pump props under the ground. This prevents visual glitches caused by duplicate props.
- Backup files for the originals are included (`nj_01_stream4.ymapBACKUP` and `queens_w_stream10.ymapBACKUP`).
- If LCPP releases a FiveM patch in the future, verify that these two YMAP files have not been altered. If they have, an update will be required. However, changes to these files are unlikely.

---

## How to Install

1. **Move `lcpp_gas_pumps` to your resources folder**:  
   Place the `lcpp_gas_pumps` folder into your FiveM/RP Framework resources folder (e.g., `[defaultmaps]` or any similar folder).  

   If you placed the folder directly into the `resources` directory, add this line to your `server.cfg` at the bottom of your resources list:  
   ```plaintext
   ensure lcpp_gas_pumps
   ```

2. **Move the `libertycity` folder**:  
   Cut (`Ctrl+X`) the `libertycity` folder from inside `lcpp_gas_pumps` and paste (`Ctrl+V`) it into your existing `libertycity` folder from the LCPP map files. This will automatically place the files into the correct subfolders.

https://github.com/user-attachments/assets/0ba45212-a175-41e7-acef-99dd7dc8b6f6

3. **Replace files**:  
   When prompted, click **OK** to replace files.

---

## TP Coordinates
Use the following teleport commands to visit the fueling locations:

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

---

## Pump Models for Fuel Scripts
These are the prop models used for fuel scripts:

- `prop_gas_pump_1a`
- `prop_gas_pump_1b`
- `prop_gas_pump_old2`
- `prop_air_fueltrail1`
- `prop_air_fueltrail2`
  
