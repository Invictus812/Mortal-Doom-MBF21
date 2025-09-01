# Mortal-Doom-MBF21

**BACKSTORY:**  
Several months back I released my first-ever Doom gameplay mod, "Mortal Doom" - a fork of BDLite which was... amateurish to say the least.  Once I learned of the world outside of GZDoom and how DeHackEd and CompLvls work, my understanding of the game's systems grew dramatically.  I made The Dead Simple Sprite Mod with the goal of smoothing the game out without using anything beyond the default state table.  I'd hoped to eventually make something even grander, smoother, and more detailed - in the vein of my original project idea but more refined.  This is the first step on the way there: Dead Simple upgraded and ported to MBF21, now reusing the Mortal Doom name because we're pretty far removed from anything simple at this point.  Eventually, once ID24 becomes functional in DoomTools, this _will_ be ported to ID24HACKED with all the excesses I'd intended from the start, but I'm pretty happy with this for now.  The goal here was to make the game smoother and much... _much_ harder, but just like with Dead Simple: It's still Doom.

To start, since we have access to the extended state table now, of course all the extra animated objects like key cards and skulls, decorations, health items, and extra effects from the DehExtra add-on are here as well. 

**WEAPONS:**  
- Fist: Mechanically unchanged, but now with smoother and ambidextrous animations.  Doomguy cracks his knuckles before assuming a fighting stance.  
- Chainsaw: Now swung around for a more intense firing animation rather than just lazily holding it out in front of you.  Doomguy pulls the cord when you draw.  
- Pistol: Shoots 14% faster, ejects shell casings, and now has a draw animation.  
- Shotgun: The pump action has been replaced with a lever action Model 1887.  Mostly mechanically unchanged, though there's a surprise for those daring enough to fire from melee range ;)  
- Super Shotgun, Chaingun (SMG), Rocket Launcher, and Plasma Rifle: A couple frames and effects added for smoothness, but mechanically there's no change from Dead Simple.  
- BFG: _**MUCH**_ nicer animations compared to before, but functionally speaking it's still the BFG.  

 All enemy projectiles have gotten a speed buff, and all enemies now use the "Higher Missile Chance" flag - meaning they'll shoot at you MUCH more frequently.

**ENEMIES:**  
- Zombiemen: Smoothed and alternate death animations.  Increased rate of fire and they still stand their ground by calling refire.  
- ShotgunGuy: Smoothed and alternate death animations.  They now _also_ call refire if you're still in their line of sight.  
- ChaingunGuy: Increased ROF, now matches the player's.  
  (The former humans are kinda lame by comparison: here's the real good stuff)  
- Imp: Smoothed animations and alternate deaths.  They now have a discrete melee animation distinct from their ranged attack.  Additionally, they also will occasionally throw three fireballs in rapid succession.  
- Demons: Smoothed animations and alternate deaths.  
- Cacodemons: Smoothed animations and alternate deaths.  They have a chance to fire a spread of fireballs in front of them.  
- HellKnights: Now use an entirely distinct sprite set - they look more like Barons now if we're being completely honest.  They have a three-in-a-row attack just like the imps (albeit slower), and they'll also throw a spread of three fireballs at once.  
- Barons of Hell: Now use an entirely distinct sprite set - they're charred black and carry permanent marks from their time in Hell.  They have a _five_-in-a-row attack just like the HellKnights (albeit faster), and they'll also throw a spread of five fireballs at once.  
- Arachnotrons: Smoothed animations, projectiles now have a much smoother explosion animation and have a trail mimicking the player's plasma shots.  
- Lost Souls, Mancubi, Pain Elementals, Cyberdemons, and Spider Masterminds: Smoothed animations - no major changes to code besides the aforementioned "kill the player more" flag.

**BRGHTMPS AND NUGHUD ARE ALSO PROVIDED AND STILL COMPATIBLE AS BEFORE**

**THIS MOD HAS BEEN TESTED AND IS FULLY\* COMPATIBLE WITH:**  
- The Woof! family of ports (incuding Nugget and Cherry)  
- Doom Retro  
- DSDA-Doom  
- GZDoom
- The Eternity Engine
- Helion  

*KNOWN ISSUES:  
- Currently, of the ports I've tested here, only Woof!-family ports and Helion are able to accept the BRGHTMPS lump, though Doom Retro should be fixing this feature in a future update.
- Doom Retro and GZDoom like to CTD when you hit the ENDOOM screen in BTSX but you've already quit at that point so I'm not too worried about it.  

**HOW TO USE:**  
Two versions of this mod are included. The one ending with "_No_Enemies" deletes the extra attacks for the enemies if you REALLY only want the smooth animations.  
If your source port has an autoload folder and you want to use them, you can go ahead and add brghtmps.lmp and the NUGHUD into the "all" section.  If you're NOT playing Legacy of Rust, load the IWAD, then map PWAD, Mortal Doom, then the NUGHUD if you don't want it in the autoload folder.  If you ARE playing Legacy of Rust, Mortal Doom must be loaded BEFORE Legacy of Rust to allow overwriting the Plasma Rifle and BFG.  The Rust Patch must be loaded afterwards to put the new shocktrooper sprites and strings consistent with the LoR conten﻿t in the game. NUGHUD goes at the end as per usual if not in your autoload folder.

**CREDITS:**  
Sgt Mark IV - Brutal Doom v21 and v22 (Fist, Pistol, Shotgun, BFG)  
OSJC Latchford - Major Crisis (SMG, Plasma Rifle)  
Sonik.O.Fan aka Tesefy - Brutal Doom v21 Vanilla Gloves (Rocket Launcher)  
Lobo - Doom Forever (Imp Sprites, some effects)  
c0mbolynch - Supercharge weapons addon (Super Shotgun)  
cybermonday - New lever action shotgun  
Tormentor667 and The Repository - HellKnights and Barons of Hell

Please enjoy this mod, and let me know what you think!  As always - comments, feedback, and constructive criticism are all welcome.  All other complaints can be emailed to rpitchford@gearbox.com. 
