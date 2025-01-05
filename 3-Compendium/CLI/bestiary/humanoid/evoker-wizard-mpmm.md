---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Evoker Wizard"]
---
# [Evoker Wizard](3-Compendium\CLI\bestiary\humanoid/evoker-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 262, Volo's Guide to Monsters p. 214*  

Evokers harness arcane energy to destroy. Many armies employ evokers to rain destruction down on enemy forces.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Evoker Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "121"
"hit_dice": "22d8 + 22"
"stats":
- !!int "9"
- !!int "14"
- !!int "12"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "7"
"skillsaves":
  "History": !!int "7"
  "Arcana": !!int "7"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"traits":
- "desc": "The evoker casts one of the following spells, using Intelligence as the\
    \ spellcasting ability (spell save DC 15):\n\nAt will: light, mage hand, message,\
    \ prestidigitation\n\n1/day each: wall of ice\n\n2/day each: ice storm,\
    \ lightning bolt, mage armor"
  "name": "Spellcasting"
"actions":
- "desc": "The evoker makes three Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 25 (4d10 + 3) force damage."
  "name": "Arcane Burst"
- "desc": "The evoker unleashes a magical explosion of a particular damage type: cold,\
    \ fire, lightning, or thunder. The magic erupts in a 20-foot-radius sphere centered\
    \ on a point within 150 feet of the evoker. Each creature in that area must make\
    \ a DC 15 Dexterity saving throw. The evoker can select up to three creatures\
    \ it can see in the area to ignore the spell, as the evoker sculpts the spell's\
    \ energy around them. On a failed save, a creature takes 40 (9d8) damage of the\
    \ chosen type and is knocked prone. On a successful save, a creature takes half\
    \ as much damage and isn't knocked prone."
  "name": "Sculpted Explosion (Recharge 4-6)"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Evoker Wizard.webp"
```
^statblock

## Environment

urban