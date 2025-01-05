---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
aliases: ["Doomwake Giant"]
---
# [Doomwake Giant](3-Compendium\CLI\bestiary\giant/doomwake-giant-mot.md)
*Source: Mythic Odysseys of Theros p. 224*  

Belief is a powerful force in Theros, capable of bringing about wonders and changing the world—but not always for the better. Doomwake giants arise from pernicious fears that infect a whole city or region. If enough mortals dread destruction for long enough, their terror can manifest as one of these massive Nyxborn beings. Once unleashed, a doomwake giant goes on a rampage, fulfilling the prophecy mortals believed into being. After doing so, these terrors typically roam to the edges of the world, where they either fade away over time or become legends that take on their own terrible life.

A spectrum of giants claims territory across Theros, drawing strength from aspects of the world itself—from ancient stone and roiling flames to the depths of the seas and skies. Unlike many creatures of legend, most giants owe their existence not to Nyx and the dreams of mortals, but to natural forces in the land. As a result, Theran giants are typically infused with the elements they embody, which might manifest as flaming beards, frozen skin, hair crackling with lightning, or other primal incarnations.

Beyond these primal giants, though, other giants fill the tales of Theros.

```statblock
"name": "Doomwake Giant (MOT)"
"size": "Huge"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "162"
"hit_dice": "13d12 + 78"
"stats":
- !!int "24"
- !!int "12"
- !!int "22"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "10"
"skillsaves":
  "Intimidation": !!int "7"
  "Perception": !!int "6"
"damage_immunities": "necrotic, poison"
"condition_immunities": "frightened, poisoned"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Giant"
"cr": "11"
"traits":
- "desc": "Any creature that starts its turn within 10 feet of the giant must succeed\
    \ on a DC 18 Constitution saving throw, or it takes 10 (3d6) necrotic damage and\
    \ can't regain hit points until the start of its next turn. On a successful saving\
    \ throw, the creature is immune to the giant's Aura of Erebos for 24 hours."
  "name": "Aura of Erebos"
- "desc": "The giant has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The giant makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one target. Hit: 20\
    \ (3d8 + 7) bludgeoning damage plus 10 (3d6) necrotic damage."
  "name": "Slam"
- "desc": "The giant exhales a mighty gust that creates a blast of deadly mist in\
    \ a 60-foot line that is 10 feet wide. Each creature in that line must make a\
    \ DC 18 Constitution saving throw. On a failed save, the creature takes 36 (8d8)\
    \ necrotic damage and is knocked prone. On a successful save, a creature takes\
    \ half as much damage and isn't knocked prone."
  "name": "Noxious Gust (Recharge 5-6)"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Doomwake Giant.webp"
```
^statblock