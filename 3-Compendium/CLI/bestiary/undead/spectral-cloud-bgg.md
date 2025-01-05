---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Spectral Cloud"]
---
# [Spectral Cloud](3-Compendium\CLI\bestiary\undead/spectral-cloud-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 176*  

A cloud giant that dies through an act of betrayal or an ill-fated wager sometimes returns as a spectral cloud. While this Undead seems to be merely a thick cloud or fog bank, observers can sometimes spot a shadowy bipedal figure lurking within. At the heart of the cloud, the figure's appearance becomes clear: a skeletal cloud giant corpse.

Tales suggest cloud giants sometimes seek this fate rather than accept the end of their naturally long lives. In such stories, a cloud giant undergoes a ritual in which its heart is transplanted into a cloud, causing the giant's body to dissolve and its spirit to animate the cloud.

```statblock
"name": "Spectral Cloud (BGG)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Neutral"
"ac": !!int "11"
"hp": !!int "189"
"hit_dice": "18d12 + 72"
"stats":
- !!int "24"
- !!int "12"
- !!int "18"
- !!int "12"
- !!int "17"
- !!int "16"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "6"
"skillsaves":
  "Perception": !!int "8"
"damage_resistances": "cold; necrotic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "poison, thunder"
"condition_immunities": "charmed, exhaustion, frightened, grappled, paralyzed, petrified,\
  \ poisoned, prone, restrained"
"senses": "passive Perception 18"
"languages": "Common, Giant"
"cr": "13"
"traits":
- "desc": "Attack rolls against the spectral cloud are made with disadvantage unless\
    \ the attacker is within 15 feet of the spectral cloud or the spectral cloud is\
    \ incapacitated."
  "name": "Blurred Form"
- "desc": "The spectral cloud can move through other creatures and objects as if they\
    \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
"actions":
- "desc": "The spectral cloud makes two Spectral Touch attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 20\
    \ (3d8 + 7) force damage plus 10 (3d6) necrotic damage. If the target is a creature,\
    \ it must succeed on a DC 20 Constitution saving throw, or its hit point maximum\
    \ is reduced by an amount equal to the necrotic damage taken. This reduction lasts\
    \ until the target finishes a long rest. The target dies if its hit point maximum\
    \ is reduced to 0.\n\nA Humanoid slain by this attack immediately rises as a miniature\
    \ spectral cloud (use the [specter](/3-Compendium/CLI/bestiary/undead/specter.md)\
    \ stat block in the Monster Manual). The miniature spectral cloud acts as an ally\
    \ of its creator but isn't under its control."
  "name": "Spectral Touch"
- "desc": "The spectral cloud emits intensely cold wind in a 60-foot line that is\
    \ 10 feet wide. Each creature in that area must make a DC 20 Constitution saving\
    \ throw. On a failed save, a creature takes 38 (7d10) cold damage and has the\
    \ incapacitated condition for 1 minute. The affected creature can repeat the saving\
    \ throw at the end of each of its turns, ending the effect on itself on a success.\
    \ On a successful save, a creature takes half as much damage only.\n\nIf a creature's\
    \ saving throw is successful or the effect ends for it, that creature is immune\
    \ to this spectral cloud's Chilling Winds for the next 24 hours."
  "name": "Chilling Winds (Recharge 5-6)"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Spectral Cloud.webp"
```
^statblock