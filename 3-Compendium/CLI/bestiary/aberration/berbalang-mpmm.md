---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Berbalang"]
---
# [Berbalang](3-Compendium\CLI\bestiary\aberration/berbalang-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 61, Mordenkainen's Tome of Foes p. 120*  

Berbalangs creep across the petrified remains of dead gods adrift on the Astral Plane. Obsessed with gathering secrets, both from the gods they inhabit and from the bones of dead creatures, they call forth the spirits of the dead and force them to divulge what they learned in life.

Berbalangs prefer to speak only to dead things, and specifically only to the spirits they call forth in the hope of learning secrets. They record their stories on the bones that once belonged to these creatures, thus preserving the information they gain.

Pursuit of knowledge drives everything berbalangs do. Although they mostly learn their secrets from the dead, they aren't above spying on the living to take knowledge from them as well. A berbalang can create a spectral duplicate of itself and send the duplicate out to gather information on other planes by watching places where the gods and their servants gather. When a berbalang is perceiving its environment through its duplicate, its actual body is unconscious and can't protect itself. Thus, a berbalang typically uses its duplicate for only a short time before returning its consciousness to its body.

The knowledge that berbalangs accumulate makes them great sources of information for powerful people traveling the planes. Berbalangs ignore petitioners, however, unless they come bearing a choice secret or the bones of a particularly interesting creature. Some githyanki have been able to strike deals with the creatures, using berbalangs to spy on their enemies and to watch over their creches on the Material Plane.

```statblock
"name": "Berbalang (MPMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Typically  Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "49"
"hit_dice": "14d8 - 14"
"stats":
- !!int "9"
- !!int "16"
- !!int "9"
- !!int "17"
- !!int "11"
- !!int "10"
"speed": "30 ft., fly 40 ft."
"saves":
  "Dexterity": !!int "5"
  "Intelligence": !!int "5"
"skillsaves":
  "Religion": !!int "5"
  "Insight": !!int "2"
  "Perception": !!int "2"
  "History": !!int "5"
  "Arcana": !!int "5"
"senses": "truesight 120 ft., passive Perception 12"
"languages": "all"
"cr": "2"
"traits":
- "desc": "The berbalang casts one of the following spells, requiring no material\
    \ components and using Intelligence as the spellcasting ability:\n\nAt will:\
    \ speak with dead\n\n1/day: plane shift (self only)"
  "name": "Spellcasting"
"actions":
- "desc": "The berbalang makes one Bite attack and one\n\nClaw attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) piercing damage plus 4 (1d8) psychic damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (2d4\
    \ + 3) slashing damage."
  "name": "Claw"
"bonus_actions":
- "desc": "The berbalang creates one spectral duplicate of itself in an unoccupied\
    \ space it can see within 60 feet of it. While the duplicate exists, the berbalang\
    \ is unconscious. A berbalang can have only one duplicate at a time. The duplicate\
    \ disappears when it or the berbalang drops to 0 hit points or when the berbalang\
    \ dismisses it (no action required).\n\nThe duplicate has the same statistics\
    \ and knowledge as the berbalang, and everything experienced by the duplicate\
    \ is known by the berbalang. All damage dealt by the duplicate's attacks is psychic\
    \ damage."
  "name": "Spectral Duplicate (Recharges after a Short or Long Rest)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Berbalang.webp"
```
^statblock

## Environment

desert