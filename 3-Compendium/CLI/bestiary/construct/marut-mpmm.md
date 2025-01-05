---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct/inevitable
statblock: inline
aliases: ["Marut"]
---
# [Marut](3-Compendium\CLI\bestiary\construct/marut-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 173, Mordenkainen's Tome of Foes p. 213*  

The nigh-unstoppable inevitables serve a singular purpose: they enforce contracts forged in the Hall of Concordance in the city of Sigil. Primus, the leader of the modrons, created maruts and other inevitables to bring order to dealings between planar folk. A wide array of disparate creatures, including yugoloths, will enter into a contract with inevitables if asked.

The Hall of Concordance is an embassy of pure law in Sigil, the City of Doors. In the hall, parties who agree to mutual terms—and who pay the requisite gold to the Kolyarut, a mechanical engine of absolute jurisprudence—can have their contract chiseled onto a sheet of gold that is placed in the chest of a marut. From that moment until the contract is fulfilled, the marut is bound to enforce its terms and to punish any party who breaks them. A marut resorts to lethal force only if a contract calls for it, if the contract is fully broken, or if the marut is attacked.

Inevitables care nothing for the spirit of an agreement, only the letter. A marut enforces what is written, not what was meant by or supposed to be understood from the writing. The Kolyarut rejects contracts that contain vague, contradictory, or unenforceable terms. Beyond that, it doesn't care whether both parties understand what they're agreeing to.

```statblock
"name": "Marut (MPMM)"
"size": "Large"
"type": "construct"
"subtype": "inevitable"
"alignment": "Typically  Lawful Neutral"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "432"
"hit_dice": "32d10 + 256"
"stats":
- !!int "28"
- !!int "12"
- !!int "26"
- !!int "19"
- !!int "15"
- !!int "18"
"speed": "40 ft., fly 30 ft. (hover)"
"saves":
  "Charisma": !!int "12"
  "Wisdom": !!int "10"
  "Intelligence": !!int "12"
"skillsaves":
  "Intimidation": !!int "12"
  "Insight": !!int "10"
  "Perception": !!int "10"
"damage_resistances": "thunder; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "charmed, frightened, paralyzed, poisoned, unconscious"
"senses": "darkvision 60 ft., passive Perception 20"
"languages": "all but rarely speaks"
"cr": "25"
"traits":
- "desc": "The marut casts plane shift, requiring no material components and using\
    \ Intelligence as the spellcasting ability. The marut can cast the spell normally,\
    \ or it can cast the spell on an unwilling creature it can see within 60 feet\
    \ of it. If it uses the latter option, the targeted creature must succeed on a\
    \ DC 20 Charisma saving throw or be banished to a teleportation circle in the\
    \ Hall of Concordance in Sigil.\n\n3/day: plane shift"
  "name": "Plane Shift (3/Day)"
- "desc": "The marut is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "If the marut fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The marut has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The marut doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The marut makes two Unerring Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: automatic hit, reach 5 ft., one target. Hit: 60\
    \ force damage, and the target is pushed up to 5 feet away from the marut if it\
    \ is Huge or smaller."
  "name": "Unerring Slam"
- "desc": "Arcane energy emanates from the marut's chest in a 60-foot cube. Every\
    \ creature in that area takes 45 radiant damage. Each creature that takes any\
    \ of this damage must succeed on a DC 20 Wisdom saving throw or be stunned until\
    \ the end of the marut's next turn."
  "name": "Blazing Edict (Recharge 5-6)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Marut.webp"
```
^statblock