---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Firefist"]
---
# [Firefist](3-Compendium\CLI\bestiary\humanoid/firefist-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros firefists combine potent magic with peerless fighting ability, inspiring all who serve alongside them. They often act as the point of contact between the Boros Legion and the angelic leaders.

```statblock
"name": "Firefist (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "4"
  "Religion": !!int "3"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "7"
"traits":
- "desc": "The firefist is a 9th-level Boros spellcaster. Its spellcasting ability\
    \ is Wisdom (spell save DC 14, +6 to hit with spell attacks). It has the following\
    \ cleric spells prepared:\n\nCantrips (at will): fire bolt, light, sacred\
    \ flame, spare the dying\n\n1st level (4 slots): guiding bolt, healing word,\
    \ heroism, shield of faith\n\n2nd level (3 slots): lesser restoration, scorching\
    \ ray\n\n3rd level (3 slots): blinding smite, crusader's mantle, revivify\n\
    \n4th level (3 slots): banishment, wall of fire\n\n5th level (1 slots):\
    \ flame strike"
  "name": "Spellcasting"
"actions":
- "desc": "The firefist makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) slashing damage."
  "name": "Greatsword"
"reactions":
- "desc": "When the firefist or one creature it can see within 30 feet of it makes\
    \ an attack roll, the firefist grants a +10 bonus to that roll."
  "name": "Guided Attack (Recharges after a Short or Long Rest)"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Firefist.webp"
```
^statblock