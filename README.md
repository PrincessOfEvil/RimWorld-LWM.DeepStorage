# LWM's DeepStorage - a mod for RimWorld

## This is a functional version of Deep Storage Units that will likely be [WIP] for a while yet.

LWM presents yet another way to deal with your storage needs:  Deep Storage units!

Currently available are multiple buildings that can store more than one object at a time.  Inspired by Skullywag's Extended Storage, this mod takes a different approach - storage buildings that pawns can simply carry multiple items to.  An approach that got a lot harder with 1.0, BTW, but I like the results so far.

This mod will be updating as I tweak items and fix bugs, but I wanted to make it available now that it's mostly working.

Pallets, clothing racks, food storage trays, etc.  You can also write your own &lt;ThingDef&gt;s if you don't like what I've done.

## Requirements
 * HugsLib (load it first, as usual) https://steamcommunity.com/sharedfiles/filedetails/?id=818773962 or on github, etc

## Installation
 * Put the LWM.DeepStorage folder (under _Mod) inside your game's Mod/ folder.  Update often?

## Deep Storage Units
 * Big Shelf - a shelf with enough space to store two items per cell
 * Medicine Cabinet - what it says on the box
 * Meal Tray Racks - efficient storage for meals.  Or desserts.
 * Food Baskets - store raw food, some plant matter, or pile in drugs
 * Meat Hooks - I think you can figure out what these are for
 * Weapon Lockers - currently requires Machining? Efficiently store weapons!
 * Clothing Rack - currently stores both civilian and military clothing - subject to change
 * Pallet - for piling so many things onto!
 * Pallet with Wrapping - can store loose matter, too!
 * Skips - Are you American?  Did you know "Dumpster" is a registered TM?  Rock chunks, heavy resournces

Using Deep Storage - bonus tip:  If you have selected an item in DeepStorage, if you right-click, you jump the storage unit!

## Known Bugs
 * If something destroys a DSU (or a player moves it while items are in it), items may become invisible.  Saving and re-loading will solve this problem.
 * If, for whatever reason, more items end up in Deep Storage than a DSU can hold, pawns will not notice and will leave them there.  Yes, it's obscure.

## Planned/Likely Changes
 * Possibly limit by mass.
 * Possibly limit by total mass.
 * Possible options
 * Possible changes to how much/what kinds of stuff is allowed in various units
 * Possible more units
 * Wooden Weapon Cabinets for pre-industrial eras.

## Compatibility (load Deep Storage after these)
 * Combat Extended - Weapon Lockers can store a maximum total Bulk (Sumghai)
 * RimWorld Search Agency (Hauling Hysteresis): hysteresis disabled for DSUs

## Uncompatibility - or - Strange Bugs?
 * Likely uncompatible with other storage solutions that pile lots of things in one place (extended storage, RT_Shelves, ???)
 * I f***ed with the Selector and some mesh Drawing.  It's possible, altho unlikely, this may cause an incompatibility

The code can be found online at: https://github.com/lilwhitemouse/RimWorld-LWM.DeepStorage

On Steam: https://steamcommunity.com/id/littlewhitemouse/myworkshopfiles/?appid=294100

In the Ludeon Forum: https://ludeon.com/forums/index.php?topic=47707.0



Most images used with permission from Skullywag. (Thanks!)

Weapons Cabinets and Lockers are sumghai's. (Also thanks!)

Meat Hooks are (c) LWM.

## License
Almost all code (c) LWM.

Also (currently) includes some code from Ratysz, allowing right-click to select actions on items, which Sumghai had permission to use (also GPL).  Thanks!

Released under GPL 3.0.

All of LWM's code (and sumghai's additions) are also released under LGPL, because I think that the LGPL is the license we should actually be using for mods.  Not that anyone is likely to complain, but altho we have a stupid copyright system, we should still use it correctly.

All of LWM's code (and sumghai's) are also available to Ludeon Studios, should they be incorporated into the base RimWorld game.

