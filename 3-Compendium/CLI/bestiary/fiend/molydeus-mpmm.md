---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Molydeus"]
---
# [Molydeus](3-Compendium\CLI\bestiary\fiend/molydeus-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 184, Mordenkainen's Tome of Foes p. 134*  

The fearsome molydeus speaks for the demon lord it serves and enforces its master's will. This demon is 12 feet tall, and its bipedal body has a slavering wolfs head and a fanged serpent's head. Its demon lord can speak and see through the serpent head; this master also uses the molydeus to guard treasures, slay foes, and terrify troops into obedience.

A molydeus's demon lord bestows on it a powerful weapon that dissolves if the molydeus dies. The weapon's form varies depending on the creator, but that doesn't affect the weapon's capabilities.

```statblock
"name": "Molydeus (MPMM)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "216"
"hit_dice": "16d12 + 112"
"stats":
- !!int "28"
- !!int "22"
- !!int "25"
- !!int "21"
- !!int "24"
- !!int "24"
"speed": "40 ft."
"saves":
  "Charisma": !!int "14"
  "Wisdom": !!int "14"
  "Strength": !!int "16"
  "Constitution": !!int "14"
"skillsaves":
  "Perception": !!int "21"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "blinded, charmed, deafened, frightened, poisoned, stunned"
"senses": "truesight 120 ft., passive Perception 31"
"languages": "Abyssal, telepathy 120 ft."
"cr": "21"
"traits":
- "desc": "The molydeus casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 22):\n\nAt will:\
    \ dispel magic, polymorph, telekinesis, teleport\n\n3/day: lightning bolt"
  "name": "Spellcasting"
- "desc": "If the molydeus fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The molydeus has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The molydeus makes one Demonic Weapon attack, one Snakebite attack, and\
    \ one Wolf Bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one target. Hit: 35\
    \ (4d12 + 9) force damage. If the target has at least one head and the molydeus\
    \ rolled a 20 on the attack roll, the target is decapitated and dies if it can't\
    \ survive without that head. A target is immune to this effect if it takes none\
    \ of the damage, has legendary actions, or is Huge or larger. Such a creature\
    \ takes an extra 27 (6d8) force damage from the hit."
  "name": "Demonic Weapon"
- "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one creature. Hit: 16\
    \ (2d6 + 9) poison damage. The target must succeed on a DC 22 Constitution saving\
    \ throw, or its hit point maximum is reduced by an amount equal to the damage\
    \ taken. This reduction lasts until the target finishes a long rest. The target\
    \ transforms into a [manes](/3-Compendium/CLI/bestiary/fiend/manes.md) if this\
    \ reduces its hit point maximum to 0. This transformation can be ended only by\
    \ a wish spell."
  "name": "Snakebite"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 25\
    \ (3d10 + 9) necrotic damage."
  "name": "Wolf Bite"
"legendary_actions":
- "desc": "The molydeus makes one Demonic Weapon or Snakebite attack."
  "name": "Attack"
- "desc": "The molydeus moves without provoking opportunity attacks."
  "name": "Move"
- "desc": "The molydeus uses Spellcasting."
  "name": "Cast a Spell (Costs 2 Actions)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Molydeus.webp"
```
^statblock