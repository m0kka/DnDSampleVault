---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Rubblebelt Stalker"]
---
# [Rubblebelt Stalker](3-Compendium\CLI\bestiary\humanoid/rubblebelt-stalker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 239*  

Rubblebelt stalkers are scouts and skirmishers for the Gruul Clans. They excel at moving over challenging terrain, whether they're picking their way through treacherous ruins or clambering across rooftops. They favor ambush tactics and avoid confrontations with stronger forces, relying on their superior mobility to make their escape.

```statblock
"name": "Rubblebelt Stalker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"ac_class": "piecemeal armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "10"
- !!int "15"
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "8"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Athletics": !!int "2"
  "Stealth": !!int "4"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
- "desc": "In the first round of a combat, the stalker has advantage on attack rolls\
    \ against any creature that hasn't taken a turn yet."
  "name": "Ambusher"
- "desc": "The stalker can take the Disengage or Hide action as a bonus action on\
    \ each of its turns."
  "name": "Nimble Escape"
- "desc": "The stalker has advantage on Dexterity (Stealth) checks made to hide in\
    \ ruins, and its speed is not reduced in difficult terrain composed of rubble."
  "name": "Ruin Dweller"
- "desc": "The stalker deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The stalker makes three attacks with its shortsword."
  "name": "Multiattack"
- "desc": "Melee Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2)\
    \ piercing damage."
  "name": "Shortsword"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Rubblebelt Stalker.webp"
```
^statblock