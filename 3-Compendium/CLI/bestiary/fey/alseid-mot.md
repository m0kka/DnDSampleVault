---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Alseid"]
---
# [Alseid](3-Compendium\CLI\bestiary\fey/alseid-mot.md)
*Source: Mythic Odysseys of Theros p. 235*  

Touched with the golden light of the sun, alseids inhabit meadows, plains, and lands of cultivated natural beauty. Many live in closer proximity to human civilization than other nymphs. Farmers are grateful for the presence of alseids on their lands and often leave them offerings of mead, honey, flowers, and dates in return for protecting their flocks and making their crops more abundant.

## Nymphs

Divine servants that inhabit unspoiled corners of the world, nymphs protect places of natural power and infuse their surroundings with the magic of Nyx. Some are benevolent and aid those who live off the land, while others embody violent aspects of nature. In either case, nymphs generally avoid other sapient creatures, preferring to mind the cycles of nature, the daily interplay of wild animals, or other cosmic forces. Occasionally, though, groups of the same kind of nymphs congregate in a place of natural power or beauty. In times of special need, deities tied to facets of nature might employ nymphs as messengers, guardians, or scouts.

### Immortal Nature

A nymph doesn't require food, drink, or sleep.

```statblock
"name": "Alseid (MOT)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Good"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "14"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Persuasion": !!int "6"
"damage_resistances": "radiant"
"damage_immunities": "poison"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "passive Perception 12"
"languages": "Common, Sylvan"
"cr": "1"
"traits":
- "desc": "The alseid's spellcasting ability is Charisma (spell save DC 14). It can\
    \ innately cast the following spells, requiring no material components:\n\n1/day\
    \ each: calm emotions, lesser restoration, plant growth\n\n3/day each: cure\
    \ wounds, charm person, sleep"
  "name": "Innate Spellcasting"
- "desc": "The alseid has advantage on Dexterity (Stealth) checks made to hide while\
    \ it is in grassland."
  "name": "Hide in Plain Sight"
- "desc": "The alseid has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The alseid makes two radiant touch attacks."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (1d10\
    \ + 4) radiant damage."
  "name": "Radiant Touch"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Alseid.webp"
```
^statblock