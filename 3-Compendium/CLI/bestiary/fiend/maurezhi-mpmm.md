---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Maurezhi"]
---
# [Maurezhi](3-Compendium\CLI\bestiary\fiend/maurezhi-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 175, Mordenkainen's Tome of Foes p. 133*  

When Doresain, the King of Ghouls, corrupted a society of elves, he created a new sort of demon—the maurezhi—to lead packs of [ghouls](ghoul-xmm.md) and [ghasts](ghast-xmm.md) on the Material Plane.

When a maurezhi consumes the corpse of a Humanoid it has slain—a process that takes about 10 minutes—it instantly assumes the creature's appearance as it was in life. The new appearance begins to rot away over the next few days, eventually revealing the demon's original form.

A maurezhi is contagion incarnate. Its bite can drain a victim's sense of self. If this affliction is allowed to go far enough, the victim is infected with an unholy hunger for flesh that overpowers their personality and transforms them into a ghoul.

```statblock
"name": "Maurezhi (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"stats":
- !!int "14"
- !!int "17"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
"damage_resistances": "cold; fire; lightning; necrotic; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, poisoned"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Abyssal, Elvish, telepathy 120 ft."
"cr": "7"
"traits":
- "desc": "The maurezhi can assume the appearance of any Medium Humanoid it eats.\
    \ It remains in this form for 1d6 days, during which time the form gradually decays\
    \ until, when the effect ends, the form sloughs from the demon's body."
  "name": "Assume Form"
- "desc": "The maurezhi has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The maurezhi makes one Bite attack and one Claw attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 14 (2d10\
    \ + 3) piercing damage. If the target is a Humanoid, its Charisma score is reduced\
    \ by 1d4. This reduction lasts until the target finishes a short or long rest.\
    \ The target dies if this reduces its Charisma to 0. It rises 24 hours later as\
    \ a [ghoul](/3-Compendium/CLI/bestiary/undead/ghoul-xmm.md)  unless it has been\
    \ revived or its corpse has been destroyed."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12 (2d8\
    \ + 3) slashing damage. If the target is a creature other than an Undead, it must\
    \ succeed on a DC 12 Constitution saving throw or be paralyzed for 1 minute. The\
    \ target can repeat the saving throw at the end of each of its turns, ending the\
    \ effect on itself on a success."
  "name": "Claw"
- "desc": "The maurezhi targets one dead ghoul or [ghast](/3-Compendium/CLI/bestiary/undead/ghast-xmm.md)\
    \ it can see within 30 feet of it. The target is revived with all its hit points."
  "name": "Raise Ghoul (Recharge 5-6)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Maurezhi.webp"
```
^statblock

## Environment

swamp, urban