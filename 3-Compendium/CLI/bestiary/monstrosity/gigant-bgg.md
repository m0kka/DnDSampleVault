---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Gigant"]
---
# [Gigant](3-Compendium\CLI\bestiary\monstrosity/gigant-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 154*  

A gigant is a towering insectile creature variously regarded as a harbinger of doom, a defender of nature, and a divine messenger of mysterious purpose. Giants regard them as a plague, since gigants prefer giants over other food. Some giants claim gigants are created by the weird magical aura that surrounds a gargantua.

A gigant resembles an enormous beetle with legs ending in sharp talons. It uses its talons to bring creatures to its enormous mandibles, which are strong enough to carry a giant to the gigant's nest to be devoured.

A gigant's wings are usually folded under its carapace, but the speedy flier can also beat its wings to create a horrible sound or to spread a toxic dust.

```statblock
"name": "Gigant (BGG)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "325"
"hit_dice": "21d20 + 105"
"stats":
- !!int "24"
- !!int "14"
- !!int "21"
- !!int "3"
- !!int "14"
- !!int "11"
"speed": "50 ft., burrow 50 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "8"
"skillsaves":
  "Perception": !!int "8"
"senses": "darkvision 120 ft., passive Perception 18"
"languages": ""
"cr": "20"
"traits":
- "desc": "The gigant has advantage on saving throws against spells, and any creature\
    \ that makes a spell attack against the gigant has disadvantage on the attack\
    \ roll."
  "name": "Spell-Resistant Carapace"
"actions":
- "desc": "The gigant makes one Mandibles attack and two Talons attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one creature. Hit: 21\
    \ (4d6 + 7) slashing damage, and the target has the grappled condition (escape\
    \ DC 17). Until the grapple ends, the target takes 21 (4d6 + 7) slashing damage\
    \ at the start of each of the gigant's turns. While the gigant is grappling a\
    \ target, it can't use Mandibles against other targets."
  "name": "Mandibles"
- "desc": "Melee Weapon Attack: +13 to hit, reach 20 ft., one target. Hit: 17\
    \ (3d6 + 7) slashing damage, and the target is pulled 10 feet straight toward\
    \ the gigant."
  "name": "Talons"
- "desc": "The gigant releases magical dust from its wings in a 30-foot cube. Each\
    \ creature in that area must make a DC 19 Constitution saving throw, taking 45\
    \ (10d8) poison damage on a failed save, or half as much damage on a successful\
    \ one. On a success or failure, the creature has the poisoned condition for 1\
    \ hour. While poisoned this way, the creature can't regain hit points."
  "name": "Scale Dust (Recharge 5-6)"
"bonus_actions":
- "desc": "The gigant produces a horrid droning sound by rapidly beating its wings.\
    \ Each creature within 10 feet of the gigant must succeed on a DC 19 Constitution\
    \ saving throw or take 10 (3d6) thunder damage and have the incapacitated condition\
    \ until the end of its next turn. The gigant can then fly up to half its flying\
    \ speed."
  "name": "Drone"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Gigant.webp"
```
^statblock