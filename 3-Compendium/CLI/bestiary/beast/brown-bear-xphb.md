---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Brown Bear"]
---
# [Brown Bear](3-Compendium\CLI\bestiary\beast/brown-bear-xphb.md)
*Source: Player's Handbook (2024) p. 347, Monster Manual (2024) p. 350*  

```statblock
"name": "Brown Bear (XPHB)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "22"
"hit_dice": "3d10 + 6"
"stats":
- !!int "17"
- !!int "12"
- !!int "15"
- !!int "2"
- !!int "13"
- !!int "7"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "None"
"cr": "1"
"actions":
- "desc": "The bear makes one Bite attack and one Claw attack."
  "name": "Multiattack"
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 7 (1d8 + 3) Piercing damage."
  "name": "Bite"
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 5 (1d4 + 3) Slashing damage, and\
    \ the target has the [Prone](/3-Compendium/CLI/rules/conditions.md#Prone) condition\
    \ if it is Huge or smaller."
  "name": "Claw"
"source":
- "XPHB"
- "XMM"
"image": "bestiary/tokens/XPHB/Brown Bear.webp"
```
^statblock