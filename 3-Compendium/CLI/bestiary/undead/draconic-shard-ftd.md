---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ftd
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Draconic Shard"]
---
# [Draconic Shard](3-Compendium\CLI\bestiary\undead/draconic-shard-ftd.md)
*Source: Fizban's Treasury of Dragons p. 181*  

Gem dragons wield psionic power, and when a powerful gem dragon perishes, the force of the dragon's will and mind sometimes refuses to pass on. This essence lingers in the form of a psychic remnant called a draconic shard.

A draconic shard in its true form resembles a shimmering, spectral image of the dragon. More often, though, a shard inhabits an object the gem dragon poured psionic power into—typically a weapon or other item from the dragon's hoard. In this vessel, a draconic shard continues to pursue the interests and struggles that drove the dragon, perhaps even accompanying adventurers in the guise of an intelligent magic item and steering them to fulfill the dragon's designs.

A draconic shard is difficult to destroy. Destroying the shard's spectral form or an object the shard inhabits forces the spirit into the form of a cracked gemstone while the spirit slowly regains strength. Only if that stone is destroyed can the shard be put to rest.

```statblock
"name": "Draconic Shard (FTD)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Neutral"
"ac": !!int "17"
"ac_class": "deflection"
"hp": !!int "168"
"hit_dice": "16d12 + 64"
"stats":
- !!int "1"
- !!int "12"
- !!int "18"
- !!int "22"
- !!int "18"
- !!int "22"
"speed": "0 ft., fly 80 ft. (hover)"
"saves":
  "Charisma": !!int "12"
  "Dexterity": !!int "7"
  "Wisdom": !!int "10"
  "Intelligence": !!int "12"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "16"
  "History": !!int "12"
  "Arcana": !!int "12"
"damage_resistances": "acid; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "cold, necrotic, poison, psychic"
"condition_immunities": "charmed, exhaustion, frightened, grappled, paralyzed, petrified,\
  \ poisoned, prone"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 26"
"languages": "Common, Draconic, telepathy 120 ft."
"cr": "17"
"traits":
- "desc": "The shard casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 20):\n\nAt\
    \ will: detect thoughts, invisibility, telekinesis"
  "name": "Spellcasting (Psionics)"
- "desc": "The shard's AC includes its Intelligence modifier."
  "name": "Deflection"
- "desc": "The shard can move through creatures and objects as if they were difficult\
    \ terrain. If it ends its turn inside an object, it takes 5 (1d10) force damage."
  "name": "Incorporeal Movement"
- "desc": "If the shard fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "When it drops to 0 hit points, the shard disappears and leaves a Tiny cracked\
    \ gemstone in its space. The gemstone matches the kind of gem dragon it was in\
    \ life and has AC 20, 15 hit points, and immunity to all damage except force.\
    \ Unless the gemstone is destroyed, after  days, the gemstone dissipates and the\
    \ shard re-forms, regaining all its hit points and appearing in the place the\
    \ gemstone once occupied or in the nearest unoccupied space."
  "name": "Rejuvenation"
- "desc": "The shard doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The shard makes two Telekinetic Rend attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +12 to hit, reach 10 ft. or range 120 ft.,\
    \ one target. Hit: 15 (2d8 + 6) force damage."
  "name": "Telekinetic Rend"
- "desc": "The shard disappears as it pours its psychic essence into a Medium or smaller\
    \ nonsentient object it can see within 30 feet of it, magically possessing it.\
    \ The object uses the shard's AC, and any damage dealt to the object applies to\
    \ the shard's hit points. The shard inhabits the object until it uses an action\
    \ to leave; until it is turned; until it is reduced to 0 hit points; or until\
    \ an effect that ends possession, such as a dispel evil and good spell, is used\
    \ on it. When it leaves the object, it reappears in the nearest unoccupied space.\n\
    \nWhile inhabited, the object becomes a magic item if it wasn't already, and a\
    \ Tiny cracked gemstone matching the kind of gem dragon the shard was in life\
    \ appears somewhere on the object. The shard can cause the object to fly using\
    \ the shard's own flying speed, use its senses, speak verbally or telepathically,\
    \ cast spells, and use its legendary actions.\n\nIf a creature wears or carries\
    \ the inhabited object, the shard can grant the creature the following benefits:\n\
    \nEach of the creature's attacks deals an extra 1d8 force damage on a hit.\n\n\
    The creature gains resistance to psychic damage."
  "name": "Inhabit Object"
- "desc": "The shard unleashes a pulse of psychic power. Each creature of the shard's\
    \ choice in a 60-foot-radius sphere centered on it must make a DC 20 Intelligence\
    \ saving throw. On a failed save, the creature takes 55 (10d10) psychic damage\
    \ and is stunned until the end of its next turn. On a successful save, the creature\
    \ takes half as much damage and isn't stunned."
  "name": "Psychic Crush (Recharge 5-6)"
"legendary_actions":
- "desc": "The shard makes one Telekinetic Rend attack."
  "name": "Rend"
- "desc": "The shard uses Spellcasting."
  "name": "Cast a Spell (Costs 2 Actions)"
- "desc": "The shard targets a creature it can see within 30 feet of it. The target\
    \ must succeed on a DC 20 Wisdom saving throw or be charmed until the end of its\
    \ next turn. While charmed in this way, the target becomes the shard's puppet,\
    \ acting and moving in accordance with its telepathic commands. While under the\
    \ shard's control, the target can take only the Attack (shard chooses the target)\
    \ or Dash action on its turn."
  "name": "Commanding Thought (Costs 2 Actions)"
"source":
- "FTD"
"image": "bestiary/tokens/FTD/Draconic Shard.webp"
```
^statblock