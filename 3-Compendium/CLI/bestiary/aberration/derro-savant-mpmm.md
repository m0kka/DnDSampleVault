---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/aberration/sorcerer
statblock: inline
aliases: ["Derro Savant"]
---
# [Derro Savant](3-Compendium\CLI\bestiary\aberration/derro-savant-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 92, Mordenkainen's Tome of Foes p. 159*  

> [!quote] A quote from Mordenkainen  
> 
> Mind flayers must be stopped. They have visited horrors on countless worlds, and entire groups of people have been mutated by illithid experiments. Such are the derro.
> 
> Whenever I've met them, I refuse to fight, no matter how violent they might be. I think of the dwarves they once were. and I must confess that even I have shed tears.

Derro slink through the subterranean realms, seeking places that are safe from the perils of the Underdark. Equal parts fearful and vicious, bands of these dwarf-kin prey on those weaker than themselves, while giving simpering obeisance to any creatures they deem more powerful. A lone derro may seem pitiable, but a cackling, spitting, growling, howling horde of them is horrifying to behold.

Fractious in groups and individually weak, derro would have died out long ago but for two elements of their character. They are cautious and distrustful, which serves them well as they navigate the dangers of the Underdark and its societies. They also have a stronger-than-normal tendency to develop sorcerous power. Individuals who do so usually serve as leaders and are known as savants.

Grandiose fantasies and rampant fanaticism have obscured derro's true origin, even among themselves. Most dwarves don't recognize derro as kin, but the legends that derro tell about their people and the story that duergar believe share a grain of truth. According to the histories of some duergar, derro are descended from a dwarven community that was left behind when the others escaped the rule of mind flayers. These remnants were so distorted by the mind flayers' psionic power that the dwarves became Aberrations.

Derro tell their own stories of flight and survival in the Underdark, in which mind flayers aren't always the enemy. They tell of two brothers, the gods Diirinka and Diinkarazan, and of how Diirinka cleverly betrayed his sibling so that he could steal magical power from the evil they escaped. The danger the brothers are said to face in this legend varies, depending on whatever foe the savants want to lead their people against, yet the essence of the story remains the same: a lesson of survival at any price and an example of how deceitfulness and cruelty can be virtues.

```statblock
"name": "Derro Savant (MPMM)"
"size": "Small"
"type": "aberration"
"subtype": "sorcerer"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "leather armor"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"stats":
- !!int "9"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "5"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
"senses": "darkvision 120 ft., passive Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "3"
"traits":
- "desc": "The derro casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 12):\n\nAt will: mage hand, message, prestidigitation\n\
    \n1/day each: invisibility, sleep, spider climb"
  "name": "Spellcasting"
- "desc": "The derro has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "While in sunlight, the derro has disadvantage on attack rolls, as well\
    \ as on Wisdom (Perception) checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage."
  "name": "Quarterstaff"
- "desc": "The derro launches a brilliant beam of magical energy in a 5-foot-wide\
    \ line that is 60 feet long. Each creature in the line must make a DC 12 Dexterity\
    \ saving throw, taking 21 (6d6) radiant damage on a failed save, or half as much\
    \ damage on a successful one."
  "name": "Chromatic Beam"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Derro Savant.webp"
```
^statblock

## Environment

underdark