---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
aliases: ["Shadar-kai Gloom Weaver"]
---
# [Shadar-kai Gloom Weaver](3-Compendium\CLI\bestiary\humanoid/shadar-kai-gloom-weaver-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 213, Mordenkainen's Tome of Foes p. 224*  

Although they're formidable warriors, gloom weavers are often content to hide in the shadows, watching as their very presence affects their victims. Their bleak energy weighs down the heart, causing those nearby to feel the approach of death. If detected, gloom weavers use their shadow magic to reduce enemies to ghastly corpses.

## Shadar-kai

In the gloom of the Shadowfell live shadar-kai, elves whose ancestors served the Raven Queen, a god of death and memory. They were brought to that realm in ages past, so long ago that they're now adapted to its cheerless environment, both physically and mentally.

Eons of exposure to the influence of the Shadowfell has left shadar-kai often joyless and mournful. In that realm, they have pale hair, wrinkled gray skin, and swollen joints that give them a corpselike aspect. They appear more youthful while on other planes, but their skin always retains a deathly ashen hue. When in the Shadowfell, they detest mirrors and avoid keeping things that remind them of their age.

Shadar-kai of the Raven Queen watch over both the Shadowfell and the Material Plane, scouting out choice souls and tragedies that might please their deity. They are rumored to be able to coax worldly events along tragic paths for her amusement. The Raven Queen is famously cryptic even to her most devoted followers, however; their efforts are rewarded only with vague omens they interpret as best they can.

### Fortress of Memories

The shadar-kai who are most devoted to the Raven Queen serve her at the Fortress of Memories, her twisted castle in the Shadowfell. The fortress is a mournful place, filled with incessant echoes of the past. Flocks of ravens that act as the Raven Queen's eyes and ears darken the skies around it when they emerge from within, bearing her cryptic messages and omens far and wide across the multiverse.

Within the fortress are items that the Raven Queen finds irresistible: objects invested with deep feelings of sorrow, longing, or remorse. These items are brought to her as gifts from the shadar-kai, and include furniture, clocks, mirrors, jewels, and toys. Ghostly visions of people, places, and pets also appear in the fortress. Any of these things can spontaneously appear about her lair, every object and apparition being a metaphoric representation of some story—great or small—that was saturated with raw emotion.

Shadar-kai encountered outside the Shadowfell are often on quests to find the most sorrow-touched items they can find to bring back to their queen's gloomy castle.

```statblock
"name": "Shadar-kai Gloom Weaver (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Typically  Neutral Evil"
"ac": !!int "14"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"stats":
- !!int "11"
- !!int "18"
- !!int "14"
- !!int "15"
- !!int "12"
- !!int "18"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "8"
  "Constitution": !!int "6"
"damage_immunities": "necrotic"
"condition_immunities": "charmed, exhaustion"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Elvish"
"cr": "9"
"traits":
- "desc": "The shadar-kai casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 16):\n\
    \nAt will: arcane eye, mage armor, minor illusion, prestidigitation, speak\
    \ with dead\n\n1/day each: arcane gate, bane, confusion, darkness, fear, major\
    \ image, true seeing"
  "name": "Spellcasting"
- "desc": "Beasts and Humanoids (except elves) have disadvantage on saving throws\
    \ while within 10 feet of the shadar-kai."
  "name": "Burden of Time"
- "desc": "The shadar-kai has advantage on saving throws against being charmed, and\
    \ magic can't put it to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "The shadar-kai makes three Shadow Spear attacks. It can replace one attack\
    \ with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 30/120,\
    \ one target. Hit: 7 (1d6 + 4) piercing damage plus 26 (4d12) necrotic damage.\
    \ Hit or Miss: The spear magically returns to the shadar-kai's hand immediately\
    \ after a ranged attack."
  "name": "Shadow Spear"
"reactions":
- "desc": "When the shadar-kai takes damage, it turns invisible and teleports, along\
    \ with any equipment it is wearing or carrying, up to 60 feet to an unoccupied\
    \ space it can see. It remains invisible until the start of its next turn or until\
    \ it attacks or casts a spell."
  "name": "Misty Escape (Recharge 6-6)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Shadar-kai Gloom Weaver.webp"
```
^statblock

## Environment

underdark, urban