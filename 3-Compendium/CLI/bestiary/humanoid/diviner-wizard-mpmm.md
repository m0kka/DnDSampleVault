---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Diviner Wizard"]
---
# [Diviner Wizard](3-Compendium\CLI\bestiary\humanoid/diviner-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 261, Volo's Guide to Monsters p. 213*  

Diviners peer into the future and know that knowledge is power. They might act aloof and mysterious, hinting at omens and secrets, or they might be know-it-alls, spilling insights to advance their own status.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Diviner Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "90"
"hit_dice": "20d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "18"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "7"
"skillsaves":
  "History": !!int "7"
  "Arcana": !!int "7"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "8"
"traits":
- "desc": "The diviner casts one of the following spells, using Intelligence as the\
    \ spellcasting ability (spell save DC 15):\n\nAt will: mage hand, message,\
    \ prestidigitation\n\n1/day each: true seeing\n\n2/day each: arcane eye,\
    \ detect magic, detect thoughts, fly, lightning bolt, locate object, mage armor,\
    \ Rary's telepathic bond"
  "name": "Spellcasting"
"actions":
- "desc": "The diviner makes three Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 20 (3d10 + 4) radiant damage."
  "name": "Arcane Burst"
- "desc": "The diviner magically creates a burst of illumination in a 10-foot-radius\
    \ sphere centered on a point within 120 feet of it. Each creature in that area\
    \ must make a DC 15 Wisdom saving throw. On a failed save, a creature takes 45\
    \ (10d8) psychic damage and is stunned until the end of the diviner's next turn.\
    \ On a successful save, the creature takes half as much damage and isn't stunned."
  "name": "Overwhelming Revelation (Recharge 5-6)"
"reactions":
- "desc": "When the diviner or a creature it can see makes an attack roll, a saving\
    \ throw, or an ability check, the diviner rolls a d20 and chooses whether to use\
    \ that roll in place of the d20 rolled for the attack roll, saving throw, or ability\
    \ check. "
  "name": "Portent (3/Day)"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Diviner Wizard.webp"
```
^statblock

## Environment

urban