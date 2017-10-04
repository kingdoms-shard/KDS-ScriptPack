
Created by Soulless
compiled from Neruns distro from RUNUO
Dialogs and some material from amonvangrall

VERSION 1.0.1
fixed some errors
needs ter mur monster defs added, they do not currently exist within sphere's scripts. (let me know if anyone has them all)

VERSION 1.0.2
fixed issues with spawns not wanting to spawn their full array of creatures.
fixed issues with home and homedist on chars

VERSION 1.0.3
fixed issue with duplicate doors on felucca/trammel britain bank
benefactor of britain is now a t_normal type
added moongate script to the pack
added uoclassic spawns for those who want an old spawn server. (must use command for this, not in the dialog)
fixed sysmessages for signs/doors/moongates generation/removal
fixed issue with moongate removal not working
added check to skip different stages of Magincia based on reported client version
  *Old Magincia [Client <= 6.0.3.1]
  *Magincia Ruins [Client >= 6.0.4.0 && Client <= 7.0.13.0]
  *New Magincia [Client >= 7.0.13.1]



TODO
make items spawn near the spawner, if taken, or decay reset timer and take away more1
add in TERMUR creatures
do not spawn ocllo deco if it's destroyed. 
do not spawn signs in magincia or occllo if they are destroyed
do not spawn towncrier in occllo or magincia if they are destroyed



place this in your spheretables :

scripts/custom/spawners/
scripts/custom/spawners/npcs/
scripts/custom/spawners/npcs/felucca/
scripts/custom/spawners/npcs/ilshenar/
scripts/custom/spawners/npcs/malas/
scripts/custom/spawners/npcs/mondain/
scripts/custom/spawners/npcs/tokuno/
scripts/custom/spawners/npcs/trammel/
scripts/custom/spawners/npcs/uoclassic/
scripts/custom/spawners/decoration/
scripts/custom/spawners/decoration/felucca/
scripts/custom/spawners/decoration/ilshenar/
scripts/custom/spawners/decoration/malas/
scripts/custom/spawners/decoration/misc/
scripts/custom/spawners/decoration/ter_mur/
scripts/custom/spawners/decoration/tokuno/
scripts/custom/spawners/decoration/trammel/


You may want to increase these settings in sphere.ini, here's how mine look

// Max NPC chars for a sector to prevent lag
MaxComplexity=128		//32

// Amount of items in one sector to start showing "x items too complex"
MaxSectorComplexity=2048		//1024


After that you're good to go just go in game add i_world_decorator and i_world_spawner

dclick the items, spawn and decorate your world. 

