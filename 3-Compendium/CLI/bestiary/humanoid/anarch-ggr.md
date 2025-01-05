---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Anarch"]
---
# [Anarch](3-Compendium\CLI\bestiary\humanoid/anarch-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 239*  

The rank-and-file members of the Gruul Clans, called anarchs, despise civilization and have sworn to tear down both its physical structures and its institutions. Anarchs scavenge everything, from the hide armor they wear to the weapons they wield. As they pick through the refuse of the rubblebelts, they sometimes come across magic items and other valuable treasures.

```statblock
"name": "Anarch (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "hide armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "13"
- !!int "12"
- !!int "9"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
  "Survival": !!int "2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/4"
"traits":
- "desc": "As a bonus action, the anarch can move up to its speed toward a hostile\
    \ creature it can see."
  "name": "Aggressive"
- "desc": "The anarch deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage, or 7 (1d10 + 2) piercing damage if used with two hands."
  "name": "Spiked Club"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Anarch.webp"
```
^statblock