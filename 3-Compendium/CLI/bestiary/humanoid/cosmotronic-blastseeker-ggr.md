---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Cosmotronic Blastseeker"]
---
# [Cosmotronic Blastseeker](3-Compendium\CLI\bestiary\humanoid/cosmotronic-blastseeker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 242*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Cosmotronic Blastseeker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"ac_class": "chain shirt"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "14"
- !!int "15"
- !!int "16"
- !!int "18"
- !!int "9"
- !!int "12"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "3"
  "Perception": !!int "1"
  "Arcana": !!int "6"
"senses": "passive Perception 11"
"languages": "any one language (usually Common)"
"cr": "4"
"traits":
- "desc": "The blastseeker's innate spellcasting ability is Intelligence (spell save\
    \ DC 14, +6 to hit with spell attacks). The blastseeker can innately cast the\
    \ following spells, requiring no components other than its Izzet gear, which doesn't\
    \ function for others:\n\n2/day: fireball\n\n3/day each: scorching ray,\
    \ shield, thunderwave"
  "name": "Innate Spellcasting"
- "desc": "When the blastseeker rolls damage for a spell, it can reroll up to four\
    \ dice of damage. It must use the new dice."
  "name": "Empowered Spell (3/Day)"
- "desc": "The blastseeker makes one attack roll, ability check, or saving throw with\
    \ advantage."
  "name": "Tides of Chaos (1/Day)"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage, or 7 (1d10 + 2) bludgeoning damage if used with two\
    \ hands."
  "name": "Warhammer"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Cosmotronic Blastseeker.webp"
```
^statblock