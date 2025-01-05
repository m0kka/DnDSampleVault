---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Lawmage"]
---
# [Lawmage](3-Compendium\CLI\bestiary\humanoid/lawmage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 228*  

The Azorius Senate has spellcasters who are trained to capture lawbreakers and bring them to justice. A lawmage's magic is focused on restraining criminals and on protecting bystanders from becoming casualties when arresters are pursuing malefactors. A significant proportion of the guild's vedalken are lawmages.

```statblock
"name": "Lawmage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "breastplate"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"stats":
- !!int "13"
- !!int "12"
- !!int "14"
- !!int "17"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "6"
"skillsaves":
  "Perception": !!int "5"
  "Arcana": !!int "6"
  "Persuasion": !!int "4"
"senses": "passive Perception 15"
"languages": "Common plus any one language"
"cr": "6"
"traits":
- "desc": "The lawmage is an 8th-level Azorius spellcaster. Its spellcasting ability\
    \ is Intelligence (spell save DC 14, +6 to hit with spell attacks). The lawmage\
    \ has the following wizard spells prepared:\n\nCantrips (at will): fire bolt,\
    \ friends, light, message\n\n1st level (4 slots): alarm, expeditious retreat,\
    \ shield\n\n2nd level (3 slots): arcane lock, detect thoughts, hold person\n\
    \n3rd level (3 slots): clairvoyance, dispel magic, slow\n\n4th level (2\
    \ slots): locate creature, stoneskin"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage if used with two\
    \ hands."
  "name": "Quarterstaff"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Lawmage.webp"
```
^statblock