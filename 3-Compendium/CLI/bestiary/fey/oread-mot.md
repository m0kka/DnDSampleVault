---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Oread"]
---
# [Oread](3-Compendium\CLI\bestiary\fey/oread-mot.md)
*Source: Mythic Odysseys of Theros p. 237*  

Aggressive oreads number among the most dangerous nymphs, as they embody the wild might of flames, volcanism, and the hidden forces of the earth. These creatures typically dwell in remote mountain crags and near volcanoes, where they caper among the forces of dissolution and rebirth. During avalanches and volcanic eruptions, groups of oreads might race ahead of the destruction, dancing, singing, and doing what they can to maximize the impending devastation.

## Honor Among Fey

Hearkening back to some ages-old conflict, oreads refuse to knowingly destroy any land inhabited by another nymph. While they won't work to alter the natural course of destruction, neither will they make another nymph's home part of any calamity they encourage. As a result, part of what makes an alseid's field or a dryad's grove seem so blessed is that oreads go out of their way to leave such sites alone.

## Tales of Fire

The followers of Purphoros regard oreads with special reverence, as myths tell of cagey smiths befriending these nymphs and convincing them to aid in creating phenomenal works. In some tales, a smith finds an oread and allows it to relish in the destruction of a novel or remarkable item. In recompense, the oread provides the smith with materials drawn from the burning heart of the world, allowing the smith to create an even greater wonder. In more tales, though, a smith pursues an oread, then later the mortal's associates find familiar tools and a heap of ashes.

## Nymphs

Divine servants that inhabit unspoiled corners of the world, nymphs protect places of natural power and infuse their surroundings with the magic of Nyx. Some are benevolent and aid those who live off the land, while others embody violent aspects of nature. In either case, nymphs generally avoid other sapient creatures, preferring to mind the cycles of nature, the daily interplay of wild animals, or other cosmic forces. Occasionally, though, groups of the same kind of nymphs congregate in a place of natural power or beauty. In times of special need, deities tied to facets of nature might employ nymphs as messengers, guardians, or scouts.

### Immortal Nature

A nymph doesn't require food, drink, or sleep.

```statblock
"name": "Oread (MOT)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"stats":
- !!int "14"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Performance": !!int "6"
  "Acrobatics": !!int "4"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "passive Perception 11"
"languages": "Common, Sylvan"
"cr": "4"
"traits":
- "desc": "The oread's spellcasting ability is Charisma (spell save DC 14, +6 to hit\
    \ with spell attacks). It can innately cast the following spells, requiring no\
    \ material components:\n\nAt will: fire bolt (see \"Actions\" below)\n\n1/day\
    \ each: hellish rebuke (see \"Reactions\" below), scorching ray\n\n3/day:\
    \ burning hands"
  "name": "Innate Spellcasting"
- "desc": "The oread is invisible while fully immersed in fire."
  "name": "Invisible in Fire"
- "desc": "The oread has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The oread attacks twice with its fiery touch or fire bolt."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (1d10\
    \ + 4) fire damage."
  "name": "Fiery Touch"
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 5 (1d10)\
    \ fire damage."
  "name": "Fire Bolt (Cantrip)"
"reactions":
- "desc": "When the oread is damaged by a creature within 60 feet of the oread that\
    \ it can see, the creature that damaged the oread must make a DC 14 Dexterity\
    \ saving throw, taking 16 (3d10) fire damage on a failed save, or half as much\
    \ damage on a successful one."
  "name": "Hellish Rebuke (2nd-Level Spell; 1/Day)"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Oread.webp"
```
^statblock