---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Demilich (Trap Soul)"]
---
# [Demilich (Trap Soul)](3-Compendium\CLI\bestiary\undead/demilich-trap-soul.md)
*Source: Monster Manual p. 48, Explorer's Guide to Wildemount*  

```statblock
"name": "Demilich (Trap Soul)"
"size": "Tiny"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "80"
"hit_dice": "32d4"
"stats":
- !!int "1"
- !!int "20"
- !!int "10"
- !!int "20"
- !!int "17"
- !!int "20"
"speed": "0 ft., fly 30 ft. (hover)"
"saves":
  "Charisma": !!int "11"
  "Wisdom": !!int "9"
  "Intelligence": !!int "11"
  "Constitution": !!int "6"
"damage_resistances": "bludgeoning, piercing, slashing from magic weapons"
"damage_immunities": "necrotic; poison; psychic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"condition_immunities": "charmed, deafened, exhaustion, frightened, paralyzed, petrified,\
  \ poisoned, prone, stunned"
"senses": "truesight 120 ft., passive Perception 13"
"languages": ""
"cr": "21"
"traits":
- "desc": "If the demilich is subjected to an effect that allows it to make a saving\
    \ throw to take only half damage, it instead takes no damage if it succeeds on\
    \ the saving throw, and only half damage if it fails."
  "name": "Avoidance"
- "desc": "If the demilich fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The demilich is immune to effects that turn undead."
  "name": "Turn Immunity"
"actions":
- "desc": "The demilich emits a bloodcurdling howl. Each creature within 30 feet of\
    \ the demilich that can hear the howl must succeed on a DC 15 Constitution saving\
    \ throw or drop to 0 hit points. On a successful save, the creature is frightened\
    \ until the end of its next turn."
  "name": "Howl (Recharge 5-6)"
- "desc": "The demilich targets up to three creatures that it can see within 10 feet\
    \ of it. Each target must succeed on a DC 19 Constitution saving throw or take\
    \ 21 (6d6) necrotic damage, and the demilich regains hit points equal to the total\
    \ damage dealt to all targets."
  "name": "Life Drain"
- "desc": "The demilich targets one creature that it can see within 30 feet of it.\
    \ The target must make a DC 19 Charisma saving throw. On a failed save, the target's\
    \ soul is magically trapped inside one of the demilich's gems. While the soul\
    \ is trapped, the target's body and all the equipment it is carrying cease to\
    \ exist. On a successful save, the target takes 24 (7d6) necrotic damage, and\
    \ if this damage reduces the target to 0 hit points, its soul is trapped as if\
    \ it failed the saving throw. A soul trapped in a gem for 24 hours is devoured\
    \ and ceases to exist.\n\nIf the demilich drops to 0 hit points, it is destroyed\
    \ and turns to powder, leaving behind its gems. Crushing a gem releases any soul\
    \ trapped within, at which point the target's body re-forms in an unoccupied space\
    \ nearest to the gem and in the same state as when it was trapped."
  "name": "Trap Soul"
"legendary_actions":
- "desc": "The demilich flies up to half its flying speed."
  "name": "Flight"
- "desc": "The demilich magically swirls its dusty remains. Each creature within 10\
    \ feet of the demilich, including around a corner, must succeed on a DC 15 Constitution\
    \ saving throw or be blinded until the end of the demilich's next turn. A creature\
    \ that succeeds on the saving throw is immune to this effect until the end of\
    \ the demilich's next turn."
  "name": "Cloud of Dust"
- "desc": "Each creature with in 30 feet of the demilich must make a DC 15 Constitution\
    \ saving throw. On a failed save, the creature's hit point maximum is magically\
    \ reduced by 10 (3d6). If a creature's hit point maximum is reduced to 0 by this\
    \ effect, the creature dies. A creature's hit point maximum can be restored with\
    \ the  greater restoration spell or similar magic."
  "name": "Energy Drain (Costs 2 Actions)"
- "desc": "The demilich targets one creature it can see within 30 feet of it. The\
    \ target must succeed on a DC 15 Wisdom saving throw or be magically cursed. Until\
    \ the curse ends, the target has disadvantage on attack rolls and saving throws.\
    \ The target can repeat the saving throw at the end of each of its turns, ending\
    \ the curse on a success."
  "name": "Vile Curse (Costs 3 Actions)"
"source":
- "MM"
- "EGW"
```
^statblock