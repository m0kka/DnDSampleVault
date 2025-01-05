---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/simic-hybrid
statblock: inline
aliases: ["Hybrid Spy"]
---
# [Hybrid Spy](3-Compendium\CLI\bestiary\humanoid/hybrid-spy-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 218*  

## Simic Hybrids

The Guardian Project is a consequence of increasing tension within the Simic Combine as the threat of interguild conflict looms. Believing that the Simic must be prepared to fight for their lives when that conflict comes to a head, biomancers have created soldiers to help defend the guild. These hybrids (also called guardians, after the name of the project) are created from human, vedalken, and elf guild members who volunteer to be transformed.

```statblock
"name": "Hybrid Spy (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "Simic hybrid"
"alignment": "Neutral Good"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "13"
- !!int "14"
- !!int "9"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common plus any one language"
"cr": "1/2"
"traits":
- "desc": "The hybrid has advantage on Dexterity (Stealth) checks made to hide."
  "name": "Chameleon Skin"
- "desc": "The hybrid can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The hybrid makes two shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Hybrid Spy.webp"
```
^statblock