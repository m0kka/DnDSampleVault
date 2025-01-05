---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Warlock of the Great Old One"]
---
# [Warlock of the Great Old One](3-Compendium\CLI\bestiary\humanoid/warlock-of-the-great-old-one-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 256, Volo's Guide to Monsters p. 220, The Book of Many Things*  

Warlocks of the Great Old One gain their powers through magical pacts forged with eldritch entities from strange and distant realms of existence. Some of these warlocks associate with cultists devoted to these entities, as well as Aberrations that share their goals, yet other warlocks of the Great Old One are experts at rooting out the chaos and wickedness inspired by bizarre beings from beyond the stars.

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

```statblock
"name": "Warlock of the Great Old One (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with mage armor"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "9"
- !!int "16"
- !!int "15"
- !!int "12"
- !!int "12"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "4"
"skillsaves":
  "History": !!int "4"
  "Arcana": !!int "4"
"damage_resistances": "psychic"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "any two languages, telepathy 30 ft."
"cr": "6"
"traits":
- "desc": "The warlock casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 15): \n\nAt will: detect magic, guidance, levitate,\
    \ mage armor (self only), mage hand, minor illusion, prestidigitation\n\n1/day\
    \ each: arcane gate, detect thoughts, true seeing"
  "name": "Spellcasting"
- "desc": "At the start of each of the warlock's turns, each creature of its choice\
    \ within 10 feet of it must succeed on a DC 15 Wisdom saving throw or take 10\
    \ (3d6) psychic damage, provided that the warlock isn't incapacitated."
  "name": "Whispering Aura"
"actions":
- "desc": "The warlock makes two Dagger attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage plus 10 (3d6) psychic damage."
  "name": "Dagger"
- "desc": "The warlock opens a momentary extraplanar rift within 60 feet of it. The\
    \ rift is a scream-filled, 20-foot cube. Each creature in that area must make\
    \ a DC 15 Wisdom saving throw. On a failed save, a creature takes 9 (2d8) psychic\
    \ damage and is frightened of the warlock until the start of the warlock's next\
    \ turn. On a successful save, a creature takes half as much damage and isn't frightened."
  "name": "Howling Void"
"source":
- "MPMM"
- "VGM"
- "BMT"
"image": "bestiary/tokens/MPMM/Warlock of the Great Old One.webp"
```
^statblock

## Environment

arctic, hill, mountain, underdark, urban