---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/goblinoid
statblock: inline
aliases: ["Hobgoblin Iron Shadow"]
---
# [Hobgoblin Iron Shadow](3-Compendium\CLI\bestiary\fey/hobgoblin-iron-shadow-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 154, Volo's Guide to Monsters p. 162*  

Iron shadows are hobgoblin martial artists who serve fey and mortal courts as secret police, scouts, and assassins. They spy to ferret out treachery, rebellion, and betrayal and deal with it ruthlessly. Iron shadows possess agility and stamina matched only by their ironclad commitment to the will of their masters. They wield a deadly combination of unarmed fighting techniques and shadow magic to deceive and defeat their foes. While on secret missions, they wear masks crafted to resemble monsters, both to conceal their identities and to strike fear into their foes.

An iron shadow is usually recruited from the ranks of the Feywild's hobgoblin armies or from among the hobgoblins who have resided in the Material Plane for centuries. A candidate for admission undergoes a series of tests designed to reveal any potential for treachery. Those who fail are slain, while those who pass receive secret training in the arts of magic and stealth. This indoctrination is a slow and arduous process; many aspirants don't finish it, and years might go by during which the iron shadows welcome no new members into their ranks. When a recruit's training is complete, they are tasked with conducting assassinations and spy missions.

```statblock
"name": "Hobgoblin Iron Shadow (MPMM)"
"size": "Medium"
"type": "fey"
"subtype": "goblinoid"
"alignment": "Typically  Lawful Neutral"
"ac": !!int "15"
"ac_class": "Unarmored Defense"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "14"
- !!int "16"
- !!int "15"
- !!int "14"
- !!int "15"
- !!int "11"
"speed": "40 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Stealth": !!int "5"
  "Acrobatics": !!int "5"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Goblin"
"cr": "2"
"traits":
- "desc": "The hobgoblin casts one of the following spells, using Intelligence as\
    \ the spellcasting ability (spell save DC 12):\n\nAt will: minor illusion,\
    \ prestidigitation\n\n1/day each: charm person, disguise self, silent image"
  "name": "Spellcasting"
- "desc": "While the hobgoblin is wearing no armor and wielding no shield, its AC\
    \ includes its Wisdom modifier."
  "name": "Unarmored Defense"
"actions":
- "desc": "The hobgoblin makes four attacks, each of which can be an Unarmed Strike\
    \ or a Dart attack. It can also use\n\nShadow Jaunt once, either before or after\
    \ one of the attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) bludgeoning damage."
  "name": "Unarmed Strike"
- "desc": "Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. Hit:\
    \ 5 (1d4 + 3) piercing damage."
  "name": "Dart"
- "desc": "The hobgoblin teleports, along with any equipment it is wearing or carrying,\
    \ up to 30 feet to an unoccupied space it can see. Both the space it leaves and\
    \ its destination must be in dim light or darkness."
  "name": "Shadow Jaunt"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Hobgoblin Iron Shadow.webp"
```
^statblock

## Environment

forest, grassland, hill