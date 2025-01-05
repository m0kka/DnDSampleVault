---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Ironscale Hydra"]
---
# [Ironscale Hydra](3-Compendium\CLI\bestiary\monstrosity/ironscale-hydra-mot.md)
*Source: Mythic Odysseys of Theros p. 231*  

Five-headed ironscale hydras lurk in the wild places of the world, being common foes for heroes seeking to test their mettle against terrors worthy of the gods' notice. Most ironscale hydras inhabit lakes and boggy caverns, from which they hunt unwary creatures that come for a drink or swim.

What krakens are to the sea and dragons are to the sky, hydras are to the lands of Theros. Various hydras dwell at the fringes of civilization, from the bog-dwelling hydras known across the multiverse to massive ironscale hydras that lurk in deep wildernesses. Beyond even these exist serpentine horrors born of the whims of foul gods, like the legendary hydra Polukranos.

```statblock
"name": "Ironscale Hydra (MOT)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "181"
"hit_dice": "11d20 + 66"
"stats":
- !!int "22"
- !!int "10"
- !!int "22"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "40 ft., swim 40 ft."
"skillsaves":
  "Perception": !!int "8"
"damage_immunities": "acid"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": ""
"cr": "12"
"traits":
- "desc": "When the hydra takes piercing or slashing damage, each creature within\
    \ 5 feet of the hydra takes 9 (2d8) acid damage."
  "name": "Acidic Blood"
- "desc": "The hydra can hold its breath for 1 hour."
  "name": "Hold Breath"
- "desc": "The hydra has five heads. While it has more than one head, the hydra has\
    \ advantage on saving throws against being blinded, charmed, deafened, frightened,\
    \ stunned, or knocked unconscious. Whenever the hydra takes 35 or more damage\
    \ in a single turn, one of its heads dies. If all its heads die, the hydra dies.\
    \ At the end of its turn, it grows two heads for each of its heads that died since\
    \ its last turn, unless it has taken fire damage since its last turn. The hydra\
    \ regains 10 hit points for each head regrown in this way."
  "name": "Multiple Heads"
- "desc": "For each head the hydra has beyond one, it gets an extra reaction that\
    \ can be used only for opportunity attacks."
  "name": "Reactive Heads"
- "desc": "While the hydra sleeps, at least one of its heads is awake."
  "name": "Wakeful"
"actions":
- "desc": "The hydra makes as many bite attacks as it has heads."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 15 ft., one target. Hit: 17\
    \ (2d10 + 6) piercing damage."
  "name": "Bite"
"source":
- "MOT"
"image": "bestiary/tokens/MOT/Ironscale Hydra.webp"
```
^statblock