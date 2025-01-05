---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/
statblock: inline
aliases: ["Otherworldly Steed"]
---
# [Otherworldly Steed](3-Compendium\CLI\bestiary/otherworldly-steed-xphb.md)
*Source: Player's Handbook (2024) p. 273*  

```statblock
"name": "Otherworldly Steed (XPHB)"
"size": "Large"
"alignment": "Neutral"
"ac_class": "10 + 1 per spell level"
"stats":
- !!int "18"
- !!int "12"
- !!int "14"
- !!int "6"
- !!int "12"
- !!int "8"
"speed": "60 ft., fly 60 ft. (requires level 4+ spell)"
"senses": "passive Perception 11"
"languages": "telepathy 1 mile (works only with you)"
"traits":
- "desc": "When you regain Hit Points from a level 1+ spell, the steed regains the\
    \ same number of Hit Points if you're within 5 feet of it."
  "name": "Life Bond"
"actions":
- "desc": "Melee Attack: YourSpellAttack Bonus equals your spell attack modifier,\
    \ reach 5 ft. Hit: 1d8 + the spell's level of Radiant (Celestial), Psychic (Fey),\
    \ or Necrotic (Fiend) damage."
  "name": "Otherworldly Slam"
"bonus_actions":
- "desc": "Wisdom Saving Throw: DC equals your spell save DC, one creature within\
    \ 60 feet the steed can see. Failure: The target has the [Frightened](/3-Compendium/CLI/rules/conditions.md#Frightened)\
    \ condition until the end of your next turn."
  "name": "Fell Glare (Fiend Only; Recharges after a Long Rest)"
- "desc": "The steed teleports, along with its rider, to an unoccupied space of your\
    \ choice up to 60 feet away from itself."
  "name": "Fey Step (Fey Only; Recharges after a Long Rest)"
- "desc": "One creature within 5 feet of the steed regains a number of Hit Points\
    \ equal to 2d8 + the spell's level."
  "name": "Healing Touch (Celestial Only; Recharges after a Long Rest)"
"source":
- "XPHB"
"image": "bestiary/tokens/XPHB/Otherworldly Steed.webp"
```
^statblock