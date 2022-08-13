---
layout: post
title: Minecraft world downloads (1.16.5 / 2022)
author: Joey
---
The Survival and Creative world downloads from the last server reset in March 2022 are now available. 

<!--more-->

These worlds were last opened in Minecraft 1.16.5. 

⚠ **Warning**: The downloads will be significantly larger after being unzipped, especially for Creative! 

|--
| World name | ZIP download size | Uncompressed size |
|--
| [**Survival**](https://f001.backblazeb2.com/file/N3FS-worlds/2022/survival_main.zip) | 6.3 GB | 10.3 GB
| [**Creative**](https://f001.backblazeb2.com/file/N3FS-worlds/2022/creative_main.zip) | 1.1 GB | 24.6 GB ⚠
|--

Have fun!

## Notes

These files are being provided as-is from the server. You should be able to open each world by copying each folder into your `.minecraft/saves` folder. 

**Changing game modes**: Go to the Pause menu, select Open to LAN, and set Allow Cheats to On. After this, you should be able to change game mode by using the command `/gamemode creative`.

**Merging files for the Nether and The End dimensions**: For multi-dimension worlds like Survival, each world dimension is in its own folder: world, world_nether, and world_the_end. 

If you want the dimensions to work properly within a single world, copy the main `world` folder first, then copy and replace the DIM-1 folder from the Nether and the DIM1 folder from The End into the main world folder. 

You should end up with a folder layout like this: 

* world
    * /region
    * /DIM-1 (copied from world_nether)
    * /DIM1 (copied from world_the_end)
    * level.dat and other files and folders
