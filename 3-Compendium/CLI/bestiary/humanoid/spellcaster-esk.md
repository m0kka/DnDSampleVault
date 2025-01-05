---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/esk
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Spellcaster"]
---
# [Spellcaster](3-Compendium\CLI\bestiary\humanoid/spellcaster-esk.md)
*Source: Essentials Kit p. 63*  

```statblock
"name": "Spellcaster (ESK)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "leather armor"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "15"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
"skillsaves":
  "Investigation": !!int "4"
  "Religion": !!int "4"
  "Arcana": !!int "4"
"senses": "passive Perception 12"
"languages": "Common, plus one of your choice"
"traits":
- "desc": "The spellcaster's spellcasting ability is Wisdom (spell save DC 12, +4\
    \ to hit with spell attacks). The spellcaster has following cleric spells prepared:\n\
    \nCantrips (at will): guidance, sacred flame\n\n1st level (2 slots): cure\
    \ wounds"
  "name": "Spellcasting (Healer)"
- "desc": "The spellcaster's spellcasting ability is Intelligence (spell save DC 12,\
    \ +4 to hit with spell attacks). The spellcaster has following wizard spells prepared:\n\
    \nCantrips (at will): fire bolt, light\n\n1st level (2 slots): sleep"
  "name": "Spellcasting (Mage)"
- "desc": "Choose a role for the spellcaster: healer or mage. Your choice determines\
    \ which Spellcasting trait to use below."
  "name": "Magical Role"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands."
  "name": "Quarterstaff"
"source":
- "ESK"
"image": "bestiary/tokens/ESK/Spellcaster.webp"
```
^statblock