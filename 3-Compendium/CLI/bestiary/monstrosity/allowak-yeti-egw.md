---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Allowak Yeti"]
---
# [Allowak Yeti](3-Compendium\CLI\bestiary\monstrosity/allowak-yeti-egw.md)
*Source: Explorer's Guide to Wildemount p. 126*  

```statblock
"name": "Allowak Yeti (EGW)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "51"
"hit_dice": "6d10 + 18"
"stats":
- !!int "18"
- !!int "13"
- !!int "16"
- !!int "16"
- !!int "12"
- !!int "10"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "3"
"damage_immunities": "cold"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Yeti"
"cr": "3"
"traits":
- "desc": "If the yeti takes fire damage, it has disadvantage on attack rolls and\
    \ ability checks until the end of its next turn."
  "name": "Fear of Fire"
- "desc": "The yeti has advantage on Wisdom (Perception) checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The yeti has advantage on Dexterity (Stealth) checks made to hide in snowy\
    \ terrain."
  "name": "Snow Camouflage"
"actions":
- "desc": "The yeti can use its Chilling Gaze and makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage plus 3 (1d6) cold damage."
  "name": "Claw"
- "desc": "The yeti targets one creature it can see within 30 feet of it. If the target\
    \ can see the yeti, the target must succeed on a DC 13 Constitution saving throw\
    \ against this magic or take 10 (3d6) cold damage and then be paralyzed for 1\
    \ minute, unless it is immune to cold damage. The target can repeat the saving\
    \ throw at the end of each of its turns, ending the effect on itself on a success.\
    \ If the target's saving throw is successful, or if the effect ends on it, the\
    \ target is immune to the Chilling Gaze of all yetis (but not abominable yetis)\
    \ for 1 hour."
  "name": "Chilling Gaze"
"source":
- "EGW"
"image": "bestiary/tokens/EGW/Allowak Yeti.webp"
```
^statblock