---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Wurm"]
---
# [Wurm](3-Compendium\CLI\bestiary\monstrosity/wurm-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 225*  

Wurms are huge creatures that resemble limbless, wingless dragons. They burrow through the earth and eat virtually anything they come across, and their movement accounts for much of the destruction in the rubblebelt regions of Ravnica. A wurm burrows through loose earth by using deep sonic vibrations to liquefy the earth in front of it and swim through the area. The soil resolidifies and closes behind it. Moving through rock is slower and more difficult, and the wurm leaves a tunnel in its wake. The Gruul Clans appreciate the devastation wurms can create, and the clans sometimes lure them into civilized areas where the destruction can be vast.

```statblock
"name": "Wurm (GGR)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"stats":
- !!int "24"
- !!int "10"
- !!int "22"
- !!int "3"
- !!int "12"
- !!int "4"
"speed": "50 ft., burrow 30 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "11"
"senses": "blindsight 60 ft., tremorsense 60 ft., passive Perception 11"
"languages": ""
"cr": "14"
"traits":
- "desc": "The wurm deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "The wurm creates earth tremors as it moves overland or underground. Any\
    \ creature that comes within 30 feet of the moving wurm for the first time on\
    \ a turn must succeed on a DC 20 Dexterity saving throw or take 10 (3d6) bludgeoning\
    \ damage and fall prone. Any structure or object anchored to the ground that comes\
    \ within 30 feet of the moving wurm for the first time on a turn takes 10 (3d6)\
    \ force damage."
  "name": "Earth Tremors"
- "desc": "The wurm can burrow through solid rock at half its burrow speed and leaves\
    \ a 10-foot-diameter tunnel in its wake."
  "name": "Tunneler"
"actions":
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 24\
    \ (5d6 + 7) piercing damage. If the target is a Medium or smaller creature, it\
    \ must succeed on a DC 20 Dexterity saving throw or be swallowed by the wurm.\
    \ A swallowed creature is blinded and restrained, has total cover against attacks\
    \ and other effects outside the wurm, and takes 17 (5d6) acid damage at the start\
    \ of each of the wurm's turns. If the wurm takes 30 damage or more on a single\
    \ turn from a creature inside it, the wurm must succeed on a DC 21 Constitution\
    \ saving throw at the end of that turn or regurgitate all swallowed creatures,\
    \ which fall prone in a space within 10 feet of the wurm. If the wurm dies, a\
    \ swallowed creature is no longer restrained by it and can escape from the corpse\
    \ by using 20 feet of movement, exiting prone."
  "name": "Bite"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Wurm.webp"
```
^statblock