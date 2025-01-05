---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Typhon"]
---
# [Typhon](3-Compendium\CLI\bestiary\monstrosity/typhon-mot.md)
*Source: Mythic Odysseys of Theros p. 246*  

Titanic horrors of writhing flesh and gnashing maws, typhons slither through the Underworld seeking only to consume. Once the souls of mortal warlords and cruel tyrants, typhons come into being over ages of festering bitterness and rage. Over time, these souls twist into eternally ravenous monstrosities, which rampage through the realm of the dead, consuming souls by the thousands. The Underworld remains their prison, though, and most would relish nothing more than to escape and slaughter the living once more.

```statblock
"name": "Typhon (MOT)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"stats":
- !!int "24"
- !!int "10"
- !!int "20"
- !!int "7"
- !!int "12"
- !!int "13"
"speed": "40 ft."
"saves":
  "Constitution": !!int "10"
"damage_immunities": "acid, necrotic"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common"
"cr": "15"
"traits":
- "desc": "The typhon has advantage on Wisdom (Perception) checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The typhon regains 20 hit points at the start of its turn. If it takes\
    \ radiant damage, this trait doesn't function at the start of its next turn. The\
    \ typhon dies only if it starts its turn with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
"actions":
- "desc": "The typhon makes three attacks: one with its Flurry of Bites, one to constrict,\
    \ and one with its maw."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 35\
    \ (8d6 + 7) piercing damage."
  "name": "Flurry of Bites"
- "desc": "Melee Weapon Attack: +12 to hit, reach 15 ft., one Large or smaller creature.\
    \ Hit: 17 (3d6 + 7) bludgeoning damage, and the target is grappled (escape DC\
    \ 19). Until this grapple ends, the target is restrained and takes 17 (3d6 + 7)\
    \ bludgeoning damage at the start of each of its turns. The typhon can have up\
    \ to two creatures constricted."
  "name": "Constrict"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 26\
    \ (3d12 + 7) piercing damage plus 19 (3d12) acid damage."
  "name": "Maw"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Typhon.webp"
```
^statblock