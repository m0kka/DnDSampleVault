---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Young Kruthik"]
---
# [Young Kruthik](3-Compendium\CLI\bestiary\monstrosity/young-kruthik-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 168, Mordenkainen's Tome of Foes p. 211*  

Kruthiks hatch from eggs laid by female adults. Each egg is about the size of an adult human's head and hatches within a month. Tiny kruthik hatchlings are harmless and rarely stray far from the nest. They feed primarily on offal and one another. Within a month, the survivors become young kruthiks large enough to hunt and defend themselves.

## Kruthiks

> [!quote] A quote from Mordenkainen  
> 
> Imagine a hive of ants the size of horses, but the ants are wearing armor.

> [!quote] A quote from Mordenkainen  
> 
> Other creatures that abide in hives serve a purpose in the natural world. Bees pollinate flowers. Termites make earth out of wood. Kruthiks, by contrast, slay societies.

Kruthiks are chitin-covered reptiles that hunt in packs and nest in sprawling subterranean warrens. They are attracted to sources of heat, such as dwarven forges and pools of molten lava, and carve out lairs as close to such locations as possible. As they burrow through the earth, they leave behind tunnels—evidence that is often the first clue to the nearby presence of a kruthik hive. Kruthiks also make use of preexisting underground chambers, incorporating them into their lairs when they can.

Kruthiks communicate with one another through a series of hisses and chittering noises. These sounds can often be heard in advance of a kruthik attack. Whenever their lair is invaded, kruthik guards send out an alarm by rapidly tapping the stone floor with their sharp legs.

In addition to having an acute sense of smell, kruthiks can see in the dark and can detect vibrations in the earth around them. They take the scent of their own dead as a warning and avoid areas where many other kruthiks have died. Slaying a sufficient number of kruthiks in one area might cause the remaining hive members to move elsewhere.

Although they can feed on carrion, kruthiks prefer live prey. They kill enemies by impaling them on their spiked limbs, then grind up the flesh and bones with mandibles strong enough to chew rock. When several kruthiks gang up on a single foe, they become frenzied and even more lethal.

Kruthiks abide the presence of Constructs, Elementals, Oozes, and Undead, and they use such creatures to help guard their hive. They are smart enough to barricade some tunnels and dig new ones that keep their neighbors away from their eggs.

```statblock
"name": "Young Kruthik (MPMM)"
"size": "Small"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"stats":
- !!int "13"
- !!int "16"
- !!int "13"
- !!int "4"
- !!int "10"
- !!int "6"
"speed": "30 ft., burrow 10 ft., climb 30 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "darkvision 30 ft., tremorsense 60 ft., passive Perception 14"
"languages": "Kruthik"
"cr": "1/8"
"traits":
- "desc": "The kruthik has advantage on an attack roll against a creature if at least\
    \ one of the kruthik's allies is within 5 feet of the creature and the ally isn't\
    \ incapacitated."
  "name": "Pack Tactics"
- "desc": "The kruthik can burrow through solid rock at half its burrowing speed and\
    \ leaves a 2½-foot-diameter tunnel in its wake."
  "name": "Tunneler"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) piercing damage."
  "name": "Stab"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Young Kruthik.webp"
```
^statblock

## Environment

desert, mountain, underdark