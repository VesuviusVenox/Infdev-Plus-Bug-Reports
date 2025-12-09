# Infdev-Plus-Bug-Reports
A public repository used to track bugs related to Infdev+. Anyone can contribute to this and it is actively tracked by the developer!

PLEASE USE THE CORRESPONDING TEMPLATE WHEN POSTING BUGS!!! If you do not provide adequate information (e.g. you don't fully fill out the form or don't use it at all), YOUR REPORT WILL BE MARKED AS INVALID AND IGNROED! 
Please do not flood the repo with nothingburger reports!

Common problems:
* Mod requires at least 4 GB of memory to run properly. This is caused by some type of a memory leak in the code and is being actively investigated.
* Some structures may generate only halfway or are otherwise missing important rooms (such as the key room in the stronghold). This is being investigated.
* The AI system used by some mobs is still the original, Infdev system, so they may have difficulties pathfinding or get stuck. This will be addressed soon by migrating them to the new AI system.
* In very rare cases, you may experience a crash when generating chunks at or near a forest biome. This is caused by an infinite leaf decay loop the game can't exit out of, but should be fixed if you reload the world. This will be resolved when I rewrite the leaf decay in the near future.
* There is no multiplayer as of yet.

