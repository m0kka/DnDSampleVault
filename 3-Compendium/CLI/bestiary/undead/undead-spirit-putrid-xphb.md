---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Undead Spirit (Putrid)"]
---
# [Undead Spirit (Putrid)](3-Compendium\CLI\bestiary\undead/undead-spirit-putrid-xphb.md)
*Source: Player's Handbook (2024) p. 328*  

```statblock
"name": "Undead Spirit (Putrid) (XPHB)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral"
"ac_class": "11 + the spell's level"
"stats":
- !!int "12"
- !!int "16"
- !!int "15"
- !!int "4"
- !!int "10"
- !!int "9"
"speed": "30 ft."
"damage_immunities": "necrotic, poison"
"condition_immunities": "exhaustion, frightened, paralyzed, poisoned"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages you know"
"traits":
- "desc": "Constitution Saving Throw: DC equals your spell save DC, any creature\
    \ (other than you) that starts its turn within a 5-foot Emanation originating\
    \ from the spirit. Failure: The creature has the [Poisoned](/3-Compendium/CLI/rules/conditions.md#Poisoned)\
    \ condition until the start of its next turn."
  "name": "Festering Aura"
"actions":
- "desc": "The spirit makes a number of attacks equal to half this spell's level (round\
    \ down)."
  "name": "Multiattack"
- "desc": "Melee Attack: YourSpellAttack Bonus equals your spell attack modifier,\
    \ reach 5 ft. Hit: 1d6 + 3 + the spell's level Slashing damage. If the target\
    \ has the [Poisoned](/3-Compendium/CLI/rules/conditions.md#Poisoned) condition,\
    \ it has the [Paralyzed](/3-Compendium/CLI/rules/conditions.md#Paralyzed) condition\
    \ until the end of its next turn."
  "name": "Rotting Claw"
"source":
- "XPHB"
```
^statblock