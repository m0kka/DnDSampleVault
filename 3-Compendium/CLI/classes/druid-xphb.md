---
obsidianUIMode: preview
cssclasses: json5e-class
tags:
- ttrpg-cli/class/druid
- ttrpg-cli/compendium/src/5e/xphb
aliases: ["Druid"]
---
# Druid
*Source: Player's Handbook (2024) p. 78*  

> [!tldr]- Feature progression
> 
> | Level | PB | Features |
> |-------|----|----------|
> | 1st | +2 | [Druidic](#Druidic%20(Level%201)), [Primal Order](#Primal%20Order%20(Level%201)), [Spellcasting](#Spellcasting%20(Level%201)) |
> | 2nd | +2 | [Wild Companion](#Wild%20Companion%20(Level%202)), [Wild Shape](#Wild%20Shape%20(Level%202)) |
> | 3rd | +2 | [Druid Subclass](#Druid%20Subclass%20(Level%203)) |
> | 4th | +2 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%204)) |
> | 5th | +3 | [Wild Resurgence](#Wild%20Resurgence%20(Level%205)) |
> | 6th | +3 | [Subclass Feature](#Subclass%20Feature%20(Level%206)) |
> | 7th | +3 | [Elemental Fury](#Elemental%20Fury%20(Level%207)) |
> | 8th | +3 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%208)) |
> | 9th | +4 | ⏤ |
> | 10th | +4 | [Subclass Feature](#Subclass%20Feature%20(Level%2010)) |
> | 11th | +4 | ⏤ |
> | 12th | +4 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%2012)) |
> | 13th | +5 | ⏤ |
> | 14th | +5 | [Subclass Feature](#Subclass%20Feature%20(Level%2014)) |
> | 15th | +5 | [Improved Elemental Fury](#Improved%20Elemental%20Fury%20(Level%2015)) |
> | 16th | +5 | [Ability Score Improvement](#Ability%20Score%20Improvement%20(Level%2016)) |
> | 17th | +6 | ⏤ |
> | 18th | +6 | [Beast Spells](#Beast%20Spells%20(Level%2018)) |
> | 19th | +6 | [Epic Boon](#Epic%20Boon%20(Level%2019)) |
> | 20th | +6 | [Archdruid](#Archdruid%20(Level%2020)) |
> 
> - PB: Proficiency Bonus
^feature-progression

> [!tldr]- Class progression
> 
> | Level | Wild Shape | Cantrips | Prepared Spells | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th |
> |-------|------------|----------|-----------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|
> | 1st | ⏤ | 2 | 4 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 2nd | 2 | 2 | 5 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 3rd | 2 | 2 | 6 | 4 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 4th | 2 | 3 | 7 | 4 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 5th | 2 | 3 | 9 | 4 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 6th | 3 | 3 | 10 | 4 | 3 | 3 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 7th | 3 | 3 | 11 | 4 | 3 | 3 | 1 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 8th | 3 | 3 | 12 | 4 | 3 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ | ⏤ |
> | 9th | 3 | 3 | 14 | 4 | 3 | 3 | 3 | 1 | ⏤ | ⏤ | ⏤ | ⏤ |
> | 10th | 3 | 4 | 15 | 4 | 3 | 3 | 3 | 2 | ⏤ | ⏤ | ⏤ | ⏤ |
> | 11th | 3 | 4 | 16 | 4 | 3 | 3 | 3 | 2 | 1 | ⏤ | ⏤ | ⏤ |
> | 12th | 3 | 4 | 16 | 4 | 3 | 3 | 3 | 2 | 1 | ⏤ | ⏤ | ⏤ |
> | 13th | 3 | 4 | 17 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | ⏤ | ⏤ |
> | 14th | 3 | 4 | 17 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | ⏤ | ⏤ |
> | 15th | 3 | 4 | 18 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | ⏤ |
> | 16th | 3 | 4 | 18 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | ⏤ |
> | 17th | 4 | 4 | 19 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | 1 |
> | 18th | 4 | 4 | 20 | 4 | 3 | 3 | 3 | 3 | 1 | 1 | 1 | 1 |
> | 19th | 4 | 4 | 21 | 4 | 3 | 3 | 3 | 3 | 2 | 1 | 1 | 1 |
> | 20th | 4 | 4 | 22 | 4 | 3 | 3 | 3 | 3 | 2 | 2 | 1 | 1 |
> 
> - 1st-9th: Spell slots per level
^class-progression

## Hit Points

- **Hit Dice**: 1d8 per Druid level
- **Hit Points at First Level:** 8 + CON
- **Hit Points at Higher Levels:** add 4 OR 1d8 + CON  (minimum of 1)

## Starting Druid

You are proficient with the following items, in addition to any proficiencies provided by your race or background.

- **Saving Throws**: Intelligence, Wisdom
- **Armor**: light, shield
- **Weapons**: simple
- **Tools**: [Herbalism Kit](herbalism-kit-xphb.md)
- **Skills**: Choose 2 from *Animal Handling*, *Arcana*, *Insight*, *Medicine*, *Nature*, *Perception*, *Religion*, *Survival*

You begin play with the following equipment, in addition to any equipment provided by your background.


## Multiclassing Druid

To multiclass as a Druid, you must meet the following prerequisites:

You gain the following proficiencies:

- **Armor**: light, shield
- **Weapons**: none
- **Tools**: none

## Druid

Druids belong to ancient orders that call on the forces of nature. Harnessing the magic of animals, plants, and the four elements, Druids heal, transform into animals, and wield elemental destruction.

Revering nature above all, individual Druids gain their magic from nature, a nature deity, or both, and they typically unite with other Druids to perform rites that mark the passage of the seasons and other natural cycles.

Druids are concerned with the delicate ecological balance that sustains plant and animal life and with the need for people to live in harmony with nature. Druids often guard sacred sites or watch over regions of unspoiled nature, but when a significant danger arises, Druids take a more active role as adventurers who combat the threat.

## Class Features

### Druidic (Level 1)

You know Druidic, the secret language of Druids. While learning this ancient tongue, you also unlocked the magic of communicating with animals; you always have the [Speak with Animals](speak-with-animals-xphb.md) spell prepared.

You can use Druidic to leave hidden messages. You and others who know Druidic automatically spot such a message. Others spot the message's presence with a successful DC 15 Intelligence ([Investigation](skills.md#Investigation)) check but can't decipher it without magic.

### Primal Order (Level 1)

You have dedicated yourself to one of the following sacred roles of your choice.

- **Magician**  

    You know one extra cantrip from the Druid spell list. In addition, your mystical connection to nature gives you a bonus to your Intelligence ([Arcana](skills.md#Arcana) or [Nature](skills.md#Nature)) checks. The bonus equals your Wisdom modifier (minimum bonus of +1).  

- **Warden**  

    Trained for battle, you gain proficiency with Martial weapons and training with Medium armor.  

### Spellcasting (Level 1)

You have learned to cast spells through studying the mystical forces of nature. See "chapter 7" for the rules on spellcasting. The information below details how you use those rules with Druid spells, which appear on the Druid spell list later in the class's description.

#### Cantrips

You know two cantrips of your choice from the Druid spell list. [Druidcraft](druidcraft-xphb.md) and [Produce Flame](produce-flame-xphb.md) are recommended.

Whenever you gain a Druid level, you can replace one of your cantrips with another cantrip of your choice from the Druid spell list.

When you reach Druid levels 4 and 10, you learn another cantrip of your choice from the Druid spell list, as shown in the Cantrips column of the Druid Features table.

#### Spell Slots

The Druid Features table shows how many spell slots you have to cast your level 1+ spells. You regain all expended slots when you finish a [Long Rest](long-rest-xphb.md).

#### Prepared Spells of Level 1+

You prepare the list of level 1+ spells that are available for you to cast with this feature. To start, choose four level 1 spells from the Druid spell list. [Animal Friendship](animal-friendship-xphb.md), [Cure Wounds](cure-wounds-xphb.md), [Faerie Fire](/3-Compendium/CLI/spells/faerie-fire-xphb.md), and [Thunderwave](thunderwave-xphb.md) are recommended.

The number of spells on your list increases as you gain Druid levels, as shown in the Prepared Spells column of the Druid Features table. Whenever that number increases, choose additional spells from the Druid spell list until the number of spells on your list matches the number on the table. The chosen spells must be of a level for which you have spell slots. For example, if you're a level 3 Druid, your list of prepared spells can include six spells of levels 1 and 2 in any combination.

If another Druid feature gives you spells that you always have prepared, those spells don't count against the number of spells you can prepare with this feature, but those spells otherwise count as Druid spells for you.

#### Changing Your Prepared Spells

Whenever you finish a [Long Rest](long-rest-xphb.md), you can change your list of prepared spells, replacing any of the spells with other Druid spells for which you have spell slots.

#### Spellcasting Ability

Wisdom is your spellcasting ability for your Druid spells.

#### Spellcasting Focus

You can use a [Druidic Focus](druidic-focus-xphb.md) as a [Spellcasting Focus](spellcasting-focus-xphb.md) for your Druid spells.

### Wild Companion (Level 2)

You can summon a nature spirit that assumes an animal form to aid you. As a [Magic](actions.md#Magic) action, you can expend a spell slot or a use of Wild Shape to cast the [Find Familiar](/3-Compendium/CLI/spells/find-familiar-xphb.md) spell without Material components.

When you cast the spell in this way, the familiar is Fey and disappears when you finish a [Long Rest](long-rest-xphb.md).

### Wild Shape (Level 2)

The power of nature allows you to assume the form of an animal. As a [Bonus Action](bonus-action-xphb.md), you shape-shift into a Beast form that you have learned for this feature (see "Known Forms" below). You stay in that form for a number of hours equal to half your Druid level or until you use Wild Shape again, have the [Incapacitated](conditions.md#Incapacitated) condition, or die. You can also leave the form early as a [Bonus Action](bonus-action-xphb.md).

#### Number of Uses

You can use Wild Shape twice. You regain one expended use when you finish a [Short Rest](short-rest-xphb.md), and you regain all expended uses when you finish a [Long Rest](long-rest-xphb.md).

You gain additional uses when you reach certain Druid levels, as shown in the Wild Shape column of the Druid Features table.

#### Known Forms

You know four Beast forms for this feature, chosen from among Beast stat blocks that have a maximum [Challenge Rating](challenge-rating-xphb.md) of 1/4 and that lack a [Fly Speed](fly-speed-xphb.md) (see appendix B for stat block options). The [Rat](rat-xphb.md), [Riding Horse](3-Compendium/CLI/bestiary/beast/riding-horse-xphb.md), [Spider](spider-xphb.md), and [Wolf](wolf-xphb.md) are recommended. Whenever you finish a [Long Rest](long-rest-xphb.md), you can replace one of your known forms with another eligible form.

When you reach certain Druid levels, your number of known forms and the maximum [Challenge Rating](challenge-rating-xphb.md) for those forms increases, as shown in the Beast Shapes table. In addition, starting at level 8, you can adopt a form that has a [Fly Speed](fly-speed-xphb.md).

When choosing known forms, you may look in the [Monster](monster-xphb.md) Manual or elsewhere for eligible Beasts if the Dungeon Master permits you to do so.

**Beast Shapes**

| Druid Level | Known Forms | Max CR | Fly Speed |
|-------------|-------------|--------|-----------|
| 2 | 4 | 1/4 | No |
| 4 | 6 | 1/2 | No |
| 8 | 8 | 1 | Yes |
^beast-shapes

#### Rules While Transformed

While in a form, you retain your personality, memories, and ability to speak, and the following rules apply:

- **Temporary Hit Points.** When you assume a Wild Shape form, you gain a number of [Temporary Hit Points](temporary-hit-points-xphb.md) equal to your Druid level.  
- **Game Statistics.** Your game statistics are replaced by the Beast's stat block, but you retain your creature type; [Hit Points](hit-points-xphb.md); [Hit Point Dice](hit-point-dice-xphb.md); Intelligence, Wisdom, and Charisma scores; class features; languages; and feats. You also retain your skill and saving throw proficiencies and use your [Proficiency](proficiency-xphb.md) for them, in addition to gaining the proficiencies of the creature. If a skill or saving throw modifier in the Beast's stat block is higher than yours, use the one in the stat block.  
- **No Spellcasting.** You can't cast spells, but shape-shifting doesn't break your [Concentration](conditions.md#Concentration) or otherwise interfere with a spell you've already cast.  
- **Objects.** Your ability to handle objects is determined by the form's limbs rather than your own. In addition, you choose whether your equipment falls in your space, merges into your new form, or is worn by it. Worn equipment functions as normal, but the DM decides whether it's practical for the new form to wear a piece of equipment based on the creature's size and shape. Your equipment doesn't change size or shape to match the new form, and any equipment that the new form can't wear must either fall to the ground or merge with the form. Equipment that merges with the form has no effect while you're in that form.  

### Druid Subclass (Level 3)

You gain a Druid subclass of your choice. A subclass is a specialization that grants you features at certain Druid levels. For the rest of your career, you gain each of your subclass's features that are of your Druid level or lower.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify. You gain this feature again at Druid levels 8, 12, and 16.

### Wild Resurgence (Level 5)

Once on each of your turns, if you have no uses of Wild Shape left, you can give yourself one use by expending a spell slot (no action required).

In addition, you can expend one use of Wild Shape (no action required) to give yourself a level 1 spell slot, but you can't do so again until you finish a [Long Rest](long-rest-xphb.md).

### Subclass Feature (Level 6)

You gain a feature from your Druid Subclass.

### Elemental Fury (Level 7)

The might of the elements flows through you. You gain one of the following options of your choice.

#### Potent Spellcasting

Add your Wisdom modifier to the damage you deal with any Druid cantrip.

#### Primal Strike

Once on each of your turns when you hit a creature with an attack roll using a weapon or a Beast form's attack in Wild Shape, you can cause the target to take an extra `1d8` Cold, Fire, Lightning, or Thunder damage (choose when you hit).

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) Feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 10)

You gain a feature from your Druid Subclass.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) Feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 14)

You gain a feature from your Druid Subclass.

### Improved Elemental Fury (Level 15)

The option you chose for Elemental Fury grows more powerful, as detailed below.

#### Potent Spellcasting

When you cast a Druid cantrip with a range of 10 feet or greater, the spell's range increases by 300 feet.

#### Primal Strike

The extra damage of your Primal Strike increases to `2d8`.

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](ability-score-improvement-xphb.md) Feat or another feat of your choice for which you qualify.

### Beast Spells (Level 18)

While using Wild Shape, you can cast spells in Beast form, except for any spell that has a Material component with a cost specified or that consumes its Material component.

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify. [Boon of Dimensional Travel](boon-of-dimensional-travel-xphb.md) is recommended.

### Archdruid (Level 20)

The vitality of nature constantly blooms within you, granting you the following benefits.

#### Evergreen Wild Shape

Whenever you roll [Initiative](initiative-xphb.md) and have no uses of Wild Shape left, you regain one expended use of it.

#### Nature Magician

You can convert uses of Wild Shape into a spell slot (no action required). Choose a number of your unexpended uses of Wild Shape and convert them into a single spell slot, with each use contributing 2 spell levels. For example, if you convert two uses of Wild Shape, you produce a level 4 spell slot. Once you use this benefit, you can't do so again until you finish a [Long Rest](long-rest-xphb.md).

#### Longevity

The primal magic that you wield causes you to age more slowly. For every ten years that pass, your body ages only one year.