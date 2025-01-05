---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Echo of Demogorgon"]
---
# [Echo of Demogorgon](3-Compendium\CLI\bestiary\fiend/echo-of-demogorgon-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 132*  

> [!quote] A quote from Bigby  
> 
> No transformation wrought by the hand (or tentacle, whatever) of a demon lord is rightly understood as a "blessing."

Some legends claim the first ettins were orcs transformed by Demogorgon, the Prince of Demons, while others tie their origin to Grolantor or another god of the Ordning. Whatever the truth of their origin, ettins sometimes recognize a kindred soul in the two-headed Demogorgon and devote themselves to his service. Those who prove exceptionally valuable to Demogorgon's purposes in the Material Plane are rewarded with a "blessing" that transforms them into monstrous echoes of their demon patron.

The arms of an echo of Demogorgon transform into powerful tentacles, and the heads take on a more bestial appearance. The transformation leaves the echo frenzied with rage; the two heads shout and howl at each other with a fury that resounds with demonic magic, sowing discord and confusion around them. As the echo's monstrous heads roar and bite at each other, nearby creatures are racked with psychic pain or join in the ruckus, attacking their allies.

```statblock
"name": "Echo of Demogorgon (BGG)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "typically  Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"stats":
- !!int "22"
- !!int "10"
- !!int "17"
- !!int "10"
- !!int "12"
- !!int "14"
"speed": "40 ft."
"saves":
  "Charisma": !!int "5"
  "Strength": !!int "9"
"skillsaves":
  "Perception": !!int "7"
"damage_resistances": "cold, fire, lightning"
"condition_immunities": "charmed, frightened"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Abyssal, Giant, Orc"
"cr": "6"
"traits":
- "desc": "The echo has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "When one of the echo's heads is asleep, its other head is awake."
  "name": "Wakeful"
"actions":
- "desc": "The echo makes two Tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 13 (2d6\
    \ + 6) bludgeoning damage plus 9 (2d8) necrotic damage."
  "name": "Tentacle"
"bonus_actions":
- "desc": "The echo directs its frenzied howls at one creature it can see within 60\
    \ feet of itself. The target must succeed on a DC 13 Wisdom saving throw or suffer\
    \ one of the following effects of the echo's choice:\n\n- Confused Reaction.\
    \ The target must use its reaction to make a melee attack against another creature\
    \ of the echo's choice that the echo can see.  \n- Psychic Torment. The target\
    \ takes 13 (2d12) psychic damage.  "
  "name": "Discordant Screams"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Echo of Demogorgon.webp"
```
^statblock