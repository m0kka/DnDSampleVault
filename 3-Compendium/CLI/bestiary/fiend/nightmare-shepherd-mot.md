---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
aliases: ["Nightmare Shepherd"]
---
# [Nightmare Shepherd](3-Compendium\CLI\bestiary\fiend/nightmare-shepherd-mot.md)
*Source: Mythic Odysseys of Theros p. 221*  

A nightmare shepherd is a gaunt, ashen fiend with leathery wings. It carries a shepherd's crook, which it uses to direct a flock of wandering dead that it torments and occasionally feeds upon.

```statblock
"name": "Nightmare Shepherd (MOT)"
"size": "Large"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "133"
"hit_dice": "14d10 + 56"
"stats":
- !!int "19"
- !!int "15"
- !!int "18"
- !!int "14"
- !!int "17"
- !!int "20"
"speed": "30 ft., fly 60 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "8"
"skillsaves":
  "Deception": !!int "9"
  "Perception": !!int "7"
  "Arcana": !!int "6"
  "Persuasion": !!int "9"
"damage_resistances": "cold, necrotic"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Abyssal, Common, Infernal"
"cr": "11"
"traits":
- "desc": "The shepherd's spellcasting ability is Charisma (spell save DC 17). It\
    \ can innately cast the following spells, requiring no material components:\n\n\
    1/day each: confusion, dispel magic, hold person, suggestion"
  "name": "Innate Spellcasting"
- "desc": "Undead creatures within 30 feet of the shepherd gain a +5 bonus to attack\
    \ and damage rolls. When any other creature that isn't undead or a construct starts\
    \ its turn within 30 feet of the shepherd, that creature must succeed on a DC\
    \ 17 Wisdom saving throw or take 11 (2d10) psychic damage."
  "name": "Aura of Nightmares"
- "desc": "The shepherd has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The shepherd makes two attacks: one with its claws and one with its staff."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 13 (2d8\
    \ + 4) slashing damage plus 16 (3d10) necrotic damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 11 (2d6\
    \ + 4) bludgeoning damage, or 13 (2d8 + 4) bludgeoning damage if used with two\
    \ hands, plus 26 (4d12) psychic damage."
  "name": "Staff"
- "desc": "The shepherd pulls twisted souls from the Underworld; 1d6 [shadows](/3-Compendium/CLI/bestiary/undead/shadow.md)\
    \ (without Sunlight Weakness) arise in unoccupied spaces within 20 feet of the\
    \ shepherd. The shadows act right after the shepherd on the same initiative count\
    \ and fight until they're destroyed. They disappear when the shepherd dies."
  "name": "Herd the Underworld (Recharges after a Short or Long Rest)"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Nightmare Shepherd.webp"
```
^statblock