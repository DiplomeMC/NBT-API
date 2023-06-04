# NBT-API

The NBT API allows you to add custom NBT tags to Itemstacks, TileEntities and Entities, or modify excisting ones!
It completely uses reflections to interact with NMS code and works with all the latest versions. On server start the plugin checks all reflections.

Tested on Spigot
(1.7*)1.8.8-1.19
1.7.10 Crucible
The NBTInjector will not work with: 1.12.0, 1.12.1, 1.13.0 (Please just update to the final release of your chosen version)
On startup you will get a notification if there is a version problem!
* 1.7 Notes: Use a 1.7 with R4 (1.7.10), NBTLists may not work, everything using Gson is disabled(Add Gson before the NBTAPI loads, to turn it back on), and you can't get the NBTTypes, because 1.7 is missing this feature. Also apparently 1.7 has a bug where items can just lose their nbt data. TLDR: 1.7.10 is somewhat broken and not everything might work due to 1.7.10 limitations/old bugs.

What do I have to do as a server owner?
Just download the jar and drop it in the plugins folder. Done.
Note that outdated plugins may ask for "ItemNBTAPI". In this case download version 1.8.3 from the versions tab. The outdated "ItemNBTAPI" and "NBTApi" can be used at the same time.
Important for version 2.0.0: Don't reload while using the NBTInjector. Reloading, in general, is a horrible thing and it will break the NBTInjector in horrible ways! When updating plugins/changing configs always restart the server normally!
