---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Frost Salamander"]
---
# [Frost Salamander](3-Compendium\CLI\bestiary\elemental/frost-salamander-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 132, Mordenkainen's Tome of Foes p. 223*  

Frost salamanders are natives of the Plane of Ice, also called the Frostfell, which rests between the Plane of Air and the Plane of Water. Frost salamanders especially like to hunt warm-blooded creatures. They sometimes travel to frigid climes on the Material Plane by wandering through planar gates.

Frost salamanders' aggressive appetite for any heat source leads them to attack expeditions and settlements that other predators would avoid, as they often mistake the fire of a forge or a campfire for a large, tasty meal. Azers use this predilection to hunt frost salamanders. Venturing into the Frostfell, they use large fires to lure these creatures into traps, then kill them and collect their hides and fangs for use in crafting weapons and armor.

Although frost salamanders can burrow their way through loose soil, they prefer to dig into ice. They roll around in piles of broken chunks of ice, allowing it to scratch their backs as they grind it down. This habit leads them to create extensive networks of ice caves, which become ever larger as they claw fresh chunks of ice from the walls of their lairs.

A frost salamander that dwells in a lair for a while carves out enough space to allow a small army to camp within. Inexperienced travelers who come across these caves see them as a welcome shelter, though they are anything but. Frost salamanders greedily devour any prey foolhardy enough to try sleeping in their lairs.

On rare occasions, [frost giants](frost-giant.md) capture and tame these creatures, using them to burrow into the ice to help create outposts and fortresses.

```statblock
"name": "Frost Salamander (MPMM)"
"size": "Huge"
"type": "elemental"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d12 + 64"
"stats":
- !!int "20"
- !!int "12"
- !!int "18"
- !!int "7"
- !!int "11"
- !!int "7"
"speed": "60 ft., burrow 40 ft., climb 40 ft."
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "8"
"skillsaves":
  "Perception": !!int "4"
"damage_vulnerabilities": "fire"
"damage_immunities": "cold"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 14"
"languages": "Primordial"
"cr": "9"
"traits":
- "desc": "When the salamander takes fire damage, its\n\nFreezing Breath automatically\
    \ recharges."
  "name": "Burning Fury"
"actions":
- "desc": "The salamander makes one Bite attack and four Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 9 (1d8\
    \ + 5) piercing damage plus 5 (1d10) cold damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 8 (1d6\
    \ + 5) piercing damage."
  "name": "Claw"
- "desc": "The salamander exhales chill wind in a 60-foot cone. Each creature in that\
    \ area must make a DC 17 Constitution saving throw, taking 44 (8d10) cold damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Freezing Breath (Recharge 6)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Frost Salamander.webp"
```
^statblock

## Environment

arctic