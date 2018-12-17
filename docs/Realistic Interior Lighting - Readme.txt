Realistic Interior Lighting v.8
by Scarecrow


***Beta/WIP***

I recommend a NV or brighter pip boy light mod to go with this, darker nights goes together as well.


DESCRIPTION


I always thought it was rather silly a room with no windows/covered windows would be bright as day with just a single dirty light bulb with likely dirty electricity (isn't that the name? I can't remember...), so here is my solution to that.


INSTALLATION

****CRITICAL****
Make sure you've got your monitor brightness levels set correctly, AS WELL AS the in-game.  Someone correct me if I am wrong but the quick rundown is, (for LCDs) you want to max out your contrast, then adjust your brightness according to a chromatic scale (http://w4zt.com/screen/ has a bunch, "A to Z" one is the best).  Then once you've got that set up you want to adjust your in game brightness to the point where the second black square is one point above the same level of blackness as the actual black square.  For me that just means all the way down, YMMV.

Thanks Snabbik:
---------------------------------------------------------------------------
I've always used:

http://www.lagom.nl/lcd-test/index.php

http://www.normankor...or_test_pattern

http://www.photoscie...co.uk/Gamma.htm

I think the first link is the one I use most often for monitor calibration.
---------------------------------------------------------------------------

So like I said, your mileage may vary and don't necessarily be ironclad on 100 contrast, it just happens to be mine I guess (I check out with the color tests).
****CRITICAL**** 

Load the two DLC files if you have the appropriate DLC on top of the base file.

Load after everything else, before your merged patch. If you don't have one you should probably check out the guide for FO3Edit and learn how to use it, it's incredibly easy to learn and get ahold of, allowing you to get full compatability with 95% of the mods you use.

I've got two compatability patches for the DLC, thought I haven't really looked at the DLC beyond seeing which ones have lighting templates and changing just tho's, I haven't touched any cells yet and wont for a while.


COMPATABILITY


Should only conflict with other lighting mods, and any mod that edits the... I don't know what it's called, I geuss the header information of a cell, so that's what I'm calling it, if someone knows the correct name of what I'm talking about then please correct me. I'm not aware of to many that do, all mods that add stuff to cells like spawn points (MMM), items, npc's won't conflict unless they directly modify the header (all that is in the header is the lighting information, cell name, and ownership values). The only two mod's that I've seen that conflict are UOP and OWNED!, both conflicts are minor and limited to one or two cells, and IIRC I included the UOP changes in the .esp, and really, any potential conflicts are incredibly easy to fix if you know a little about FO3Edit/Merged Patches. Should also work with any mods that add a (vanilla) lighting template to new cells.


KNOWN ISSUES


At the moment I've just sort of gone over the lighting in every cell (via way of the Lighting Templates for 80% of them, for the others that didn't have a Lighting Template, I attached one to it, hence the potential conflicts in some cell headers) and with a broadsword, made everything darker. Bethesda generally did a really good job in FO3 of placing light where it should be so all I need to do is mess with the ambient light; however sometimes you'll get places where there's no light but a visibly working lamp or something (the statesmen hotel). I generally wont add a light source as it would take WAY to much time and patience to add one to every missing spot in the game, but for "major" area's (like quest hubs) that look really weird without one I may end up adding a few (Citadel Lab).

The rest of the changes are going to come as I play the game and find stuff that looks odd. Originally I was planning on customising each "friendly" cell (IE Megaton/Tenpenny/various quest houses with friendly NPC's) and making them much brighter while trying to keep the mood, but Bethesda did a much better job in FO3 then Oblivion with their light placement etc. and I find even when it's basically dark as hell theres plenty of light around to see mostly clearly, and I've grown attached to the way it looks. Of course I may still end up changing it, hence the beta/wip tag. I'm also going to see if I can somehow change the template with the night and day cycle (for brighter rooms during the day for certain templates) in a script, thought that will probably not be in the immediate future.

And the main reason I'm releasing this as is, is so that people can get me some data! So if you see something odd looking or have suggestions for specific cells be sure and leave a comment of where I can look.


CHANGELOG
Beta .8
-Increased Metro Template ambient lighting slightly
-Increased Underworld Template ambient lighting
-Added Jefferson Memorial Template
-Increased Office Template ambient lighting slightly
-Increased Shack Template ambient lighting slightly
-Added Dunwich ImageSpace and Template
-Increased Shack Template ambient lighting slightly
-Added Point Lookout .esp

Beta .72
-Adjusted the various metro area's to have a consistent ImageSpace - essentially means its much darker
-Adjusted the fog levels in the metro area's to reduce silhouttes in the distance

Beta .71
-Adjusted most templates again, generally it's a bit darker

Beta .7
-Adjusted all Templates, generally it's a bit brighter
-Adjusted Air Control Tower - DLC BS
-Adjusted Citadel Armory - DLC BS
-Added Outcast ownership to Fort Independance

Beta .61
-Adjusted Enclave Template
-Adjusted Paradise Falls
-Adjusted the Citadel
-Added some lights to the Citadel Lab
-Fixed a few DLC BS cells

Beta .6
-Adjusted Underworld Template
-Adjusted Vault 112
-Adjusted Vault 101
-Adjusted Tenpenny Tower
-Fixed quite a few cells that were not inheriting Ambient Color from their lighting templates

Beta .5
-Initial release