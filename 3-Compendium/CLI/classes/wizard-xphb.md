---
obsidianUIMode: preview
cssclasses: json5e-class
tags:
- ttrpg-cli/class/wizard
- ttrpg-cli/compendium/src/5e/xphb
aliases: ["Wizard"]
---
# Wizard
*Source: Player's Handbook (2024) p. 164. Available in the Free Rules (2024)*  

> [!tldr]- Feature progression
> 
> | Level | PB | Features |
> |-------|----|----------|
> | 1st | +2 | [Spellcasting](#Spellcasting%20(Level%201)), [Ritual Adept](#Ritual%20Adept%20(Level%201)), [Arcane Recovery](#Arcane%20Recovery%20(Level%201)) |
> | 2nd | +2 | [Scholar](#Scholar%20(Level%202)) |
> | 3rd | +2 | [Wizard Subclass](#Wizard%20Subclass%20(Level%203)) |
> | 4th | +2 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%204)) |
> | 5th | +3 | [Memorize Spell](#Memorize%20Spell%20(Level%205)) |
> | 6th | +3 | [Subclass Feature](#Subclass%20Feature%20(Level%206)) |
> | 7th | +3 | ⏤ |
> | 8th | +3 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%208)) |
> | 9th | +4 | ⏤ |
> | 10th | +4 | [Subclass Feature](#Subclass%20Feature%20(Level%2010)) |
> | 11th | +4 | ⏤ |
> | 12th | +4 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%2012)) |
> | 13th | +5 | ⏤ |
> | 14th | +5 | [Subclass Feature](#Subclass%20Feature%20(Level%2014)) |
> | 15th | +5 | ⏤ |
> | 16th | +5 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%2016)) |
> | 17th | +6 | ⏤ |
> | 18th | +6 | [Spell Mastery](#Spell%20Mastery%20(Level%2018)) |
> | 19th | +6 | [Epic Boon](#Epic%20Boon%20(Level%2019)) |
> | 20th | +6 | [Signature Spells](#Signature%20Spells%20(Level%2020)) |
> 
> - PB: Proficiency Bonus
^feature-progression

> [!tldr]- Class progression
> 
> | Level | Cantrips | Prepared Spells | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th |
> |-------|----------|-----------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|
> | 1st | 3 | 4 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 2nd | 3 | 5 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 3rd | 3 | 6 | 4 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 4th | 4 | 7 | 4 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 5th | 4 | 9 | 4 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 6th | 4 | 10 | 4 | 3 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 7th | 4 | 11 | 4 | 3 | 3 | 1 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 8th | 4 | 12 | 4 | 3 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 9th | 4 | 14 | 4 | 3 | 3 | 3 | 1 | ⏤ | ⏤ | ⏤ | ⏤ |
> | 10th | 5 | 15 | 4 | 3 | 3 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ |
> | 11th | 5 | 16 | 4 | 3 | 3 | 3 | 2 | 1 | ⏤ | ⏤ | ⏤ |
> | 12th | 5 | 16 | 4 | 3 | 3 | 3 | 2 | 1 | ⏤ | ⏤ | ⏤ |
> | 13th | 5 | 17 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | ⏤ | ⏤ |
> | 14th | 5 | 18 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | ⏤ | ⏤ |
> | 15th | 5 | 19 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | ⏤ |
> | 16th | 5 | 21 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | ⏤ |
> | 17th | 5 | 22 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | 1 |
> | 18th | 5 | 23 | 4 | 3 | 3 | 3 | 3 | 1 | 1 | 1 | 1 |
> | 19th | 5 | 24 | 4 | 3 | 3 | 3 | 3 | 2 | 1 | 1 | 1 |
> | 20th | 5 | 25 | 4 | 3 | 3 | 3 | 3 | 2 | 2 | 1 | 1 |
> 
> - 1st-9th: Spell slots per level
^class-progression

## Hit Points

- **Hit Dice**: 1d6 per Wizard level
- **Hit Points at First Level:** 6 + CON
- **Hit Points at Higher Levels:** add 3 OR 1d6 + CON  (minimum of 1)

## Starting Wizard

You are proficient with the following items, in addition to any proficiencies provided by your race or background.

- **Saving Throws**: Intelligence, Wisdom
- **Armor**: none
- **Weapons**: simple
- **Tools**: none
- **Skills**: Choose 2 from *Arcana*, *History*, *Insight*, *Investigation*, *Medicine*, *Religion*

You begin play with the following equipment, in addition to any equipment provided by your background.


## Multiclassing Wizard

To multiclass as a Wizard, you must meet the following prerequisites:


## Wizard

Wizards are defined by their exhaustive study of magic's inner workings. They cast spells of explosive fire, arcing lightning, subtle deception, and spectacular transformations. Their magic conjures monsters from other planes of existence, glimpses the future, or forms protective barriers. Their mightiest spells change one substance into another, call meteors from the sky, or open portals to other worlds.

Most Wizards share a scholarly approach to magic. They examine the theoretical underpinnings of magic, particularly the categorization of spells into schools of magic. Renowned Wizards such as Bigby, Tasha, Mordenkainen, and Yolande have built on their studies to invent iconic spells now used across the multiverse.

The closest a Wizard is likely to come to an ordinary life is working as a sage or lecturer. Other Wizards sell their services as advisers, serve in military forces, or pursue lives of crime or domination.

But the lure of knowledge calls even the most unadventurous Wizards from the safety of their libraries and laboratories and into crumbling ruins and lost cities. Most Wizards believe that their counterparts in ancient civilizations knew secrets of magic that have been lost to the ages, and discovering those secrets could unlock the path to a power greater than any magic available in the present age.

## Class Features

### Spellcasting (Level 1)

As a student of arcane magic, you have learned to cast spells. See "chapter 7" for the rules on spellcasting. The information below details how you use those rules with Wizard spells, which appear in the Wizard spell list later in the class's description.

#### Cantrips

You know three Wizard cantrips of your choice. [Light](light-xphb.md), [Mage Hand](mage-hand-xphb.md), and [Ray of Frost](/3-Compendium/CLI/spells/ray-of-frost-xphb.md) are recommended. Whenever you finish a [Long Rest](long-rest-xphb.md), you can replace one of your cantrips from this feature with another Wizard cantrip of your choice.

When you reach Wizard levels 4 and 10, you learn another Wizard cantrip of your choice, as shown in the Cantrips column of the Wizard Features table.

#### Spellbook

Your wizardly apprenticeship culminated in the creation of a unique book: your spellbook. It is a Tiny object that weighs 3 pounds, contains 100 pages, and can be read only by you or someone casting [Identify](identify-xphb.md). You determine the book's appearance and materials, such as a gilt-edged tome or a collection of vellum bound with twine.

The book contains the level 1+ spells you know. It starts with six level 1 Wizard spells of your choice. [Detect Magic](detect-magic-xphb.md), [Feather Fall](/3-Compendium/CLI/spells/feather-fall-xphb.md), [Mage Armor](mage-armor-xphb.md), [Magic Missile](/3-Compendium/CLI/spells/magic-missile-xphb.md), [Sleep](sleep-xphb.md), and [Thunderwave](thunderwave-xphb.md) are recommended.

Whenever you gain a Wizard level after 1, add two Wizard spells of your choice to your spellbook. Each of these spells must be of a level for which you have spell slots, as shown in the Wizard Features table. The spells are the culmination of arcane research you do regularly.

#### Spell Slots

The Wizard Features table shows how many spell slots you have to cast your level 1+ spells. You regain all expended slots when you finish a [Long Rest](long-rest-xphb.md).

#### Prepared Spells of Level 1+

You prepare the list of level 1+ spells that are available for you to cast with this feature. To do so, choose four spells from your spellbook. The chosen spells must be of a level for which you have spell slots.

The number of spells on your list increases as you gain Wizard levels, as shown in the Prepared Spells column of the Wizard Features table. Whenever that number increases, choose additional Wizard spells until the number of spells on your list matches the number in the table. The chosen spells must be of a level for which you have spell slots. For example, if you're a level 3 Wizard, your list of prepared spells can include six spells of levels 1 and 2 in any combination, chosen from your spellbook.

If another Wizard feature gives you spells that you always have prepared, those spells don't count against the number of spells you can prepare with this feature, but those spells otherwise count as Wizard spells for you.

#### Changing Your Prepared Spells

Whenever you finish a [Long Rest](long-rest-xphb.md), you can change your list of prepared spells, replacing any of the spells there with spells from your spellbook.

#### Spellcasting Ability

Intelligence is your spellcasting ability for your Wizard spells.

#### Spellcasting Focus

You can use an [Arcane Focus](arcane-focus-xphb.md) or your spellbook as a [Spellcasting Focus](spellcasting-focus-xphb.md) for your Wizard spells.

> [!note] Expanding and Replacing a Spellbook
> 
> The spells you add to your spellbook as you gain levels reflect your ongoing magical research, but you might find other spells during your adventures that you can add to the book. You could discover a Wizard spell on a [Spell Scroll](spell-scroll-xdmg.md), for example, and then copy it into your spellbook.
> 
> **Copying a Spell into the Book.** When you find a level 1+ Wizard spell, you can copy it into your spellbook if it's of a level you can prepare and if you have time to copy it. For each level of the spell, the transcription takes 2 hours and costs 50 GP. Afterward you can prepare the spell like the other spells in your spellbook.
> 
> **Copying the Book.** You can copy a spell from your spellbook into another book. This is like copying a new spell into your spellbook but faster, since you already know how to cast the spell. You need spend only 1 hour and 10 GP for each level of the copied spell.
> 
> If you lose your spellbook, you can use the same procedure to transcribe the Wizard spells that you have prepared into a new spellbook. Filling out the remainder of the new book requires you to find new spells to do so. For this reason, many wizards keep a backup spellbook.
^expanding-and-replacing-a-spellbook

### Ritual Adept (Level 1)

You can cast any spell as a [Ritual](ritual-xphb.md) if that spell has the [Ritual](ritual-xphb.md) tag and the spell is in your spellbook. You needn't have the spell prepared, but you must read from the book to cast a spell in this way.

### Arcane Recovery (Level 1)

You can regain some of your magical energy by studying your spellbook. When you finish a [Short Rest](short-rest-xphb.md), you can choose expended spell slots to recover. The spell slots can have a combined level equal to no more than half your Wizard level (round up), and none of the slots can be level 6 or higher. For example, if you're a level 4 Wizard, you can recover up to two levels' worth of spell slots, regaining either one level 2 spell slot or two level 1 spell slots.

Once you use this feature, you can't do so again until you finish a [Long Rest](long-rest-xphb.md).

### Scholar (Level 2)

While studying magic, you also specialized in another field of study. Choose one of the following skills in which you have proficiency: [Arcana](skills.md#Arcana), [History](skills.md#History), [Investigation](skills.md#Investigation), [Medicine](skills.md#Medicine), [Nature](skills.md#Nature), or [Religion](skills.md#Religion). You have [Expertise](expertise-xphb.md) in the chosen skill.

### Wizard Subclass (Level 3)

You gain a Wizard subclass of your choice. A subclass is a specialization that grants you features at certain Wizard levels. For the rest of your career, you gain each of your subclass's features that are of your Wizard level or lower.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify. You gain this feature again at Wizard levels 8, 12, and 16.

### Memorize Spell (Level 5)

Whenever you finish a [Short Rest](short-rest-xphb.md), you can study your spellbook and replace one of the level 1+ Wizard spells you have prepared for your Spellcasting feature with another level 1+ spell from the book.

### Subclass Feature (Level 6)

You gain a feature from your Wizard Subclass.

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) Feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 10)

You gain a feature from your Wizard Subclass.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) Feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 14)

You gain a feature from your Wizard Subclass.

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) Feat or another feat of your choice for which you qualify.

### Spell Mastery (Level 18)

You have achieved such mastery over certain spells that you can cast them at will. Choose a level 1 and a level 2 spell in your spellbook that have a casting time of an action. You always have those spells prepared, and you can cast them at their lowest level without expending a spell slot. To cast either spell at a higher level, you must expend a spell slot.

Whenever you finish a [Long Rest](long-rest-xphb.md), you can study your spellbook and replace one of those spells with an eligible spell of the same level from the book.

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify. [Boon of Spell Recall](boon-of-spell-recall-xphb.md) is recommended.

### Signature Spells (Level 20)

Choose two level 3 spells in your spellbook as your signature spells. You always have these spells prepared, and you can cast each of them once at level 3 without expending a spell slot. When you do so, you can't cast them in this way again until you finish a [Short Rest](short-rest-xphb.md) or [Long Rest](long-rest-xphb.md). To cast either spell at a higher level, you must expend a spell slot.