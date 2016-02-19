# ArmA 3 EDEN Tools
This is a plugin I made for ArmA 3's new 3D Editor - EDEN. It's main purpose is to make life easier when working with the Exile mod. It will generate code for you in a copy and paste format.

# Current Features
| Feature  | Description |
| ------------- | ------------- |
| Generate Code for Objects  | This will generate code compatible with Exile for all objects in the active scenario.  |
| Generate Code for Markers  | Much like the above, though I have not yet implemented this.  |
| Create Spawn Group | This will create 100 units of type Exile_Unit_GhostPlayer - used for players when spawning. |
| Generate Code for Spawns | This generates the code in the old SQM format. Some edits might be needed. |
| Select Target Object | This will select the current object as the 'target' - used for relative loot positions. |
| Toggle Loot Preview | This will spawn some loot on all the markers, giving you a preview of how it would look. |
| Generate Code for Loot | This will generate the code in a copy and paste format, add this to your config.cpp. |
| Clear Loot Sphere | This will delete all current loot spheres. **Does not yet work as intended** |

#YouTube Video
I put together a very basic video showcasing how the loot generation works, I'll try and create a better video later on where I explain how it all works. But most of it is rather self-explanatory. https://www.youtube.com/watch?v=ayW7DQb4-b8

# Known Issues
• When clearing all loot spheres, the object themselves are removed. But the EDEN Editor icons remain and can be moved around - code is still generated despite the objects not really being there. Have yet to find a solution for this.
• When deleting your selected target, the green outline remains. Again, yet to find a solutions since EDEN events don't seem to be working for me.
• More to come...

# Changelog
Will post new features and bug fixes here.
