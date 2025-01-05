---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Girallon"]
---
# [Girallon](3-Compendium\CLI\bestiary\monstrosity/girallon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 139, Volo's Guide to Monsters p. 152*  

A girallon looks like an oversized, four-armed ape with grayish-tan skin and white fur. Its vicious fangs and claws reveal it to be a monstrous predator.

Girallons are most common in temperate or warm forest environments abundant with life. They share apes' adeptness at climbing, although few trees can support the weight of these half-ton creatures. The ruins of cities, especially those found in deep forests and jungles, seem to attract girallons. They see a city's buildings as a superior sort of forest whose uppermost "branches" can safely support them. The creatures can easily scale walls and battlements, and they perch on tower tops and other high vantages to keep an eye on the surrounding area.

When girallons can't climb, they stalk the forest floor, lurk in narrow ravines or shallow caves, or hide in ruined sites while waiting for prey to come near. A girallon is surprisingly stealthy, considering its size and its lack of camouflage.

Girallons form loose bands of several individuals and their offspring, usually led by a dominant adult that also tends to be the oldest member of the group. When on the hunt away from their lair, girallons use roars and body language to communicate with one another over distance. Each individual typically hunts alone and widely separated from the others to ensure that everyone gets adequate fodder. The leader might organize members to work together to make a big kill, however. If they succeed, everyone in the group shares the spoils, with the best parts going to those caring for their young.

Girallons' strange appearance and attraction to ruins lead sages to believe they were created through magic to serve as guardians for some lost empire. When that empire fell ages ago, girallons turned feral and spread out across the world.

Numerous creatures have tried to tame, subjugate, or cooperate with the monsters. For instance, some forest-dwelling peoples capture girallons and train them to serve as sentinels. Recognizing that girallons are peaceful among their own kind, other folk have learned how to approach a group's leader, offering food and other gifts in hopes of establishing an alliance with the creatures.

Girallons that are well treated might be willing to serve as guards, though they lack the intelligence to take on tasks more complicated than attacking strangers who enter their domain. A girallon that's captured when young and carefully trained could end up in a seemingly unlikely place, such as guarding the entrance to a city's thieves' guild. Those who would keep a girallon must always be wary, however, because the creature could revert to its predatory nature at any time.

```statblock
"name": "Girallon (MPMM)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"stats":
- !!int "18"
- !!int "16"
- !!int "16"
- !!int "5"
- !!int "12"
- !!int "7"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "4"
"actions":
- "desc": "The girallon makes one Bite attack and four Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 7 (1d6\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage."
  "name": "Claw"
"bonus_actions":
- "desc": "The girallon moves up to its speed toward a hostile creature that it can\
    \ see."
  "name": "Aggressive"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Girallon.webp"
```
^statblock

## Environment

forest