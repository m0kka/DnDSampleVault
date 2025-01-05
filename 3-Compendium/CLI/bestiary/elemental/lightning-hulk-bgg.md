---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Lightning Hulk"]
---
# [Lightning Hulk](3-Compendium\CLI\bestiary\elemental/lightning-hulk-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 158*  

> [!quote] A quote from Bigby  
> 
> At least the lightning hulk and the dust hulk seem satisfied with their lot in life. There's a grace to their existence, as fractured as it seems.

Lightning hulks are the descendants of storm giants who retreated from the world in ages past. Over the course of centuries, the elemental nature of these giants—aided by infusions of energy from the Elemental Planes—grew to dominate these giants, eventually freeing them from the limitations of flesh.

A lightning hulk is essentially a living bolt of lightning, with the one lasting vestige of its former nature being a vague face that appears at the head of the bolt as it streams through the air. In rare moments, the hulk coalesces into a bipedal shape resembling a storm giant, but these moments are as fleeting as a lightning strike. At other times, particularly when near metal or solid earth, the hulk seems on the verge of dispersing entirely, losing its last shreds of cohesion as a single entity. Its mental state is similarly incoherent: a lightning hulk rushes from one place to another with little sense of purpose and no hint of the contemplation that occupies its distant cousin giants.

```statblock
"name": "Lightning Hulk (BGG)"
"size": "Large"
"type": "elemental"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "15"
"hp": !!int "102"
"hit_dice": "12d10 + 36"
"stats":
- !!int "18"
- !!int "21"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "15"
"speed": "0 ft., fly 90 ft. (hover)"
"saves":
  "Charisma": !!int "6"
  "Dexterity": !!int "9"
  "Wisdom": !!int "6"
  "Constitution": !!int "7"
"skillsaves":
  "Perception": !!int "6"
"damage_resistances": "cold; thunder; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "lightning, poison"
"condition_immunities": "exhaustion, grappled, paralyzed, petrified, poisoned, prone,\
  \ restrained"
"senses": "passive Perception 16"
"languages": "Auran, Giant"
"cr": "9"
"traits":
- "desc": "The lightning hulk sheds bright light in a 20-foot radius and dim light\
    \ for an additional 20 feet."
  "name": "Illumination"
- "desc": "The lightning hulk can enter a hostile creature's space and stop there.\
    \ The first time the lightning hulk enters a creature's space on a turn, or if\
    \ it begins its turn in a creature's space, that creature takes 7 (2d6) lightning\
    \ damage. The hulk can also move through a space as narrow as 1 inch without squeezing.\
    \ A creature that touches the lightning hulk or hits it with a melee attack while\
    \ within 5 feet of it takes 7 (2d6) lightning damage."
  "name": "Lightning Form"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +9 to hit, reach 10 ft. or range 60 ft.,\
    \ one target. Hit: 18 (4d8) lightning damage. If the target is a creature, it\
    \ can't take reactions until the start of its next turn, and lightning jumps from\
    \ the target to another creature of the lightning hulk's choice that it can see\
    \ within 30 feet of the target. The second creature must succeed on a DC 18 Dexterity\
    \ saving throw or take 18 (4d8) lightning damage."
  "name": "Arc Lightning"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Lightning Hulk.webp"
```
^statblock