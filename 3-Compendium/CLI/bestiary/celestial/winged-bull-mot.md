---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
aliases: ["Winged Bull"]
---
# [Winged Bull](3-Compendium\CLI\bestiary\celestial/winged-bull-mot.md)
*Source: Mythic Odysseys of Theros p. 214*  

Archons always ride into battle on fearsome winged mounts. Some legends suggest that the mount is actually a physical manifestation of the archon's will, allowing the pair to act with a single mind. The two most common archon mounts are winged bulls and winged lions.

```statblock
"name": "Winged Bull (MOT)"
"size": "Large"
"type": "celestial"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"stats":
- !!int "20"
- !!int "14"
- !!int "18"
- !!int "6"
- !!int "10"
- !!int "5"
"speed": "60 ft., fly 60 ft."
"senses": "passive Perception 10"
"languages": "understands Celestial but can't speak"
"cr": "4"
"traits":
- "desc": "If the bull moves at least 20 feet straight toward a creature and then\
    \ hits it with a gore attack on the same turn, the target takes an extra 19 (3d12)\
    \ piercing damage."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 18 (2d12\
    \ + 5) piercing damage."
  "name": "Gore"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Winged Bull.webp"
```
^statblock