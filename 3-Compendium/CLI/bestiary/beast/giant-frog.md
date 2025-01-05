---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Giant Frog"]
---
# [Giant Frog](3-Compendium\CLI\bestiary\beast/giant-frog.md)
*Source: Monster Manual p. 325, Explorer's Guide to Wildemount. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Giant Frog"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "18"
"hit_dice": "4d8"
"stats":
- !!int "12"
- !!int "13"
- !!int "11"
- !!int "2"
- !!int "10"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "2"
"senses": "darkvision 30 ft., passive Perception 12"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The frog can breathe air and water."
  "name": "Amphibious"
- "desc": "The frog's long jump is up to 20 feet and its high jump is up to 10 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) piercing damage, and the target is grappled (escape DC 11). Until this\
    \ grapple ends, the target is restrained, and the frog can't bite another target."
  "name": "Bite"
- "desc": "The frog makes one bite attack against a Small or smaller target it is\
    \ grappling. If the attack hits, the target is swallowed, and the grapple ends.\
    \ The swallowed target is blinded and restrained, it has total cover against attacks\
    \ and other effects outside the frog, and it takes 5 (2d4) acid damage at the\
    \ start of each of the frog's turns. The frog can have only one target swallowed\
    \ at a time. If the frog dies, a swallowed creature is no longer restrained by\
    \ it and can escape from the corpse using 5 feet of movement, exiting prone."
  "name": "Swallow"
"source":
- "MM"
- "EGW"
"image": "bestiary/tokens/MM/Giant Frog.webp"
```
^statblock

## Environment

forest, swamp