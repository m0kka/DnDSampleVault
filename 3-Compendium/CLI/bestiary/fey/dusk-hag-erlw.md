---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Dusk Hag"]
---
# [Dusk Hag](3-Compendium\CLI\bestiary\fey/dusk-hag-erlw.md)
*Source: Eberron: Rising from the Last War p. 292*  

Dusk hags resemble gnarled crones with shriveled orange skin, tangled gray hair, and eyes that burn like hot coals. They see visions of the future in their dreams, and their dark magic allows them to influence the dreams of others, sending messages or inflicting nightmares with a touch. Tales talk of ambitious wizards, frantic monarchs, and desperate heroes undertaking quests or making bargains with a dusk hag in exchange for its prophecies and visions of the future. But the information gained from a dusk hag often has a way of causing more pain than joy. Like all hags, dusk hags enjoy causing strife to those who bargain with them, and find ways to twist and turn promises to their own advantage. The Dusk Hag Prophecies table provides examples of the sort of dreams dusk hags might share with unsuspecting sleepers.

**Dusk Hag Prophecies**

`dice: [](dusk-hag-erlw.md#^dusk-hag-prophecies)`

| dice: d10 | Prophecy |
|-----------|----------|
| 1 | "A red hat approaches with ill intent. Be wary." |
| 2 | "A ship comes on a sea of bones, but treasure waits behind a silver skull." |
| 3 | "Three days, three deaths, three eyes, three breaths." |
| 4 | "Doom falls on the peacock and the sparrow alike. Best be a raven." |
| 5 | "A white hand on a black field holds the golden key." |
| 6 | "Beware the black horse." |
| 7 | "The fish is your friend." |
| 8 | "The stairs downward lead to that which you seek." |
| 9 | "Look for two crossed swords. There your goal lies." |
| 10 | "If you see two crows, turn back. Beyond is death." |
^dusk-hag-prophecies

```statblock
"name": "Dusk Hag (ERLW)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "15d8 + 15"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "17"
- !!int "16"
- !!int "18"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "6"
"skillsaves":
  "Deception": !!int "7"
  "Insight": !!int "6"
  "Perception": !!int "6"
"condition_immunities": "blinded, charmed, frightened"
"senses": "blindsight 60 ft., passive Perception 16"
"languages": "Common, Giant, Infernal"
"cr": "6"
"traits":
- "desc": "The hag's spellcasting ability is Charisma (spell save DC 15). She can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: detect magic, disguise self\n\n1/day each: legend lore, scrying\n\
    \n3/day each: dream, hypnotic pattern, sleep (9d8)"
  "name": "Innate Spellcasting"
- "desc": "The hag has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The hag makes two Nightmare Touch attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Claws"
- "desc": "Melee Spell Attack: +7 to hit, reach 5 ft., one creature. Hit: 18 (4d6\
    \ + 4) psychic damage. If the target is unconscious, it takes an extra 10 (3d6)\
    \ psychic damage and is cursed until the hag dies or the curse is removed. The\
    \ cursed creature's hit point maximum decreases by 5 (1d10) whenever it finishes\
    \ a long rest."
  "name": "Nightmare Touch"
"reactions":
- "desc": "When an unconscious creature the hag can see within 30 feet of her regains\
    \ consciousness, the hag can force the creature to make a DC 15 Wisdom saving\
    \ throw. Unless the save succeeds, the creature takes 11 (2d10) psychic damage,\
    \ and the hag regains hit points equal to the amount of damage taken."
  "name": "Dream Eater"
"source":
- "ERLW"
"image": "bestiary/tokens/ERLW/Dusk Hag.webp"
```
^statblock