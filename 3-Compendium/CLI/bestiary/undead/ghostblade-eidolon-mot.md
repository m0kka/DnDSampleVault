---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Ghostblade Eidolon"]
---
# [Ghostblade Eidolon](3-Compendium\CLI\bestiary\undead/ghostblade-eidolon-mot.md)
*Source: Mythic Odysseys of Theros p. 222*  

When a mortal soul traumatically sacrifices its identity in order to escape the Underworld as a Returned, its identity manifests as a spirit-like eidolon. While eidolons possess many of the skills and details related to their past lives, they're disconnected from those experiences, choosing to wander the world or brood in haunts they're drawn to in death. They care nothing for morbid reunions with their lost bodies or Returned remnants.

Of the various types of eidolons, ghostblade eidolons typically arise from fallen warriors and believe they're endlessly embroiled in great battles.

```statblock
"name": "Ghostblade Eidolon (MOT)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"stats":
- !!int "16"
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "12"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "6"
  "Perception": !!int "4"
  "Acrobatics": !!int "5"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, frightened, grappled, paralyzed, petrified,\
  \ poisoned, restrained"
"senses": "passive Perception 14"
"languages": "the languages it knew in life"
"cr": "5"
"traits":
- "desc": "Attack rolls against the eidolon are made with disadvantage unless the\
    \ eidolon is incapacitated."
  "name": "Blurred Form"
- "desc": "The eidolon can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "The eidolon has advantage on saving throws against any effect that turns\
    \ undead."
  "name": "Turn Resistance"
"actions":
- "desc": "The eidolon makes two ghostblade attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 3) slashing damage plus 11 (2d10) force damage."
  "name": "Ghostblade"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Ghostblade Eidolon.webp"
```
^statblock