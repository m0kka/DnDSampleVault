---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/shifter
statblock: inline
aliases: ["Shifter"]
---
# [Shifter](3-Compendium\CLI\bestiary\humanoid/shifter-erlw.md)
*Source: Eberron: Rising from the Last War p. 319*  

Shifters are tied to primal spirits, which most of them refer to as the beast within. They are lithe of form and have bestial features: large eyes, flat noses, pointed ears, and light fur over much of their bodies. When a shifter fully embraces the beast within by "shifting," these features become even more pronounced.

```statblock
"name": "Shifter (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "shifter"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "leather armor"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"stats":
- !!int "12"
- !!int "16"
- !!int "14"
- !!int "11"
- !!int "15"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Nature": !!int "2"
  "Insight": !!int "4"
  "Perception": !!int "4"
  "Acrobatics": !!int "5"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common"
"cr": "1/2"
"traits":
- "desc": "As a bonus action, the shifter takes on a more bestial form for 1 minute\
    \ or until it dies. The shifter gains 5 temporary hit points. It can make a bite\
    \ attack when it activates this trait and also as a bonus action on each of its\
    \ turns while in its bestial form."
  "name": "Shifting (Recharges after a Short or Long Rest)"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 5 (1d4\
    \ + 3) piercing damage."
  "name": "Bite"
"source":
- "ERLW"
"image": "bestiary/tokens/ERLW/Shifter.webp"
```
^statblock