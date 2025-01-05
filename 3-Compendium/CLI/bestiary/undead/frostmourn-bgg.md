---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Frostmourn"]
---
# [Frostmourn](3-Compendium\CLI\bestiary\undead/frostmourn-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 147*  

When a frost giant is murdered in a dishonorable manner—perhaps poisoned, stabbed in the back, or killed while sleeping—the slain giant can rise as a frostmourn. Driven by its desire for vengeance, the frostmourn can turn the living into frozen statues with a touch or blast enemies with frigid wind. Achieving vengeance is not always enough to grant these creatures rest; often, their hatred and loathing of the living is sufficient to keep them roaming the wilds for years after their murderers are slain.

A frostmourn looks like a desiccated corpse mummified by exposure to bitter cold. It carries the marks of its death on its body: a wound that seeps frosty vapor or vibrant, purple veins showing the ravages of poison. It can momentarily dissolve its body into a swirling blizzard to avoid harm, reforming at a distance to continue its assault.

```statblock
"name": "Frostmourn (BGG)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"stats":
- !!int "23"
- !!int "9"
- !!int "21"
- !!int "9"
- !!int "11"
- !!int "18"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "9"
"skillsaves":
  "Athletics": !!int "10"
  "Perception": !!int "4"
"damage_vulnerabilities": "fire"
"damage_immunities": "cold, poison"
"condition_immunities": "charmed, exhaustion, frightened, grappled, paralyzed, petrified,\
  \ poisoned, prone, restrained"
"senses": "passive Perception 14"
"languages": "Giant"
"cr": "10"
"actions":
- "desc": "The frostmourn makes one Freezing Touch attack and one Icy Axe attack.\
    \ It can replace one of these attacks with a Polar Ray attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one creature. Hit: 18\
    \ (4d8) cold damage plus 18 (4d8) necrotic damage. If this damage would reduce\
    \ the target to 0 hit points, the target drops to 1 hit point instead and has\
    \ the petrified condition, turning into a frozen statue.\n\nIf the statue takes\
    \ bludgeoning damage, it shatters, killing the frozen creature. If the statue\
    \ would take fire damage, it instead takes no damage and thaws, ending the petrification."
  "name": "Freezing Touch"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 19\
    \ (3d8 + 6) slashing damage plus 7 (2d6) cold damage."
  "name": "Icy Axe"
- "desc": "Ranged Spell Attack: +8 to hit, range 120 ft., one target. Hit: 31\
    \ (5d10 + 4) cold damage, and the target's speed is reduced by 10 feet until the\
    \ end of its next turn."
  "name": "Polar Ray"
"reactions":
- "desc": "Immediately after a creature the frostmourn can see hits it with an attack\
    \ roll, the frostmourn momentarily dissolves into a blizzard, reducing the damage\
    \ to itself by half. The frostmourn can then magically teleport to an unoccupied\
    \ space it can see within 30 feet of itself."
  "name": "Blizzard Escape"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Frostmourn.webp"
```
^statblock