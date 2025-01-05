---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Returned Kakomantis"]
---
# [Returned Kakomantis](3-Compendium\CLI\bestiary\undead/returned-kakomantis-mot.md)
*Source: Mythic Odysseys of Theros p. 240*  

Although the dead typically recall little of their lives, some have an obsession with magic that survives both death and rebirth as a Returned. These Returned, called kakomanteis, use their magical prowess to control the energy that suffuses the Underworld.

Returned have escaped the Underworld and dwell among the living once more, but their second lives are rarely what they expected—not that they remember what it was they expected. As a result of having followed the Path of Phenax (see chapter 4), the Returned lose their identities, which manifest as separate beings known as eidolons. The experience of escaping the Underworld also causes them to lose their faces, which become expressionless surfaces with empty eye sockets and gaping mouths. These blank surfaces they cover with distinctive golden masks.

Returned reenter the world blank and undead. No longer possessing the ability to form long-term memories, they generally can't build meaningful relationships or establish new lives. Instead, most experience fleeting emotions and follow hollow routines, their existences reduced to shadow plays without weight or substance.

```statblock
"name": "Returned Kakomantis (MOT)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "10"
- !!int "17"
- !!int "14"
- !!int "13"
- !!int "12"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "2"
  "Stealth": !!int "5"
  "Acrobatics": !!int "5"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "passive Perception 11"
"languages": "the languages it knew in life"
"cr": "4"
"traits":
- "desc": "If another creature deals damage to the Returned, the Returned makes attack\
    \ rolls with advantage until the end of its next turn."
  "name": "Fleeting Anger"
- "desc": "The Returned has advantage on saving throws against any effect that turns\
    \ undead."
  "name": "Turn Resistance"
- "desc": "The Returned is immune to any effect that would sense its emotions or read\
    \ its thoughts. Wisdom (Insight) checks to ascertain the Returned's intentions\
    \ or sincerity are made with disadvantage."
  "name": "Unreadable Face"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 10 (3d6) poison damage."
  "name": "Shortsword"
- "desc": "Ranged Spell Attack: +4 to hit, range 120 ft., one creature. Hit: 13\
    \ (2d8 + 2) necrotic damage, and the target can't regain hit points until the\
    \ start of the Returned's next turn. If the target is missing any of its hit points,\
    \ it instead takes 17 (2d12 + 2) necrotic damage."
  "name": "Underworld Bolt"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Returned Kakomantis.webp"
```
^statblock