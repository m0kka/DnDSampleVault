---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Druid of the Old Ways"]
---
# [Druid of the Old Ways](3-Compendium\CLI\bestiary\humanoid/druid-of-the-old-ways-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 239*  

The druids of the Old Ways are the keepers of ancient Gruul traditions devoted to the primal ferocity of animal gods such as Ilharg the Raze-Boar and Kashath the Stalker.

## The End-Raze

The druids of the Old Ways believe that civilization will never be eradicated by scattered raids and petty skirmishes. They cling to the idea of a coming apocalypse, the End-Raze, when Ilharg's hoofs will trample every brick and stone of Ravnica's soaring skylines to rubble. The world will return to a state of nature in which the lawless code of muscle and savagery will reign once again.

```statblock
"name": "Druid of the Old Ways (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"ac_class": "hide armor"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"stats":
- !!int "11"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "20"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "8"
  "Constitution": !!int "6"
"skillsaves":
  "Nature": !!int "3"
  "Perception": !!int "8"
  "Survival": !!int "8"
"senses": "passive Perception 18"
"languages": "Common, Druidic"
"cr": "7"
"traits":
- "desc": "The druid is a 12th-level Gruul spellcaster. Its spellcasting ability is\
    \ Wisdom (spell save DC 16, +8 to hit with spell attacks). It has the following\
    \ druid spells prepared:\n\nCantrips (at will): druidcraft, produce flame,\
    \ resistance, thorn whip\n\n1st level (4 slots): cure wounds, faerie fire,\
    \ thunderwave\n\n2nd level (3 slots): beast sense, flame blade, pass without\
    \ trace\n\n3rd level (3 slots): conjure animals, dispel magic, plant growth\n\
    \n4th level (3 slots): dominate beast, freedom of movement, wall of fire\n\
    \n5th level (2 slots): commune with nature, conjure elemental, scrying\n\n\
    6th level (1 slots): transport via plants, wall of thorns"
  "name": "Spellcasting"
- "desc": "The druid deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "The druid can communicate with beasts and plants as if they shared a language."
  "name": "Speak with Beasts and Plants"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands."
  "name": "Quarterstaff"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Druid of the Old Ways.webp"
```
^statblock