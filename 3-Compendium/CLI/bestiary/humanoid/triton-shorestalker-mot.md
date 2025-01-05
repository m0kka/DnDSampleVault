---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/triton
statblock: inline
aliases: ["Triton Shorestalker"]
---
# [Triton Shorestalker](3-Compendium\CLI\bestiary\humanoid/triton-shorestalker-mot.md)
*Source: Mythic Odysseys of Theros p. 244*  

Some insults don't wash away with the tides. When surface dwellers threaten the safety of triton communities, impede upon Thassa's holiest depths, or steal the treasures of the deep, triton shorestalkers seek vengeance. Using speed and poison harvested from deadly sea beasts, these triton assassins slip into shallow waters and strike when least expected. Often, surface dwellers don't even realize they've been attacked by shorestalkers, chalking disappearances and deaths up to the innumerable dangers of the sea.

Clever, far-ranging people of the sea, tritons live rich lives unknown to most land-dwelling individuals. While the waves separate most tritons from land-dwellers, occasionally the inhabitants of the surface and the deep come into conflict. In such cases, tritons prove skilled at sabotaging ocean-going vessels, employing water-based magic, and otherwise whipping up the fury of the sea. Few dare insult tritons in their home environment, but those who do and survive often learn that the tritons' wrath doesn't end at the shore.

```statblock
"name": "Triton Shorestalker (MOT)"
"size": "Medium"
"type": "humanoid"
"subtype": "triton"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "10"
- !!int "15"
- !!int "11"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "5"
  "Perception": !!int "4"
"damage_resistances": "cold"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Primordial"
"cr": "2"
"traits":
- "desc": "The triton's spellcasting ability is Wisdom (spell save DC 12). It can\
    \ innately cast the following spells, requiring no material components:\n\n1/day\
    \ each: fog cloud, gust of wind"
  "name": "Innate Spellcasting"
- "desc": "The triton can breathe air and water."
  "name": "Amphibious"
- "desc": "The triton can take the Disengage or Hide actions as a bonus action on\
    \ each of its turns."
  "name": "Nimble Escape"
"actions":
- "desc": "The triton makes two urchin-spine shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 10 (3d6) poison damage. If the damage reduces a creature\
    \ to 0 hit points, that creature is stable but poisoned for 1 hour, even after\
    \ regaining hit points, and is paralyzed while poisoned in this way."
  "name": "Urchin-Spine Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 30/60 ft., one target. Hit:\
    \ 5 (1d4 + 3) piercing damage plus 10 (3d6) poison damage."
  "name": "Poisoned Spine"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Triton Shorestalker.webp"
```
^statblock