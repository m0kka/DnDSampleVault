---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Feyr"]
---
# [Feyr](3-Compendium\CLI\bestiary\aberration/feyr-bam.md)
*Source: Boo's Astral Menagerie p. 22, The Book of Many Things*  

A feyr (pronounced "fear") is a tentacled horror that feeds quietly on strong emotions. To minimize the chance of harm to itself, it prefers to devour the nightmares of other creatures while they sleep.

Feyrs shun bright light but aren't harmed by it. Consequently, they are as much at home in the void of Wildspace as they are in dark alleys and dungeons. A feyr that comes across a spelljamming ship tries to enter the ship's air envelope and stow away, remaining secluded and invisible until it finds a sleeping victim it can attack. It retreats rather than allows itself to perish in a confrontation.

```statblock
"name": "Feyr (BAM)"
"size": "Large"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "88"
"hit_dice": "16d10"
"stats":
- !!int "16"
- !!int "16"
- !!int "11"
- !!int "14"
- !!int "14"
- !!int "11"
"speed": "0 ft., fly 50 ft. (hover)"
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "5"
"skillsaves":
  "Stealth": !!int "9"
  "Perception": !!int "5"
"condition_immunities": "frightened"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": ""
"cr": "5"
"traits":
- "desc": "The feyr doesn't require air."
  "name": "Unusual Nature"
"actions":
- "desc": "The feyr makes one Frightful Bite attack and one Tentacle attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 8 (1d10\
    \ + 3) piercing damage, and each creature within 10 feet of the feyr that can\
    \ see it must succeed on a DC 13 Wisdom saving throw or be frightened of the feyr\
    \ until the end of the feyr's next turn."
  "name": "Frightful Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one creature. Hit: 17\
    \ (4d6 + 3) psychic damage, and the target is grappled (escape DC 13). Until this\
    \ grapple ends, the feyr can't use this tentacle against other targets. The feyr\
    \ has two tentacles, each of which can grapple one creature."
  "name": "Tentacle"
- "desc": "The feyr becomes invisible until it attacks, uses Nightmare Fuel, or uses\
    \ a bonus action to become visible."
  "name": "Invisibility"
- "desc": "The feyr targets one unconscious creature it can see within 10 feet of\
    \ itself. The target must succeed on a DC 13 Wisdom saving throw or take 27 (5d10)\
    \ psychic damage, and the feyr gains temporary hit points equal to the damage\
    \ dealt."
  "name": "Nightmare Fuel (1/Day)"
"source":
- "BAM"
- "BMT"
"image": "bestiary/tokens/BAM/Feyr.webp"
```
^statblock