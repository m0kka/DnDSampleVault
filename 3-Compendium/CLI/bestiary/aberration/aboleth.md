---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Aboleth"]
---
# [Aboleth](3-Compendium\CLI\bestiary\aberration/aboleth.md)
*Source: Monster Manual p. 13, The Book of Many Things. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Before the coming of the gods, aboleths lurked in primordial oceans and underground lakes. They reached out with their minds and seized control of the burgeoning life-forms of the mortal realm, making those creatures their slaves. Their dominance made them like gods. Then the true gods appeared, smashing the aboleths' empire and freeing their slaves. Aboleths have never forgotten.

## Eternal Memories

Aboleths have flawless memories. They pass on their knowledge and experience from generation to generation. Thus, the injury of their defeat by the gods remains perfectly preserved in their minds.

Aboleths' minds are treasure troves of ancient lore, recalling moments from prehistory with perfect clarity. They plot patiently and intricately across eons. Few creatures can conceive of the extent of an aboleth's plan.

### Gods in the Lake

Aboleths dwell in watery environments, including ocean abysses, deep lakes, and the Elemental Plane of Water. In these domains and the lands that adjoin them, aboleths are like gods, demanding worship and obedience from their subjects. When they consume other creatures, aboleths add the knowledge and experiences of their prey to their eternal memories. Aboleths use their telepathic powers to read the minds of creatures and know their desires. An aboleth uses this knowledge to gain a creature's loyalty, promising to fulfill such wants in exchange for obedience. Within its lair, the aboleth can further use its powers to override senses, granting creatures, such as its followers, the illusion of promised rewards.

## Enemies of the Gods

The aboleths' fall from power is written in stark clarity on their flawless memories, for aboleths never truly die. If an aboleth's body is destroyed, its spirit returns to the Elemental Plane of Water, where a new body coalesces for it over days or months.

Ultimately, aboleths dream of overthrowing the gods and regaining control of the world. Aboleths have had untold eons to plot and to prepare their plans for perfect execution.

> [!quote] A quote from Vaqir Zekh'r, githzerai philosopher and author of The Far Realm: Real Yet Unreal  
> 
> Could it be that the aboleths are older than the gods... that before the divine ones came to be, such horrors shaped the multiverse? Now there's a chilling thought.

## An Aboleth's Lair

Aboleths lair in subterranean lakes or the rocky depths of the ocean, often surrounded by the ruins of an ancient, fallen aboleth city. An aboleth spends most of its existence underwater, surfacing occasionally to treat with visitors or deranged worshipers.

```statblock
"name": "Aboleth"
"size": "Large"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "135"
"hit_dice": "18d10 + 36"
"stats":
- !!int "21"
- !!int "9"
- !!int "15"
- !!int "18"
- !!int "15"
- !!int "18"
"speed": "10 ft., swim 40 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "8"
  "Constitution": !!int "6"
"skillsaves":
  "Perception": !!int "10"
  "History": !!int "12"
"senses": "darkvision 120 ft., passive Perception 20"
"languages": "Deep Speech, telepathy 120 ft."
"cr": "10"
"traits":
- "desc": "The aboleth can breathe air and water."
  "name": "Amphibious"
- "desc": "While underwater, the aboleth is surrounded by transformative mucus. A\
    \ creature that touches the aboleth or that hits it with a melee attack while\
    \ within 5 feet of it must make a DC 14 Constitution saving throw. On a failure,\
    \ the creature is diseased for 1d4 hours. The diseased creature can breathe only\
    \ underwater."
  "name": "Mucous Cloud"
- "desc": "If a creature communicates telepathically with the aboleth, the aboleth\
    \ learns the creature's greatest desires if the aboleth can see the creature."
  "name": "Probing Telepathy"
"actions":
- "desc": "The aboleth makes three tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 12 (2d6\
    \ + 5) bludgeoning damage. If the target is a creature, it must succeed on a DC\
    \ 14 Constitution saving throw or become diseased. The disease has no effect for\
    \ 1 minute and can be removed by any magic that cures disease. After 1 minute,\
    \ the diseased creature's skin becomes translucent and slimy, the creature can't\
    \ regain hit points unless it is underwater, and the disease can be removed only\
    \ by heal or another disease-curing spell of 6th level or higher. When the creature\
    \ is outside a body of water, it takes 6 (1d12) acid damage every 10 minutes unless\
    \ moisture is applied to the skin before 10 minutes have passed."
  "name": "Tentacle"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 15 (3d6\
    \ + 5) bludgeoning damage."
  "name": "Tail"
- "desc": "The aboleth targets one creature it can see within 30 feet of it. The target\
    \ must succeed on a DC 14 Wisdom saving throw or be magically charmed by the aboleth\
    \ until the aboleth dies or until it is on a different plane of existence from\
    \ the target. The charmed target is under the aboleth's control and can't take\
    \ reactions, and the aboleth and the target can communicate telepathically with\
    \ each other over any distance.\n\nWhenever the charmed target takes damage, the\
    \ target can repeat the saving throw. On a success, the effect ends. No more than\
    \ once every 24 hours, the target can also repeat the saving throw when it is\
    \ at least 1 mile away from the aboleth."
  "name": "Enslave (3/Day)"
"legendary_actions":
- "desc": "The aboleth makes a Wisdom (Perception) check."
  "name": "Detect"
- "desc": "The aboleth makes one tail attack."
  "name": "Tail Swipe"
- "desc": "One creature charmed by the aboleth takes 10 (3d6) psychic damage, and\
    \ the aboleth regains hit points equal to the damage the creature takes."
  "name": "Psychic Drain (Costs 2 Actions)"
"source":
- "MM"
- "BMT"
"image": "bestiary/tokens/MM/Aboleth.webp"
```
^statblock

## Environment

underdark