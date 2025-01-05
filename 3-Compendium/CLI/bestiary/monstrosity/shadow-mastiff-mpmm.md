---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Shadow Mastiff"]
---
# [Shadow Mastiff](3-Compendium\CLI\bestiary\monstrosity/shadow-mastiff-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 215, Volo's Guide to Monsters p. 190*  

Shunning sunlight, these hounds are usually met as a pack. Some faiths devoted to deities of gloom and night, such as that of Shar in the Forgotten Realms, perform unholy rites to summon shadow mastiffs to work as temple sentinels and bodyguards.

## Shadow Mastiffs

Shadow mastiffs—hounds of the Shadowfell—move invisibly through the shadows, always on the hunt.

```statblock
"name": "Shadow Mastiff (MPMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Typically  Neutral Evil"
"ac": !!int "12"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "5"
- !!int "12"
- !!int "5"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "5"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks while\
  \ in dim light or darkness"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "2"
"traits":
- "desc": "The shadow mastiff can see ethereal creatures and objects."
  "name": "Ethereal Awareness"
- "desc": "While in bright light created by sunlight, the shadow mastiff has disadvantage\
    \ on attack rolls, ability checks, and saving throws."
  "name": "Sunlight Weakness"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) piercing damage. If the target is a creature, it must succeed on a DC 13\
    \ Strength saving throw or be knocked prone."
  "name": "Bite"
"bonus_actions":
- "desc": "While in dim light or darkness, the shadow mastiff becomes invisible, along\
    \ with anything it is wearing or carrying. The invisibility lasts until the shadow\
    \ mastiff uses a bonus action to end it or until the shadow mastiff attacks, is\
    \ in bright light, or is incapacitated."
  "name": "Shadow Blend"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Shadow Mastiff.webp"
```
^statblock

## Environment

forest, hill, swamp