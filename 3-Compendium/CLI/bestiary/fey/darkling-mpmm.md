---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Darkling"]
---
# [Darkling](3-Compendium\CLI\bestiary\fey/darkling-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 84, Volo's Guide to Monsters p. 134*  

The Summer Queen's curse causes a darkling's body to absorb light, which wizens the creature, much like the effect of rapid aging. For this reason, darklings cover their entire bodies with clothing when exposure to light is a risk. The light darklings absorb over the course of their lives explodes outward when they die, incinerating the creatures and much of their possessions.

## Darklings

Ancient legends speak of a seelie fey who betrayed the Summer Queen. In the Summer Queens' wrath, she cursed every member of his house. The seelie fey's true name has been stricken from history, but the stories call him Dubh Catha ("Dark Crow" in Common), and other Fey refer to the house's descendants as dubh sith—"darklings." Darklings dwell in secluded caverns and chambers beneath the towns of other species. From such enclaves, they quietly ply their trade as thieves and assassins.

```statblock
"name": "Darkling (MPMM)"
"size": "Small"
"type": "fey"
"alignment": "Typically  Chaotic Neutral"
"ac": !!int "14"
"ac_class": "leather armor"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"stats":
- !!int "9"
- !!int "16"
- !!int "12"
- !!int "10"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "2"
  "Stealth": !!int "7"
  "Perception": !!int "5"
  "Acrobatics": !!int "5"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 15"
"languages": "Elvish, Sylvan"
"cr": "1/2"
"traits":
- "desc": "When the darkling dies, nonmagical light flashes out from it in a 10-foot\
    \ radius as its body and possessions, other than metal or magic objects, burn\
    \ to ash. Any creature in that area must succeed on a DC 10 Constitution saving\
    \ throw or be blinded until the end of its next turn."
  "name": "Death Flash"
- "desc": "While in bright light, the darkling has disadvantage on attack rolls, as\
    \ well as on Wisdom (Perception) checks that rely on sight."
  "name": "Light Sensitivity"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage plus 7 (2d6) necrotic damage."
  "name": "Dagger"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Darkling.webp"
```
^statblock

## Environment

forest, swamp, underdark, urban