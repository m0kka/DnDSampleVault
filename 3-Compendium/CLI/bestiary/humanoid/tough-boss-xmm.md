---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Tough Boss"]
---
# [Tough Boss](3-Compendium\CLI\bestiary\humanoid/tough-boss-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Tough Boss (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "16"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"stats":
- !!int "17"
- !!int "14"
- !!int "16"
- !!int "11"
- !!int "10"
- !!int "11"
"speed": "30 ft."
"saves":
  "Charisma": !!int "2"
  "Strength": !!int "5"
  "Constitution": !!int "5"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "4"
"traits":
- "desc": "The tough has Advantage on an attack roll against a creature if at least\
    \ one of the tough's allies is within 5 feet of the creature and the ally doesn't\
    \ have the [Incapacitated](/3-Compendium/CLI/rules/conditions.md#Incapacitated)\
    \ condition."
  "name": "Pack Tactics"
"actions":
- "desc": "The tough makes two attacks, using Warhammer or Heavy Crossbow in any combination."
  "name": "Multiattack"
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 12 (2d8 + 3) Bludgeoning damage,\
    \ and if the target is Large or smaller, the tough can push the target up to 10\
    \ feet straight away from itself."
  "name": "Warhammer"
- "desc": "Ranged Attack: +4, range 100/400 ft. Hit: 13 (2d10 + 2) Piercing damage."
  "name": "Heavy Crossbow"
"source":
- "XMM"
"image": "bestiary/tokens/XMM/Tough Boss.webp"
```
^statblock