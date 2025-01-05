---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
aliases: ["Homunculus"]
---
# [Homunculus](3-Compendium\CLI\bestiary\construct/homunculus.md)
*Source: Monster Manual p. 188, Eberron: Rising from the Last War, Mythic Odysseys of Theros, The Book of Many Things. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Shaping a mixture of clay, ash, mandrake root, and blood, one can channel rare ritual magic to create a faithful, squirrel-sized companion.

A homunculus is a construct that acts as an extension of its creator, with the two sharing thoughts, senses, and language through a mystical bond. A master can have only one homunculus at a time (attempts to create another one always fail), and when its master dies, the homunculus also dies.

## Shared Mind

A homunculus knows everything its creator knows, including all the languages the creator can speak and read. Likewise, everything the construct senses is known to its master, even over great distances, provided both are on the same plane. Functioning as a spy, a scout, an emissary, or a messenger, a homunculus is an invaluable servant for a spellcaster engaged in secret experimentation or adventuring.

```statblock
"name": "Homunculus"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "5"
"hit_dice": "2d4"
"stats":
- !!int "4"
- !!int "15"
- !!int "11"
- !!int "10"
- !!int "10"
- !!int "7"
"speed": "20 ft., fly 40 ft."
"damage_immunities": "poison"
"condition_immunities": "charmed, poisoned"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "0"
"traits":
- "desc": "While the homunculus is on the same plane of existence as its master, it\
    \ can magically convey what it senses to its master, and the two can communicate\
    \ telepathically."
  "name": "Telepathic Bond"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 1 piercing\
    \ damage, and the target must succeed on a DC 10 Constitution saving throw or\
    \ be poisoned for 1 minute. If the saving throw fails by 5 or more, the target\
    \ is instead poisoned for 5 (1d10) minutes and unconscious while poisoned in this\
    \ way."
  "name": "Bite"
"source":
- "MM"
- "ERLW"
- "MOT"
- "BMT"
"image": "bestiary/tokens/MM/Homunculus.webp"
```
^statblock