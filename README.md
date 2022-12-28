# TheoryCraft for Turtle WoW 1.16.5

TheoryCraft calculates DPS and other similarly insightful info, about what each specific ability or spell does. 
This info can be configured to be added to the mouseover tooltip, 
and you can also choose one of these calculated values to display atop your actionbars' spells and in the spellbook.

Install this addon (remove -master if you download this repo directly), and use `/tc` ingame to configure.

Useful metrics included include:

Damage per Second  
Healing per Second   
Damage per Mana  
Healing per Mana  
Crit Chance of Spell  
Damage until OOM  
Min Max or Average possible damage/healing  
Casts left until OOM  

TheoryCraft will take into account your set bonuses, enemy armor (by target) and enemy school resists (set manually).

Usually spells and some abilities have tooltips that will say that they do X to Y amount of damage, 
while the actual damage range is far ahead due to your gear. 
TheoryCraft's Embed option will update these values to their actual damage calculated by this addon.

TheoryCraft can also show how your current gear is responsible for your extra damage, 
and also predict how much damage/healing that more stats would add.

## Migrating from TheoryCraft for blizzlike 1.12
TheoryCraft-Turtle is a fork of the original version of TC, and they will conflict if you try using both. 
Delete your old wowfolder/Interface/AddOns/TheoryCraft/ folder.

To migrate your old TC settings, browse to wowfolder/WTF/Account/*username*/*realmname*/*charactername*/SavedVariables/ 
and rename TheoryCraft.lua to TheoryCraft-Turtle.lua, and do the same to the file in wowfolder/WTF/Account/*username*/ 
if you want to save the enemy mob and player armor values that TC has been estimating and storing.
