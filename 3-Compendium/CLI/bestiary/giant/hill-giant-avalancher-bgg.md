---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/druid
statblock: inline
aliases: ["Hill Giant Avalancher"]
---
# [Hill Giant Avalancher](3-Compendium\CLI\bestiary\giant/hill-giant-avalancher-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 157*  

Hill giants who master rune magic discover a close connection to the natural forces of earth and stone. Their magic, combined with their size and strength, helps them quickly rise to positions of leadership.

These hill giants drape themselves in rocks attached to chains or ropes, then use their magic to knock down and pummel their foes with these stones. This magic, combined with their ability to defeat and devour their prey as quickly as a torrent of boulders cascades down a mountain, leads other giants to call them avalanchers.

```statblock
"name": "Hill Giant Avalancher (BGG)"
"size": "Huge"
"type": "giant"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "220"
"hit_dice": "21d12 + 84"
"stats":
- !!int "21"
- !!int "8"
- !!int "19"
- !!int "9"
- !!int "18"
- !!int "10"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "8"
  "Strength": !!int "9"
  "Constitution": !!int "8"
"skillsaves":
  "Nature": !!int "7"
  "Perception": !!int "8"
"senses": "passive Perception 18"
"languages": "Common, Giant"
"cr": "12"
"traits":
- "desc": "The giant casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 16):\n\nAt will: druidcraft, guidance\n\n1/day\
    \ each: stone shape, wall of stone"
  "name": "Spellcasting"
- "desc": "The giant has a hill rune inscribed on a rock or some other object in its\
    \ possession. While holding or wearing the object bearing the rune, the giant\
    \ can use its Stone Avalanche action and Hill Rebuff reaction.\n\nThe object bearing\
    \ the rune has AC 15; 20 hit points; and immunity to necrotic, poison, and psychic\
    \ damage. The object regains all its hit points at the end of every turn, but\
    \ it turns to dust if reduced to 0 hit points or when the giant dies. If the rune\
    \ is destroyed, the giant can inscribe a hill rune on an object in its possession\
    \ when it finishes a short or long rest."
  "name": "Hill Rune"
- "desc": "If the giant fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The giant makes one Greatclub attack and uses Stone Bolas."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 18 (3d8\
    \ + 5) bludgeoning damage plus 9 (2d8) thunder damage."
  "name": "Greatclub"
- "desc": "The giant conjures three stone balls connected by lines of magical force\
    \ and throws them at one creature it can see within 60 feet of itself. The target\
    \ must make a DC 16 Dexterity saving throw. On a failed save, the target has the\
    \ restrained condition until the start of the giant's next turn, and the stones\
    \ erupt in a burst of thunderous energy that deals 14 (4d6) thunder damage to\
    \ the target and each creature within 10 feet of the target. On a successful save,\
    \ the stones vanish without erupting."
  "name": "Stone Bolas"
- "desc": "The giant conjures a hail of rocks in a 20-foot-radius, 40-foot-high cylinder\
    \ centered on a point on the ground it can see within 120 feet of itself. Each\
    \ creature in that area must make a DC 16 Dexterity saving throw. On a failed\
    \ save, a creature takes 28 (8d6) bludgeoning damage and has the prone condition.\
    \ On a successful save, a creature takes half as much damage only.\n\nThe rocks\
    \ turn the ground in that area into difficult terrain until the start of the giant's\
    \ next turn, when the rocks vanish."
  "name": "Stone Avalanche (Requires Hill Rune)"
"reactions":
- "desc": "Immediately after the giant takes damage from a creature it can see within\
    \ 10 feet of itself, that creature must succeed on a DC 16 Constitution saving\
    \ throw or take 10 (3d6) force damage and be pushed horizontally 10 feet away\
    \ from the giant."
  "name": "Hill Rebuff (Requires Hill Rune)"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Hill Giant Avalancher.webp"
```
^statblock