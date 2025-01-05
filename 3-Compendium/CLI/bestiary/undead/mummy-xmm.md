---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Mummy"]
---
# [Mummy](3-Compendium\CLI\bestiary\undead/mummy-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Mummy (XMM)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "8"
- !!int "15"
- !!int "6"
- !!int "10"
- !!int "12"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "2"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "The mummy can use its Dreadful Glare and makes one attack with its rotting\
    \ fist."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) bludgeoning damage plus 10 (3d6) necrotic damage. If the target is a creature,\
    \ it must succeed on a DC 12 Constitution saving throw or be cursed with mummy\
    \ rot. The cursed target can't regain hit points, and its hit point maximum decreases\
    \ by 10 (3d6) for every 24 hours that elapse. If the curse reduces the target's\
    \ hit point maximum to 0, the target dies, and its body turns to dust. The curse\
    \ lasts until removed by the remove curse spell or other magic."
  "name": "Rotting Fist"
- "desc": "The mummy targets one creature it can see within 60 feet of it. If the\
    \ target can see the mummy, it must succeed on a DC 11 Wisdom saving throw against\
    \ this magic or become frightened until the end of the mummy's next turn. If the\
    \ target fails the saving throw by 5 or more, it is also paralyzed for the same\
    \ duration. A target that succeeds on the saving throw is immune to the Dreadful\
    \ Glare of all mummies (but not mummy lords) for the next 24 hours."
  "name": "Dreadful Glare"
"source":
- "XMM"
```
^statblock