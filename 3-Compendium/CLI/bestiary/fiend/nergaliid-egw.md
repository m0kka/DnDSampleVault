---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
aliases: ["Nergaliid"]
---
# [Nergaliid](3-Compendium\CLI\bestiary\fiend/nergaliid-egw.md)
*Source: Explorer's Guide to Wildemount p. 296*  

Corpulent, scaled, and utterly repulsive, these vicious devils stalk the dark edges of society away from prying eyes, subsisting on the life force of unsuspecting humanoids. Creatures that die to the nergaliid's feeding leave a corrupted undead corpse behind known as a husk zombie (see earlier in this chapter).

The nergaliid favors feeding on the life force of sleeping humanoids, feasting on the same prey nightly—so long as its victim remains unaware. This ensures a lasting source of nourishment, with the victim beset by terrible nightmares as long as the feeding continues. When a nergaliid is discovered, it tries to strike a deal with the one who uncovered it. It might offer material wealth in exchange for freedom and silence. Only when an accord seems unlikely does the nergaliid attack.

```statblock
"name": "Nergaliid (EGW)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "4d10 + 20"
"stats":
- !!int "18"
- !!int "12"
- !!int "20"
- !!int "12"
- !!int "10"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "5"
  "Perception": !!int "2"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Common, Infernal"
"cr": "3"
"traits":
- "desc": "While in dim light or darkness, the nergaliid can take the Hide action\
    \ as a bonus action."
  "name": "Shadow Stealth"
- "desc": "The nergaliid's long jump is up to 30 feet and its high jump is up to 20\
    \ feet, with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 13\
    \ (2d8 + 4) piercing damage, and the target must succeed on a DC 15 Constitution\
    \ saving throw or become poisoned for 1 minute. The poisoned creature can repeat\
    \ the saving throw at the end of each of its turns, ending the effect on itself\
    \ on a success."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 20 ft., one target. Hit: 10 (1d12\
    \ + 4) bludgeoning damage."
  "name": "Tongue Lash"
- "desc": "The nergaliid magically draws the life from a humanoid it can see within\
    \ 40 feet of it. The target must make a DC 15 Wisdom saving throw. An incapacitated\
    \ target fails the save automatically. On a failed save, the creature takes 10\
    \ (3d6) psychic damage, and the nergaliid gains temporary hit points equal to\
    \ the damage taken. On a successful save, the target takes half as much damage,\
    \ and the nergaliid doesn't gain temporary hit points. If this damage kills the\
    \ target, its body rises at the end of the nergaliid's current turn as a [husk\
    \ zombie](/3-Compendium/CLI/bestiary/undead/husk-zombie-egw.md) (see earlier in\
    \ this chapter)."
  "name": "Siphon Life (Recharge 4-6)"
"source":
- "EGW"
"image": "bestiary/tokens/EGW/Nergaliid.webp"
```
^statblock