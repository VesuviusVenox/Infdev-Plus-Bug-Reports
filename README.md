# Infdev-Plus-Bug-Reports
A public repository used to track bugs related to Infdev+. Anyone can contribute to this and it is actively tracked by the developer!

Please adhere to the following rules when reporting issues. Failure to comply with these may lead to your issue being closed without further investigation. The developer(s) need as much information as possible to get to the bottom of specific issues!

* Mod version. Very important, as the reported bug might already be fixed in a newer version!
* If reporting crashes, please attach a full crash log. Crash logs can easily be accessed from the MultiMC console, and they should also be stored in the mod's instance folder.
* Screenshots/Videos demonstrating the issue (if possible)
* Full description of the issue
* Steps to reproduce (or what you were doing before the issue happened, to help us reproduce it on our end)
* If reporting graphical issues, make sure to also include your driver version, GPU make and model and operating system (you can find all of these in the debug screen in-game)

Common problems:
* Mod requires at least 4 GB of memory to run properly. This is caused by some type of a memory leak in the code and is being actively investigated.
* Some structures may generate only halfway or are otherwise missing important rooms (such as the key room in the stronghold). This is being investigated.
* The AI system used by some mobs is still the original, Infdev system, so they may have difficulties pathfinding or get stuck. This will be addressed soon by migrating them to the new AI system.
* In very rare cases, you may experience a crash when generating chunks at or near a forest biome. This is caused by an infinite leaf decay loop the game can't exit out of, but should be fixed if you reload the world. This will be resolved when I rewrite the leaf decay in the near future.
* There is no multiplayer as of yet.

