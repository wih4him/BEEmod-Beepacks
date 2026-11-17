# TurretsTessersTetras

An item pack for BEEmod, for Portal 2's Puzzle Maker: turrets, tessers and tetras in one pack, 18 items.

## The items

- **T-Stop/Slow**
- **Zemeckis Cube**
- **Tessers**
- **Multidimensional Button**
- **Player-Tesser**
- **Portal Cube**
- **Turret Target Flip Panel**
- **Tetrahedral Cube** (Standard, Companion, Reflection, Sphere and IcosoKey forms, chosen with the Cube Type, plus the heart Companion, which shows a broken heart when it fizzles)
- **Tetrabutton (Tributton)**
- **Rotatable Faith Plate**
- **Turret Detection Plate (AND)**
- **Turret-Portal and Focused-Energy Remote-Control Device (Universal Remote)**
- **Turret Recharging Station**
- **Portal Turret [Stationary]**
- **Portal Cube-Turret**
- **Pellet Turret [Stationary]**
- **Pellet Cube-Turret**
- **Projectile Detection-Retention Filter**

Each item's description in BEEmod explains its boxes, inputs and controls.

## Requirements

- Portal 2
- BEEmod 4.46.1

## Installing

Download `U_WIH_G_TURRETSTESSERSTETRAS_2_20.bee_pack` and put it in BEEmod's `packages` folder. Then restart BEEmod.

**Updating from an older version:** each version has its own item IDs, so BEEmod cannot export a palette that still holds items from an older version. Take the old items out of the palette and put the new ones in. Remove the older `.bee_pack` from the `packages` folder too.

## Files these items write on your computer

Some items save files, so that time can be recalled or keys can be taken. Nothing else is written.

| Item | What it writes | Where |
|---|---|---|
| **Zemeckis Cube** (only a copy that can recall time) | Saved games `zem_0.sav` to `zem_10.sav`, about 3 MB each at most. The same names are written over every time, so they never grow in number. | `Portal 2\portal2\SAVE\<your Steam ID>\` |
| **T-Stop/Slow** (only a copy with Start Reversed) | One saved game, `wih_tstop.sav`, about 3 MB at most, written over every time. | the same folder |
| Items that take a key for their controls (some forms of the **T-Stop/Slow**, the **Player-Tesser** and the **Zemeckis Cube**) | Your own `config.cfg` is rewritten with the settings it already holds, before a key is taken, and read again to give the key back. No file is added. | `Portal 2\portal2\cfg\config.cfg`, `Portal 2\update\cfg\config.cfg` and the Steam Cloud copy |

These saves stay after the pack is removed. They show in Portal 2's Load Game list, where you can delete them, and Steam Cloud copies them if it is on.

## Thanks

A big thank-you to Valve and the Portal 2 team, and to the entire BEEmod community. Their game and mod made this set of items possible.
