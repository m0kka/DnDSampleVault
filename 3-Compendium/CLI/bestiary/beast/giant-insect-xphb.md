---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Giant Insect"]
---
# [Giant Insect](3-Compendium\CLI\bestiary\beast/giant-insect-xphb.md)
*Source: Player's Handbook (2024) p. 279*  

```statblock
"name": "Giant Insect (XPHB)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac_class": "11 + the spell's level"
"stats":
- !!int "17"
- !!int "13"
- !!int "15"
- !!int "4"
- !!int "14"
- !!int "3"
"speed": "40 ft., climb 40 ft., fly 40 ft. (Wasp only)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "understands the languages you know"
"traits":
- "desc": "The insect can climb difficult surfaces, including along ceilings, without\
    \ needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The insect makes a number of attacks equal to half this spell's level (round\
    \ down)."
  "name": "Multiattack"
- "desc": "Melee Attack: YourSpellAttack Bonus equals your spell attack modifier,\
    \ reach 10 ft. Hit: 1d6 + 3 + the spell's level Piercing damage plus 1d4 Poison\
    \ damage."
  "name": "Poison Jab"
- "desc": "Ranged Attack: YourSpellAttack Bonus equals your spell attack modifier,\
    \ range 60 ft. Hit: 1d10 + 3 + the spell's level Bludgeoning damage, and the\
    \ target's Speed is reduced to 0 until the start of the insect's next turn."
  "name": "Web Bolt (Spider Only)"
"bonus_actions":
- "desc": "Constitution Saving Throw: Your spell save DC, one creature the insect\
    \ can see within 10 feet. Failure: The target has the [Poisoned](/3-Compendium/CLI/rules/conditions.md#Poisoned)\
    \ condition until the start of the insect's next turn."
  "name": "Venomous Spew (Centipede Only)"
"source":
- "XPHB"
"image": "bestiary/tokens/XPHB/Giant Insect.webp"
```
^statblock