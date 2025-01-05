---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Galvanic Blastseeker"]
---
# [Galvanic Blastseeker](3-Compendium\CLI\bestiary\humanoid/galvanic-blastseeker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 243*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Galvanic Blastseeker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "10"
- !!int "17"
- !!int "14"
- !!int "19"
- !!int "10"
- !!int "13"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
"skillsaves":
  "Perception": !!int "3"
  "Acrobatics": !!int "6"
  "Arcana": !!int "7"
"damage_resistances": "lightning, thunder"
"senses": "passive Perception 13"
"languages": "Common and Primordial, plus any one language"
"cr": "5"
"traits":
- "desc": "The blastseeker's innate spellcasting ability is Intelligence (spell save\
    \ DC 15, +7 to hit with spell attacks). The blastseeker can innately cast the\
    \ following spells, requiring no components other than its Izzet gear, which doesn't\
    \ function for others:\n\n1/day: stoneskin\n\n3/day each: levitate, lightning\
    \ bolt, thunderwave"
  "name": "Innate Spellcasting"
- "desc": "When the blastseeker casts lightning bolt or thunderwave, it can roll a\
    \ die. On an odd number, the blastseeker takes 9 (2d8) force damage. On an even\
    \ number, the spell also deals 9 (2d8) lightning damage to each target that fails\
    \ its saving throw."
  "name": "Galvanic Overcast (Recharge 5-6)"
- "desc": "When the blastseeker casts lightning bolt or thunderwave, all other creatures\
    \ within 10 feet of the blastseeker each take 3 lightning damage."
  "name": "Heart of the Storm"
- "desc": "The blastseeker can use a bonus action to fly up to 10 feet without provoking\
    \ opportunity attacks."
  "name": "Gust-Propelled Leap"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d6) piercing damage, or 4 (1d8) piercing damage\
    \ if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Galvanic Blastseeker.webp"
```
^statblock