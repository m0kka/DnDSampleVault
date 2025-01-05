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
aliases: ["Abjurer Wizard"]
---
# [Abjurer Wizard](3-Compendium\CLI\bestiary\humanoid/abjurer-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 260, Volo's Guide to Monsters p. 209*  

Abjurers specialize in creating protective magical wards. Monarchs, nobles, and other wealthy individuals commonly hire abjurers to provide protection.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Abjurer Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"stats":
- !!int "9"
- !!int "14"
- !!int "14"
- !!int "18"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "8"
"skillsaves":
  "History": !!int "8"
  "Arcana": !!int "8"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"traits":
- "desc": "The abjurer casts one of the following spells, using Intelligence as the\
    \ spellcasting ability (spell save DC 16):\n\nAt will: dancing lights, mage\
    \ hand, message, prestidigitation\n\n1/day each: arcane lock, banishment,\
    \ globe of invulnerability, invisibility, wall of force\n\n2/day each: dispel\
    \ magic, lightning bolt, mage armor"
  "name": "Spellcasting"
"actions":
- "desc": "The abjurer makes three Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 20 (3d10 + 4) force damage."
  "name": "Arcane Burst"
- "desc": "Each creature in a 20-foot cube originating from the abjurer must make\
    \ a DC 16 Constitution saving throw. On a failed save, a creature takes 36 (8d8)\
    \ force damage and is pushed up to 10 feet away from the abjurer. On a successful\
    \ save, a creature takes half as much damage and isn't pushed."
  "name": "Force Blast"
"reactions":
- "desc": "When the abjurer or a creature it can see within 30 feet of it takes damage,\
    \ the abjurer magically creates a protective barrier around itself or the other\
    \ creature. The barrier reduces the damage to the protected creature by 26 (4d10\
    \ + 4), to a minimum of 0, and then vanishes."
  "name": "Arcane Ward (Recharge 4-6)"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Abjurer Wizard.webp"
```
^statblock

## Environment

urban