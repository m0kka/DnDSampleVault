---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/construct
statblock: inline
aliases: ["Colossus of Akros"]
---
# [Colossus of Akros](3-Compendium\CLI\bestiary\construct/colossus-of-akros-mot.md)
*Source: Mythic Odysseys of Theros p. 218*  

An enormous golem of bronze and iron overlooks the path leading to the polis of Akros. Though it is rarely called on to defend the polis, the sight of its towering form is enough to ease the minds of the populace. In truly desperate times, priests of Purphoros work their magic to call the colossus to life, whereupon the earth rumbles as it steps down from its twin plinths to place itself before the threat.

```statblock
"name": "Colossus of Akros (MOT)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "350"
"hit_dice": "20d20 + 140"
"stats":
- !!int "28"
- !!int "10"
- !!int "25"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "60 ft."
"saves":
  "Strength": !!int "16"
  "Constitution": !!int "14"
"skillsaves":
  "Athletics": !!int "16"
  "Perception": !!int "7"
"damage_immunities": "fire; poison; psychic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, poisoned,\
  \ stunned, unconscious"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "understands Common and Celestial but can't speak"
"cr": "23"
"traits":
- "desc": "When the colossus drops to 0 hit points, it crumbles and is destroyed.\
    \ Any creature on the ground within 30 feet of the crumbling statue must make\
    \ a DC 22 Dexterity saving throw, taking 22 (4d10) bludgeoning damage and 22 (4d10)\
    \ fire damage on a failed save, or half as much damage on a successful one."
  "name": "Crumbling Destruction"
- "desc": "Whenever the colossus is subjected to fire damage, it takes no damage and\
    \ instead regains a number of hit points equal to the fire damage dealt."
  "name": "Fire Absorption"
- "desc": "The colossus is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The colossus's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "The colossus deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The colossus of Akros makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +16 to hit, reach 15 ft., or range 200/600\
    \ ft., one target. Hit: 23 (4d6 + 9) piercing damage, or 27 (4d8 + 9) piercing\
    \ damage if used with two hands to make a melee attack. If the colossus makes\
    \ a ranged attack with this spear, the spear magically returns to its hand after\
    \ the attack."
  "name": "Spear"
- "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one target. Hit: 36\
    \ (6d8 + 9) slashing damage."
  "name": "Sword"
- "desc": "Magical flames issue from the colossus toward up to three creatures the\
    \ colossus can see within 90 feet of it. Each target must make a DC 24 Dexterity\
    \ saving throw, taking 36 (8d8) fire damage on a failed save, or half as much\
    \ damage on a successful one. On a failed save, a target also magically catches\
    \ fire for 1 minute. At the end of each of its turns thereafter, the burning target\
    \ repeats the saving throw. It takes 18 (4d8) fire damage on a failed save, and\
    \ the effect ends on a successful one."
  "name": "Flames of Akros (Recharge 6)"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Colossus of Akros.webp"
```
^statblock