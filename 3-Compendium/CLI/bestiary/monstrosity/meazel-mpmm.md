---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Meazel"]
---
# [Meazel](3-Compendium\CLI\bestiary\monstrosity/meazel-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 177, Mordenkainen's Tome of Foes p. 214*  

Meazels are malicious hermits who fled to the Shadowfell to escape their mortal existence and contemplate their misery. There the shadows transformed them, and their bitterness made them twisted and cruel. Now hate burns in their hearts, and they resent any intrusion into their suffering, waylaying travelers who venture too close to their lairs.

The evil that corrupted meazels also imbued them with magical powers that allow them to move through shadows with ease. They can step from one pool of darkness into another one, using this talent to ambush prey. Sometimes they snatch victims around the throat with their strangling cords and then step away; other times they ferry their victims to isolated spots and then leave the hapless souls to the designs of whatever horrors lurk there.

Any creatures meazels draw through the shadows are cursed by the meazels' baleful magic. The curse acts as a beacon; sorrowsworn (which appear in this book), Undead, and other terrors sense where they are located and descend on the stranded victims to tear them apart.

```statblock
"name": "Meazel (MPMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Typically  Neutral Evil"
"ac": !!int "13"
"hp": !!int "35"
"hit_dice": "10d8 - 10"
"stats":
- !!int "8"
- !!int "17"
- !!int "9"
- !!int "14"
- !!int "13"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "3"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common"
"cr": "1"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target of the meazel's\
    \ size or smaller. Hit: 6 (1d6 + 3) bludgeoning damage, and the target is grappled\
    \ (escape DC 13 with disadvantage). Until the grapple ends, the target takes 10\
    \ (2d6 + 3) bludgeoning damage at the start of each of the meazel's turns. The\
    \ meazel can't make weapon attacks while grappling a creature in this way."
  "name": "Garrote"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 3 (1d6) necrotic damage"
  "name": "Shortsword"
- "desc": "The meazel, any equipment it is wearing or carrying, and any creature it\
    \ is grappling teleport to an unoccupied space within 500 feet of it, provided\
    \ that the starting space and the destination are in dim light or darkness. The\
    \ destination must be a place the meazel has seen before, but it need not be within\
    \ line of sight. If the destination space is occupied, the teleportation leads\
    \ to the nearest unoccupied space.\n\nAny other creature the meazel teleports\
    \ becomes cursed for 1 hour or until the curse is ended by remove curse or greater\
    \ restoration. Until this curse ends, every Undead and every creature native to\
    \ the Shadowfell within 300 feet of the cursed creature can sense it, which prevents\
    \ that creature from hiding from them."
  "name": "Shadow Teleport (Recharge 5-6)"
"bonus_actions":
- "desc": "While in dim light or darkness, the meazel takes the Hide action."
  "name": "Shadow Stealth"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Meazel.webp"
```
^statblock

## Environment

desert, forest, grassland, hill, mountain, swamp, underdark, urban