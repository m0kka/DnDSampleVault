---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon
statblock: inline
aliases: ["Draconic Spirit"]
---
# [Draconic Spirit](3-Compendium\CLI\bestiary\dragon/draconic-spirit-xphb.md)
*Source: Player's Handbook (2024) p. 325*  

```statblock
"name": "Draconic Spirit (XPHB)"
"size": "Large"
"type": "dragon"
"alignment": "Neutral"
"ac_class": "14 + the spell's level"
"stats":
- !!int "19"
- !!int "14"
- !!int "17"
- !!int "10"
- !!int "14"
- !!int "14"
"speed": "30 ft., fly 60 ft., swim 30 ft."
"damage_resistances": "acid, cold, fire, lightning, poison"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "blindsight 30 ft., darkvision 60 ft., passive Perception 12"
"languages": "Draconic, understands the languages you know"
"traits":
- "desc": "When you summon the spirit, choose one of its Resistances. You have Resistance\
    \ to the chosen damage type until the spell ends."
  "name": "Shared Resistances"
"actions":
- "desc": "The spirit makes a number of Rend attacks equal to half the spell's level\
    \ (round down), and it uses Breath Weapon."
  "name": "Multiattack"
- "desc": "Melee Attack: YourSpellAttack Bonus equals your spell attack modifier,\
    \ reach 10 feet. Hit: 1d6 + 4 + the spell's level Piercing damage."
  "name": "Rend"
- "desc": "Dexterity Saving Throw: DC equals your spell save DC, each creature in\
    \ a 30-foot Cone. Failure: 2d6 damage of a type this spirit has Resistance to\
    \ (your choice when you cast the spell). Success: Half damage."
  "name": "Breath Weapon"
"source":
- "XPHB"
"image": "bestiary/tokens/XPHB/Draconic Spirit.webp"
```
^statblock