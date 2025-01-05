---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Lampad"]
---
# [Lampad](3-Compendium\CLI\bestiary\fey/lampad-mot.md)
*Source: Mythic Odysseys of Theros p. 235*  

Lampads guard the shadowed paths of the world, depths typically trod by souls destined for the Underworld. These rarely seen nymphs assist Athreos in guiding the dead, moving among the spirits that collect along the Tartyx River and reclaiming wayward souls that try to slip back to the mortal world. This means lampads are most often spotted in graveyards, crumbling crypts, and tunnels that bore deep into the earth, and near portals to the Underworld.

## Nymphs

Divine servants that inhabit unspoiled corners of the world, nymphs protect places of natural power and infuse their surroundings with the magic of Nyx. Some are benevolent and aid those who live off the land, while others embody violent aspects of nature. In either case, nymphs generally avoid other sapient creatures, preferring to mind the cycles of nature, the daily interplay of wild animals, or other cosmic forces. Occasionally, though, groups of the same kind of nymphs congregate in a place of natural power or beauty. In times of special need, deities tied to facets of nature might employ nymphs as messengers, guardians, or scouts.

### Immortal Nature

A nymph doesn't require food, drink, or sleep.

```statblock
"name": "Lampad (MOT)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "12"
- !!int "13"
- !!int "14"
- !!int "11"
- !!int "12"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "6"
  "Deception": !!int "6"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "passive Perception 11"
"languages": "Common, Sylvan"
"cr": "3"
"traits":
- "desc": "The lampad's spellcasting ability is Charisma (+6 to hit with spell attacks).\
    \ It can innately cast the following spells, requiring no material components:\n\
    \nAt will: chill touch (see \"Actions\" below), gentle repose"
  "name": "Innate Spellcasting"
- "desc": "Once on its turn, the lampad can use 10 feet of its movement to step magically\
    \ into one creature's corpse within its reach and emerge from a second creature's\
    \ corpse within 60 feet of the first corpse, appearing in an unoccupied space\
    \ within 5 feet of the second corpse. Both corpses must be Medium or bigger."
  "name": "Corpse Stride"
- "desc": "The lampad has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The lampad attacks twice with its necrotic touch or chill touch."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (1d10\
    \ + 4) necrotic damage."
  "name": "Necrotic Touch"
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one creature. Hit: 9\
    \ (2d8) necrotic damage, and the target can't regain hit points until the start\
    \ of the lampad's next turn. If the target is undead, it has disadvantage on attack\
    \ rolls against the lampad until the end of the lampad's next turn."
  "name": "Chill Touch (Cantrip)"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Lampad.webp"
```
^statblock