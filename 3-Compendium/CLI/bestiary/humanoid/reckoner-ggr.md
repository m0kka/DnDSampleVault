---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Reckoner"]
---
# [Reckoner](3-Compendium\CLI\bestiary\humanoid/reckoner-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros reckoners combine physical power and magical prowess, serving as the shock troops of the legion. They are adept at breaking up mobs and organized lines of defense. Sometimes described as living thunderstorms, reckoners charge their bodies with lightning that bursts forth in their spells and lashes out at enemies who harm them. Many reckoners are minotaurs.

```statblock
"name": "Reckoner (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "15"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "2"
  "Perception": !!int "3"
  "Arcana": !!int "4"
"senses": "passive Perception 13"
"languages": "Common plus any one language"
"cr": "4"
"traits":
- "desc": "The reckoner is a 5th-level Boros spellcaster. Its spellcasting ability\
    \ is Intelligence (spell save DC 12, +4 to hit with spell attacks). The reckoner\
    \ has the following wizard spells prepared:\n\nCantrips (at will): blade ward,\
    \ light, message, shocking grasp\n\n1st level (4 slots): guiding bolt, shield,\
    \ thunderwave, witch bolt\n\n2nd level (3 slots): blur, levitate\n\n3rd\
    \ level (2 slots): lightning bolt"
  "name": "Spellcasting"
- "desc": "The reckoner has advantage on initiative rolls."
  "name": "First Strike"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
"reactions":
- "desc": "When a creature hits the reckoner with an attack, the attacker takes lightning\
    \ damage equal to half the damage dealt by the attack."
  "name": "Lightning Backlash (Recharge 5-6)"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Reckoner.webp"
```
^statblock