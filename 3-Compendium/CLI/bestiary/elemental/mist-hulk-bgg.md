---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Mist Hulk"]
---
# [Mist Hulk](3-Compendium\CLI\bestiary\elemental/mist-hulk-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 160*  

> [!quote] A quote from Diancastra  
> 
> I mourn for the hulks, all of them. The sight of a mist hulk, in particular, fills me with a melancholy that is hard to shake off.

Descended from ancient cloud giants, mist hulks are Elementals that embody their ancestors' mixed elemental nature of Air and Water. After countless ages of isolation—often on one of the Elemental Planes or some hidden demiplane—they retain the barest hint of their ancestors' physical form, and even less of the giants' culture.

A mist hulk resembles a bipedal figure made of dark rain clouds. Parts of its body seem more solid than others, but these parts are transparent enough that the churning vapors of the hulk's substance are visible inside. Wisps of cloud constantly leak from the creature, as if it might dissolve completely at any time. When it is slain, its misty form condenses into a torrent of water.

A mist hulk's mood is always gloomy, and when threatened, it often howls in infectious misery. All who hear this wail are magically reminded of past regrets, real or imagined.

```statblock
"name": "Mist Hulk (BGG)"
"size": "Large"
"type": "elemental"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "15"
"hp": !!int "94"
"hit_dice": "9d10 + 45"
"stats":
- !!int "18"
- !!int "21"
- !!int "20"
- !!int "11"
- !!int "13"
- !!int "16"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "4"
  "Constitution": !!int "8"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "4"
"damage_resistances": "thunder"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, paralyzed, poisoned, restrained"
"senses": "passive Perception 14"
"languages": "Auran, Giant"
"cr": "6"
"traits":
- "desc": "The mist hulk can enter another creature's space and stop there. It can\
    \ move through a space as narrow as 1 inch without squeezing."
  "name": "Air Form"
- "desc": "When the mist hulk dies, it bursts in a wave of water. Each creature within\
    \ 10 feet of it must make a DC 16 Dexterity saving throw. On a failed save, a\
    \ creature takes 11 (2d10) bludgeoning damage and has the prone condition. On\
    \ a successful save, a creature takes half as much damage only."
  "name": "Death Burst"
"actions":
- "desc": "The mist hulk makes two Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 16 (2d10\
    \ + 5) cold damage."
  "name": "Slam"
- "desc": "The mist hulk releases a wail infused with magical anguish. Each creature\
    \ within 30 feet of it must make a DC 14 Wisdom saving throw. A creature in the\
    \ mist hulk's space has disadvantage on the saving throw. On a failed save, a\
    \ creature takes 14 (4d6) psychic damage and has the incapacitated condition for\
    \ 1 minute. The affected creature can repeat the saving throw at the end of each\
    \ of its turns, ending the effect on itself on a success."
  "name": "Hideous Wailing (Recharge 5-6)"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Mist Hulk.webp"
```
^statblock