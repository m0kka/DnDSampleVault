---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Spotted Lion"]
---
# [Spotted Lion](3-Compendium\CLI\bestiary\beast/spotted-lion-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 177*  

> [!quote] A quote from Bigby  
> 
> When it comes to infiltrating giant steadings, I must admit that spotted lions are in some ways preferable to, say, dire wolves or cave bears. Namely, if they're well fed, they're more likely to stretch and yawn than they are to raise an alarm when they spot you.

Roughly twice the size of a common lion, a spotted lion has a dusky coat and mane, both speckled with charcoal-colored spots. Spotted lions gather in prides to hunt enormous prey ranging from giant elk to mammoths. Stone and cloud giants often keep these massive beasts as pets and hunting companions.

```statblock
"name": "Spotted Lion (BGG)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "66"
"hit_dice": "7d12 + 21"
"stats":
- !!int "23"
- !!int "14"
- !!int "17"
- !!int "5"
- !!int "13"
- !!int "10"
"speed": "60 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "3"
"traits":
- "desc": "The lion has advantage on an attack roll against a creature if at least\
    \ one of the lion's allies is within 5 feet of the target and the ally doesn't\
    \ have the incapacitated condition."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 15 (2d8\
    \ + 6) piercing damage. If the lion moved at least 20 feet straight toward the\
    \ target immediately before the hit, the target must succeed on a DC 16 Strength\
    \ saving throw or have the prone condition. If the target has the prone condition,\
    \ the lion can make another Rend attack against it as a bonus action."
  "name": "Rend"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Spotted Lion.webp"
```
^statblock