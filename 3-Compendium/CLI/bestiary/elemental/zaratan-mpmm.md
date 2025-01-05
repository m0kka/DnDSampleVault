---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Zaratan"]
---
# [Zaratan](3-Compendium\CLI\bestiary\elemental/zaratan-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 278, Mordenkainen's Tome of Foes p. 201*  

When a zaratan is summoned from the Elemental Plane of Earth, the ground rises up to take the shape of a hulking, armored reptile. A zaratan's steps trigger shock waves severe enough to level structures. It expresses its rage through trumpeting calls and the occasional boulder or blast of debris it spews from its cavernous maw. If seriously injured, a zaratan retracts its appendages to gain shelter beneath its impervious shell, biding its time until it recovers and can resume its march.

```statblock
"name": "Zaratan (MPMM)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Typically  Neutral"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "307"
"hit_dice": "15d20 + 150"
"stats":
- !!int "30"
- !!int "10"
- !!int "30"
- !!int "2"
- !!int "21"
- !!int "18"
"speed": "40 ft., swim 40 ft."
"saves":
  "Charisma": !!int "11"
  "Wisdom": !!int "12"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, paralyzed, petrified, poisoned, stunned"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 15"
"languages": ""
"cr": "22"
"traits":
- "desc": "If the zaratan fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The elemental deals double damage to objects and structures (included in\
    \ Earth-Shaking Movement)."
  "name": "Siege Monster"
"actions":
- "desc": "The zaratan makes one Bite attack and one Stomp attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 20 ft., one target. Hit: 28\
    \ (4d8 + 10) force damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +17 to hit, reach 20 ft., one target. Hit: 26\
    \ (3d10 + 10) thunder damage."
  "name": "Stomp"
- "desc": "Ranged Weapon Attack: +17 to hit, range 120 ft./240 ft., one target.\
    \ Hit: 31 (6d8 + 10) force damage."
  "name": "Spit Rock"
- "desc": "The zaratan exhales rocky debris in a 90-foot cube. Each creature in that\
    \ area must make a DC 25 Dexterity saving throw. A creature takes 33 (6d10) bludgeoning\
    \ damage on a failed save, or half as much damage on a successful one. A creature\
    \ that fails the save by 5 or more is knocked prone."
  "name": "Spew Debris (Recharge 5-6)"
"bonus_actions":
- "desc": "After moving at least 10 feet on the ground, the zaratan sends a shock\
    \ wave through the ground in a 120-foot-radius circle centered on itself. That\
    \ area becomes difficult terrain for 1 minute. Each creature on the ground that\
    \ is concentrating must succeed on a DC 25 Constitution saving throw or the creature's\
    \ concentration is broken. The shock wave deals 100 thunder damage to all structures\
    \ in contact with the ground in the area. If a creature is near a structure that\
    \ collapses, the creature might be buried; a creature within half the distance\
    \ of the structure's height must make a DC 25 Dexterity saving throw. On a failed\
    \ save, the creature takes 17 (5d6) bludgeoning damage, is knocked prone, and\
    \ is trapped in the rubble. A trapped creature is restrained, requiring a successful\
    \ DC 20 Strength (Athletics) check as an action to escape. Another creature within\
    \ 5 feet of the buried creature can use its action to clear rubble and grant advantage\
    \ on the check. If three creatures use their actions in this way, the check is\
    \ an automatic success. On a successful save, the creature takes half as much\
    \ damage and doesn't fall prone or become trapped."
  "name": "Earth-Shaking Movement"
"legendary_actions":
- "desc": "The zaratan makes one Stomp attack."
  "name": "Stomp"
- "desc": "The zaratan moves up to its speed."
  "name": "Move"
- "desc": "The zaratan makes one Spit Rock attack."
  "name": "Spit (Costs 2 Actions)"
- "desc": "The zaratan retracts into its shell. Until it takes its Emerge action,\
    \ it has resistance to all damage, and it is restrained. The next time it takes\
    \ a legendary action, it must take its Revitalize or Emerge action."
  "name": "Retract (Costs 2 Actions)"
- "desc": "The zaratan can use this option only if it is retracted in its shell. It\
    \ regains 52 (5d20) hit points. The next time it takes a legendary action, it\
    \ must take its Emerge action."
  "name": "Revitalize (Costs 2 Actions)"
- "desc": "The zaratan emerges from its shell and makes one Spit Rock attack. It can\
    \ use this option only if it is retracted in its shell."
  "name": "Emerge (Costs 2 Actions)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Zaratan.webp"
```
^statblock

## Environment

desert, forest, grassland, hill, mountain, underdark