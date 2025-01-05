---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/ooze
statblock: inline
aliases: ["Slithering Tracker"]
---
# [Slithering Tracker](3-Compendium\CLI\bestiary\ooze/slithering-tracker-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 221, Volo's Guide to Monsters p. 191*  

The quest for revenge sometimes leads those terribly aggrieved to undergo a ritual whereby they transform into bodies of semiliquid sentience known as slithering trackers. Innocuous and insidious at the same time, a slithering tracker flows into places where a normal creature can't go and brings its own brand of watery death down on its quarry.

The ritual for creating a slithering tracker is known to hags, liches, and priests who worship gods of vengeance. It can be performed only on a willing creature that hungers for revenge. The ritual sucks all the moisture from the subject's body, killing it. Yet the subject's mind lives on in the puddle that issues forth from the remains, and so too does its insatiable need for retribution.

A slithering tracker tastes the ground it courses over, seeking any trace of its prey. To kill, a slithering tracker rises up and enshrouds a creature, attempting to drown the creature while also draining it of blood.

Achieving revenge against its target doesn't end a slithering tracker's existence or its hunger for blood. Some slithering trackers remain aware of their purpose and extend their quest for vengeance to others, such as anyone who supported or befriended the original target. Most of the time, though, a tracker's mind can't cope with being trapped in liquid form, unable to communicate, and driven by the desire for blood; after fulfilling its duty, the overwhelmed creature attacks indiscriminately until it is destroyed.

```statblock
"name": "Slithering Tracker (MPMM)"
"size": "Medium"
"type": "ooze"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "14"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "16"
- !!int "19"
- !!int "15"
- !!int "10"
- !!int "14"
- !!int "11"
"speed": "30 ft., climb 30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "8"
  "Survival": !!int "6"
"damage_vulnerabilities": "cold, fire"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "blinded, deafened, exhaustion, grappled, paralyzed, petrified,\
  \ prone, restrained, unconscious"
"senses": "blindsight 120 ft., passive Perception 12"
"languages": "understands languages it knew in its previous form but can't speak"
"cr": "3"
"traits":
- "desc": "If the slithering tracker is motionless at the start of combat, it has\
    \ advantage on its initiative roll. Moreover, if a creature hasn't observed the\
    \ slithering tracker move or act, that creature must succeed on a DC 18 Intelligence\
    \ (Investigation) check to discern that the slithering tracker isn't a puddle."
  "name": "False Appearance"
- "desc": "The slithering tracker can enter an enemy's space and stop there. It can\
    \ also move through a space as narrow as 1 inch wide without squeezing."
  "name": "Liquid Form"
- "desc": "The slithering tracker can climb difficult surfaces, including upside down\
    \ on ceilings, without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) bludgeoning damage."
  "name": "Slam"
- "desc": "One Large or smaller creature that the slithering tracker can see within\
    \ 5 feet of it must succeed on a DC 13 Dexterity saving throw or be grappled (escape\
    \ DC 13). Until this grapple ends, the target is restrained and unable to breathe\
    \ unless it can breathe water. In addition, the grappled target takes 16 (3d10)\
    \ necrotic damage at the start of each of its turns. The slithering tracker can\
    \ grapple only one target at a time.\n\nWhile grappling the target, the slithering\
    \ tracker takes only half any damage dealt to it (rounded down), and the target\
    \ takes the other half."
  "name": "Life Leech"
"bonus_actions":
- "desc": "If underwater, the slithering tracker takes the Hide action, and it makes\
    \ the Dexterity (Stealth) check with advantage."
  "name": "Watery Stealth"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Slithering Tracker.webp"
```
^statblock

## Environment

underdark, urban