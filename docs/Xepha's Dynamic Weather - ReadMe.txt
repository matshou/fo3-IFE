Name: Dynamic Weather
Version: 3.0
Date: 12/02/2012
Category: Gameplay Effects and Changes
Requirements: Fallout 3 v1.7
Optional Requirements: Operation Anchorage (DLC), The Pitt (DLC), Broken Steel (DLC), Point Lookout (DLC)
Author: Xepha
Source: http://www.fallout3nexus.com/downloads/file.php?id=10607



======================
Description/Details:
======================

Remaining true to Bethesda's vision of a polluted/radioactive/post-apocalyptic world, Dynamic Weather presents a more natural, progressively changing, weather system.  Utilizing Bethesda's original weather types, my own custom weather types and assets from Skingrad's Enhanced Weather, Dynamic Weather includes Rainstorms, Lightning Storms as well as Fog and Sandstorms.

In varying degrees and depending on cloud cover, Dynamic Weather has much darker nights than Vanilla Fallout 3.  Some form of Night Vision (Night Vision Goggles/Night Ghoul Eyes (Mart's Mutant Mod)) is recommended for the darkest nights.



======================
Install/Load Order:
======================

If you are updating from previous versions, a Clean Install *must* be performed:

1. If installing fresh (i.e., no previous versions) go to step 4.  If updating from previous versions go to Step 2.

2. Deactivate/delete ALL Dynamic Weather esm/esp's and files:

Xepha's Dynamic Weather.esm
ALL Xepha's Dynamic Weather - *.esp's
C:\..\Fallout 3\Data\Textures\Sky\DWLightCloudsUpper.dds

3. Start Fallout 3 and (preferably in an interior location) save your game to a new save slot then quit the game.

4. Extract files to your \Fallout 3\Data\ folder

5. Using FOMM, place a check-mark beside the required file(s) and adjust load order:

all other esm's
Xepha's Dynamic Weather.esm							(***Required ***)
... 
other mods/esp's
...
Xepha's Dynamic Weather - Main.esp					(***Required ***)

6. Enjoy the weather! :p

Load Xepha's Dynamic Weather.esm as your *last* esm.
Load all other Xepha's Dynamic Weather - xxx.esp's very late/last in your load order.

For advice on load order for the optional plugins, read the appropriate readme.

Note: Where readme's state that Xepha's Dynamic Weather - Main.esp is *required*, but you have opted to use the Xepha's Dynamic Weather - Main + DLC Merged.esp plugin. the Main.esp is no longer required, since you are now using the merged version.


============================
Un-Install:
============================

1. Deactivate/delete ALL Dynamic Weather esm/esp's:

Xepha's Dynamic Weather.esm
ALL Xepha's Dynamic Weather - *.esp's

2. Delete the following:

..\Fallout 3\Data\Textures\Sky\DWLightCloudsUpper.dds



======================
Updates/History:
======================

Dynamic Weather 3.0, 12/02/2012

Massively overdue, this rather major update deserves the jump to 3.0, I think.  The main focus being one of customization, allowing you to pick and choose your favoured weather types whilst still in game.

There are also multiple merged versions allowing custom installations configured to your requirements.

See the relevant readme's for more details on use/installation.


ESM/Weather Machine:
----------------------

* Several new and reworked weather types added.

* Weather/Climate is now fully customizable, whilst at the same time remaining dynamic.  All configured via the Weather Machine.

* "Purifed" weather types are now disabled by default.  Use the Weather Machine to activate them.

* Rain and Sandstorms have, by default, a 3.5 day delay before they will appear.  Configurable via the Weather Machine.

The Weather Machine now comes in multiple versions depending on the level of "immersion" required:

* Quest Added - This small, tiny, baby, mini, un-marked quest is my personally recommended way of integrating this climate restoring weather device into the game.  You just have to find it first. 

Just like the G.E.C.K., the W.A.R.M. is a Vault-Tec/Future-Tec developed device, and since it is a Prototype version, that didn't quite make it into production before "the bombs fell", you won't find it in any Vault - but you might find it in a Vault-Tec related building in the D.C. Ruins area. ;)

* Vendor Added - Moira, being the budding scientist that she is, was always on the lookout for interesting technology, on her travels.  Nip into Craterside Supply, she might have a *spare* Weather Machine for you.  At a price.

* Start Game Added - The method offered previously.  The Weather Machine is instantly added to your PipBoy upon starting the game.

Whilst an accompanying Note is added to your PipBoy detailing the Weather Machines various functions, it might worth having a look through the more intelligible ReadMe, if it doesn't make any sense.  (The in-game Note uses more technical and rather dry language - simply for the purposes of game integration/immersion).  There's also a bit of information as to how things work.


DLC plugins:
----------------------

* For those that have all DLC a merged plugin can be used instead:
	Xepha's Dynamic Weather - Main + DLC Merged.esp

	
Night Eye Edition (NEE):
------------------------

* For those that have Operation Anchorage and have followed the instructions to install Dynamic Weather - Rain, a merged plugin can be used instead:
	Xepha's Dynamic Weather - Night Eye Edition Merged (NEE+OA+Rain).esp

	
Rain:
----------------------

* Stuck rain drops are now fixed! :D \o/


Sandstorm:
----------------------

* For those that have FOSE installed and want Armor Damage a merged plugin can be used instead:
	Dynamic Weather - Sandstorms + Armor Damage (FOSE)



Dynamic Weather 2.5, 18/05/2011

A fairly minor update that fixes a few bugs, amongst other things.

* Fixed a couple of scripting bugs that may have caused certain weather types to have less likelihood of appearing.  Updates apply to both the ESM and Anchorage plugin.

* Added another weather type to the Anchorage plugin, using the OA cloud texture (this time, of the ultra clear variety).

* Tweaked the custom light cloud texture.



Dynamic Weather 2.4, 01/05/2011

Quite a few script changes in this version so a clean install is mandatory if you will, please.

* New to Dynamic Weather, the Weather Machine integrates seemlessly into your Fallout 3 experience, enabling the player greater control over weather and climate - See the Weather Machine Readme for details! :D

* Night Eye Edition rebuilt from scratch.  Think I've nailed it this time. ;)

* Further climate script tweaks for greater weather diversity.

* Minor edits to address whiteout/overbright issues with sunrise on clear weather types.

* Internal edits to OA and OA(NEE) plugin for cleaner overrides.

* Various script tweaks/bug fixes.



Dynamic Weather 2.3, 22/01/2011

Almost immediately as I released 2.2, it seemed to me that certain weather types at night looked washed out, lacked contrast and were over colour-tinted (all blue or all green) - this had to go.  4 months of slow and steady progress later Dynamic Weather 2.3 is born...

* Nights received a major overhaul with a view to reduce the overall tint whilst at the same time allowing more natural colour to come through (when activating your Pipboy Light, for instance).  Visibility at near distances has been slightly increased (even on the darkest/overcast nights) whilst far distance visibility has been significantly reduced.

* Climate script tweaks favouring clearer weather types.  There is also a significant delay (at least one or two days) between Rain and Sandstorms - so they should never appear with a few hours of each other.

* Dynamic Weather standard now disables Rain related weather types (these will have appeared as fog/mist type weather in previous versions when used without the rain plugin).  The optional Dynamic Weather Rain plugin now correctly enables these when Enhanced Weather powered Rain is activated.

* Night Eye Edition (ie, less darker nights), makes a welcome return for some. :)  Night Eye Edition nights return a level of brightness that lies somewhere between Dynamic Weather standard and Vanilla Fallout 3.

* Somewhat of a joint effort by myself and ScoobyFO3@nexus, Dynamic Sneak Bonus replaces previous versions of my Night Time Sneak Boost plugin by applying varying amounts to your Sneak Skill, depending on the current weather/cloud cover and time of day.  Activating your Pipboy Light negates these bonuses.

* Minor update to the Green Tint Remover.  Fogged versions of weather types appearing in DC now have a green tint removing Image Space applied.



Dynamic Weather 2.21, 25/08/2010

* Xepha's Dynamic Weather.ESM:  Hotfix to eliminate the possibility that weather could change during the Tranquility Lane and Anchorage Simulations.

* Xepha's Dynamic Weather - Broken Steel.ESP:  Minor fix to script relating to displayed weather in Broken Steel locations.



Dynamic Weather 2.2, 24/08/2010

* As originally intended, and in a return to my Darker Nights light levels, nights are now significantly darker (you really do need those NVGoggles now! ;)

* Various weather types at night have also received further refinement.

* In the process of developing 2.0 I tried a few things that didn't quite work out.  Unfortunately, I neglected to remove all these things upon release.  Increased fog effects would have become apparent when leaving Megaton (fixed in 2.11) and entering the Wasteland having been in DC.  This should now be fixed. :)

* When starting a new game with the mod already installed, the weather greeting you when exiting Vault 101 for the first time will be the same as in Vanilla FO3 - retaining that never-seen-the-sun-before-its-so-bright-its-hurting-my-eyes moment.  Installing the mod mid-game, however, will generate a random weather type to be displayed (no rain/fog/sandstorms though).

* There is now a significant delay between rain and sandstorm (at least 12 hours) so they will no longer appear within a few hours of each other.

* The climate scripts have recieved something of an overhaul and are now more modular, making for easier reading/updates.



Dynamic Weather 2.11, 02/08/2010

* Maintenance Update: addresses an issue which may have erroneously caused fogged weather types to appear in the Wasteland (outside Megaton).



Dynamic Weather 2.1, 30/07/2010

* New, cleaner/clearer "Light Cloud" weather type added to both the ESM and Anchorage plugin.  Overwrite and replace whilst in an Interior Cell.

* DC Ruins weather types tweaked.

* New weather group added.  Fog now has it's own weather group that makes fog have a chance of only appearing at night and after rain (which is based loosley on the actual meterological conditions that cause fog to appear).



Dynamic Weather 2.0, 22/07/2010

* Complete overhaul of climate system.  The Dynamic Weather Progressive Climate is now entirely scripted for a more natural progression of weather types.

* Improvements/refinements across all weather types.

* Several entirely new de-greened, cleaner/clearer weather types.

* Weather types are now persistent across saves/game sessions.  Weather changes after Fast-Travelling are also disabled.

* Climate volatility (or, how often the weather changes) is now more dynamic - meaning the amount of time between weather changes will never be the same. Weather changes can occur anywhere between 1 and every 4 hours (by default).

* The DC Ruins now exhibit a "fogged-up" version of the weather types that are used in the Wasteland.  Essentially, this is a return to the fog/view distances that are used in vanilla FO3 and should ensure that nights in the DC Ruins are as dark as they should be.  These are also used in the Dynamic Weather DLC plugins.

* Rain weather types are now integrated into the Progressive Climate script, minus the Enhanced Weather Rain Sounds/Effects.  Follow the Dynamic Weather - Rain ReadMe Install instructions to activate the Rain effects.

* The player-following dust particle effects of the Sandstorm weather type have now been moved to their own separate esp.  This is primarily to give a choice for players with performance issues, but also paves the way for future additional effects to the Sandstorms (radiation/damage).  The scripted Sandstorm sequence and weather types remain integrated into the new Progressive Climate, however.

* Dynamic Weather DLC plugins now utilize all Dynamic Weather's weather types.

* A few weather types have gone away.  The Pitt specific weather type now exists as "Pollution".  The Point Lookout specific "foggy" weather type is no longer used.  The old style "Fog" weather type is also no longer used (due to poor transitions).



Dynamic Weather 1.3, 28/05/2010

* Dynamic Weather - Main, Dynamic Weather - Rain, Dynamic Weather - Night Eye Edition and Dynamic Weather - Climate OverRider have all been updated.  Details are outlined below.

* The Sandstorm weather type now includes a dust particle effect which follows the player around, simulating a sandstorm, as well being updated for a more "sandy" feel.

* Two new Rain based weather types have been added.  Heavy Rain Only is based on the Heavy Rain weather type but doesn't have any lightning/thunder sounds/effects.  Lightning Storm, built from the ground up, features the lightning sounds/effects but no Rain.

* Climate/Weather chance re-evaluated (Rain weather types in particular).  Weather Volatility adjusted (weather types now change every 3 hours).

* Climate Overrider updated to reflect changes/additions.

* Various nips and tucks to other weather types and some behind the scenes tidying up.



Dynamic Weather 1.2 - Rain, 04/03/2010

* Dynamic Weather - Rain adds two new weather types to the Dynamic Weather climate utilizing the Rain meshes and textures and Sound Effects of Skingrad24's Enhanced Weather Rain mod.

* Heavy Rain uses thunder and heavy rain sound effects and lightning effects against a heavily overcast and dark weather type.  Heavy Rain has a 50 percent chance of appearing.

* Light Rain uses light rain sound effects against a modified, unused weather type, found in the Fallout3.esm (similar to Wasteland East).  Light rain has a 60 percent chance of appearing.

* Full ReadMe in the Dynamic Weather - Rain.zip - READ IT!



Dynamic Weather 1.2, 18/02/2010

* Version 1.2 of Dynamic Weather has been considerably overhauled since Version 1.0.  To allow easier development of future updates the main file has been split into an ESM and an ESP (containing overrides to be loaded late in your load order).

* All optional DLC plugins have been updated due to the ESMification of the main files.  

* With 1.2 comes the release of The Pitt optional plugin.  The original Pitt weather types have been overhauled/discarded entirely as they (to me) leaved much to be desired.  Out of this comes an entirely new weather type which can also appear in the Wasteland.

* Also with 1.2 comes Point Lookout optional plugin.  The original Point Lookout weather types have been overhauled/discarded entirely.  The original Point Lookout fog had a very caricature quality about it which is in stark contrast to the Wasteland weather types and would have made for some very ugly transitions.

* Night Darkness has been given an overhaul so that now, how dark night gets depends on cloud cover - clear skies give the brightest nights, whilst overcast skies give the darkest nights.

* Night Eye Edition created to accommodate players that don't like to use full-on darker nights mods.

* Experimental Green Tint Remover for those people that are really sensitive to green. ;)  Consider this an Alpha release.



Dynamic Weather 1.1, (not released)

* Main file split and ESMified.  

* Optional DLC plugins updated.  

* The Pitt plugin created.



Dynamic Weather 1.0, 12/31/2009

* Initial release



======================
DLC plugins:
======================

* Operation Anchorage:  Adds a new weather type to the Wasteland using the clouds seen in the simulator.  Bailey's Crossroads has been given the Dynamic Weather treatment - the simulator remains untouched, however.

* The Pitt:  Applies Dynamic Weather to The Pitt locations.  Weather types appearing in the Pitt have been Image Space adjusted in keeping with the polluted atmosphere.

* Broken Steel:  Applies Dynamic Weather to Broken Steel locations.

* Point Lookout:  Applies Dynamic Weather to Point Lookout locations.  Weather types appearing in Point Lookout have been Image Space adjusted in keeping with the swamp atmosphere.



======================
Miscellaneous Extras:
======================

* Dynamic Weather - Weather Machine: Integrates seemlessly into your Fallout 3 experience, enabling the player greater control over weather and climate - see the Weather Machine Readme for details.

* Dynamic Weather - Rain:  An optional plugin that adds weather effects to the Dynamic Weather climate utilizing the Rain meshes and textures and Sound Effects of Skingrad24's Enhanced Weather Rain mod.

* Dynamic Weather - Sandstorm:  An optional plugin that adds sand/dust particle effects to the Sandstorm weather type.

* Dynamic Weather - Sandstorms + Armor Damage (FOSE):  Requiring FOSE, this optional plugin adds armor/health damaging effects when a Sandstorm is in progress.  A -2 Perception penalty is also applied unless the player is wearing protective eye-wear including (but not limited to) Biker Goggles, Power Armor Helmets and Security Guard Helmets. This merged version now includes the previously separate Dynamic Weather - Sandstorms.

* Dynamic Weather - Dynamic Sneak Bonus:  Replaces previous versions of my Night Time Sneak Boost plugin by applying varying amounts to your Sneak Skill depending on the current weather/cloud cover and time of day.

* Green Tint Remover:  An optional plugin for those people that are really sensitive to green. ;)

* Dynamic Weather - Night Eye Edition:  An optional plugin that return a level of brightness to nights that lies somewhere between Dynamic Weather standard and Vanilla Fallout 3.



==============
Other Notes:
==============

I would highly recommend using a smaller timescale when using Dynamic Weather, because as well as making the days last longer, it also increases the length of weather transitions/changes.  To change timescale, open the console and type:

set timescale to x

Where x is a number - default is 30.  I would recommend a setting of around 10.

I would also highly recommend the use of Night Vision Goggles, as nights will now be *very* dark.  I've been using Antistar's Nightvision Goggles - Powered for a long time now - http://www.fallout3nexus.com/downloads/file.php?id=2725  Personally, I think the rather "chunky" model fits in quite nicely with whole Fallout 3 50's vibe.  Though if you want a more modern look, Alexscorpions Animated NV Goggles are highly recommended - http://www.fallout3nexus.com/downloads/file.php?id=12841

(Don't forget, eating the eyes of Marts Mutant Mod's Night Ghouls also provides enhanced night vision!)



============================
Compatibility:
============================

Will *not* work with other weather mods.

Dynamic Weather - Rain has been designed to work with the parts of Enhanced Weather - Rain and Snow as outlined in the Dynamic Weather - Rain Readme - Read it!



============================
Bugs/Issues:
============================

- Gamebro deficiency: If the weather is in transition (i.e. changing) when moving from exterior to interior cells, the clouds will fail to appear when you go outside again.  A workaround script is in place to handle this and although the effect can be a little jarring, it's a lot less immersion breaking than staring at the sky wondering "Where have all the clouds gone?" (clouds suddenly blink into existence) "Oh.. There they are...".



==============
Contact:
==============

Xepha @ http://www.bethsoft.com/bgsforums/
Xepha537 @ http://www.fallout3nexus.com



==============
Credits:
==============

Thanks to TheOutbreak/Yossarian22, whose work forms a foundation for this mod.
Thanks to the Fallout 3 modding community for its wealth of information
Thanks to Bethesda for creating Fallout 3.
Thanks to www.fallout3nexus.com for the one-stop-shop resource for authors and players.

Special thanks and Kudos go out to:

Skingrad24 for his Enhanced Weather Rain mod and for being kind enough in providing his Modders Readme.txt, the information of which made Dynamic Weather - Rain possible.

ScoobyFO3, Jeoshua and anyone who has been kind enough to leavea a comment, for their invaluable suggestions, ideas, comments and general support.  Thanks guys! :)



==============
Tools Used:
==============

The G.E.C.K. - http://geck.bethsoft.com/index.php/Main_Page
FO3Edit - http://www.fallout3nexus.com/downloads/file.php?id=637
GIMP - http://www.gimp.org
7-Zip - http://www.7-zip.org
Fallout 3 ReadMe Generator: http://www.fallout3nexus.com/downloads/file.php?id=8269



================
Licensing/Legal:
================

Not to be: re-distributed; uploaded; repackaged; without prior, express, written permission, no exception.