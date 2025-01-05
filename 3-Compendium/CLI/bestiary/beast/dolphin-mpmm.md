---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Dolphin"]
---
# [Dolphin](3-Compendium\CLI\bestiary\beast/dolphin-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 97, Volo's Guide to Monsters p. 208*  

Dolphins are symbols of wisdom and playfulness among the sea folk of many worlds. Found in oceans and in the Elemental Plane of Water, dolphins are befriended by druids and rangers, and many tales speak of dolphins that appeared out of nowhere to protect swimmers from sharks and other aquatic predators.

## Dolphins

Dolphins are clever, social marine mammals that feed on small fish and squid. An adult specimen is between 5 and 6 feet long.

```statblock
"name": "Dolphin (MPMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "13"
- !!int "13"
- !!int "6"
- !!int "12"
- !!int "7"
"speed": "0 ft., swim 60 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": ""
"cr": "1/8"
"traits":
- "desc": "The dolphin can hold its breath for 20 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage. If the dolphin moved at least 30 feet straight toward\
    \ the target immediately before the hit, the target takes an extra 3 (1d6) bludgeoning\
    \ damage."
  "name": "Slam"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Dolphin.webp"
```
^statblock

## Environment

coastal, underwater