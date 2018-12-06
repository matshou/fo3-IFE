###################################################
# Fellout - The Fallout 3 Weather Overhaul 1.21   #
###################################################
# Author: Hattix                                  #
# Relies on: Nothing                              #
# Installation: Nothing special needed            #
# Replaces: Atmospheric Sun Glare, older Fellout  #
# Includes Atmospheric Sun Glare by LadyDeadlock  #
# Used with permission.                           #
# Contributions by: Drag0ntamer                   #
###################################################


###################################################
#                 Rationalé                       #
###################################################

200  years since  the  bombs fell  and somehow everything  is tinted green?  Things  in Fallout and
Fallout2 weren't green.

Fellout changes all that, giving a harsh world more reminiscent of the Sahara Desert or the Mad Max/
Road Warrior movies though due to popular demand (and if Enhanced Weather is installed)  some areas
will have rain.

Fellout also neutralises indoor lighting,  removes green fogging and also water has been changed in
most places. This is a l ittle experimental for the time being,  but still quite a lot  better than
glowy green clouds of fog.

Some purists may love it, some may hate it, but most people should get a kick out of the overhauled
weather systems.  If Fellout feels  like a mod, then it's  failed.  If  it feels  like how the game
should have been, it's succeeded.  Read on for installation instructions and more information about
the mod.

- Hattix

###################################################
#             What Fellout Does                   #
###################################################

The main order of business is threefold.

Firstly, Fellout neutralises global lighting. Areas which specify their own custom lighting aren't
affected, areas which use global lights will find the lighting to be neutral instead of tinted
green. Fellout also operates on water, both placeable static (wasteland pools) and large bodies,
making them muddy instead of green.

Second up is the ImageSpaceModifiers, a post-processing applied to the screen. Fallout3 uses these
for the get-hit blur, the explosion shake, chems wearing off and for bloom effects. It also uses
them to tint everything some shade of green or brown. Fellout removes the tinting entirely, it's
like looking through a piece of dirty glass and then having the glass taken away. This will
improve performance a little.

Third, of course, is the weather. Fellout replaces every weather mode and most of the climates
(climates are collections of weather modes attached to a certain area) with realistic models. The
stock game used the same four weathers almost all the time, Fellout has far more than that, adding
a little diversity to the sky. Fellout makes nights rather intense: You can see quite well nearby,
but at a distance you're effectively blind in most areas. Just like real life! Hopefully this
strikes a good balance between realistic and unplayable and unrealistic but playable.

###################################################
#                Load Order                       #
###################################################

Fellout-full.esp needs to go quite low in the load order. It needs to go below mods which add items
to interior cells, such as Weapon Mod Kits and FOOK. This is changed in version 1.1.17 because
Fellout now includes changes to interior fogging. In future, Fellout may be distributed as two ESPs
for this reason, one ESP with the weather, another with the interiors.

GECK, by default, saves the entire cell if a minor edit is made to it, so you'd lose the fogging
Fellout has changed.

With this in mind, 1.1.17 and above has been cleaned by FO3Edit.

Fellout-pipboylight.esp needs to go pretty high in the load order, above large overhaul mods like
FOOK, FWE and MMM.

With Fellout being so popular, mods which conflict with it generally say so in their own documentation.
Recent versions of FOMM are also Fellout-aware and can auto-sort it into a good place in your load-
order. FOMM does place Fellout 1.1 too high, but there'll be no problems other than a few minor
cosmetic conflicts.


###################################################
#          FOOK 2 USERS READ THIS WELL            #
###################################################

Fellout 1.1.17 is included in FOOK2 1.1 beta. Fellout 1.21 is included in FOOK2 1.1.

Load future versions of Fellout BELOW FOOK2-Main.esp


###################################################
#               The INI File                      #
###################################################

Optional but recommended. From your "My Documents" ("Documents" in Vista/Win7), enter "My Games"
and then "Fallout3". Here you will see "FalloutPrefs.ini". Open this and find the line:

fGamma=1.0000

You must change this to 1.xxxx, where xxxx is anything you so choose. I recommend fGamma=1.1867
only because it's a setting the game makes itself and it's what Fellout is tested with.

Why have you done this, you may be asking? It solves a nasty video driver bug which can have
things far too dark in Fallout 3. If you, in game, set the brightness down a notch but the game
actually gets brighter, then you're affected by this bug and this fix will solve it.


###################################################
#                  Installation                   #
###################################################

After the InvalidateOlderFiles ini  tweak (which may not be necessary anyway) you  merely  copy the
mod and the textures into the  data folder. Activate the  mod as you would any other mod. If you've
installed a mod before, you're fine. Fellout needs no special treatment. ArchiveInvalidation is not
necessary.

###################################################
#                  Known Issues                   #
###################################################

1. Sun glare reverts to default on entering and leaving an indoor space.  This is an issue with the
game and Fellout can't do anything about it. - Partly corrected in Fellout 1.1.17. See issue 5.

2. The skybox mesh is made up of strips.  When looking up,  this can be seen as circles or bands of
different colour.  Quarl (I think) made a fix for  it which simply flattened  out the colour of the
entire sky.  Fellout's not  compatible with that.  The unmodded game had  the same issue and so did
Oblivion.  If anyone wants to make  a mesh with about  triple the number of strips  (if that's even
possible) which doesn't flatten the whole thing, I'll probably use it.

3. If you load the DLC add-ons,  but your DLCs are  being managed by  Games for Windows Live  (FOMM
can't see the DLCs)  then you will get crashes.  The solution is to have  FOMM manage the DLCs, not
GfWL. If this is not possible, do not use the Fellout DLC add-ons and especially not BrokenSteel.

4. At least one internal  test version of 1.1.17  exhibited problems  with HDR becoming "stuck" and
making the screen much too bright. This is temporarily solved by issuing the console command "cal",
"clear adapted lights"  which  resets HDR.  This also  seems to have  the side-effect of  restoring
broken sun glare.

5. Water around Project Purity can look odd with squares of green and grey. This is because you're
using Broken Steel but are not properly loading Fellout's Broken Steel add-on.

###################################################
#                    Feedback                     #
###################################################

If you're going to  post about Fellout  with something  you'd like  to see done better, then please
follow these guidelines:
Where were you in the game? (E.g. Near Old Olney in the wasteland)
What time of day was it? (E.g. 5am)
What was the weather like? (E.g. Overcast)
What was wrong? (E.g. Fog colour didn't match horizon)
ALL feedback is welcome,  though not all emails may be answered.  Your feedback got Fellout from
Beta 8 to the current version.

###################################################
#               ArchiveInvalidation               #
###################################################

"ArchiveInvalidation.txt" is absolutely not supported. If you use this and have problems, you're
on your own. See here for more info:
http://devnull.devakm.googlepages.com/archiveinvalidation

It cannot be reiterated how ugly a hack the ArchiveInvalidation.txt is. Either use Quazzy's
ArchiveInvalidationInvalidated (AII) or Timeslip's Fallout Mod Manager (FOMM)'s "Toggle Invalidation"
function. Both do the same thing.

###################################################
#                    Contact                      #
###################################################

Fellout was made by Hattix and any queries can be sent to fellout [at] hattix.co.uk. I will provide
full support for any issue with Fellout.


###################################################
#	          Technical Junk                  #
###################################################

Read this to also know what may conflict with Fellout.  Fellout adjusts all weather conditions in a
self-consistent manner.  Unless another weather mod is  specifically stated to be a Fellout add-on,
it cannot  be  compatible  with Fellout.  Fellout changes all  four  cloud layers  (including their
textures), ambient, sun, sunlight, and all other weather attributes for all four times of day.  It
changes all weather attributes. It controls the climates for all areas, basically, Fellout changes
the entire weather system of the game.

Fellout, as of 1.1.17, also changes all the water to remove the green and to push the fogging back.
The water looked like it was full of algae, which is a bit odd for irradiated water!

Some of Fellout's most effective changes are in ImageSpaceModifiers. Mods which change these also
will conflict with Fellout. In general, Fellout doesn't touch ISMs not associated with outdoor
lighting conditions so, for example, a mod which changes the Tranquility Lane ISMs will not
conflict with Fellout.

So weathers, climates, IMADs, fogging and lighting all fall under Fellout's banner. Please clean
your mods so you're not overriding Fellout with the game defaults.

###################################################
#                   Modders                       #
###################################################

To avoid annoyances,  if you wish your PipBoy light mod to work with Fellout, keep it the same or a
similar colour, on the red/yellow/orange side of white, never on the blue or green side.

Fellout mostly changes things, it actually "adds" very little. This is great news for most mods,
since a conflict will just make things look funny, it won't actually cause any instability.

In general, follow these rules if you wish to work with Fellout:
- Sky Lower and Horizon are very important, the player will see them most.  For colouring sunsets
and sunrises, only use Horizon. The sun's glare is part of the Sun colour, use that.
- Fog and Horizon are best linked. That way distant scenery tends to fade into the haze naturally.
Have fog just a little darker. If your horizon is (R,G,B) 140, 144, 212 then have fog something like 135,
140, 205.
- On overcast days, link Fog with the Cloud Layers.
- Keep cloud layers the same colour or you'll find fogging problems.
- Cloud that has gaps in it should be very light. While grey cloud before a blue sky is realistic,
the fogging won't look right at all since the skybox isn't fogged. Push the fog really far back.
- Don't use ambient for tinting sunsets and sunrises (like Bethesda did!),  use Sunlight for that,
you get much better shadow filling.
- Fellout has neutralised the ImageSpace Modifiers. Don't use them for anything other than special
effects. Tinting is right out, it looks silly and reduces colour gamut.

###################################################
#     REDISTRIBUTION AND LEGAL - READ THIS        #
###################################################

Reuse Fellout's resources as you see fit, design a mod to work with Fellout as you see fit.
Do not simply redistribute or bundle Fellout without seeking permission. There were too many
outdated versions of Fellout bundled with other mods, people were saying that "Fellout's no good
because..." then giving a reason which was fixed months ago. Do not reuse the "Fellout" name in
in your mod's name except as "MyMod For Fellout".

Fellout may not be used commercially by any party other than Bethesda Softworks, Zenimax Media or
their authorised partners.

Fellout's ESP resources are copyrighted by Bethesda Softworks (thanks, GECK license restrictions).

SPECIAL RESTRICTIONS APPLY TO FELLOUT'S TEXTURE RESOURCES! Several of the texture resources are
copyrighted by people who aren't me and I cannot grant permission for any redistribution or
modification as it isn't my permission to grant. I have the permission, I can't re-license it
other than as an intact Fellout distribution.

Fellout 1.0.15 and above may not be distributed in the Fileplanet Mods Pack as this is commercial
use. FP included 1.0.14 without asking permission, without checking for the latest version (which
was 1.0.16 at the time) or checking that it was compatible with the other mods. If you got this
from the Fileplanet Mods Pack, you have an out of date version which may cause problems. Download
the latest version here: http://fallout3nexus.com/downloads/file.php?id=2672 Fileplanet may still
use 1.0.14 or below as they see fit.

The above provision was not made lightly. On reviewing the list of mods included and the spirit
they were included with, Fileplanet (I believe) were genuinely trying to do a good thing, but in
doing so they'd blindly just added mods seemingly for the hell of it, including a bunch of 
redundant mods (Fellout and ASG, for example, when Fellout includes ASG) and mods known to cause
severe problems when used together.

The redistribution rules changed at the 1.0.14 to 1.0.15 boundary. The older rules still apply to
Fellout 1.0.14 and below, 1.0.15 is different and future versions will be the same as 1.0.15.





###################
# VERSION HISTORY #
###################

Release 1.21R2
FIX: Another too bright urban weather.
FIX: Returned twilight timings to default, since it didn't work well with Arwen's Realism Tweaks.

Release 1.21
Thanks to the Ars Technica GESC forum for testing.
FIX: Urban imagespaces looked terrible. The whole thing was just too bright and without contrast - 
Sunlight Dimmer was set to 3.0 for some crazy reason. Urban areas are now much darker.
FIX: Some lighting levels, especially in the north wasteland.
FIX: Northern wasteland somehow got slightly green daytime clouds.
TWEAK: IMADs tweaked up to accept FOOK2's nightvision (also made by me).
TWEAK: Since the wasteland weather is usually clear, this weather mode has extended sunsets and
sunrises. Sunrise begins a hour earlier and ends a hour earlier. Sunset is delayed by two hours.
This means you get more daytime and less night.

Release 1.20
Thanks to Nexus user gregor_y, who helped with testing. A lot of this stuff got in between 1.0.16R2
and 1.1.17 when I changed the lighting system. I'll have it all ironed out by perhaps October 2015
or so.

FIX: Brown paper bag size lighting screwups in the DC Mall and other areas.
FIX: Emission HDR problems at WastelandEast.
FIXES: Lots of them as I ran into them. A few mismatched clouds here and there, a slightly off fog,
that sort of thing.
FIX: Northern Wasteland area was looking idiotic in the new lighting, especially at night. Didn't
I fix this in 1.1.17???
TWEAK: Potomac upstream water. I really, really hate the reflection shader in FO3. It's impossible
to make it look anything realistic without disabling the noise generator, and then it looks like
a sheet of glass. Argh!
TO DO: There's still something going on with climates that isn't shown in GECK. Bethesda, what did
you break in FO3 that worked in Oblivion?
TO NEVER DO AGAIN: 1.19. Apologies to the 350 or so people who downloaded it in the few hours it was
on the Nexus.

Release 1.19
FIX: Too bright and too dark nights.
FIX: Fixes for dumb looking water.
NEW: Almost all waters now much murkier.
FIX: FOOK2 1.1 integrated version of Fellout fixed up.
Changed version numbering system from major.minor.build to just major.build.

Release 1.1.18
Quick spot-fix for some dodgy waters.
Minor tweaks.

Release 1.1.17
TO-DO: Something odd is going on with climates.
TO-DO: MORE CLOUD TEXTURES!
TO-DO: Split into two ESPs
OLD: Bye bye SOTD! There is no SOTD version for Fellout 1.1.17, mainly because the nights don't
get so dark anymore. SOTD may be returning, so watch this space.
BUGFIX: WastelandNorth looked terrible at night. (BUGFIX: Beta3 - WastelandNorth looked crap at
sunrise and sunset too!)
BUGFIX: WastelandDecay looked like ass. I think this came in something like 1.0.13 or so, sorry!
NEW: Wasteland weather is now quite volatile with two distinct clear modes and a cloudy mode.
CHANGE: "WastelandClear" sky-lower made a little darker, HDR was clamping it to white. Thanks to
fys for some pretty dedicated testing. THAT MEANS THE WHITE SKIES "BUG" IS GONE!
NEW: Sun glare toned down a lot. Someone at Bethesda had it set pretty incredibly high.
NEW: All places now have at least some variability to their weather.
WOOHOO: Minor version changed to 1! Fellout 1.1 is here, guys!
NEW: Water, both placeable and static, is now not glowy green. But it does have the radioactive
effect still attached (this wasn't changed) because other mods play with that.
NEW: Water looks much less like smoke. You can actually see through it, especially shallow pools.
Of course you can't see very well through it, mind.
BUGFIX: Sunlight in mornings and evenings was going a bit green.
NEW: All-new weather modes added to the wasteland. New textures, new everything.
NEW: Point Lookout add-on.
NEW: New cloud texture by Drag0ntamer. Thanks!
BUGFIX: Some skies were too bright at night.
BUGFIX: SOTD in 1.0.16 often wasn't. This was so bad that someone *else* actually fixed it!
http://www.fallout3nexus.com/downloads/file.php?id=9853
SOTD is re-generated on every release, so any problems with it don't travel from one release
to the next.

Hotfix 1.0.16 Revision 2

Megaton weather sunrise and sunset fog corrected.
Full version was TOO dark, making even night vision inadequate. It's been made three times lighter
which is still too dark to play without NV.
Wasteland weathers weren't dark enough. Very slight fixes here.


Release 1.0.16
Fellout fixes the HDR, which was removed from 1.0.15. With HDR enabled, the game tints
everything some variety of brown or green. This is unnecessary with Fellout's lighting system.
Without HDR enabled, Fellout doesn't need this fix and it will be ignored. Previous versions
just neutralised the tinting, but 1.0.16 removes it entirely.
Fellout has overhauled its entire ImageSpace system.
EWR compatibility finalised, rainy weathers made more common and much more atmospheric. It will
never rain in the wasteland (yet), but the DC ruins has a fairly good chance of it. It worked as
intended in 1.0.15, which was pretty amazing since very little else of 1.0.15 worked properly.
More interior lighting fixes and de-greens.
DC Ruins weather modes revisited.
NEW: HDR optimisations can cause a slight framerate boost on some systems.
NEW: Fellout no longer includes a modified PipBoy light in the main ESP. The PipBoy light has
been moved to an additional ESP. This is for compatibility with FOOK.
BUGFIX: Fellout Full is now as dark at night as it's meant to be. 1.0.15 didn't actually have a
"full" version, both ESPs were SOTD. Oops.
BUGFIX: 1.0.15 removed the HDR modifications which brought some degree of tinting back. Since
1.0.14 and below didn't actually do the HDR properly (nighttime lighting was horrible), 16 has
the proper scheme going on.

Release 1.0.15
Fellout no longer requires HDR.
Fellout is now simply called "Fellout".
Altered the climates for some variety. This is to prepare for a future version which will add
all-new cloud layers and weather modes.
NEW: If you have Enhanced Weather - Rain installed, Fellout will add the chance of rain to
certain areas. *UNTESTED, PROBABLY WON'T WORK AT ALL, CRASH THE GAME OR MAKE DEMONS SHOOT FROM
YOUR NOSTRILS*
NEW: Wasteland weather has some variety now.
BUGFIX: Green wasteland horizon cloud is now not green.
BUGFIX: Leaving one worldspace and entering another has changed in 1.5. Unless the weather is
specifically reset, the weather will remain as it was on the old worldspace. This was causing
problems when leaving Megaton, as it is a different worldspace to the wasteland. To solve it,
Megaton now uses very similar weather to the wasteland.
BUG: Entering an indoor area and leaving it removes the ASG sunglare. It's a game problem and
can't be corrected here. ASG alone suffers the same problem.
NEW: Changed distribution terms.

 
Release 1.0.14
Tweaks to DC Mall nights
Wasteland North sunrises and sunsets were screwy
Yet more fog fixing
No longer considered "Beta". Some people think "beta" means the mod's going to cause problems,
which Fellout has never even been capable of. Since by this stage most of the issues with
Fellout's lighting should be resolved, Fellout is out of beta.
Sun glare greatly improved.
Most nights are lighter, but still quite dark.
SOTD is back!
Urban climate now has a low chance of being clear.
ISMs now handle nighttime effects to make it look more like night and less like "dark day".
FWO is now only supported with HDR. It will work without it, but not as well.
Tweaked overcast twilight to be much less red/yellow

Beta 13
Indoor lighting has been de-greened.
Moon is a bit brighter - No ESP only version for Beta 13.
Sun glare has been removed from overcast weathers.
No SOTD version planned for Beta 13. Use Beta 12 if nights are a problem.
More fog fixes.

Beta 12
People seem divided on whether dark nights are good. So, for those wanting unrealistic sojourns in
a post  apocalyptic hell  hole in the middle of the night,  Fellout Scared of the Dark edition is
part of Beta 12. This is Fellout-Lite, quite literally, and includes much brighter nights.
Sneaking will be more difficult than in Fellout-Full as ambient light is a factor.
Changes:
Ambient  lighting  is now  almost neutral  at all times. Sunsets,  sunrises are  handled much more
realistically by the sunlight itself.
More fogging problems. When will they go away?
GECK doesn't handle HDR properly,  so previewing Fellout's weather is...difficult.  Sometimes it's
too dark or light in daytime in the actual game.
Beta 9's days have been restored. Beta 10 got skies too dark.
Overcast weathers are darker, clear weathers are brighter.
Sunset conditions from some Urban overcast weathers are near completely gone. It'll just gradually
get dark.
YES THE NIGHTS ARE A BIT BLUE.  Deal with it.  You don't have colour vision at night.   Ambient is
blue but moonlight is not.

Beta 11
More fogging issues and another crazy sunset.

Beta 10
Some fogging issues where the fog didn't match the horizon were corrected. Seems there may be more
of those problems lurking around.

Beta 9
Feedback from FO3Nexus has led to nights becoming brighter and less blue, moonlight becoming *much*
stronger and two very red sunsets being removed.

Beta 8
No serious problems found in Beta 7  (famous last words) so  it's time to go public with Fellout.
Last-minute change: PipBoy light is FAR too ranged for interior cells, so it was dropped to 75.
First release to FO3Nexus.

Beta 7
Initial pass over GECK done, testing beta.  Megaton night needs more ambient, some moonlight is too
blue, etc. HDR vs non-HDR makes a massive difference. Probably not going to support non-HDR.

Beta 6
Snapshot preview for Ars GESC.

Beta 5
PipBoy light  adapted  to work with Fellout and be useful.  Range increased to 150  (from 15). First
complete weather mode is done. Looks pretty impressive.
Changed some interior lighting, it doesn't make sense for even interiors to be puke-green.

Beta 4
More weather modes modded.  This is a losing battle, I'm going to have to overhaul the entire thing
to make it look anything like consistent. Moon texture fixed. Realisation: Any weather mod is going
to conflict with this, so I ought to abandon it or make it a complete overhaul.

Beta 3
Some slightly modified textures.

Beta 2
Initial release on  the GESC forum.  Basic,  changes some sky and cloud colours,  but green is still
everywhere. It does more than Clear Skies, but not much more.

Alpha (Late December 2008)
Clear Skies doesn't change much weather but it does show me that it can be done. I've been meaning
to get into TES modding for a while, let's see how this goes.



