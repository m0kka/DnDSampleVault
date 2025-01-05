---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Isperia"]
---
# [Isperia](3-Compendium\CLI\bestiary\npc/isperia-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 227*  

Isperia is the current guildmaster of the Azorius Senate. As a sphinx, she is aloof and values solitude above all. However, she has been forced to give up her privacy to deal with the increased crime and chaos on Ravnica.

Isperia is devoted to her guild's belief that law is the ultimate bulwark against chaos, and it is her steady hand that guides the Azorius through these uncertain times. As guildmaster, Isperia serves as the supreme judge, a role that takes advantage of her encyclopedic knowledge of Ravnica's labyrinthine legal system.

If an encounter turns violent, Isperia refrains from using lethal force if possible, preferring to subdue a wrongdoing so that the legal system can mete out justice.

```statblock
"name": "Isperia (GGR)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "261"
"hit_dice": "18d20 + 72"
"stats":
- !!int "20"
- !!int "14"
- !!int "18"
- !!int "23"
- !!int "26"
- !!int "20"
"speed": "40 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "9"
  "Wisdom": !!int "15"
  "Intelligence": !!int "13"
  "Constitution": !!int "11"
"skillsaves":
  "Insight": !!int "15"
  "Perception": !!int "15"
  "History": !!int "13"
  "Arcana": !!int "13"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "charmed, frightened"
"senses": "truesight 120 ft., passive Perception 25"
"languages": "Common, Sphinx"
"cr": "21"
"traits":
- "desc": "Isperia's innate spellcasting ability is Wisdom (spell save DC 23). Isperia\
    \ can innately cast imprisonment twice per day, requiring no material components.\n\
    \n2/day: imprisonment"
  "name": "Innate Spellcasting"
- "desc": "Isperia is a 15th-level Azorius spellcaster. Her spellcasting ability is\
    \ Wisdom (spell save DC 23, +14 to hit with spell attacks). Isperia has the following\
    \ cleric spells prepared:\n\nCantrips (at will): guidance, light, resistance,\
    \ sacred flame, thaumaturgy\n\n1st level (4 slots): command, detect evil and\
    \ good, ensnaring strike, sanctuary, shield of faith\n\n2nd level (3 slots):\
    \ arcane lock, augury, calm emotions, hold person, silence, zone of truth\n\n\
    3rd level (3 slots): bestow curse, clairvoyance, counterspell, dispel magic,\
    \ tongues\n\n4th level (3 slots): divination, locate creature\n\n5th level\
    \ (2 slots): dispel evil and good, scrying\n\n6th level (1 slots): word\
    \ of recall\n\n7th level (1 slots): divine word\n\n8th level (1 slots):\
    \ antimagic field"
  "name": "Spellcasting"
- "desc": "Isperia is immune to any effect that would sense her emotions or read her\
    \ thoughts, as well as any divination spell that she refuses. Wisdom (Insight)\
    \ checks made to ascertain her intentions or sincerity have disadvantage."
  "name": "Inscrutable"
- "desc": "If Isperia fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Isperia has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Isperia makes two claw attacks. She can cast a spell with a casting time\
    \ of 1 action in place of one claw attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 21 (3d10\
    \ + 5) slashing damage. If the target is a creature, it must succeed on a DC 23\
    \ Wisdom saving throw or take 14 (4d6) psychic damage after each attack it makes\
    \ against Isperia before the start of her next turn."
  "name": "Claw"
- "desc": "Isperia chooses up to three creatures she can see within 90 feet of her.\
    \ Each target must succeed on a DC 23 Intelligence saving throw or Isperia chooses\
    \ an action for that target: Attack, Cast a Spell, Dash, Disengage, Dodge, Help,\
    \ Hide, Ready, Search, or Use an Object. The affected target can't take that action\
    \ for 1 minute. At the end of each of the target's turns, it can end the effect\
    \ on itself with a successful DC 23 Intelligence saving throw. A target that succeeds\
    \ on the saving throw becomes immune to Isperia's Supreme Legal Authority for\
    \ 24 hours."
  "name": "Supreme Legal Authority"
"legendary_actions":
- "desc": "Isperia makes one claw attack."
  "name": "Claw Attack"
- "desc": "Isperia casts a spell of 3rd level or lower from her list of prepared spells,\
    \ using a spell slot as normal."
  "name": "Cast a Spell (Costs 2 Actions)"
- "desc": "Isperia uses Supreme Legal Authority."
  "name": "Supreme Legal Authority (Costs 3 Actions)"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Isperia.webp"
```
^statblock