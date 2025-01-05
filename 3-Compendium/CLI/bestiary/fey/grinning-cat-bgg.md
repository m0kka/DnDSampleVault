---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Grinning Cat"]
---
# [Grinning Cat](3-Compendium\CLI\bestiary\fey/grinning-cat-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 156*  

Grinning cats are mischievous Fey who delight in pestering and misleading travelers. They resemble oversized domestic cats with long, needlelike claws, but they're distinguished by the wide, toothy smiles that give them their name.

Grinning cats often dwell in or near giants' enclaves. They spend much of their time invisible, lounging on tree branches until prey—or a potential conversation partner—wanders by. While trading riddles or witticisms, a cat often decides to reveal its grin, its tail, or sometimes its whole head to confuse or intimidate the creature it's talking to.

A grinning cat can be persuaded to bestow one of its whiskers as a gift. A creature holding a whisker can use it to cast the misty step spell once, then the whisker turns to smoke and is destroyed. If a grinning cat is slain, `2d12` of its whiskers can be retrieved for this purpose.

> [!quote] A quote from Bigby  
> 
> My one and only interaction with a grinning cat made me want to wipe the smirk off that thing's face with a great big clenched fist, if you get my meaning.

> [!quote] A quote from Diancastra  
> 
> Trust me when I tell you that the cat was every bit as annoyed as you were, my friend.


```statblock
"name": "Grinning Cat (BGG)"
"size": "Large"
"type": "fey"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "7d10 + 7"
"stats":
- !!int "14"
- !!int "15"
- !!int "13"
- !!int "15"
- !!int "14"
- !!int "16"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Sylvan"
"cr": "1"
"traits":
- "desc": "The grinning cat has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (1d10\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) slashing damage. If the grinning cat was invisible before it attacked,\
    \ the target must succeed on a DC 12 Strength saving throw or have the prone condition.\
    \ If the target has the prone condition, the cat can make a Bite attack against\
    \ it as a bonus action."
  "name": "Claws"
- "desc": "The grinning cat magically becomes invisible for 1 hour or until it attacks,\
    \ gradually fading away over the course of its turn. It can choose to leave part\
    \ of its body visible, such as its tail, its head, or its grinning mouth. Any\
    \ equipment the cat wears or carries is invisible with it."
  "name": "Fade Away"
"bonus_actions":
- "desc": "The grinning cat becomes visible or makes part of its body visible. Any\
    \ equipment the cat wears or carries on a visible part of its body also becomes\
    \ visible."
  "name": "Fade Back"
- "desc": "The grinning cat teleports, along with any equipment it is wearing or carrying,\
    \ up to 60 feet to an unoccupied space it can see."
  "name": "Grinning Step"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Grinning Cat.webp"
```
^statblock