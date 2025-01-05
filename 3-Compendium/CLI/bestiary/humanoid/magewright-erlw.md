---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Magewright"]
---
# [Magewright](3-Compendium\CLI\bestiary\humanoid/magewright-erlw.md)
*Source: Eberron: Rising from the Last War p. 318*  

In Khorvaire, magic is part of everyday life. A chef might use prestidigitation to heat and season food, while a blacksmith uses mending to perform minor repairs and guidance to help inspire their work. Those who work minor magic into their labors are called magewrights.

Far more limited in magical power than a typical spellcaster, a magewright is dedicated to learning a handful of spells, and magewrights cast their non-cantrip spells as rituals—even spells that can't normally be cast in this way. Most magewright rituals take 10 minutes to perform, but certain complex rituals can take up to 1 hour. However long the ritual takes, it requires extra material components, usually in the form of dragonshards.

## Creating a Magewright

The magewright stat block provides the baseline statistics for a magewright. You then add to that baseline by choosing a specialty from the Magewright Specialties table, or roll for one. The specialty determines additional spells the magewright knows, including ones that can be cast only as rituals. The specialty also gives the magewright more proficiencies.

**Magewright Specialties**

`dice: [](magewright-erlw.md#^magewright-specialties)`

| dice: d8 | Specialty | Spells | Proficiencies |
|----------|-----------|--------|---------------|
| 1 | Artisan | Guidance, mending | One type of artisan's tools |
| 2 | Entertainer | Minor illusion, thaumaturgy. Ritual only: disguise self. | Performance (+3) |
| 3 | Healer | Resistance, spare the dying. Ritual only: detect poison and disease, lesser restoration (1 hour). | Medicine (+4), [herbalism kit](herbalism-kit-xphb.md) |
| 4 | Lamplighter | Light. Ritual only: continual flame (1 hour). | [Tinker's tools](tinkers-tools-xphb.md) |
| 5 | Locksmith | Mending. Ritual only: arcane lock (1 hour), knock. | [Thieves' tools](thieves-tools-xphb.md), [tinker's tools](tinkers-tools-xphb.md) |
| 6 | Mediator | Guidance. Ritual only: comprehend languages, zone of truth. | Insight (+4), Persuasion (+3) |
| 7 | Medium | Minor illusion. Ritual only: speak with dead. | Deception (+3), Religion (+4) |
| 8 | Oracle | Guidance. Ritual only: augury, divination (1 hour). | History (+4), Religion (+4) |
^magewright-specialties

```statblock
"name": "Magewright (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "13"
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Arcana": !!int "4"
"senses": "passive Perception 12"
"languages": "Common plus any two languages"
"cr": "0"
"traits":
- "desc": "The magewright's spellcasting ability is Intelligence (spell save DC 12).\
    \ To cast one of its rituals, the magewright must provide additional material\
    \ components whose value in gold pieces is 20 times the spell's level. These components\
    \ are consumed when the ritual is finished. The magewright knows the following\
    \ spells:\n\nAt will: mage hand, prestidigitation"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage."
  "name": "Dagger"
"source":
- "ERLW"
"image": "bestiary/tokens/ERLW/Magewright.webp"
```
^statblock