---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Biomancer"]
---
# [Biomancer](3-Compendium\CLI\bestiary\humanoid/biomancer-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 256*  

Nearly all the innovation and advancement in Simic bioengineering comes from the work of biomancers. Specialists in hybridizing and altering creatures through a mixture of science and magic, they have spawned countless hybrids and krasis in search of the perfect union between nature and civilization.

```statblock
"name": "Biomancer (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "splint armor"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"stats":
- !!int "10"
- !!int "15"
- !!int "14"
- !!int "20"
- !!int "14"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "9"
"skillsaves":
  "Nature": !!int "9"
  "Arcana": !!int "9"
"senses": "passive Perception 12"
"languages": "Common plus any one language"
"cr": "10"
"traits":
- "desc": "The biomancer is a 16th-level Simic spellcaster. Its spellcasting ability\
    \ is Intelligence (spell save DC 17, +9 to hit with spell attacks). The biomancer\
    \ has the following wizard spells prepared:\n\nCantrips (at will): acid splash,\
    \ light, mending, poison spray, shocking grasp\n\n1st level (4 slots): detect\
    \ magic, grease, shield\n\n2nd level (3 slots): alter self, darkvision, enlarge/reduce,\
    \ hold person\n\n3rd level (3 slots): counterspell, dispel magic, haste, protection\
    \ from energy\n\n4th level (3 slots): confusion, conjure minor elementals,\
    \ polymorph\n\n5th level (2 slots): cone of cold, creation, hold monster\n\
    \n6th level (1 slots): move earth, wall of ice\n\n7th level (1 slots):\
    \ prismatic spray\n\n8th level (1 slots): control weather"
  "name": "Spellcasting"
- "desc": "The biomancer magically emanates life-giving energy within 30 feet of itself.\
    \ Any ally of the biomancer that starts its turn there regains 5 (1d10) hit points."
  "name": "Bolstering Presence"
- "desc": "The biomancer has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Scimitar"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Biomancer.webp"
```
^statblock