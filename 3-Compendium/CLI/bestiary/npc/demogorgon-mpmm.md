---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/26
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Demogorgon"]
---
# [Demogorgon](3-Compendium\CLI\bestiary\npc/demogorgon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 90, Mordenkainen's Tome of Foes p. 144*  

> [!quote] A quote from Mordenkainen  
> 
> Are two heads better than one? In Demogorgon's case, the two double the horror and the chaos.

Prince of Demons, the Sibilant Beast, and Master of the Spiraling Depths, Demogorgon is the embodiment of chaos, confusion, and destruction, seeking to corrupt all that is good and undermine order in the multiverse, to see everything dragged howling into the infinite depths of the Abyss.

The demon lord is a meld of different forms. He has a saurian lower body and clawed, webbed feet; suckered tentacles sprout from the shoulders of his great apelike torso, which is surmounted by two hideous simian heads named Aameul and Hathradiah. Their gaze brings bewilderment and confusion to any who confront them.

Similarly, the spiraling Y sign of Demogorgon's cult drives those who contemplate it for too long to delirium. As a result, all followers of the Prince of Demons break with reality sooner or later.

## Cultists of Demogorgon

> [!note]
> See the Cult of Demogorgon entry.

## Demogorgon's Lair

Demogorgon makes his lair in a palace called Abysm, found on a layer of the Abyss known as the Gaping Maw. Demogorgon's lair is a place of confusion and duality; the portion of the palace that lies above water takes the form of two serpentine towers, each crowned by a skull-shaped minaret. There, Demogorgon's heads contemplate the mysteries of the arcane while arguing about how best to obliterate their rivals. The bulk of this palace extends deep underwater, in chill and darkened caverns.

```statblock
"name": "Demogorgon (MPMM)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "464"
"hit_dice": "32d12 + 256"
"stats":
- !!int "29"
- !!int "14"
- !!int "26"
- !!int "20"
- !!int "17"
- !!int "25"
"speed": "50 ft., swim 50 ft."
"saves":
  "Charisma": !!int "15"
  "Dexterity": !!int "10"
  "Wisdom": !!int "11"
  "Constitution": !!int "16"
"skillsaves":
  "Insight": !!int "11"
  "Perception": !!int "19"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "charmed, exhaustion, frightened, poisoned"
"senses": "truesight 120 ft., passive Perception 29"
"languages": "all, telepathy 120 ft."
"cr": "26"
"traits":
- "desc": "Demogorgon casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 23):\n\nAt will:\
    \ detect magic, major image\n\n1/day each: feeblemind, project image\n\n3/day\
    \ each: dispel magic, fear, telekinesis"
  "name": "Spellcasting"
- "desc": "If Demogorgon fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Demogorgon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Demogorgon has advantage on saving throws against being blinded, deafened,\
    \ stunned, or knocked unconscious."
  "name": "Two Heads"
"actions":
- "desc": "Demogorgon makes two Tentacle attacks. He can replace one attack with a\
    \ use of Gaze."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 28\
    \ (3d12 + 9) force damage. If the target is a creature, it must succeed on a DC\
    \ 23 Constitution saving throw, or its hit point maximum is reduced by an amount\
    \ equal to the damage taken. This reduction lasts until the target finishes a\
    \ long rest. The target dies if its hit point maximum is reduced to 0."
  "name": "Tentacle"
- "desc": "Demogorgon turns his magical gaze toward one creature he can see within\
    \ 120 feet of him. The target must succeed on a DC 23 Wisdom saving throw or suffer\
    \ one of the following effects (choose one or roll a d6):\n\n- 1–2 Beguiling\
    \ Gaze. The target is stunned until the start of Demogorgon's next turn or until\
    \ Demogorgon is no longer within line of sight.  \n- 3–4 Confusing Gaze. The\
    \ target suffers the effect of the confusion spell without making a saving throw.\
    \ The effect lasts until the start of Demogorgon's next turn. Demogorgon doesn't\
    \ need to concentrate on the spell.  \n- 5–6 Hypnotic Gaze. The target is\
    \ charmed by Demogorgon until the start of Demogorgon's next turn. Demogorgon\
    \ chooses how the charmed target uses its action, reaction, and movement.  "
  "name": "Gaze"
"legendary_actions":
- "desc": "Demogorgon uses Gaze and must use either Beguiling Gaze or Confusing Gaze."
  "name": "Gaze"
- "desc": "Melee Weapon Attack: +17 to hit, reach 15 ft., one target. Hit: 20\
    \ (2d10 + 9) bludgeoning damage plus 11 (2d10) necrotic damage."
  "name": "Tail"
- "desc": "Demogorgon uses Spellcasting."
  "name": "Cast a Spell (Costs 2 Actions)"
"source":
- "MPMM"
- "MTF"
"image": "bestiary/tokens/MPMM/Demogorgon.webp"
```
^statblock