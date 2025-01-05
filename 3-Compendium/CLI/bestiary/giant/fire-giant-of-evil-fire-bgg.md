---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
aliases: ["Fire Giant of Evil Fire"]
---
# [Fire Giant of Evil Fire](3-Compendium\CLI\bestiary\giant/fire-giant-of-evil-fire-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 139*  

A fire giant is born around flame, works with flame, and lives among flames, but a fire giant who gazes into flames too deeply may see the Prince of Evil Fire, Imix, gazing back. Giants who fall to Imix's corruption might leave their homes to join with likeminded cultists, but others remain within their communities to pursue Imix's destructive agenda.

A fire giant of Evil Fire forges a set of armor and weapons in flames blessed by Imix. The giant can then call on these magical flames to strike the foes of the Eternal Flame. The armor forged in these flames welds to the flesh, so while the giant isn't burned, the armor can't be removed once donned. When the giant dies, the armor explodes as a final gift from the All-Consuming Fire.

```statblock
"name": "Fire Giant of Evil Fire (BGG)"
"size": "Huge"
"type": "giant"
"alignment": "typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "plate"
"hp": !!int "150"
"hit_dice": "12d12 + 72"
"stats":
- !!int "25"
- !!int "9"
- !!int "23"
- !!int "10"
- !!int "19"
- !!int "14"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "8"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "11"
  "Perception": !!int "8"
"damage_immunities": "fire"
"senses": "passive Perception 18"
"languages": "Common, Giant, Ignan"
"cr": "10"
"traits":
- "desc": "When the giant drops to 0 hit points, its armor explodes, destroying the\
    \ giant's body and scattering the armor as shrapnel. Creatures within 10 feet\
    \ of the giant when its armor explodes must make a DC 18 Dexterity saving throw,\
    \ taking 21 (6d6) piercing damage on a failed save, or half as much damage on\
    \ a successful one."
  "name": "Shrapnel Explosion"
"actions":
- "desc": "The giant makes two Searing Scepter attacks or two Bolt of Imix attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 17\
    \ (3d6 + 7) bludgeoning damage plus 9 (2d8) fire damage, and the target is magically\
    \ branded. While branded in this way, the target becomes visible if it's invisible,\
    \ can't become invisible, and sheds dim light in a 5-foot radius. The brand disappears\
    \ after 24 hours, or it can be removed from a creature or an object by any spell\
    \ that ends a curse."
  "name": "Searing Scepter"
- "desc": "Ranged Spell Attack: +8 to hit, range 120 ft., one target. Hit: 20\
    \ (3d10 + 4) fire damage, and the target must succeed on a DC 16 Wisdom saving\
    \ throw or have the frightened condition until the end of the target's next turn."
  "name": "Bolt of Imix"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Fire Giant of Evil Fire.webp"
```
^statblock