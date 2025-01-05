---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/warlock
statblock: inline
aliases: ["Neogi Master"]
---
# [Neogi Master](3-Compendium\CLI\bestiary\aberration/neogi-master-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 192, Volo's Guide to Monsters p. 180*  

Neogi masters use magic, as a result of a pact between neogi and aberrant entities they met during their journey from their home world. These entities—known by such names as Acamar, Caiphon, Gibbeth, and Hadar—resemble stars and embody the essence of evil.

## Neogi

> [!quote] A quote from Mordenkainen  
> 
> Only the malevolent or the desperate do business with neogi. I generally advise against working with beings who view you as property or prey.

A neogi looks like an outsize spider with an eel's neck and head. It can poison the body and the mind of its targets and can subjugate even beings that are physically superior.

Neogi usually dwell in far-flung locations on the Material Plane, as well as in the Astral Plane and the Ethereal Plane. They left their home world long ago to conquer and devour creatures in other realms. During this era, they dominated umber hulks and used them to build sleek, spidery ships capable of traversing the multiverse.

```statblock
"name": "Neogi Master (MPMM)"
"size": "Medium"
"type": "aberration"
"subtype": "warlock"
"alignment": "Typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"stats":
- !!int "6"
- !!int "16"
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "18"
"speed": "30 ft., climb 30 ft."
"saves":
  "Wisdom": !!int "3"
"skillsaves":
  "Intimidation": !!int "6"
  "Deception": !!int "6"
  "Perception": !!int "3"
  "Arcana": !!int "5"
  "Persuasion": !!int "6"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common, Deep Speech, Undercommon, telepathy 30 ft."
"cr": "4"
"traits":
- "desc": "The neogi casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 14):\n\nAt will: guidance, mage hand, minor illusion,\
    \ prestidigitation\n\n1/day each: dimension door, hold person, hunger of Hadar"
  "name": "Spellcasting"
- "desc": "Magical darkness doesn't impede the neogi's darkvision."
  "name": "Devil's Sight"
- "desc": "The neogi has advantage on saving throws against being charmed or frightened,\
    \ and magic can't put the neogi to sleep."
  "name": "Mental Fortitude"
- "desc": "The neogi can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The neogi makes one Bite attack and one Claw attack, or it makes two Tentacle\
    \ of Hadar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 14 (4d6) poison damage, and the target must succeed\
    \ on a DC 12 Constitution saving throw or become poisoned for 1 minute. A target\
    \ can repeat the saving throw at the end of each of its turns, ending the effect\
    \ on itself on a success."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (2d4\
    \ + 3) piercing damage."
  "name": "Claw"
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 14\
    \ (3d6 + 4) necrotic damage, and the target can't take reactions until the end\
    \ of the neogi's next turn, as a spectral tentacle clings to the target."
  "name": "Tentacle of Hadar"
"bonus_actions":
- "desc": "The neogi targets one creature it can see within 30 feet of it. The target\
    \ must succeed on a DC 14 Wisdom saving throw or be magically charmed by the neogi\
    \ for 1 day, or until the neogi dies or is more than 1 mile from the target. The\
    \ charmed target obeys the neogi's commands and can't take reactions, and the\
    \ neogi and the target can communicate telepathically with each other at a distance\
    \ of up to 1 mile. Whenever the charmed target takes damage, it can repeat the\
    \ saving throw, ending the effect on itself on a success."
  "name": "Enslave (Recharges after a Short or Long Rest)"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Neogi Master.webp"
```
^statblock

## Environment

hill, underdark