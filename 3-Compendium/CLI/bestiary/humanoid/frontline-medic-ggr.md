---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Frontline Medic"]
---
# [Frontline Medic](3-Compendium\CLI\bestiary\humanoid/frontline-medic-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

The soldiers of the Boros Legion depend on skilled healers to keep them on their feet. Frontline medics use a mix of magical healing and mundane medicine to keep their compatriots alive.

```statblock
"name": "Frontline Medic (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "20"
"ac_class": "plate armor, shield"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"stats":
- !!int "15"
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "5"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "1/4"
"traits":
- "desc": "The medic is a 3rd-level Boros spellcaster. Its spellcasting ability is\
    \ Wisdom (spell save DC 11). The medic has the following cleric spells prepared:\n\
    \nCantrips (at will): mending, resistance, spare the dying\n\n1st level\
    \ (4 slots): cure wounds, sanctuary\n\n2nd level (2 slots): aid, lesser\
    \ restoration"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Frontline Medic.webp"
```
^statblock