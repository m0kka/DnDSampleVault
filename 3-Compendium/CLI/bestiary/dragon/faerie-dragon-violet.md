---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/dragon
statblock: inline
aliases: ["Faerie Dragon (Violet)"]
---
# [Faerie Dragon (Violet)](3-Compendium\CLI\bestiary\dragon/faerie-dragon-violet.md)
*Source: Monster Manual p. 133, Explorer's Guide to Wildemount, The Book of Many Things*  

A faerie dragon is a cat-sized dragon with butterfly wings. It wears a sharp-toothed grin and expresses its delight by the twitching of its tail, its merriment fading only if it is attacked.

## Invisible Tricksters

The only warning of a faerie dragon's presence is a stifled giggle. The dragon stays out of sight, watching invisibly as its victims contend with its pranks. When its fun is done, the dragon might reveal itself, depending on the disposition of its "prey."

## Friendly and Bright

A faerie dragon has a sharp mind, a fondness for treasure and good company, and a puckish sense of humor. Travelers can play to a faerie dragon's draconic nature by offering it "treasure" in the form of sweets, baked goods, and baubles in exchange for information or safe passage through its territory.

## The Colors of Age

A faerie dragon's scales change hue as it ages, moving through all the colors of the rainbow. All faerie dragons have innate spellcasting ability, gaining new spells as they mature.

| Dragon Color | Age Range |
|--------------|-----------|
| Red | 5 years or less |
| Orange | 6–10 years |
| Yellow | 11–20 years |
| Green | 21–30 years |
| Blue | 31–40 years |
| Indigo | 41–50 years |
| Violet | 51 years or more |
^dragon-color-age-range

CR 1 (200 XP) For a red, orange, or yellow faerie dragon; 2 (450 XP) for a green, blue, indigo, or violet faerie dragon

```statblock
"name": "Faerie Dragon (Violet)"
"size": "Tiny"
"type": "dragon"
"alignment": "Chaotic Good"
"ac": !!int "15"
"hp": !!int "14"
"hit_dice": "4d4 + 4"
"stats":
- !!int "3"
- !!int "20"
- !!int "13"
- !!int "14"
- !!int "12"
- !!int "16"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "3"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Draconic, Sylvan"
"cr": "2"
"traits":
- "desc": "The dragon's innate spellcasting ability is Charisma (spell save DC 13).\
    \ It can innately cast a number of spells, requiring no material components:\n\
    \n1/day each: color spray, dancing lights, hallucinatory terrain, mage hand,\
    \ major image, minor illusion, mirror image, polymorph, suggestion"
  "name": "Innate Spellcasting"
- "desc": "A faerie dragon's scales change hue as it ages, moving through all the\
    \ colors of the rainbow. All faerie dragons have innate spellcasting ability,\
    \ gaining new spells as they mature.\n\nRed—5 years or less\n\nOrange—6–10 years\n\
    \nYellow—11–20 years\n\nGreen—21–30 years\n\nBlue—31–40 years\n\nIndigo—41–50\
    \ years\n\nViolet—51 years or more\n\nA green or older faerie dragon's CR increases\
    \ to 2."
  "name": "The Colors of Age"
- "desc": "As a bonus action, the dragon can magically turn invisible until its concentration\
    \ ends (as if concentrating on a spell). Any equipment the dragon wears or carries\
    \ is invisible with it."
  "name": "Superior Invisibility"
- "desc": "Using telepathy, the dragon can magically communicate with any other faerie\
    \ dragon within 60 feet of it."
  "name": "Limited Telepathy"
- "desc": "The faerie dragon has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 1 piercing\
    \ damage."
  "name": "Bite"
- "desc": "The dragon exhales a puff of euphoria gas at one creature within 5 feet\
    \ of it. The target must succeed on a DC 11 Wisdom saving throw, or for 1 minute,\
    \ the target can't take reactions and must roll a d6 at the start of each of its\
    \ turns to determine its behavior during the turn:\n\n1–4. The target takes no\
    \ action or bonus action and uses all of its movement to move in a random direction.\n\
    \n5–6. The target doesn't move, and the only thing it can do on its turn is make\
    \ a DC 11 Wisdom saving throw, ending the effect on itself on a success."
  "name": "Euphoria Breath (Recharge 5-6)"
"lair_actions":
- "desc": "As they are presented in the \"Monster Manual\", faerie dragons don't have\
    \ access to lair actions while in their lairs. At your discretion, a green or\
    \ [older faerie dragon](/3-Compendium/CLI/bestiary/dragon/faerie-dragon-violet.md)\
    \ can take one of the following lair actions on initiative count 20 (losing initiative\
    \ ties):"
  "name": ""
- "desc": "- Chaotic Aura. The faerie dragon creates misdirecting currents of\
    \ air and magic around itself. Until initiative count 20 on the next round, whenever\
    \ a ranged attack roll misses the dragon, reroll the attack against a random creature\
    \ within 30 feet of the dragon that doesn't have total cover against the attack.\
    \  \n- Grasping Plants. The faerie dragon causes roots and vines to temporarily\
    \ grow around it; until initiative count 20 on the next round, the ground within\
    \ 20 feet of the dragon is \"difficult terrain\".  "
  "name": ""
"regional_effects":
- "desc": "The region containing a faerie dragon's lair can be transformed by its\
    \ presence, creating one or more of the following effects:"
  "name": ""
- "desc": "- Compulsory Offering. The first time a creature comes within 1 mile\
    \ of the faerie dragon's lair, the creature must succeed on a DC 15 Wisdom saving\
    \ throw or feel an overwhelming compulsion to leave an offering worth at least\
    \ 5 gp stashed in an out-of-the-way place. The dragon immediately senses the location\
    \ of this gift. A creature can be affected only once by this compulsion.  \n-\
    \ Malleable Time. Time is fluid within 1 mile of the faerie dragon's lair,\
    \ flowing somewhere between half and twice its normal speed.  \n- Mischief Afoot.\
    \ Sapient creatures that spend a year within 5 miles of the faerie dragon's lair\
    \ feel the persistent urge to play pranks on others.  "
  "name": ""
- "desc": "If the faerie dragon dies, these effects fade over the course of 1d10 days."
  "name": ""
"source":
- "MM"
- "EGW"
- "BMT"
"image": "bestiary/tokens/MM/Faerie Dragon (Violet).webp"
```
^statblock

## Environment

forest