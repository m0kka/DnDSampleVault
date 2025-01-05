---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dragonborn
statblock: inline
aliases: ["Donaar Blit'zen"]
---
# [Donaar Blit'zen](3-Compendium\CLI\bestiary\npc/donaar-blitzen-ai.md)
*Source: Acquisitions Incorporated p. 201*  

> [!quote]  
> 
> Everybody cooooool out!

The hulking dragonborn decisionist of the "C" Team, Donaar Blit'zen is an icon of brash confidence and warrior chill. He is known for his furious skill in battle, and for his propensity to fall asleep as soon as a fight is done (as well as countless other inopportune times). More immediately notable is the unique physical trait that all members of his clan bear-a stylish tail that is rare and often considered a deformity among dragonborn.

As with his tail, an odd quirk of heritage makes Donaar's acid breath more of a signature vomiting, giving rise to a driving paranoia that this regurgitation might damage his teeth. As testaments to his obsession with dental hygiene, Donaar named his greatsword Toothbrush and calls his whip Floss. He carries an actual toothbrush (named Percival) and actual floss at all times.

Those who know Donaar quickly come to recognize that the braggadocio that defines him involves a certain amount of artifice. When the young dragonborn left his clan and family to adventure in foreign climes, he realized that doing so provided the perfect opportunity to reinvent himself for folk who had no idea what he was once like. As such, Donaar has learned that no amount of bravado and compensation is too much-provided he leaves no openings for strangers to call him on it. By the same token, strangers quickly come to realize that reinforcing Donaar's self-congratulating sense of draconic entitlement makes it remarkably easy to win his favor.

Despite his easily massaged vanity, the dragonborn sometimes shows the occasional streak of selflessness. Most notably, Donaar serves in his off-hours as parttime godfather to a young dragonborn named Chronaar, who had inadvertently imprinted on Donaar as a parental figure while he watched over her while she was in her egg.

```statblock
"name": "Donaar Blit'zen (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "dragonborn"
"alignment": "Chaotic Good"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "17"
- !!int "8"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "2"
"skillsaves":
  "Intimidation": !!int "5"
  "Insight": !!int "2"
  "History": !!int "2"
  "Persuasion": !!int "5"
"damage_resistances": "acid"
"senses": "passive Perception 10"
"languages": "Common, Draconic, Orc"
"cr": "3"
"traits":
- "desc": "Donaar is a 5th-level spellcaster. His spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). He has the following paladin\
    \ spells prepared:\n\n1st level (4 slots): command, compelled duel, cure wounds,\
    \ wrathful smite\n\n2nd level (2 slots): aid, branding smite, lesser restoration,\
    \ warding bond, zone of truth"
  "name": "Spellcasting"
- "desc": "As a bonus action, Donaar causes each creature of his choice that he can\
    \ see within 30 feet of him to make a DC 13 Wisdom saving throw. On a failure,\
    \ a creature can't willingly move more than 30 feet away from Donaar. This effect\
    \ ends on the creature if Donaar is incapacitated or dies, or if the creature\
    \ is moved more than 30 feet away from him."
  "name": "Champion Challenge (Recharges after a Short or Long Rest)"
"actions":
- "desc": "Donaar makes two attacks with his greatsword or his whip."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) slashing damage. Whenever Donaar rolls a 1 or 2 on a damage die, he can\
    \ reroll the die and must use the new roll."
  "name": "Greatsword"
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 5 (1d4\
    \ + 3) slashing damage."
  "name": "Whip"
- "desc": "Donaar regurgitates acid in a 30-foot line that is 5 feet wide. Each creature\
    \ in that line must make a DC 12 Dexterity saving throw, taking 7 (2d6) acid damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Acid Vomit"
"source":
- "AI"
"image": "bestiary/tokens/AI/Donaar Blit'zen.webp"
```
^statblock