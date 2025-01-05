---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Blood Drinker Vampire"]
---
# [Blood Drinker Vampire](3-Compendium\CLI\bestiary\undead/blood-drinker-vampire-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 223*  

Plenty of blood drinkers haunt Ravnica's alleys and sewers, preying on those who are foolish enough to leave the relative safety of the crowds.

## Orzhov Vampires

Vampires thrive in the Orzhov Syndicate, where they can collect tithes and payments from their debtors in the form of blood. Their undead nature gives them the same immortality enjoyed by the oligarch spirits, but they remain capable of experiencing all the delights of their corporeal forms. In contrast to Orzhov spirits, they also retain their personalities, which are almost uniformly cruel.

## Blood Bond

Consuming a creature's blood creates a sort of empathic bond that allows the blood drinker vampire to exert some magical influence over its victim.

## Vampires

Creatures of the night, vampires are ageless undead beings who subsist on the blood of the living. They are fierce predators who mask their ravenous thirst behind a facade of sophistication and sensuality. Those who sip blood from golden chalices are no less voracious than those who tear out their victims' throats with their fangs; they just hide it better.

The vampires of Ravnica differ from those in the Monster Manual in important ways. They lack the traits and abilities that those other vampires boast, but also lack the weaknesses that hinder such vampires. What they have in common is an unquenchable thirst for the blood that sustains their undead existence.

```statblock
"name": "Blood Drinker Vampire (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"stats":
- !!int "16"
- !!int "18"
- !!int "17"
- !!int "16"
- !!int "13"
- !!int "19"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "4"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "7"
  "Stealth": !!int "7"
  "Perception": !!int "4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "8"
"actions":
- "desc": "The vampire makes three melee attacks, only one of which can be a bite\
    \ attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one willing creature, or\
    \ a creature that is grappled by the vampire, incapacitated, or restrained. Hit:\
    \ 7 (1d6 + 4) piercing damage plus 7 (2d6) necrotic damage. If the target is humanoid,\
    \ it must succeed on a DC 15 Charisma saving throw or be charmed by the vampire\
    \ for 1 minute. While charmed in this way, the target is infatuated with the vampire.\
    \ The target's hit point maximum is reduced by an amount equal to the necrotic\
    \ damage taken, and the vampire regains hit points equal to that amount. The reduction\
    \ lasts until the target finishes a long rest. The target dies if its hit point\
    \ maximum is reduced to 0."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) piercing damage."
  "name": "Rapier"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage. The vampire can also grapple the target (escape DC\
    \ 14) if it is a creature and the vampire has a hand free."
  "name": "Unarmed Strike"
"reactions":
- "desc": "The vampire adds 3 to its AC against one melee attack that would hit it.\
    \ To do so, the vampire must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "GGR"
"image": "bestiary/tokens/GGR/Blood Drinker Vampire.webp"
```
^statblock