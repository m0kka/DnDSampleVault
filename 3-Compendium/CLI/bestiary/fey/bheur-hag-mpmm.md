---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Bheur Hag"]
---
# [Bheur Hag](3-Compendium\CLI\bestiary\fey/bheur-hag-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 62, Volo's Guide to Monsters p. 160*  

Bheur hags live in wintry lands, favoring snowy mountains. These hags become more active during winter, using their ice and weather magic to make life miserable for nearby settlements.

A bheur hag's skin has the bluish hue of a person who has frozen to death. The hag's hair is white, and the hag is emaciated, with pale eyes surrounded by bruise-colored flesh. A bheur hag carries a twisted gray wooden staff that can be ridden like a flying broom and that augments the hag's magic.

Bheur hags are attracted to selfish actions inspired by deadly cold, such as murdering a traveler for a winter coat or chopping down a dryad's grove for firewood. These actions are especially sweet to a bheur if they are unwarranted, such as a greedy merchant hoarding excess food for the winter while others starve. Bheurs use their ability to manipulate weather to batter villages with freezing cold, hoping to instill a despair that turns folk against each other.

In combat, a bheur hag also strives to inspire horror. When near a recently slain foe, the hag may forgo an attack to feed on the corpse. The sight of this butchery is enough to terrify most witnesses.

```statblock
"name": "Bheur Hag (MPMM)"
"size": "Medium"
"type": "fey"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "13"
- !!int "16"
- !!int "14"
- !!int "12"
- !!int "13"
- !!int "16"
"speed": "30 ft., fly 50 ft. (hover, Graystaff magic)"
"saves":
  "Wisdom": !!int "4"
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "6"
  "Perception": !!int "4"
  "Survival": !!int "4"
"damage_immunities": "cold"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Auran, Common, Giant"
"cr": "7"
"traits":
- "desc": "While holding or riding the graystaff, the hag casts one of the following\
    \ spells, requiring no material components and using Charisma as the spellcasting\
    \ ability (spell save DC 14):\n\nAt will: hold person\n\n1/day each: cone\
    \ of cold, ice storm, wall of ice"
  "name": "Spellcasting"
- "desc": "The hag can cast the control weather spell, requiring no material components\
    \ and using Charisma as the spellcasting ability."
  "name": "Control Weather (1/Day)"
- "desc": "The hag carries a graystaff, a magic staff. The hag can use its flying\
    \ speed only while astride the staff. If the staff is lost or destroyed, the hag\
    \ must craft another, which takes a year and a day. Only a bheur hag can use a\
    \ graystaff"
  "name": "Graystaff Magic"
- "desc": "The hag can move across and climb icy surfaces without needing to make\
    \ an ability check, and difficult terrain composed of ice or snow doesn't cost\
    \ the hag extra moment."
  "name": "Ice Walk"
"actions":
- "desc": "The hag makes two Slam or Frost Shard attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 10 (2d8\
    \ + 1) bludgeoning damage plus 18 (4d8) cold damage."
  "name": "Slam"
- "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 30 (6d8\
    \ + 3) cold damage, and the target's speed is reduced by 10 feet until the start\
    \ of the hag's next turn."
  "name": "Frost Shard"
- "desc": "The hag feeds on the corpse of one enemy within reach that died within\
    \ the past minute. Each creature of the hag's choice that is within 60 feet and\
    \ able to see the feeding must succeed on a DC 15 Wisdom saving throw or be frightened\
    \ of the hag for 1 minute. While frightened in this way, a creature is incapacitated,\
    \ can't understand what others say, can't read, and speaks only in gibberish.\
    \ A creature can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success. If a creature's saving throw is successful\
    \ or the effect ends for it, the creature is immune to the hag's Horrific Feast\
    \ for the next 24 hours."
  "name": "Horrific Feast"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Bheur Hag.webp"
```
^statblock

## Environment

arctic