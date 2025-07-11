
************** ALKALINE: an enhanced Base mod by Greenwood and bmFbr. **************

=============> Major coding assistance by Khreathor and Shamblernaut. <=============

                  Alkaline is based on the Rubicon 2 mod by metlslime.
                              Additional mod contributors:
                         Kebby — modeling, animation, texturing
        ptoing — 2D art (menus, HUD, bulletholes, plasma blast, misc graphics)
 Fairweather — modeling, animation (ArachnoFloyd, Nailgun/Super Nailgun/Axe animation)
    Markie — modeling, texturing (laser cannon enhancement, Bambler, mdl ammo boxes)
                            aDaya — modeling (plasma rifle)
                            Bloodshot — modeling (chainsaw)
----------------------------------------------------------------------------------------

Mapping Quickstart
------------------

- Create a folder with the name of your release inside your Quake directory. Remember to
  keep all characters lowercase and use no spaces!
- Unzip the contents of the pack into the newly created folder.
- Load up alkaline.fgd into your map editor, select the devkit folder as your mod,
  and start mapping right away :)

The docs.html file has a complete documentation on Alkaline's mapping features. Make
sure to check the in-editor entity and field descriptions as well for specific usage
details. 


Packing your Release
--------------------

The pak0.pak file contains all the minimum necessary assets and files for Alkaline to
work. It's a simple drop-in redistributable for release, so you can just pack it up
with your map and you're ready to go.


Additional Assets
-----------------

The devkit includes several additional assets for your convenience:
- additional model props, inside the /progs/ folder, for use with misc_model or
  misc_modeltrain;
- additional looping ambient sounds, inside /sound/ambient/, for use with the
  ambient_general entity.

These files aren't necessary for the mod to work, so pick only the ones you'll use in
your map(s) when packing your release. 

Also included are 2 test maps:
- enemytest.bsp map, containing all the new monsters available in Alkaline;
- alk12_triggers.bsp, containing some advanced trigger examples (includes source map).


QuakeC Source
-------------

The QuakeC source code is available at https:///github.com/fabiolimamp/alkaline. Feel
free to fork and modify/reuse it as you will. Just make sure to give the proper credits. 

Alkaline code was compiled using FTE QuakeC Compiler, with the latest version available
at https://www.fteqcc.org. Old versions may give unexpected compile errors.


Useful console commands
-----------------------

During gameplay, one can access the console via tilde key (~) and enter the following:

RESURRECT      — Like Doom, type "resurrect" to bring Ranger back from the dead!

GIVEALL        — Gives all weapons, ammo and keys.
GIVEWEAPONS    — Gives all weapons and ammo (no keys).
QUAD           — Gives a Quad Damage for 30s.
BELT           — Gives the Invisibility Belt for 30s.
SUIT           — Gives a Biosuit for 30s.
PENTAGRAM      — Gives a Pentagram for 30s.
BOOTS          — Gives/upgrades the Jump Boots.
BOOTSTIMED     — Gives the Super Jump Boots for 30s.
BOOTSREMOVE    — Removes all boots/upgrades from the player.

FOOTSTEPS      — Toggles footstep sounds.
BULLETHOLES    — Toggles bullet/nail holes.
AUTOSAVES      — Toggles autosaves.
TRACERS        — Toggles the bullet tracers for hitscan weapons.
PLAYERTRACERS  — Toggles bullet tracers for the player's shotguns. Disabled by default.

Other developer-oriented commands are listed in the docs.

----------------------------------------------------------------------------------------

==========> ALKALINE'S MAIN WEBSITE: https://alkalinequake.wordpress.com/  <============
=================> MODDB PAGE: https://www.moddb.com/mods/alkaline <====================

* Copyrights / Permissions *

Rubicon 2 code copyright 2011 John Fitzgibbons.
Rotating entity code copyright 1997 Hipnotic Interactive.
Original Quake code copyright 1996 id Software.

You are allowed to make Quake mods with this. No commercial use is allowed.

This archive may not be distributed commercially, may not be distributed in modified or 
incomplete form, and may not be distributed in any way that misrepresents its authorship. 
Aside from those restrictions, you may distribute it freely.
