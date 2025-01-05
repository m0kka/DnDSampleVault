---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Firegaunt"]
---
# [Firegaunt](3-Compendium\CLI\bestiary\undead/firegaunt-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 137*  

A fire giant whose burning hatred prevents it from moving on to the afterlife rises as a firegaunt. Spawned from deep rancor, the firegaunt seeks out living creatures to destroy. Like a specter, it doesn't seek redemption; it just hopes to cause as much destruction as possible before attaining its final oblivion.

A firegaunt looks like a severely burned corpse. Supernatural crimson flames flow through its veins, erupting from its wounds and its mouth.

```statblock
"name": "Firegaunt (BGG)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "damaged plate"
"hp": !!int "175"
"hit_dice": "14d12 + 84"
"stats":
- !!int "25"
- !!int "7"
- !!int "23"
- !!int "10"
- !!int "14"
- !!int "13"
"speed": "40 ft."
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "2"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "11"
  "Perception": !!int "6"
"damage_resistances": "necrotic"
"damage_immunities": "fire, poison"
"condition_immunities": "exhaustion, petrified, poisoned"
"senses": "passive Perception 16"
"languages": "Giant"
"cr": "11"
"traits":
- "desc": "Whenever a creature within 5 feet of the firegaunt hits the firegaunt with\
    \ a melee attack that deals piercing or slashing damage, that creature takes 5\
    \ (1d10) fire damage."
  "name": "Fire Blood"
"actions":
- "desc": "The firegaunt makes two Heated Maul attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 23\
    \ (3d10 + 7) bludgeoning damage. The firegaunt can cause the maul to erupt with\
    \ crimson flames, and the target must succeed on a DC 18 Dexterity saving throw\
    \ or take 10 (3d6) fire damage and 10 (3d6) necrotic damage. The maul can erupt\
    \ with flames in this way only once per turn."
  "name": "Heated Maul"
- "desc": "The firegaunt emits beams of fire from its eyes, mouth, and wounds in a\
    \ 30-foot cone. Each creature in that area must make a DC 18 Dexterity saving\
    \ throw, taking 31 (7d8) fire damage on a failed save, or half as much damage\
    \ on a successful one. On a success or failure, that creature catches fire. Until\
    \ the burning creature or another creature that can reach it takes an action to\
    \ extinguish the fire, the burning creature can't regain hit points and takes\
    \ 5 (1d10) fire damage at the start of each of its turns."
  "name": "Crimson Rays (Recharge 5-6)"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Firegaunt.webp"
```
^statblock