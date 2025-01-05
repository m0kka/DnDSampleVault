---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
aliases: ["Stone Giant of Evil Earth"]
---
# [Stone Giant of Evil Earth](3-Compendium\CLI\bestiary\giant/stone-giant-of-evil-earth-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 179*  

Stone giants with a bent toward cruelty and destruction might reject the gods of the Ordning and turn to the worship of Ogrémoch, the Prince of Evil Earth. These giants view the surface world not as a realm of dream but as a nightmare worthy only of destruction, so they lend their strength to cults that plan to reduce the world to rubble.

Outfitted in heavy armor crafted to resemble the cult's patron, stone giants of Evil Earth wield weapons that pulse with thunderous energy. These giants serve as the muscle for the cult, wielding their might to destroy the surface world in the name of Ogrémoch.

```statblock
"name": "Stone Giant of Evil Earth (BGG)"
"size": "Huge"
"type": "giant"
"alignment": "typically  Neutral Evil"
"ac": !!int "20"
"ac_class": "plate"
"hp": !!int "137"
"hit_dice": "11d12 + 66"
"stats":
- !!int "23"
- !!int "13"
- !!int "22"
- !!int "10"
- !!int "12"
- !!int "9"
"speed": "40 ft."
"saves":
  "Strength": !!int "10"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "14"
  "Perception": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Giant, Terran"
"cr": "9"
"actions":
- "desc": "The giant makes two Thundering Stone Club or Boulder attacks in any combination."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 15 ft., one target. Hit: 16\
    \ (3d6 + 6) bludgeoning damage. The giant can cause the club to emit a burst of\
    \ thunderous energy that deals 10 (3d6) thunder damage to each creature, other\
    \ than the giant, within 30 feet of the target. The club can emit a burst this\
    \ way only once per turn."
  "name": "Thundering Stone Club"
- "desc": "Ranged Weapon Attack: +10 to hit, range 60/240 ft., one target. Hit:\
    \ 19 (3d8 + 6) bludgeoning damage, and the target must succeed on a DC 18 Strength\
    \ saving throw or have the prone condition. After the giant throws the boulder,\
    \ roll a d6; on a roll of 3 or lower, the giant has no more boulders to throw."
  "name": "Boulder"
"reactions":
- "desc": "In response to failing a saving throw to avoid being moved, having the\
    \ prone condition, or both, the giant succeeds instead."
  "name": "Unyielding"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Stone Giant of Evil Earth.webp"
```
^statblock