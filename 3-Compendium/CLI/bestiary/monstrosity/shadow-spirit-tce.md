---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tce
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Shadow Spirit"]
---
# [Shadow Spirit](3-Compendium\CLI\bestiary\monstrosity/shadow-spirit-tce.md)
*Source: Tasha's Cauldron of Everything p. 114*  

```statblock
"name": "Shadow Spirit (TCE)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac_class": "11 + the level of the spell (natural armor)"
"stats":
- !!int "13"
- !!int "16"
- !!int "15"
- !!int "4"
- !!int "10"
- !!int "16"
"speed": "40 ft."
"damage_resistances": "necrotic"
"condition_immunities": "frightened"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages you speak"
"traits":
- "desc": "The spirit has advantage on attack rolls against frightened creatures."
  "name": "Terror Frenzy (Fury Only)"
- "desc": "Any creature, other than you, that starts its turn within 5 feet of the\
    \ spirit has its speed reduced by 20 feet until the start of that creature's next\
    \ turn."
  "name": "Weight of Sorrow (Despair Only)"
"actions":
- "desc": "The spirit makes a number of attacks equal to half this spell's level (rounded\
    \ down)."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: YourSpellAttack to hit, reach 5 ft., one target.\
    \ Hit: 1d12 + 3 + the spell's level cold damage."
  "name": "Chilling Rend"
- "desc": "The spirit screams. Each creature within 30 feet of it must succeed on\
    \ a Wisdom saving throw against your spell save DC or be frightened for 1 minute.\
    \ The frightened creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Dreadful Scream (1/Day)"
"bonus_actions":
- "desc": "While in dim light or darkness, the spirit takes the Hide action."
  "name": "Shadow Stealth (Fear Only)"
"source":
- "TCE"
"image": "bestiary/tokens/TCE/Shadow Spirit.webp"
```
^statblock