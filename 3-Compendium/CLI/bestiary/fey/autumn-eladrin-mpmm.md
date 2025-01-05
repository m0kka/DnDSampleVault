---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/elf
statblock: inline
aliases: ["Autumn Eladrin"]
---
# [Autumn Eladrin](3-Compendium\CLI\bestiary\fey/autumn-eladrin-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 115, Mordenkainen's Tome of Foes p. 195*  

Eladrin often enter the autumn season when they are overcome by feelings of goodwill. In this aspect, they defuse conflicts and alleviate suffering by using their magic to relieve any ailments that afflict the people who come to them for aid. They tolerate no violence in their presence and move quickly to settle disputes, to ensure that peace continues to reign.

## Eladrin

> [!quote] A quote from Tasha  
> 
> If an autumn eladrin invites you over for dinner, come with an empty stomach. Their goodwill extends to heaping portions.
> 
> Note to self: send some of my spring eladrin friends to visit Mordenkainen. That'll teach him to lighten up.

Eladrin dwell in the verdant splendor of the Feywild. They are related to the elves found on the Material Plane. But while other elves can temper their wild impulses, eladrin are ruled by emotion—and due to their magical nature, they undergo physical changes to match their changes in temperament.

Eladrin have spent centuries in the Feywild, and most of them have become Fey creatures as a result—those presented here are of the Fey variety. Some are still Humanoid, however, similar in that respect to their other elven kin.

The magic flowing through eladrin responds to their emotional state by transforming them into different seasonal aspects, with behaviors and abilities that change with their forms. Some eladrin might remain in a particular aspect for years, while others run through the emotional spectrum each week.

### Changeable Natures

Whenever one of the eladrin presented here finishes a long rest, they can associate themself with a different season, provided they aren't incapacitated. When the eladrin makes this change, they use the stat block of the new season rather than their old stat block. Any damage the eladrin sustained in their previous form applies to the new form, as do any conditions or other ongoing effects affecting them.

```statblock
"name": "Autumn Eladrin (MPMM)"
"size": "Medium"
"type": "fey"
"subtype": "elf"
"alignment": "Typically  Chaotic Neutral"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "165"
"hit_dice": "22d8 + 66"
"stats":
- !!int "12"
- !!int "16"
- !!int "16"
- !!int "14"
- !!int "17"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "7"
  "Insight": !!int "7"
"damage_resistances": "psychic"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Elvish, Sylvan"
"cr": "10"
"traits":
- "desc": "The eladrin casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ hold person\n\n1/day each: greater restoration, revivify\n\n2/day each:\
    \ cure wounds (as a 5th-level spell), lesser restoration"
  "name": "Spellcasting"
- "desc": "Any non-eladrin creature that starts its turn within 60 feet of the eladrin\
    \ must make a DC 16 Wisdom saving throw. On a failed save, the creature becomes\
    \ charmed by the eladrin for 1 minute. On a successful save, the creature becomes\
    \ immune to any eladrin's Enchanting Presence for 24 hours.\n\nWhenever the eladrin\
    \ deals damage to the charmed creature, the charmed creature can repeat the saving\
    \ throw, ending the effect on itself on a success."
  "name": "Enchanting Presence"
- "desc": "The eladrin has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The eladrin makes two Longsword or Longbow attacks. It can replace one\
    \ attack with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) slashing damage, or 6 (1d10 + 1) slashing damage if used with two hands,\
    \ plus 22 (5d8) psychic damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage plus 22 (5d8) psychic damage."
  "name": "Longbow"
"bonus_actions":
- "desc": "The eladrin teleports, along with any equipment it is wearing or carrying,\
    \ up to 30 feet to an unoccupied space it can see."
  "name": "Fey Step (Recharge 4-6)"
"reactions":
- "desc": "If a creature charmed by the eladrin hits with an attack roll while within\
    \ 60 feet of the eladrin, the eladrin magically causes the attack to miss, provided\
    \ the eladrin can see the attacker."
  "name": "Foster Peace"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Autumn Eladrin.webp"
```
^statblock

## Environment

forest