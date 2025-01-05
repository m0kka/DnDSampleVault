---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
aliases: ["Troll Mutate"]
---
# [Troll Mutate](3-Compendium\CLI\bestiary\giant/troll-mutate-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 187*  

When exposed to corrupting alien energy, such as that found near a gate to the Far Realm or the strange magic that emanates through the Underdark, a regenerating troll undergoes strange mutations. Among the most common mutations are wings, stretchable bodies, resistance to magic, and a strange reflective psychic property. Many troll mutates also have small additional limbs and eyes, externalized organs, and other variations.

## Trolls

The dwarven tale titled*The Saga of Gnarldan Steelshield*claims the god Vaprak the Destroyer came into being when Annam was injured and his blood spilled on the ground. The saga further claims that trolls were born similarly when Vaprak's blood was spilled. Whatever the truth of their origin, trolls embody life's steadfast determination to grow and thrive despite all obstacles.

Trolls' rapid healing makes them subject to bizarre mutations, particularly when they regenerate in unusual environments or heal from extraordinary magical wounds. Troll amalgams and troll mutates are two examples of such strangely mutated forms.

> [!quote] A quote from Bigby  
> 
> I'll just keep reminding myself that the gods delight in the variety of their creations, new wonders are revealed every day, and the multiverse is much larger than I can imagine. And that's a good thing!

> [!quote] A quote from Diancastra  
> 
> Excellent. But these trolls are loathsome.


```statblock
"name": "Troll Mutate (BGG)"
"size": "Large"
"type": "giant"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"stats":
- !!int "19"
- !!int "13"
- !!int "18"
- !!int "17"
- !!int "9"
- !!int "12"
"speed": "30 ft., fly 30 ft. (winged form only)"
"saves":
  "Intelligence": !!int "6"
  "Constitution": !!int "7"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"senses": "blindsight 60 ft., passive Perception 15"
"languages": "Giant, telepathy 60 ft."
"cr": "7"
"traits":
- "desc": "When the troll mutate is created, it gains one of four possible body mutations\
    \ at random: 1, Elastic Body; 2, Psionic Mirror; 3, Spell Scarred; or 4, Winged\
    \ Form. This mutation determines certain traits in this stat block."
  "name": "Mutation"
- "desc": "The mutate can move through a space as narrow as 1 inch without squeezing."
  "name": "Amorphous (Elastic Body Only)"
- "desc": "The mutate has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance (Spell Scarred Only)"
- "desc": "If the mutate takes psychic damage, each creature within 20 feet of it\
    \ takes that damage as well."
  "name": "Psychic Rebuke (Psionic Mirror Only)"
- "desc": "The mutate regains 10 hit points at the start of its turn. If the mutate\
    \ takes acid or fire damage, this trait doesn't function at the start of the mutate's\
    \ next turn. The mutate dies only if it starts its turn with 0 hit points and\
    \ doesn't regenerate. If the mutate starts its turn with 0 hit points and regenerates,\
    \ it randomly gains a mutation it doesn't already have (up to a maximum of four\
    \ mutations)."
  "name": "Regeneration"
"actions":
- "desc": "The mutate makes two Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft. (or 15 ft. if the mutate\
    \ has the Elastic Body mutation), one target. Hit: 15 (2d10 + 4) slashing damage\
    \ plus 9 (2d8) force damage."
  "name": "Rend"
- "desc": "The mutate unleashes a wave of psychic energy. Each creature within 30\
    \ feet of the mutate must make a DC 14 Intelligence saving throw, taking 28 (8d6)\
    \ psychic damage on a failed save, or half as much damage on a successful one."
  "name": "Psychic Burst (Recharge 5-6)"
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Troll Mutate.webp"
```
^statblock