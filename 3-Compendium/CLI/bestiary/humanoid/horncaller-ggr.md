---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Horncaller"]
---
# [Horncaller](3-Compendium\CLI\bestiary\humanoid/horncaller-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 253*  

Specialized shamans called horncallers use their magic to call wild beasts to fight alongside Selesnya troops. In quieter times, they tend the animals associated with Selesnya enclaves and parks.

```statblock
"name": "Horncaller (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "13"
"ac_class": "hide armor"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "13"
- !!int "12"
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Nature": !!int "2"
  "Animal Handling": !!int "4"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Common plus any one language"
"cr": "1"
"traits":
- "desc": "The horncaller's innate spellcasting ability is Wisdom (spell save DC 14).\
    \ The horncaller can innately cast the following spells, requiring no material\
    \ components:\n\n1/day each: bless, conjure animals"
  "name": "Innate Spellcasting"
- "desc": "The horncaller can communicate with beasts as if they shared a language."
  "name": "Speak with Beasts"
"actions":
- "desc": "The horncaller makes two melee attacks with its staff and uses One with\
    \ the Worldsoul."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) piercing damage, or 5 (1d8 + 1) bludgeoning damage if used with two hands."
  "name": "Staff"
- "desc": "The horncaller chooses one beast it can see within 30 feet of it. If the\
    \ beast can hear the horncaller, the beast uses its reaction to make one melee\
    \ attack against a target that the horncaller can see."
  "name": "One with the Worldsoul"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Horncaller.webp"
```
^statblock