---
obsidianUIMode: preview
cssclasses: json5e-class
tags:
- ttrpg-cli/class/bard
- ttrpg-cli/compendium/src/5e/xphb
aliases: ["Bard"]
---
# Bard
*Source: Player's Handbook (2024) p. 58*  

> [!tldr]- Feature progression
> 
> | Level | PB | Features |
> |-------|----|----------|
> | 1st | +2 | [Bardic Inspiration](#Bardic%20Inspiration%20(Level%201)), [Spellcasting](#Spellcasting%20(Level%201)) |
> | 2nd | +2 | [Expertise](#Expertise%20(Level%202)), [Jack of All Trades](#Jack%20of%20All%20Trades%20(Level%202)) |
> | 3rd | +2 | [Bard Subclass](#Bard%20Subclass%20(Level%203)) |
> | 4th | +2 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%204)) |
> | 5th | +3 | [Font of Inspiration](#Font%20of%20Inspiration%20(Level%205)) |
> | 6th | +3 | [Subclass Feature](#Subclass%20Feature%20(Level%206)) |
> | 7th | +3 | [Countercharm](#Countercharm%20(Level%207)) |
> | 8th | +3 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%208)) |
> | 9th | +4 | [Expertise](#Expertise%20(Level%209)) |
> | 10th | +4 | [Magical Secrets](#Magical%20Secrets%20(Level%2010)) |
> | 11th | +4 | ⏤ |
> | 12th | +4 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%2012)) |
> | 13th | +5 | ⏤ |
> | 14th | +5 | [Subclass Feature](#Subclass%20Feature%20(Level%2014)) |
> | 15th | +5 | ⏤ |
> | 16th | +5 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%2016)) |
> | 17th | +6 | ⏤ |
> | 18th | +6 | [Superior Inspiration](#Superior%20Inspiration%20(Level%2018)) |
> | 19th | +6 | [Epic Boon](#Epic%20Boon%20(Level%2019)) |
> | 20th | +6 | [Words of Creation](#Words%20of%20Creation%20(Level%2020)) |
> 
> - PB: Proficiency Bonus
^feature-progression

> [!tldr]- Class progression
> 
> | Level | Bardic Die | Cantrips | Prepared Spells | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th |
> |-------|------------|----------|-----------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|
> | 1st | 1d6 | 2 | 4 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 2nd | 1d6 | 2 | 5 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 3rd | 1d6 | 2 | 6 | 4 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 4th | 1d6 | 3 | 7 | 4 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 5th | 1d8 | 3 | 9 | 4 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 6th | 1d8 | 3 | 10 | 4 | 3 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 7th | 1d8 | 3 | 11 | 4 | 3 | 3 | 1 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 8th | 1d8 | 3 | 12 | 4 | 3 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 9th | 1d8 | 3 | 14 | 4 | 3 | 3 | 3 | 1 | ⏤ | ⏤ | ⏤ | ⏤ |
> | 10th | 1d10 | 4 | 15 | 4 | 3 | 3 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ |
> | 11th | 1d10 | 4 | 16 | 4 | 3 | 3 | 3 | 2 | 1 | ⏤ | ⏤ | ⏤ |
> | 12th | 1d10 | 4 | 16 | 4 | 3 | 3 | 3 | 2 | 1 | ⏤ | ⏤ | ⏤ |
> | 13th | 1d10 | 4 | 17 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | ⏤ | ⏤ |
> | 14th | 1d10 | 4 | 17 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | ⏤ | ⏤ |
> | 15th | 1d12 | 4 | 18 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | ⏤ |
> | 16th | 1d12 | 4 | 18 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | ⏤ |
> | 17th | 1d12 | 4 | 19 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | 1 |
> | 18th | 1d12 | 4 | 20 | 4 | 3 | 3 | 3 | 3 | 1 | 1 | 1 | 1 |
> | 19th | 1d12 | 4 | 21 | 4 | 3 | 3 | 3 | 3 | 2 | 1 | 1 | 1 |
> | 20th | 1d12 | 4 | 22 | 4 | 3 | 3 | 3 | 3 | 2 | 2 | 1 | 1 |
> 
> - 1st-9th: Spell slots per level
^class-progression

## Hit Points

- **Hit Dice**: 1d8 per Bard level
- **Hit Points at First Level:** 8 + CON
- **Hit Points at Higher Levels:** add 4 OR 1d8 + CON  (minimum of 1)

## Starting Bard

You are proficient with the following items, in addition to any proficiencies provided by your race or background.

- **Saving Throws**: Dexterity, Charisma
- **Armor**: light
- **Weapons**: simple
- **Tools**: Choose three [Musical Instruments](musical-instrument-xphb.md)
- **Skills**: Choose 3 from *Acrobatics*, *Animal Handling*, *Arcana*, *Athletics*, *Deception*, *History*, *Insight*, *Intimidation*, *Investigation*, *Medicine*, *Nature*, *Perception*, *Performance*, *Persuasion*, *Religion*, *Sleight of Hand*, *Stealth*, *Survival*, *Spellcasting*

You begin play with the following equipment, in addition to any equipment provided by your background.


## Multiclassing Bard

To multiclass as a Bard, you must meet the following prerequisites:

You gain the following proficiencies:

- **Armor**: light
- **Weapons**: none
- **Tools**: Choose one [Musical Instrument](musical-instrument-xphb.md)
- **Skills**: Choose 1 from *Acrobatics*, *Animal Handling*, *Arcana*, *Athletics*, *Deception*, *History*, *Insight*, *Intimidation*, *Investigation*, *Medicine*, *Nature*, *Perception*, *Performance*, *Persuasion*, *Religion*, *Sleight of Hand*, *Stealth*, *Survival*

## Bard

Invoking magic through music, dance, and verse, Bards are expert at inspiring others, soothing hurts, disheartening foes, and creating illusions. Bards believe the multiverse was spoken into existence and that remnants of its Words of Creation still resound and glimmer on every plane of existence. Bardic magic attempts to harness those words, which transcend any language.

Anything can inspire a new song or tale, so Bards are fascinated by almost everything. They become masters of many things, including performing music, working magic, and making jests.

A Bard's life is spent traveling, gathering lore, telling stories, and living on the gratitude of audiences, much like any other entertainer. But Bards' depth of knowledge and mastery of magic sets them apart.

## Class Features

### Bardic Inspiration (Level 1)

You can supernaturally inspire others through words, music, or dance. This inspiration is represented by your Bardic Inspiration die, which is a `d6`.

#### Using Bardic Inspiration

As a [Bonus Action](bonus-action-xphb.md), you can inspire another creature within 60 feet of yourself who can see or hear you. That creature gains one of your Bardic Inspiration dice. A creature can have only one Bardic Inspiration die at a time.

Once within the next hour when the creature fails a [D20 Test](d20-test-xphb.md), the creature can roll the Bardic Inspiration die and add the number rolled to the `d20`, potentially turning the failure into a success. A Bardic Inspiration die is expended when it's rolled.

#### Number of Uses

You can confer a Bardic Inspiration die a number of times equal to your Charisma modifier (minimum of once), and you regain all expended uses when you finish a [Long Rest](long-rest-xphb.md).

#### At Higher Levels

Your Bardic Inspiration die changes when you reach certain Bard levels, as shown in the Bardic Die column of the Bard Features table. The die becomes a `d8` at level 5, a `d10` at level 10, and a `d12` at level 15.

### Spellcasting (Level 1)

You have learned to cast spells through your bardic arts. See "chapter 7" for the rules on spellcasting. The information below details how you use those rules with Bard spells, which appear in the Bard spell list later in the class's description.

#### Cantrips

You know two cantrips of your choice from the Bard spell list. [Dancing Lights](dancing-lights-xphb.md) and [Vicious Mockery](/3-Compendium/CLI/spells/vicious-mockery-xphb.md) are recommended.

Whenever you gain a Bard level, you can replace one of your cantrips with another cantrip of your choice from the Bard spell list.

When you reach Bard levels 4 and 10, you learn another cantrip of your choice from the Bard spell list, as shown in the Cantrips column of the Bard Features table.

#### Spell Slots

The Bard Features table shows how many spell slots you have to cast your level 1+ spells. You regain all expended slots when you finish a [Long Rest](long-rest-xphb.md).

#### Prepared Spells of Level 1+

You prepare the list of level 1+ spells that are available for you to cast with this feature. To start, choose four level 1 spells from the Bard spell list. [Charm Person](charm-person-xphb.md), [Color Spray](color-spray-xphb.md), [Dissonant Whispers](dissonant-whispers-xphb.md), and [Healing Word](/3-Compendium/CLI/spells/healing-word-xphb.md) are recommended.

The number of spells on your list increases as you gain Bard levels, as shown in the Prepared Spells column of the Bard Features table. Whenever that number increases, choose additional spells from the Bard spell list until the number of spells on your list matches the number on the table. The chosen spells must be of a level for which you have spell slots. For example, if you're a level 3 Bard, your list of prepared spells can include six spells of levels 1 and 2 in any combination.

If another Bard feature gives you spells that you always have prepared, those spells don't count against the number of spells you can prepare with this feature, but those spells otherwise count as Bard spells for you.

#### Changing Your Prepared Spells

Whenever you gain a Bard level, you can replace one spell on your list with another Bard spell for which you have spell slots.

#### Spellcasting Ability

Charisma is your spellcasting ability for your Bard spells.

#### Spellcasting Focus

You can use a [Musical Instrument](musical-instrument-xphb.md) as a [Spellcasting Focus](spellcasting-focus-xphb.md) for your Bard spells.

### Expertise (Level 2)

You gain [Expertise](expertise-xphb.md) in two of your skill proficiencies of your choice. [Performance](skills.md#Performance) and [Persuasion](skills.md#Persuasion) are recommended if you have proficiency in them.

At Bard level 9, you gain [Expertise](expertise-xphb.md) in two more of your skill proficiencies of your choice.

### Jack of All Trades (Level 2)

You can add half your [Proficiency](proficiency-xphb.md) (round down) to any ability check you make that uses a skill proficiency you lack and that doesn't otherwise use your [Proficiency](proficiency-xphb.md).

For example, if you make a Strength ([Athletics](skills.md#Athletics)) check and lack [Athletics](skills.md#Athletics) proficiency, you can add half your [Proficiency](proficiency-xphb.md) to the check.

> [!note] A Bard's Repertoire
> 
> Does your Bard beat a [drum](drum-xphb.md) while chanting the deeds of ancient heroes? Strum a [lute](lute-xphb.md) while crooning romantic tunes? Perform arias of stirring power? Recite dramatic monologues from classic tragedies? Use the rhythm of a folk dance to coordinate the movement of allies in battle? Compose naughty limericks?
> 
> When you play a Bard, consider the style of artistic performance you favor, the moods you might invoke, and the themes that inspire your own creations. Are your poems inspired by moments of natural beauty, or are they brooding reflections on loss? Do you prefer lofty hymns or rowdy tavern songs? Are you drawn to laments for the fallen or celebrations of joy? Do you dance merry jigs or perform elaborate interpretive choreography? Do you focus on one style of performance or strive to master them all?
^a-bards-repertoire

### Bard Subclass (Level 3)

You gain a Bard subclass of your choice. A subclass is a specialization that grants you features at certain Bard levels. For the rest of your career, you gain each of your subclass's features that are of your Bard level or lower.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify. You gain this feature again at Bard levels 8, 12, and 16.

### Font of Inspiration (Level 5)

You now regain all your expended uses of Bardic Inspiration when you finish a [Short Rest](short-rest-xphb.md) or [Long Rest](long-rest-xphb.md).

In addition, you can expend a spell slot (no action required) to regain one expended use of Bardic Inspiration.

### Subclass Feature (Level 6)

You gain a feature from your Bard Subclass.

### Countercharm (Level 7)

You can use musical notes or words of power to disrupt mind-influencing effects. If you or a creature within 30 feet of you fails a saving throw against an effect that applies the [Charmed](conditions.md#Charmed) or [Frightened](conditions.md#Frightened) condition, you can take a [Reaction](reaction-xphb.md) to cause the save to be rerolled, and the new roll has [Advantage](advantage-xphb.md).

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Expertise (Level 9)

You gain [Expertise](expertise-xphb.md) in two of your Skill Proficiencies of your choice.

### Magical Secrets (Level 10)

You've learned secrets from various magical traditions. Whenever you reach a Bard level (including this level) and the Prepared Spells number in the Bard Features table increases, you can choose any of your new prepared spells from the Bard, Cleric, Druid, and Wizard spell lists, and the chosen spells count as Bard spells for you (see a class's section for its spell list). In addition, whenever you replace a spell prepared for this class, you can replace it with a spell from those lists.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 14)

You gain a feature from your Bard Subclass.

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Superior Inspiration (Level 18)

When you roll [Initiative](initiative-xphb.md), you regain expended uses of Bardic Inspiration until you have two if you have fewer than that.

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify. [Boon of Spell Recall](boon-of-spell-recall-xphb.md) is recommended.

### Words of Creation (Level 20)

You have mastered two of the Words of Creation: the words of life and death. You therefore always have the [Power Word Heal](/3-Compendium/CLI/spells/power-word-heal-xphb.md) and [Power Word Kill](power-word-kill-xphb.md) spells prepared. When you cast either spell, you can target a second creature with it if that creature is within 10 feet of the first target.