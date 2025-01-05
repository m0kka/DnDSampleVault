---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ftd
- ttrpg-cli/monster/cr/19
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/gem
statblock: inline
aliases: ["Ancient Crystal Dragon"]
---
# [Ancient Crystal Dragon](3-Compendium\CLI\bestiary\dragon/ancient-crystal-dragon-ftd.md)
*Source: Fizban's Treasury of Dragons p. 170*  

Shimmering with radiant energy and brimming with life, crystal dragons enjoy an innate psionic connection to the Positive Plane that suffuses their bodies as well as their personalities with light. Though they prefer to live in desolate, frigid regions, many of them are among the friendliest of dragonkind, nurturing and optimistic.

## Inner Glow

When they hatch, crystal dragons have dull gray scales, with a few white or clear crystalline points, allowing the wyrmlings to blend in to rocky terrain in the face of danger. As they age, their scales turn snow white, then slowly fade to transparency. The oldest crystal dragons have scales of perfect clarity that bend and refract light, sometimes making them difficult to see clearly.

The radiant energy of the Positive Plane shimmers in crystal dragons' scales. It glows like starlight between their bodies and the spines and horns that hover close to their heads and backs. These horns shift with the dragon's mood: bristling with anger, lying back with fear or suspicion, and rippling in side-to-side waves with amusement or joy.

## Visions in Starlight

Many crystal dragons study the stars, recording their observations of the night sky and tracking the signs written in starlight. They read these signs as omens, giving them glimpses of what is to come, and they eagerly examine the potential futures of any creatures who come to them in peace.

Crystal dragons' connection to the radiant forces of the Positive Plane fosters a nurturing, optimistic attitude in most of these dragons. They sometimes adopt the abandoned eggs or hatchlings of other dragons; many a white wyrmling has been raised in the caring environment of a crystal dragon's lair. But they fiercely oppose destructive forces in their home territories, which sometimes leads nearby frost giants and white dragons to put aside their mutual enmity to hunt them.

## Glittering Hoards

For their treasure hoards, crystal dragons prize diamonds and baubles that refract light, collections of prophecy, works on astronomy, and star charts. When it comes to magical treasure, they seek items and spells that predict the future, create or manipulate light, or channel positive energy for healing and nurturing.

## A Crystal Dragon's Lair

Crystal dragons dwell in cold regions, where they construct ice and snow structures reminiscent of castles but open to the sky. Glittering crystals scattered about their lairs glow with gathered starlight, and caves or tunnels beneath the ice and snow provide protected areas for their hoards. They use their burrowing ability to dig blinds and secret passages throughout their lairs, allowing them to move easily—and potentially unnoticed.

The challenge rating of a legendary crystal dragon increases by 1 when it's encountered in its lair.

```statblock
"name": "Ancient Crystal Dragon (FTD)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "gem"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "222"
"hit_dice": "12d20 + 96"
"stats":
- !!int "25"
- !!int "12"
- !!int "26"
- !!int "20"
- !!int "16"
- !!int "21"
"speed": "40 ft., burrow 40 ft., climb 40 ft., fly 80 ft."
"saves":
  "Charisma": !!int "11"
  "Dexterity": !!int "7"
  "Wisdom": !!int "9"
  "Constitution": !!int "14"
"skillsaves":
  "Stealth": !!int "13"
  "Perception": !!int "15"
  "Survival": !!int "9"
"damage_resistances": "cold, radiant"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 25"
"languages": "Common, Draconic, telepathy 120 ft."
"cr": "19"
"traits":
- "desc": "The dragon casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 19):\n\nAt\
    \ will: dancing lights, guidance\n\n1/day each: command, divination, greater\
    \ restoration, hypnotic pattern, invisibility"
  "name": "Spellcasting (Psionics)"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The dragon makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 15 ft., one target. Hit: 18\
    \ (2d10 + 7) piercing damage plus 9 (2d8) radiant damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d6 + 7) slashing damage."
  "name": "Claw"
- "desc": "The dragon exhales a burst of brilliant radiance in a 90-foot cone. Each\
    \ creature in that area must make a DC 22 Constitution saving throw, taking 49\
    \ (11d8) radiant damage on a failed save, or half as much damage on a successful\
    \ one. The dragon then gains 25 temporary hit points by absorbing a portion of\
    \ the radiant energy."
  "name": "Scintillating Breath (Recharge 5-6)"
"bonus_actions":
- "desc": "The dragon magically transforms into any creature that is Medium or Small,\
    \ while retaining its game statistics (other than its size). This transformation\
    \ ends if the dragon is reduced to 0 hit points or uses a bonus action to end\
    \ it."
  "name": "Change Shape"
- "desc": "The dragon magically teleports to an unoccupied space it can see within\
    \ 60 feet of it."
  "name": "Psychic Step"
"legendary_actions":
- "desc": "The dragon makes one Claw attack."
  "name": "Claw"
- "desc": "The dragon uses Psychic Step or Spellcasting."
  "name": "Psionics (Costs 2 Actions)"
- "desc": "The dragon releases a searing beam of starlight at a creature that it can\
    \ see within 60 feet of it. The target must succeed on a DC 19 Dexterity saving\
    \ throw or take 38 (11d6) radiant damage."
  "name": "Starlight Strike (Costs 3 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the dragon can take one\
    \ of the following lair actions; the dragon can't take the same lair action two\
    \ rounds in a row:"
  "name": ""
- "desc": "- Beguiling Whisper. The dragon telepathically whispers to one creature\
    \ within range of the dragon's telepathy. The creature must succeed on a DC 15\
    \ Wisdom saving throw or be charmed by the dragon until initiative count 20 on\
    \ the next round. A creature charmed in this way obeys to the best of its ability\
    \ any command the dragon issues that isn't directly harmful to the creature. \
    \ \n- Ice Passage. The dragon can open a passage through a wall of ice or\
    \ snow that is up to 5 feet thick, creating an opening up to 30 feet wide and\
    \ high.  \n- Starlight's Gleam. The dragon chooses a point it can see in the\
    \ lair. Gleaming starlight radiates from that point to fill a 10-foot-radius sphere\
    \ with dim light. Each creature other than the dragon in that area when the light\
    \ appears must succeed on a DC 15 Dexterity saving throw or take 13 (2d12) radiant\
    \ damage and be outlined in the glow. Attack rolls made against an outlined creature\
    \ have advantage, and the creature can't hide or benefit from being invisible.\
    \ The starlight and the glow around any creature fades on initiative count 20\
    \ on the next round.  "
  "name": ""
"regional_effects":
- "desc": "The region surrounding a legendary crystal dragon's lair is altered by\
    \ the dragon's magic, creating one or more of the following effects:"
  "name": ""
- "desc": "- Clear Skies. The skies above a crystal dragon's lair remain clear\
    \ and free of precipitation unless magically altered. Winds blow lightly, posing\
    \ little threat to those approaching the lair, and visibility is the best possible\
    \ for the time of day.  \n- Crystal Profusion. Plentiful quartz crystals form\
    \ in natural stone within 6 miles of the lair, particularly in places where natural\
    \ light can shine on the crystals.  \n- Icy Sight. Ice and quartz within 6\
    \ miles of the lair become conduits for the dragon's psionic presence. As an action,\
    \ the dragon can cast the clairvoyance spell, requiring no spell components and\
    \ targeting any ice or quartz crystals in that region.  \n- Positive Energy.\
    \ Any creature that finishes a long rest within 6 miles of the lair regains two\
    \ additional spent Hit Dice.  \n- Thriving Wildlife. Animal populations flourish\
    \ within 6 miles of the lair. Ability checks made to forage for food by hunting,\
    \ fishing, or trapping in that area are made with advantage.  "
  "name": ""
- "desc": "If the dragon dies, the animal population near the lair returns to normal\
    \ levels over the course of 1d10 days. The increased Hit Die recovery ends immediately.\
    \ The existing abundance of quartz crystals remains, but new crystals form at\
    \ a normal rate."
  "name": ""
"source":
- "FTD"
"image": "bestiary/tokens/FTD/Ancient Crystal Dragon.webp"
```
^statblock