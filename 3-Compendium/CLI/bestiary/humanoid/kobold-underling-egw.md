---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/kobold
statblock: inline
aliases: ["Kobold Underling"]
---
# [Kobold Underling](3-Compendium\CLI\bestiary\humanoid/kobold-underling-egw.md)
*Source: Explorer's Guide to Wildemount p. 221*  

Kobolds are craven reptilian humanoids that commonly infest dungeons. They make up for their physical ineptitude with a cleverness for trap making.

```statblock
"name": "Kobold Underling (EGW)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "7"
"hit_dice": "3d6 - 3"
"stats":
- !!int "7"
- !!int "16"
- !!int "9"
- !!int "8"
- !!int "9"
- !!int "8"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Draconic"
"cr": "1/8"
"traits":
- "desc": "The kobold explodes 3 rounds after it dies, or immediately if it was killed\
    \ by a critical hit. The explosion destroys the kobold's body, leaving its equipment\
    \ behind. Each creature within 5 feet of the exploding kobold must make a DC 10\
    \ Dexterity saving throw, taking 4 (1d8) bludgeoning damage on a failed save,\
    \ or half as much damage on a successful one."
  "name": "Messy End"
- "desc": "The kobold has advantage on an attack roll against a creature if at least\
    \ one of the kobold's allies is within 5 feet of the creature and the ally isn't\
    \ incapacitated."
  "name": "Pack Tactics"
- "desc": "While in sunlight, the kobold has disadvantage on attack rolls, as well\
    \ as on Wisdom (Perception) checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. Hit:\
    \ 6 (1d6 + 3) piercing damage."
  "name": "Hand Crossbow"
"source":
- "EGW"
"image": "bestiary/tokens/EGW/Kobold Underling.webp"
```
^statblock