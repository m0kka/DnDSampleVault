---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Stalker of Baphomet"]
---
# [Stalker of Baphomet](3-Compendium\CLI\bestiary\fiend/stalker-of-baphomet-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 178*  

Demon worship is rare among stone giants; the destructive tendency of demons is the antithesis of the artistry that drives the stone giant's ordning. The Horned King, Baphomet, is an exception. Though he is a merciless hunter, the Prince of Beasts also crafts complex mazes as his hunting grounds. Stone giants can become mesmerized by the demon lord's mazes and enter his service. These giants can continue pursuing art by crafting mazes, while satiating their bloodlust by hunting in them.

Baphomet rewards his most faithful cultists with transformation into demonic stalkers. Such a giant grows an elaborate crown of six horns, and Baphomet gives the stone giant a magic glaive and the ability to call up horns of stone from the earth.

```statblock
"name": "Stalker of Baphomet (BGG)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"stats":
- !!int "25"
- !!int "17"
- !!int "22"
- !!int "13"
- !!int "16"
- !!int "12"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "7"
"skillsaves":
  "Athletics": !!int "15"
  "Stealth": !!int "11"
  "Perception": !!int "7"
"condition_immunities": "charmed, frightened"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Abyssal, Giant"
"cr": "12"
"traits":
- "desc": "The stalker casts one of the following spells, requiring no spell components\
    \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\n1/day\
    \ each: meld into stone, stone shape, wall of stone"
  "name": "Spellcasting"
- "desc": "The stalker can perfectly recall any path it has traveled."
  "name": "Labyrinthine Recall"
- "desc": "The stalker has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The stalker makes two Glaive attacks or two Rock attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one target. Hit: 18\
    \ (2d10 + 7) slashing damage plus 9 (2d8) force damage."
  "name": "Glaive"
- "desc": "Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. Hit:\
    \ 23 (3d10 + 7) bludgeoning damage. If the target is a Large or smaller creature,\
    \ it must succeed on a DC 19 Strength saving throw or have the prone condition.\
    \ After the stalker throws the rock, roll a d6; on a roll of 3 or lower, the stalker\
    \ has no more rocks to throw."
  "name": "Rock"
- "desc": "The stalker causes the earth to churn at a point on the ground it can see\
    \ within 60 feet of itself. Six horn-shaped stones erupt in a 30-foot-radius,\
    \ 30-foot-high cylinder centered on that point and then crumble to dust.\n\nEach\
    \ creature in that area must make a DC 15 Dexterity saving throw. On a failed\
    \ save, a creature takes 33 (6d10) piercing damage and is pushed up to 30 feet\
    \ upward and then falls. On a successful save, a creature takes half as much damage\
    \ only."
  "name": "Erupting Horns (Recharge 5-6)"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Stalker of Baphomet.webp"
```
^statblock