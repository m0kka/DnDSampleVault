---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/24
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Dyrrn"]
---
# [Dyrrn](3-Compendium\CLI\bestiary\npc/dyrrn-erlw.md)
*Source: Eberron: Rising from the Last War p. 288*  

Dyrrn is known to its followers as the Corruptor, the Stealer of Thoughts, the Slithering Lord, and the Foul Labyrinth. In the lore of the Gatekeepers, it is said that Dyrrn plants thoughts in the weak minded—the seeds of terrible ideas that fester and grow. Those who are particularly brilliant often draw the attention of the Foul Labyrinth, which hungers to consume unique minds.

## Twisting Flesh and Thought

The mind flayers of Eberron know Dyrrn as the Overmind, and it serves as the cornerstone of their collective consciousness. Of all the daelkyr, the Corruptor is the most adept at twisting minds and bodies to create monsters. It was Dyrrn who turned goblinoid prisoners into the first dolgaunts and dolgrims, creating the legions that would savage the nations of Khorvaire. Dyrrn is also a prolific creator of symbionts—treasures that tempt people to bind alien entities to their flesh.

## Dyrrn's Cults

Dyrrn's lair touches the Eldeen Reaches, and the druids of the Towering Wood are always watching for Dyrrn's influence. At the start of the Last War, the dwarves of the Mror Holds discovered passages to the daelkyr's realm below their halls, and Dyrrn's cults have spread from there.

Mind flayers often work with Dyrrn's cults, many of which are obsessed with evolution—through the use of symbionts or by becoming an aberration. Those who worship the Stealer of Thoughts believe that Dyrrn will consume all sentient beings, except for its servants.

Dyrrn most often appears as a tall humanoid male with pale skin, clad in a heavy cassock of interwoven black leather that slithers unsettlingly around the daelkyr's form. Dyrrn can extend tentacles from its body, using them to extract the brains of others.

## Dyrrn's Lair

Dyrrn makes its lair in the Palace of Sinew, a horrid site shaped from the leftover flesh and bones of the daelkyr's sculpting. The walls of the palace undulate as air flows through them, as if the space were breathing.

## Madness of Dyrrn

If a creature goes mad in Dyrrn's lair or while it can see the daelkyr, it gains a form of indefinite madness. Roll on the Madness of Dyrrn table to determine the nature of this madness, which takes the form of a character flaw that lasts until cured. Chapter 8 of the "Dungeon Master's Guide" has more information on madness.

**Madness of Dyrrn**

`dice: [](dyrrn-erlw.md#^madness-of-dyrrn)`

| dice: d6 | Flaw (lasts until cured) |
|----------|--------------------------|
| 1 | "There's an illithid parasite living in my brain!" |
| 2 | "I can feel myself evolving into an aberration." |
| 3 | "Aberrations are the only natural things." |
| 4 | "A part of me has become a conscious entity." |
| 5 | "My opponents must bow down to a mind flayer!" |
| 6 | "Dyrrn and the mind flayers simply want to unite all sentient creatures in collective consciousness. And I receive messages from the group mind!" |
^madness-of-dyrrn

```statblock
"name": "Dyrrn (ERLW)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "325"
"hit_dice": "31d8 + 186"
"stats":
- !!int "26"
- !!int "21"
- !!int "22"
- !!int "26"
- !!int "23"
- !!int "24"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "14"
  "Wisdom": !!int "13"
  "Intelligence": !!int "15"
"skillsaves":
  "Insight": !!int "13"
  "Perception": !!int "13"
  "History": !!int "15"
  "Arcana": !!int "15"
"damage_resistances": "poison, psychic"
"condition_immunities": "blinded, charmed, exhaustion, frightened, poisoned, prone"
"senses": "truesight 120 ft., passive Perception 23"
"languages": "Deep Speech, telepathy 120 ft."
"cr": "24"
"traits":
- "desc": "If a creature tries to read Dyrrn's thoughts or deals psychic damage to\
    \ it, that creature must succeed on a DC 23 Intelligence saving throw or be stunned\
    \ for 1 minute. The stunned creature can repeat the saving throw at the end of\
    \ each of its turns, ending the effect on itself on a success."
  "name": "Alien Mind"
- "desc": "If Dyrrn fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Dyrrn has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "Dyrrn regains 20 hit points at the start of its turn. If Dyrrn takes radiant\
    \ damage, this trait doesn't function at the start of its next turn. Dyrrn dies\
    \ only if it starts its turn with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
- "desc": "As a bonus action, Dyrrn can teleport up to 30 feet to an unoccupied space\
    \ it can see."
  "name": "Teleport"
"actions":
- "desc": "Dyrrn makes one Tentacle Whip attack and uses its Corruption once. Dyrrn\
    \ can replace its Tentacle Whip attack with Extract Brain if it has a creature\
    \ grappled."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 10 ft., one target. Hit: 24\
    \ (3d10 + 8) slashing damage. If the target is a Medium or smaller creature, it\
    \ is grappled (escape DC 23), pulled into an unoccupied space within 5 feet of\
    \ Dyrrn, and must succeed on a DC 23 Intelligence saving throw or be stunned until\
    \ this grapple ends. Dyrrn can't use the same tentacle whip on another target\
    \ until this grapple ends. Dyrrn has two tentacle whips."
  "name": "Tentacle Whip"
- "desc": "Dyrrn targets one creature it can see within 60 feet of it. The target\
    \ must succeed on a DC 23 Constitution saving throw or take 22 (4d6 + 8) necrotic\
    \ damage and become corrupted for 1 minute.\n\nA corrupted creature's flesh twists\
    \ in alien ways. The creature has disadvantage on attack rolls, its speed is reduced\
    \ by half, and if it tries to cast a spell, it must first succeed on a DC 15 Intelligence\
    \ check or the spell fails and is wasted. The corrupted creature can repeat the\
    \ saving throw at the end of each of its turns, ending the effect on itself on\
    \ a success."
  "name": "Corruption"
- "desc": "Melee Weapon Attack: +15 to hit, reach 5 ft., one incapacitated creature\
    \ grappled by Dyrrn. Hit: 55 (10d10) piercing damage. If this damage reduces\
    \ the target to 0 hit points, Dyrrn kills the target by extracting and devouring\
    \ its brain."
  "name": "Extract Brain"
"legendary_actions":
- "desc": "Dyrrn makes one attack with its Tentacle Whip."
  "name": "Tentacle Whip"
- "desc": "Dyrrn regurgitates an intellect devourer in an unoccupied space within\
    \ 5 feet of it. The intellect devourer is under Dyrrn's control and acts immediately\
    \ after Dyrrn in the initiative order."
  "name": "Spawn Aberration (Costs 2 Actions)"
- "desc": "Dyrrn magically emits psychic energy in a 60-foot cone. Each creature in\
    \ that area must succeed on a DC 23 Intelligence saving throw or take 30 (5d8\
    \ + 8) psychic damage and be stunned for 1 minute. A creature can repeat the saving\
    \ throw at the end of each of its turns, ending the effect on itself on a success."
  "name": "Mind Blast (Costs 3 Actions)"
"lair_actions":
- "desc": "While within the Palace of Sinew, Dyrrn can invoke the ambient magic to\
    \ take lair actions. On initiative count 20 (losing initiative ties), Dyrrn can\
    \ take a lair action to cause one of the following effects; it can't use the same\
    \ effect two rounds in a row:"
  "name": ""
- "desc": "- Dyrrn uses its Corruption action.  \n- A 30-foot-square area of ground\
    \ within 120 feet of Dyrrn sprouts tentacles until initiative count 20 on the\
    \ next round. Any creature that starts or ends its turn in the area must succeed\
    \ on a DC 23 Strength saving throw or be restrained. A creature can escape the\
    \ tentacles with a successful DC 23 Strength (Athletics) or Dexterity (Acrobatics)\
    \ check as an action.  \n- Each creature of Dyrrn's choice that it can see within\
    \ 120 feet of it must succeed on a DC 23 Wisdom saving throw or take 26 (4d12)\
    \ psychic damage. Unless the target has immunity to psychic damage, its Intelligence\
    \ score is reduced by 1d4 each time it fails the saving throw for this lair action.\
    \ The target dies if its Intelligence score is reduced to 0. The reduction lasts\
    \ until the target finishes a short or long rest.  "
  "name": ""
"regional_effects":
- "desc": "A region containing a passage to Dyrrn's lair is warped in one or more\
    \ of these ways:"
  "name": ""
- "desc": "- Plants and animals raised within 2 mile of the passage have twisted,\
    \ aberrant forms. Use the Daelkyr Modifications table for inspiration.  \n- Creatures\
    \ within 1 mile of the passage frequently feel as if something is crawling under\
    \ their skin.  \n- If a humanoid spends at least 1 hour within 1 mile of the passage,\
    \ that creature must succeed on a DC 22 Wisdom saving throw or descend into a\
    \ type of madness (see \"Madness of Dyrrn\" below). A creature that succeeds on\
    \ this saving throw can't be affected by this regional effect again for 24 hours.\
    \  "
  "name": ""
- "desc": "If Dyrrn dies, these effects fade away after 1d10 days."
  "name": ""
- "desc": "If a creature goes mad in Dyrrn's lair or while it can see the daelkyr,\
    \ it gains a form of indefinite madness. Roll on the Madness of Dyrrn table to\
    \ determine the nature of this madness, which takes the form of a character flaw\
    \ that lasts until cured. Chapter 8 of the \"Dungeon Master's Guide\" has more\
    \ information on madness.\n\nMadness of Dyrrn\n\ndice: [](dyrrn-erlw.md#^madness-of-dyrrn)\n\
    \n| dice: d6 | Flaw (lasts until cured) |\n|----------|--------------------------|\n\
    | 1 | \"There's an illithid parasite living in my brain!\" |\n| 2 | \"I can feel\
    \ myself evolving into an aberration.\" |\n| 3 | \"Aberrations are the only natural\
    \ things.\" |\n| 4 | \"A part of me has become a conscious entity.\" |\n| 5 |\
    \ \"My opponents must bow down to a mind flayer!\" |\n| 6 | \"Dyrrn and the mind\
    \ flayers simply want to unite all sentient creatures in collective consciousness.\
    \ And I receive messages from the group mind!\" |\n^madness-of-dyrrn"
  "name": "Madness of Dyrrn"
"source":
- "ERLW"
"image": "bestiary/tokens/ERLW/Dyrrn.webp"
```
^statblock