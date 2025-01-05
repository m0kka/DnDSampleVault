---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Kraken Priest"]
---
# [Kraken Priest](3-Compendium\CLI\bestiary\monstrosity/kraken-priest-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 167, Volo's Guide to Monsters p. 215*  

A kraken can seem godlike to folk who have faced its fury. Those who mistake its might for divine power and those who seek to appease the monster through veneration are sometimes rewarded with power, to serve thereafter as kraken priests.

Every kraken priest undergoes a change in appearance that reflects the kraken's influence, although each one differs in how their reverence is displayed. One kraken priest might have ink-black eyes and a suckered tentacle for a tongue, while another has a featureless face and a body covered in eyes and mouths that dribble seawater. These horrific manifestations intensify when the kraken possesses its minion to utter dire pronouncements.

```statblock
"name": "Kraken Priest (MPMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "12"
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "14"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "5"
"senses": "passive Perception 15"
"languages": "any two languages"
"cr": "5"
"traits":
- "desc": "The priest casts one of the following spells, requiring no material components\
    \ and using Wisdom as the spellcasting ability (spell save DC 13):\n\nAt will:\
    \ command, create or destroy water\n\n1/day: Evard's black tentacles\n\n3/day\
    \ each: control water, darkness, water breathing, water walk"
  "name": "Spellcasting"
- "desc": "The priest can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "The priest makes two Thunderous Touch or Thunderbolt attacks."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one target. Hit: 27 (5d10)\
    \ thunder damage."
  "name": "Thunderous Touch"
- "desc": "Ranged Spell Attack: +5 to hit, range 60 ft., one target. Hit: 11 (2d10)\
    \ lightning damage plus 11 (2d10) thunder damage, and the target is knocked prone."
  "name": "Thunderbolt"
- "desc": "A kraken speaks through the priest with a thunderous voice audible within\
    \ 300 feet. Creatures of the priest's choice that can hear the kraken's words\
    \ (which are spoken in Abyssal, Infernal, or Primordial) must succeed on a DC\
    \ 14 Wisdom saving throw or be frightened of the priest for 1 minute. A frightened\
    \ target can repeat the saving throw at the end of each of its turns, ending the\
    \ effect on itself on a success."
  "name": "Voice of the Kraken (Recharges after a Short or Long Rest)"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Kraken Priest.webp"
```
^statblock

## Environment

coastal, underwater