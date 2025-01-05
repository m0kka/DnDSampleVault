---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/yugoloth
statblock: inline
aliases: ["Oinoloth"]
---
# [Oinoloth](3-Compendium\CLI\bestiary\fiend/oinoloth-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 202, Mordenkainen's Tome of Foes p. 251*  

Grim specters of death, oinoloths bring pestilence wherever they go. When armies recognize their awful forms, their mere appearance causes soldiers to break ranks and flee, lest they succumb to one of the awful plagues that oinoloths let loose.

Oinoloths solve thorny problems by killing everyone involved. They are typically hired as a last resort when a siege has gone on too long or an army has proven too strong to overcome. Once summoned, oinoloths stalk the killing field, poisoning the ground and sickening creatures they encounter. Sometimes they might be hired to lift the very plagues they spread, but the price for such work is high, and the effort turns the creatures they save into debilitated wrecks.

```statblock
"name": "Oinoloth (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d8 + 56"
"stats":
- !!int "19"
- !!int "17"
- !!int "18"
- !!int "17"
- !!int "16"
- !!int "19"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "8"
"skillsaves":
  "Intimidation": !!int "8"
  "Deception": !!int "8"
  "Perception": !!int "7"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "poisoned"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 17"
"languages": "Abyssal, Infernal, telepathy 60 ft."
"cr": "12"
"traits":
- "desc": "The oinoloth casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ darkness, detect magic, dispel magic, hold monster, invisibility (self only)\n\
    \n1/day each: feeblemind, globe of invulnerability"
  "name": "Spellcasting"
- "desc": "The oinoloth has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The oinoloth makes two Claw attacks, and it uses Spellcasting or Teleport."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14 (3d6\
    \ + 4) slashing damage plus 22 (4d10) necrotic damage."
  "name": "Claw"
- "desc": "The oinoloth touches one willing creature within 5 feet of it. The target\
    \ regains all its hit points. In addition, the oinoloth can end one disease on\
    \ the target or remove one of the following conditions from it: blinded, deafened,\
    \ paralyzed, or poisoned. The target then gains 1 level of exhaustion, and its\
    \ hit point maximum is reduced by 7 (2d6). This reduction can be removed only\
    \ by a wish spell or by casting greater restoration on the target three times\
    \ within the same hour. The target dies if its hit point maximum is reduced to\
    \ 0."
  "name": "Corrupted Healing (Recharge 6)"
- "desc": "The oinoloth teleports, along with any equipment it is wearing or carrying,\
    \ up to 60 feet to an unoccupied space it can see."
  "name": "Teleport"
"bonus_actions":
- "desc": "The oinoloth blights the area in a 30-foot-radius sphere centered on itself.\
    \ The blight lasts for 24 hours. While the area is blighted, all normal plants\
    \ there wither and die.\n\nFurthermore, when a creature moves into the blighted\
    \ area or starts its turn there, that creature must make a DC 16 Constitution\
    \ saving throw. On a failed save, the creature takes 14 (4d6) poison damage and\
    \ is poisoned. On a successful save, the creature is immune to the oinoloth's\
    \ Bringer of Plagues for the next 24 hours.\n\nThe poisoned creature can't regain\
    \ hit points. After every 24 hours that elapse, the poisoned creature can repeat\
    \ the saving throw. On a failed save, the creature's hit point maximum is reduced\
    \ by 5 (1d10). This reduction lasts until the poison ends, and the target dies\
    \ if its hit point maximum is reduced to 0. The poison ends after the creature\
    \ successfully saves against it three times."
  "name": "Bringer of Plagues (Recharge 5-6)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Oinoloth.webp"
```
^statblock

## Environment

desert, underdark