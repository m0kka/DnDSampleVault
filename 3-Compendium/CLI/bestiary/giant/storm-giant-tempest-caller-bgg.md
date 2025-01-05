---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/sorcerer
statblock: inline
aliases: ["Storm Giant Tempest Caller"]
---
# [Storm Giant Tempest Caller](3-Compendium\CLI\bestiary\giant/storm-giant-tempest-caller-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 182*  

While most storm giants care little for the intricate details of ranking in the ordning, tempest callers proudly claim a position at the pinnacle of that ranking—and few dare to challenge them. Wielding the power of rune magic in addition to the innate magic that courses through them, these storm giants are highly respected. If any giant can draw Annam's attention to the world, it would likely be a tempest caller.

Tempest callers implant crystal balls inscribed with the storm rune into their foreheads or eye sockets, allowing them to see through magical deception. They can also create a momentary vortex of freezing winds and storm clouds around themselves, engulfing their foes in elemental fury.

```statblock
"name": "Storm Giant Tempest Caller (BGG)"
"size": "Huge"
"type": "giant"
"subtype": "sorcerer"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "310"
"hit_dice": "27d12 + 135"
"stats":
- !!int "29"
- !!int "14"
- !!int "20"
- !!int "21"
- !!int "18"
- !!int "25"
"speed": "50 ft., fly 50 ft. (hover), swim 50 ft."
"saves":
  "Charisma": !!int "13"
  "Wisdom": !!int "10"
  "Strength": !!int "15"
  "Constitution": !!int "11"
"skillsaves":
  "Athletics": !!int "15"
  "Perception": !!int "10"
  "Arcana": !!int "17"
"damage_resistances": "cold"
"damage_immunities": "lightning, thunder"
"senses": "truesight 120 ft., passive Perception 20"
"languages": "Common, Giant, Primordial"
"cr": "20"
"traits":
- "desc": "The giant casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 21, +13 to hit\
    \ with spell attacks):\n\nAt will: detect magic, detect thoughts\n\n1/day\
    \ each: control water, control weather (as an action), dispel magic, plane shift,\
    \ sending, time stop"
  "name": "Spellcasting"
- "desc": "The giant can't be surprised, and it has advantage on initiative rolls."
  "name": "Alert"
- "desc": "The giant can breathe air and water."
  "name": "Amphibious"
- "desc": "If the giant fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The giant can use its crystal ball to cast the scrying spell (save DC 17)."
  "name": "Scrying (Requires Storm Rune)"
- "desc": "The giant has a storm rune inscribed on a crystal ball. While the object\
    \ bearing the rune is embedded in its body, the giant can use its Tempest Call\
    \ action and its Scrying trait.\n\nThe object bearing the storm rune has AC 17;\
    \ 50 hit points; and immunity to necrotic, poison, and psychic damage. The object\
    \ regains all its hit points at the end of every turn, but it turns to dust if\
    \ reduced to 0 hit points or when the giant dies. If the rune is destroyed, the\
    \ giant can inscribe a storm rune on another crystal ball in its possession when\
    \ it finishes a short or long rest."
  "name": "Storm Rune"
"actions":
- "desc": "The giant makes three Lightning Blade or Lightning Lance attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d8 + 9) slashing damage plus 16 (3d10) lightning damage."
  "name": "Lightning Blade"
- "desc": "Ranged Spell Attack: +13 to hit, range 500 ft., one target. Hit: 39\
    \ (5d12 + 7) lightning damage."
  "name": "Lightning Lance"
- "desc": "The giant creates an elemental vortex that fills a 60-foot-radius sphere\
    \ centered on itself. Each creature in that area other than the giant must make\
    \ a DC 21 Dexterity saving throw. On a failed save, a creature takes 43 (8d8 +\
    \ 7) damage of a type of the giant's choosing: cold, lightning, or thunder. On\
    \ a successful save, a creature takes half as much damage."
  "name": "Tempest Call (Requires Storm Rune)"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Storm Giant Tempest Caller.webp"
```
^statblock