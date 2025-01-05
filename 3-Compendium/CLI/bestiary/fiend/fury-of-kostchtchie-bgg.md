---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Fury of Kostchtchie"]
---
# [Fury of Kostchtchie](3-Compendium\CLI\bestiary\fiend/fury-of-kostchtchie-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 148*  

Frost giants who struggle to rise in their ordning, along with those who reject Annam and his children, sometimes turn to the worship of the demon lord Kostchtchie. In the myths of these giants, Kostchtchie was once a frost giant of such tremendous might that he slew a demon lord in single combat, claimed its Abyssal realm for himself, and now waits for other frost giants to join him in conquering the rest of the Abyss.

When Kostchtchie answers the pleas of giants, he gives them supernatural strength and ferocious bloodlust. The giants' muscles expand, their arms extend past their knees, and bitter cold surrounds them. The demon lord's gifts come at a cost, though, as the giants' souls slowly burn away to fuel these newfound powers. Over time, the sensation of burning in the chest intensifies, driving these giants into a frenzy. The newly transformed Fiends quickly find that only combat can numb the burning.

```statblock
"name": "Fury of Kostchtchie (BGG)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "216"
"hit_dice": "16d12 + 112"
"stats":
- !!int "26"
- !!int "10"
- !!int "25"
- !!int "10"
- !!int "12"
- !!int "11"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "12"
"skillsaves":
  "Athletics": !!int "13"
  "Perception": !!int "6"
"damage_resistances": "fire, lightning, poison"
"damage_immunities": "cold"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Abyssal, Giant"
"cr": "14"
"traits":
- "desc": "A creature that starts its turn within 10 feet of the fury must succeed\
    \ on a DC 20 Constitution saving throw or take 11 (2d10) cold damage."
  "name": "Chilling Aura"
- "desc": "The fury has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The fury makes two Fist or Rock attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d8 + 8) bludgeoning damage plus 10 (3d6) cold damage, or 17 (5d6) cold damage\
    \ if the target took damage from the fury's Chilling Aura since the end of the\
    \ fury's last turn."
  "name": "Fist"
- "desc": "Ranged Weapon Attack: +13 to hit, range 60/240 ft., one target. Hit:\
    \ 30 (4d10 + 8) bludgeoning damage."
  "name": "Rock"
"bonus_actions":
- "desc": "The fury can move up to its speed toward an enemy it can see."
  "name": "Charge"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Fury of Kostchtchie.webp"
```
^statblock