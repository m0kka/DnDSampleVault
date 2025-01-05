---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Star Spawn Mangler"]
---
# [Star Spawn Mangler](3-Compendium\CLI\bestiary\aberration/star-spawn-mangler-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 229, Mordenkainen's Tome of Foes p. 236, The Book of Many Things*  

> [!quote] A quote from Mordenkainen  
> 
> The cultists who blaspheme reality by calling out to Elder Evils often speak of a Far Realm from which these entities hail.
> 
> In truth, there is no one place or space from which they come. There is the multiverse of things that are, and there is the multiverse of things that shouldn't be.

A mangler is a low-slung, creeping horror with multiple gangly arms—it most often has six arms but can have any number from four to eight. Manglers creep along the ground or the walls, sticking to shadows and hiding in spots that seem too shallow or well-lit to conceal anything. They appear smaller than their true size, thanks to their hunched posture and emaciated frames. Cultists summon these creatures to serve as guards and assassins, two roles at which they excel.

## Star Spawn

> [!quote] A quote from Mordenkainen  
> 
> Stars don't spawn these creatures.
> 
> Such beautiful lights shouldn't be blamed for such balefulness.

The Material Plane represents only one small part of the multiverse. Beyond the best-known planes of existence lie realms alien to mortal life. Some are so hostile that even a moment's contact is enough to break a mortal's mind. Yet beings do exist that are native to these realms: entities that are ever hungering, searching, warring, and sometimes dreaming. These Elder Evils are far older than most of the mortal peoples and always inimical to such creatures' minds.

However much they might desire to enter and dominate the Material Plane, the Elder Evils are unable or unwilling to leave their realms. Some are imprisoned in their dimensions by external forces, some are inextricably bound to their home realities, and others simply can't find any way out.

The creatures known as star spawn are the heralds, servants, and soldiers of the Elder Evils, capable of taking on forms that can journey to the Material Plane. They arrive most often in the wake of a comet—or perhaps this phenomenon merely signals that star spawn are in the vicinity and available for communication. When the signs are right, cultists gather together, read aloud their blasphemous texts, and conduct the mind-searing rituals that guide star spawn into the world.

### Elder Evil Blessings

Disciples of certain Elder Evils can bestow supernatural gifts on those who serve that cult, including star spawn. The following powers are unique to specific cults; typically a creature has only one.

- Cult of Atropus, the World Born Dead  
- Cult of Borem, of the Lake of Boiling Mud  
- Cult of Haask, the Voice of Hargut  
- Cult of Tharizdun, the Chained God  
- Cult of Tyranthraxus, the Flamed One  

```statblock
"name": "Star Spawn Mangler (MPMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "14"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "8"
- !!int "18"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "7"
"speed": "40 ft., climb 40 ft."
"saves":
  "Dexterity": !!int "7"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "7"
"damage_resistances": "cold"
"damage_immunities": "psychic"
"condition_immunities": "charmed, frightened, prone"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Deep Speech"
"cr": "5"
"traits":
- "desc": "The mangler has advantage on initiative rolls."
  "name": "Ambusher"
"actions":
- "desc": "The mangler makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage. If the attack roll has advantage, the target also takes\
    \ 7 (2d6) psychic damage."
  "name": "Claw"
- "desc": "The mangler makes six Claw attacks. Either before or after these attacks,\
    \ it can move up to its speed without provoking opportunity attacks."
  "name": "Flurry of Claws (Recharge 5-6)"
"bonus_actions":
- "desc": "While in dim light or darkness, the mangler takes the Hide action."
  "name": "Shadow Stealth"
"source":
- "MPMM"
- "MTF"
- "BMT"
"image": "bestiary/tokens/MPMM/Star Spawn Mangler.webp"
```
^statblock