---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Armanite"]
---
# [Armanite](3-Compendium\CLI\bestiary\fiend/armanite-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 50, Mordenkainen's Tome of Foes p. 131*  

Great herds of armanites race across the blasted fields of the Abyss, bent on slaughter and death, driven by unrestrained bloodlust. Whether they're controlled by more powerful demons or charging into battle for the sake of it, armanites use their claws and hooves, as well as their long, whiplike tails, to tear apart foes.

In the armies of demon lords, armanites perform the role of heavy cavalry, leading the charge and tearing into their enemies' flanks. Armanites fight all the time—even battling each other if they can't find another enemy. They make ideal shock troops, utterly ruthless and bold to the point of stupidity.

Part of what makes armanites so fearsome is the number of weapons they have at their disposal. They possess dense hooves, claws that end in curling talons, and long tails whose serrated ridges can flense the flesh from a victim, and they use them all to carve through their foes. When they're up against tough formations, they can call on their innate magic to loose bolts of lightning and blow holes in enemy ranks.

```statblock
"name": "Armanite (MPMM)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "94"
"hit_dice": "9d10 + 45"
"stats":
- !!int "21"
- !!int "18"
- !!int "21"
- !!int "8"
- !!int "12"
- !!int "13"
"speed": "60 ft."
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Abyssal, telepathy 120 ft."
"cr": "7"
"traits":
- "desc": "The armanite has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The armanite makes one Claw attack, one Hooves attack, and one Serrated\
    \ Tail attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 10 (2d4\
    \ + 5) slashing damage plus 9 (2d8) lightning damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) bludgeoning damage. If the target is a Large or smaller creature, it must\
    \ succeed on a DC 16 Strength saving throw or be knocked prone."
  "name": "Hooves"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 16 (2d10\
    \ + 5) slashing damage."
  "name": "Serrated Tail"
- "desc": "The armanite looses a bolt of lightning in a line that is 60 feet long\
    \ and 10 feet wide. Each creature in the line must make a DC 15 Dexterity saving\
    \ throw, taking 36 (8d8) lightning damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Lightning Lance (Recharge 5-6)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Armanite.webp"
```
^statblock

## Environment

underdark