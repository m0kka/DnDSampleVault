---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
aliases: ["Zakya Rakshasa"]
---
# [Zakya Rakshasa](3-Compendium\CLI\bestiary\fiend/zakya-rakshasa-erlw.md)
*Source: Eberron: Rising from the Last War p. 309*  

Millions of years before the rise of the humanoid races, the rakshasas of Eberron ruled a civilization that spanned Khorvaire. Masters of combat, the rakshasas of Eberron wield their weapons with demonic fury, rushing into battle seeking vengeance against those who bound their fiendish masters.

Rakshasas are described in the "Monster Manual". A martial variant—the zakya rakshasa—is presented here.

Zakya rakshasas are the bloodthirsty foot soldiers of the rakshasa horde. They are driven to free their fiendish rulers, seeking vengeance against the dragons and those who revere the couatls. Unlike other rakshasas with their luxurious robes and fineries, zakya rakshasas are almost always clad in battle gear: well-worn scale mail, a razor-sharp longsword, and a heavy shield bearing the emblem of their demonic master.

```statblock
"name": "Zakya Rakshasa (ERLW)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "scale mail, shield"
"hp": !!int "59"
"hit_dice": "7d8 + 28"
"stats":
- !!int "18"
- !!int "14"
- !!int "18"
- !!int "12"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "7"
  "Perception": !!int "4"
"damage_vulnerabilities": "piercing from magic weapons wielded by good creatures"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Infernal"
"cr": "5"
"traits":
- "desc": "The rakshasa's innate spellcasting ability is Charisma (spell save DC 11).\
    \ The rakshasa can innately cast the following spells, requiring no material components:\n\
    \nAt will: detect thoughts, disguise self\n\n1/day: shield"
  "name": "Innate Spellcasting"
- "desc": "The rakshasa can't be affected or detected by spells of 1st level or lower\
    \ unless it wishes to be. It has advantage on saving throws against all other\
    \ spells and magical effects."
  "name": "Limited Magic Immunity"
- "desc": "The rakshasa's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "When the rakshasa hits a creature with a melee weapon attack, the attack\
    \ deals an extra 11 (2d10) damage of the weapon's type, and the creature must\
    \ make a DC 15 Strength saving throw. On a failure, the rakshasa can push the\
    \ creature up to 10 feet away from it, knock the creature prone, or make the creature\
    \ drop one item it is holding of the rakshasa's choice."
  "name": "Martial Prowess (1/Turn)"
"actions":
- "desc": "The rakshasa makes three melee weapon attacks. Alternatively, it can make\
    \ two ranged attacks with its javelins."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  "name": "Javelin"
"source":
- "ERLW"
"image": "bestiary/tokens/ERLW/Zakya Rakshasa.webp"
```
^statblock