---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Gnoll Flesh Gnawer"]
---
# [Gnoll Flesh Gnawer](3-Compendium\CLI\bestiary\monstrosity/gnoll-flesh-gnawer-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 144, Volo's Guide to Monsters p. 154*  

These gnolls eschew the use of ranged weapons in favor of short blades that they wield with great speed and efficiency. In the thick of a fight, they dash across the battlefield, slashing and snarling as they run down stragglers and finish off wounded foes.

## Gnolls

The first gnolls were hyenas transformed by magic. Many of them were then corrupted by the demon lord Yeenoghu. Whether in service to Yeenoghu or dedicated to the survival of their kin, gnoll war bands seek to soften up foes with surprise attacks and to leave no survivors alive.

```statblock
"name": "Gnoll Flesh Gnawer (MPMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "14"
"ac_class": "studded leather"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "12"
- !!int "14"
- !!int "12"
- !!int "8"
- !!int "10"
- !!int "8"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Gnoll"
"cr": "1"
"actions":
- "desc": "The gnoll makes one Bite attack and two Shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Until the end of the turn, the gnoll's speed increases by 60 feet and it\
    \ doesn't provoke opportunity attacks."
  "name": "Sudden Rush"
"bonus_actions":
- "desc": "After the gnoll reduces a creature to 0 hit points with a melee attack\
    \ on its turn, the gnoll moves up to half its speed and makes a Bite attack."
  "name": "Rampage"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Gnoll Flesh Gnawer.webp"
```
^statblock

## Environment

arctic, forest, grassland, hill