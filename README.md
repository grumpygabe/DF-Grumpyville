# DF-Grumpyville
A big city map for Darkness Falls.

Definitely inspired by JaWoodle's MegaCity series, although it is generated in a very different way (and features one much larger city).

⚠️This mod includes an override to quests.xml so that the white river scout is able to give clear & fetch quests instead of the normal kill quests (which don't work with the large city, for whatever reason).  This *will* stay in effect for other maps played if you have this mod installed - which shouldn't be game-breaking, but is worth knowing about.⚠️

# Requirements
[Darkness Falls](https://dev.azure.com/KhaineUK/_git/DarknessFallsA20).  Obviously.

# Overview

This is a custom 6k map for Darkness Falls.  It is special primarily because it features one REALLY BIG city (ie, Grumpyville).  There are actually a couple small suburbs around it as well, but that's the big draw.
It also features limited starting points near the center of downtown Grumpyville.  All players should start relatively close together, and relatively close to the same first trader.

Starting off will probably be very spicy.  Cities in Darkness Falls are scary places, and this drops you right in the middle of one.

This map pack also includes an XML patch for the default Darkness Falls quests.  The White River Scout's usual kill quests don't work on this map.  I have theories as to why this is, but no good fix.  So instead, with this mod she'll give the normal fetch and clear quests instead.

There are also a few custom city traders I modified to fit better with the downtown tiles.

Problems?
- The scout quest thing.
- It might blow up your computer.  Seriously, big cities do this.  Good luck.
- If you look at the log, you'll see LOTS of "WRN path node otherHeight bad" messages.  This isn't gamebreaking, but they're very frequent in this map (it's quite dense) and might end up making your logsize pretty large.  It's worth keeping an eye on.
  
# Installation
It's easy.  Drop the 5-DFGrumpyville mod in your mods folder, then choose "DFalls-Grumpyville-6k" when picking a new world.

# Server Stuff
If you're trying to use this on a server, you'll need to move the DFalls-Grumpyville-6k folder in 5-DFGrumpyville/Worlds into your server's Generated Worlds folder.  Do not move the rest of the mod.
