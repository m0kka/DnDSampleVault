---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Devourer"]
---
# [Devourer](3-Compendium\CLI\bestiary\undead/devourer-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 93, Volo's Guide to Monsters p. 138*  

Of all the abominations unleashed by [Orcus](orcus-mpmm.md), devourers are among the most feared. These tall, mummy-like Undead wander the planes, consuming souls and spreading Orcus's creed of replacing all life with everlasting death.

A lesser demon that proves itself to Orcus might be granted the privilege of becoming a devourer. The Prince of Undeath transforms such a demon into an 8-foot-tall, desiccated biped with a hollowed-out ribcage, then fills the new creature with a hunger for souls. Orcus grants each new devourer the essence of a less fortunate demon to power the devourer's first foray into the planes. Most devourers remain in the Abyss or on the Astral or Ethereal Plane, pursuing Orcus's schemes and interests in those realms. When Orcus sends devourers to the Material Plane, he often sets them on a mission to create, control, and lead a plague of Undead. [Skeletons](skeleton-xphb.md), [zombies](zombie-xphb.md), [ghouls](ghoul-xmm.md), [ghasts](ghast-xmm.md), and [shadows](shadow.md) are particularly attracted to the presence of a devourer.

Devourers hunt Humanoids with the intent of consuming them body and soul. After a devourer brings a target to the brink of death, it pulls the victim's body in and traps the creature within its own ribcage. As the victim tries to stave off death (usually without success), the devourer tortures its soul with telepathic noise. When the victim expires, it undergoes a horrible transformation, springing forth from the devourer's body to begin its new existence as an Undead servitor of the monster that spawned it.

```statblock
"name": "Devourer (MPMM)"
"size": "Large"
"type": "undead"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "189"
"hit_dice": "18d10 + 90"
"stats":
- !!int "20"
- !!int "12"
- !!int "20"
- !!int "13"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Abyssal, telepathy 120 ft."
"cr": "13"
"traits":
- "desc": "A devourer doesn't require air, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The devourer makes two Claw attacks and can use either Imprison Soul or\
    \ Soul Rend, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) slashing damage plus 21 (6d6) necrotic damage."
  "name": "Claw"
- "desc": "The devourer chooses a living Humanoid with 0 hit points that it can see\
    \ within 30 feet of it. That creature is teleported inside the devourer's ribcage\
    \ and imprisoned there. While imprisoned in this way, the creature is restrained\
    \ and has disadvantage on death saving throws. If the creature dies while imprisoned,\
    \ the devourer regains 25 hit points and immediately recharges Soul Rend. Additionally,\
    \ at the start of its next turn, the devourer regurgitates the slain creature\
    \ as a bonus action, and the creature becomes an undead. If the victim had 2 or\
    \ fewer Hit Dice, it becomes a [zombie](/3-Compendium/CLI/bestiary/undead/zombie-xphb.md).\
    \ If it had 3 to 5 Hit Dice, it becomes a [ghoul](/3-Compendium/CLI/bestiary/undead/ghoul-xmm.md).\
    \ Otherwise, it becomes a [wight](/3-Compendium/CLI/bestiary/undead/wight-xmm.md).\
    \ A devourer can imprison only one creature at a time."
  "name": "Imprison Soul"
- "desc": "The devourer creates a vortex of life-draining energy in a 20-foot radius\
    \ centered on itself. Each creature in that area must make a DC 18 Constitution\
    \ saving throw, taking 44 (8d10) necrotic damage on a failed save, or half as\
    \ much damage on a successful one."
  "name": "Soul Rend (Recharge 6)"
"source":
- "MPMM"
- "VGM"
"image": "bestiary/tokens/MPMM/Devourer.webp"
```
^statblock

## Environment

underdark