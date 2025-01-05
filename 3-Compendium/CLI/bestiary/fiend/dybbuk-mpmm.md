---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Dybbuk"]
---
# [Dybbuk](3-Compendium\CLI\bestiary\fiend/dybbuk-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 113, Mordenkainen's Tome of Foes p. 132*  

Dybbuks are demons that terrorize mortals on the Material Plane by possessing corpses and giving them a semblance of life, after which the demons use them to engage in a range of sordid activities.

In their natural form, dybbuks appear as translucent flying jellyfish, trailing long tentacles as they move through the air. They rarely travel in this fashion, however. Instead, a dybbuk possesses a suitable corpse as a vehicle, rousing the body from death. Dybbuks delight in terrorizing other creatures by making their host bodies behave in horrifying ways—throwing up gouts of blood, excreting piles of squirming maggots, and contorting their limbs in impossible ways as they scuttle across the ground.

```statblock
"name": "Dybbuk (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "14"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "6"
- !!int "19"
- !!int "16"
- !!int "16"
- !!int "15"
- !!int "14"
"speed": "40 ft. (hover)"
"skillsaves":
  "Intimidation": !!int "4"
  "Deception": !!int "6"
  "Perception": !!int "4"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, frightened, grappled, paralyzed, petrified,\
  \ poisoned, prone, restrained"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Abyssal, Common, telepathy 120 ft."
"cr": "4"
"traits":
- "desc": "The dybbuk casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 12):\n\nAt will:\
    \ dimension door\n\n3/day: phantasmal force"
  "name": "Spellcasting"
- "desc": "The dybbuk can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "The dybbuk has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13 (2d8\
    \ + 4) necrotic damage. If the target is a creature, its hit point maximum is\
    \ also reduced by 3 (1d6). This reduction lasts until the target finishes a short\
    \ or long rest. The target dies if its hit point maximum is reduced to 0."
  "name": "Tentacle"
- "desc": "The dybbuk disappears into an intact corpse within 5 feet of it that belonged\
    \ to a Large or smaller Beast or Humanoid. The dybbuk gains 20 temporary hit points.\
    \ While possessing the corpse, the dybbuk adopts the corpse's size and can't use\
    \ Incorporeal Movement. Its game statistics otherwise remain the same. The possession\
    \ lasts until the temporary hit points are lost or the dybbuk ends it as a bonus\
    \ action. When the possession ends, the dybbuk appears in an unoccupied space\
    \ within 5 feet of the corpse."
  "name": "Possess Corpse (Recharge 6)"
"bonus_actions":
- "desc": "While Possess Corpse is active, the dybbuk makes the corpse do something\
    \ unnatural, such as vomit blood, twist its head all the way around, or cause\
    \ a quadruped to move as a biped. Any Beast or Humanoid that sees this behavior\
    \ must succeed on a DC 12 Wisdom saving throw or become frightened of the dybbuk\
    \ for 1 minute. The frightened creature can repeat the saving throw at the end\
    \ of each of its turns, ending the effect on itself on a success. A creature that\
    \ succeeds on a saving throw against this ability is immune to Control Corpse\
    \ for 24 hours."
  "name": "Control Corpse"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Dybbuk.webp"
```
^statblock

## Environment

desert, urban