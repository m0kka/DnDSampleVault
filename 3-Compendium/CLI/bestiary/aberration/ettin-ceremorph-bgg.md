---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Ettin Ceremorph"]
---
# [Ettin Ceremorph](3-Compendium\CLI\bestiary\aberration/ettin-ceremorph-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 133*  

Mind flayers, which are described in the*Monster Manual*, are created through ceremorphosis, a process that begins with the implantation of an illithid tadpole in the brain of a Humanoid host. Mind flayers have subjected giants to this process in an effort to create larger, stronger mind flayers, but those experiments all ended in failure: a giant's body is simply too large for a single tadpole to take over. Ettins, however, proved to be perfect subjects. An ettin's two brains provide sufficient food for two tadpoles, and the two tadpoles are able to transform the entirety of the ettin's body, creating an ettin ceremorph. As part of the transformation process, one of the ettin's heads sinks into the body, with that brain focused on controlling the body. The other head focuses on cogitation and psionic power, though its power is not as great as a mind flayer's.

Ettin ceremorphs serve mind flayer colonies, protecting the elder brains that rule the communities and guarding their treasures. They retain no memory of their previous existence as ettins.

```statblock
"name": "Ettin Ceremorph (BGG)"
"size": "Large"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "104"
"hit_dice": "11d10 + 44"
"stats":
- !!int "18"
- !!int "14"
- !!int "18"
- !!int "18"
- !!int "15"
- !!int "14"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "7"
"skillsaves":
  "Perception": !!int "8"
"damage_resistances": "psychic"
"condition_immunities": "charmed, frightened, stunned, unconscious"
"senses": "darkvision 120 ft., passive Perception 18"
"languages": "Deep Speech, Giant, telepathy 60 ft., Undercommon"
"cr": "8"
"traits":
- "desc": "The ceremorph has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The ceremorph makes one Slam attack and one Tentacles attack. The ceremorph\
    \ can replace one of the attacks with a Mind Bolt attack, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 22 (4d8\
    \ + 4) bludgeoning damage."
  "name": "Slam"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one creature. Hit: 15\
    \ (2d10 + 4) psychic damage. If the target is Large or smaller, it has the grappled\
    \ condition (escape DC 14) and must succeed on a DC 15 Intelligence saving throw\
    \ or have the stunned condition until this grapple ends."
  "name": "Tentacles"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one incapacitated Humanoid\
    \ grappled by the ceremorph. Hit: 55 (10d10) piercing damage. If this damage\
    \ reduces the target to 0 hit points, the ceremorph kills the target by extracting\
    \ and devouring its brain."
  "name": "Extract Brain"
- "desc": "Ranged Spell Attack: +7 to hit, range 120 ft., one creature. Hit: 17\
    \ (2d12 + 4) psychic damage, and the target must succeed on a DC 15 Intelligence\
    \ saving throw or have the stunned condition until the end of its next turn."
  "name": "Mind Bolt (3/Day)"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Ettin Ceremorph.webp"
```
^statblock