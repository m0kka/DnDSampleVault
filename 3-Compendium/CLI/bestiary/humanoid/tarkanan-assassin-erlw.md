---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Tarkanan Assassin"]
---
# [Tarkanan Assassin](3-Compendium\CLI\bestiary\humanoid/tarkanan-assassin-erlw.md)
*Source: Eberron: Rising from the Last War p. 320*  

Tarkanan assassins are the elite killers, spies, and thieves who work for House Tarkanan, a criminal organization specializing in theft and assassination. In addition to their deadly skill, a Tarkanan assassin possesses an aberrant dragonmark—a twisted sigil that provides them with magical power. House Tarkanan actively seeks and recruits people with aberrant dragonmarks.

> [!note] Aberrant Dragonmark Innate Spells
> 
> The power granted by an aberrant dragonmark is unpredictable. When running a Tarkanan assassin, you can roll on the Aberrant Dragonmark Innate Spells table to determine the spells gained from that NPC's aberrant mark, replacing the spells in the stat block's Innate Spellcasting trait.
> 
> `dice: [](tarkanan-assassin-erlw.md#^at-will-1-day)`
> 
> | dice: d6 | At Will | 1/Day |
> |----------|---------|-------|
> | 1 | Fire bolt (`2d10`) | Burning hands (`3d6`) |
> | 2 | Shocking grasp (`2d8`) | Chromatic orb (`4d8`) |
> | 3 | Poison spray (`2d12`) | Ray of sickness (`3d8`) |
> | 4 | Friends | Charm person (two creatures) |
> | 5 | Minor illusion | Thunderwave (`2d8`) |
> | 6 | Dancing lights | Sleep (`7d8`) |
> ^at-will-1-day
^aberrant-dragonmark-innate-spells

```statblock
"name": "Tarkanan Assassin (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "15"
"ac_class": "studded leather"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "12"
- !!int "16"
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "3"
  "Sleight of Hand": !!int "5"
  "Deception": !!int "2"
  "Stealth": !!int "5"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Thieves' cant"
"cr": "2"
"traits":
- "desc": "The assassin's spellcasting ability is Constitution (+4 to hit with spell\
    \ attacks). It can innately cast the following spells, requiring no material components:\n\
    \nAt will: fire bolt\n\n1/day: chromatic orb"
  "name": "Innate Spellcasting"
- "desc": "When the assassin casts an innate spell, each creature within 10 feet of\
    \ the assassin must make a DC 12 Constitution saving throw, taking 4 (1d8) force\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Unstable Mark"
"actions":
- "desc": "The assassin makes two shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 7 (2d6) poison damage."
  "name": "Shortsword"
- "desc": "Ranged Spell Attack: +4 to hit, range 120 ft., one target. Hit: 11\
    \ (2d10) fire damage. A flammable object hit by this spell ignites if it isn't\
    \ being worn or carried."
  "name": "Fire Bolt (Cantrip)"
- "desc": "Ranged Spell Attack: +4 to hit, range 90 ft., one creature. Hit: 18\
    \ (4d8) damage of a type chosen by the assassin: acid, cold, fire, lightning,\
    \ poison, or thunder."
  "name": "Chromatic Orb (1/Day)"
"source":
- "ERLW"
"image": "bestiary/tokens/ERLW/Tarkanan Assassin.webp"
```
^statblock