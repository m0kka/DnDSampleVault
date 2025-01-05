---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bmt
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/warlock
statblock: inline
aliases: ["Initiate of the Comet"]
---
# [Initiate of the Comet](3-Compendium\CLI\bestiary\humanoid/initiate-of-the-comet-bmt.md)
*Source: The Book of Many Things p. 93*  

Once initiated into the Heralds of the Comet, members learn magical divination practices that give them glimpses into the future.

```statblock
"name": "Initiate of the Comet (BMT)"
"size": "Medium"
"type": "humanoid"
"subtype": "warlock"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "12"
- !!int "14"
- !!int "16"
- !!int "11"
- !!int "13"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "3"
"skillsaves":
  "Arcana": !!int "2"
"senses": "passive Perception 11"
"languages": "Common plus any one language"
"cr": "4"
"traits":
- "desc": "The initiate casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 13):\n\nAt will: Mage Hand, Thaumaturgy\n\n1/day\
    \ each: Dimension Door, Divination, Enthrall"
  "name": "Spellcasting"
- "desc": "The initiate has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The initiate makes two Comet Strike attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 14 (2d10 + 3) force damage."
  "name": "Comet Strike"
"reactions":
- "desc": "When hit by an attack roll, the initiate can force the attacker to reroll\
    \ it and use the new roll, possibly causing the attack to miss."
  "name": "Moment of Foresight (1/Day)"
"source":
- "BMT"
"image": "bestiary/tokens/BMT/Initiate of the Comet.webp"
```
^statblock