---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Bandit"]
---
# [Bandit](3-Compendium\CLI\bestiary\humanoid/bandit.md)
*Source: Monster Manual p. 343, Dragon of Icespire Peak, Eberron: Rising from the Last War, Explorer's Guide to Wildemount, The Book of Many Things. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Bandits rove in gangs and are sometimes led by thugs, veterans, or spellcasters. Not all bandits are evil. Oppression, drought, disease, or famine can often drive otherwise honest folk to a life of banditry.

Pirates are bandits of the high seas. They might be freebooters interested only in treasure and murder, or they might be privateers sanctioned by the crown to attack and plunder an enemy nation's vessels.

```statblock
"name": "Bandit"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "12"
"ac_class": "leather armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "11"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/8"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d8 + 1) piercing damage."
  "name": "Light Crossbow"
"source":
- "MM"
- "DIP"
- "ERLW"
- "EGW"
- "BMT"
"image": "bestiary/tokens/MM/Bandit.webp"
```
^statblock

## Environment

coastal, hill, arctic, urban, forest, desert