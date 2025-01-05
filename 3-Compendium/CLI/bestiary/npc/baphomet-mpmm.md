---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Baphomet"]
---
# [Baphomet](3-Compendium\CLI\bestiary\npc/baphomet-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 58, Mordenkainen's Tome of Foes p. 143*  

Civilization is weakness and brutality is strength in the credo of Baphomet, the Horned King and the Prince of Beasts. He is worshiped by those who want to break the confines of civility and unleash their bestial natures, for Baphomet envisions a world without restraint, where creatures live out their most bloodthirsty desires.

Cults devoted to Baphomet use mazes and complex knots as their emblems. They create secret places to indulge themselves, including labyrinths of the sort their master favors. Bloodstained crowns and weapons of iron and brass decorate their profane altars.

Over time, a mpmm becomes tainted by his influence, gaining bloodshot eyes and coarse, thickening hair. Small horns eventually sprout from the cultist's forehead. In time, a devoted cultist might transform entirely into a minotaur, which is considered the greatest gift of the Prince of Beasts.

Baphomet appears as a fearsome, 20-foot-tall minotaur with six iron horns. A fiendish light burns in his red eyes. Although he is filled with bestial blood lust, there lies within him a cruel and cunning intellect devoted to subverting all civilization.

Baphomet wields a great glaive called Heartcleaver. He also charges his enemies and gores them with his horns, trampling his foes into the earth and rending them with his teeth like a beast.

## Cultists of Baphomet

> [!note]
> See the Cult of Baphomet entry.

## Baphomet's Lair

Baphomet's lair is his palace, the Lyktion, which is on the layer of the Abyss called the Endless Maze. Nestled within the twisting passages of the planewide labyrinth, the Lyktion is immaculately maintained and surrounded by a moat constructed in the fashion of a three-dimensional maze. The palace is a towering structure whose interior is as labyrinthine as the plane on which it stands; it is populated by [minotaurs](minotaur.md), goristros, and [quasits](quasit-xphb.md).

```statblock
"name": "Baphomet (MPMM)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "319"
"hit_dice": "22d12 + 176"
"stats":
- !!int "30"
- !!int "14"
- !!int "26"
- !!int "18"
- !!int "24"
- !!int "16"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "9"
  "Wisdom": !!int "14"
  "Constitution": !!int "15"
"skillsaves":
  "Intimidation": !!int "17"
  "Perception": !!int "14"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison; bludgeoning, piercing, slashing that is nonmagical"
"condition_immunities": "charmed, exhaustion, frightened, poisoned"
"senses": "truesight 120 ft., passive Perception 24"
"languages": "all, telepathy 120 ft."
"cr": "23"
"traits":
- "desc": "Baphomet casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 18):\n\n1/day:\
    \ teleport\n\n3/day each: dispel magic, dominate beast, maze, wall of stone"
  "name": "Spellcasting"
- "desc": "Baphomet can perfectly recall any path he has traveled, and he is immune\
    \ to the maze spell."
  "name": "Labyrinthine Recall"
- "desc": "If Baphomet fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Baphomet has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Baphomet makes one Bite attack, one Gore attack, and one Heartcleaver attack.\
    \ He also uses Frightful Presence."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 19\
    \ (2d8 + 10) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d6 + 10) piercing damage. If Baphomet moved at least 10 feet straight toward\
    \ the target immediately before the hit, the target takes an extra 16 (3d10) piercing\
    \ damage. If the target is a creature, it must succeed on a DC 25 Strength saving\
    \ throw or be pushed up to 10 feet away and knocked prone."
  "name": "Gore"
- "desc": "Melee Weapon Attack: +17 to hit, reach 15 ft., one target. Hit: 21\
    \ (2d10 + 10) force damage."
  "name": "Heartcleaver"
- "desc": "Each creature of Baphomet's choice within 120 feet of him and aware of\
    \ him must succeed on a DC 18 Wisdom saving throw or become frightened for 1 minute.\
    \ A frightened creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success. These later saves have disadvantage\
    \ if Baphomet is within line of sight of the creature.\n\nIf a creature succeeds\
    \ on any of these saves or the effect ends on it, the creature is immune to Baphomet's\
    \ Frightful Presence for the next 24 hours."
  "name": "Frightful Presence"
"legendary_actions":
- "desc": "Baphomet makes one Heartcleaver attack."
  "name": "Heartcleaver Attack"
- "desc": "Baphomet moves up to his speed without provoking opportunity attacks, then\
    \ makes a Gore attack."
  "name": "Charge (Costs 2 Actions)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Baphomet.webp"
```
^statblock