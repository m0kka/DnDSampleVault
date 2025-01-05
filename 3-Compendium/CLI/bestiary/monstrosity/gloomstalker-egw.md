---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Gloomstalker"]
---
# [Gloomstalker](3-Compendium\CLI\bestiary\monstrosity/gloomstalker-egw.md)
*Source: Explorer's Guide to Wildemount p. 291*  

A gloomstalker is a terrifying, winged predator resembling a wyvern composed of twisting shadows, with glowing eyes and dagger-like teeth.

```statblock
"name": "Gloomstalker (EGW)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"stats":
- !!int "22"
- !!int "16"
- !!int "14"
- !!int "5"
- !!int "17"
- !!int "14"
"speed": "40 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "6"
  "Strength": !!int "9"
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "9"
  "Stealth": !!int "6"
  "Perception": !!int "6"
"damage_vulnerabilities": "radiant"
"senses": "darkvision 240 ft, passive Perception 16"
"languages": "understands Common but can't speak"
"cr": "6"
"traits":
- "desc": "As a bonus action, the gloomstalker can teleport up to 40 feet to an unoccupied\
    \ space it can see."
  "name": "Shadowstep"
- "desc": "While in sunlight, the gloomstalker has disadvantage on attack rolls, as\
    \ well as on Wisdom (Perception) checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The gloomstalker makes two attacks: one with its bite and one with its\
    \ claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 15\
    \ (2d8 + 6) piercing damage plus 7 (2d6) necrotic damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 13 (2d6\
    \ + 6) slashing damage plus 7 (2d6) necrotic damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one Medium or smaller creature.\
    \ Hit: 13 (2d6 + 6) slashing damage plus 7 (2d6) necrotic damage, and the target\
    \ is grappled (escape DC 17). While grappled in this way, the target is restrained."
  "name": "Snatch"
- "desc": "The gloomstalker emits a terrible shriek. Each enemy within 60 feet of\
    \ the gloomstalker that can hear it must succeed on a DC 13 Constitution saving\
    \ throw or be paralyzed until the end of the enemy's next turn."
  "name": "Shriek (Recharge 6)"
"source":
- "EGW"
"image": "bestiary/tokens/EGW/Gloomstalker.webp"
```
^statblock