---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/dip
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/gnome
statblock: inline
aliases: ["Rock Gnome Recluse"]
---
# [Rock Gnome Recluse](3-Compendium\CLI\bestiary\humanoid/rock-gnome-recluse-dip.md)
*Source: Dragon of Icespire Peak p. 62*  

Rock gnome recluses are skilled in the arcane arts. They use their magical talents to create all kinds of wondrous inventions, very few of which work as intended.

```statblock
"name": "Rock Gnome Recluse (DIP)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Chaotic Neutral"
"ac": !!int "10"
"ac_class": "13 with mage armor"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "6"
- !!int "11"
- !!int "10"
- !!int "15"
- !!int "10"
- !!int "13"
"speed": "25 ft."
"skillsaves":
  "History": !!int "4"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Gnomish"
"cr": "1/4"
"traits":
- "desc": "The gnome is a 2nd-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 12, +4 to hit with spell attacks). It has the following wizard\
    \ spells prepared:\n\nCantrips (at will): mage hand, prestidigitation, ray\
    \ of frost (see \"Actions\" below)\n\n1st level (3 slots): detect magic, mage\
    \ armor, magic missile (see \"Actions\" below), shield"
  "name": "Spellcasting"
- "desc": "The gnome has advantage on Intelligence, Wisdom, and Charisma saving throws\
    \ against magic."
  "name": "Gnome Cunning"
"actions":
- "desc": "The gnome creates three magical darts. Each dart hits a creature the gnome\
    \ chooses within 120 feet of it and deals 3 (1d4 + 1) force damage."
  "name": "Magic Missile (Expends a 1st-Level Spell Slot)"
- "desc": "Ranged Spell Attack: +4 to hit, range 60 ft., one creature. Hit: 4\
    \ (1d8) cold damage, and the target's speed is reduced by 10 feet until the start\
    \ of the gnome's next turn."
  "name": "Ray of Frost"
"source":
- "DIP"
"image": "bestiary/tokens/DIP/Rock Gnome Recluse.webp"
```
^statblock