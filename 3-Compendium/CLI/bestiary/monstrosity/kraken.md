---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
aliases: ["Kraken"]
---
# [Kraken](3-Compendium\CLI\bestiary\monstrosity/kraken.md)
*Source: Monster Manual p. 197, Explorer's Guide to Wildemount, Mythic Odysseys of Theros, The Book of Many Things. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Beneath the waves, the kraken sleeps for untold ages, awaiting some fell sign or calling. Land-born mortals who sail the open sea forget the reasons their ancestors dreaded the ocean, even as the races of the deep ignore strange gaps in their histories when their civilizations nearly vanished after the appearance of the tentacled horror.

## Leviathans of Legend

At the beginning of time, krakens served as fierce warriors of the gods. When the gods' wars ended, the krakens shrugged free of their servitude, never again to be bound by other beings. Whole nations quake in fear when the kraken emerges from its dark demesne, and even in the middle of the deepest oceans, storms rise or abate according to its will. The kraken is a primeval force that obliterates the greatest achievements of civilization as if they were castles in the sand. Its devastating attacks can destroy ocean trade and halt communication between coastal cities.

An ominous darkness presages a kraken's attack, and a cloud of inky poison colors the water around it. Galleons and warships vanish when its tentacles uncoil from the deep, the kraken breaking their masts like kindling before drawing down ships and crew. Not even landlocked surface dwellers are safe from a kraken's wrath. Krakens can breathe air as easily as water, and some crawl up rivers to nest in freshwater lakes, destroying cities and towns along the way. Adventurers tell of these monsters lairing in the ruins of lakeside citadels, their tentacles twined around leaning towers of disintegrating stone.

## Mortal Foes

Some krakens are virtual gods, with cults and minions spread across sea and land. Others are allied with Olhydra, the evil Princess of Elemental Water, and use her cultists to enforce their will on land and sea. A kraken pleased with its worshipers can becalm rough seas and bring a bounteous harvest of fish to the faithful. However, the devious mind of a kraken is ancient beyond reckoning, and is ultimately bent to the ruination of all things.

> [!quote] A quote from From Night of the Kraken Cult by Malfeore Serrang, pirate-mage of Tethyr  
> 
> A kraken dreams of casting its tentacles into the heavens and strangling that which birthed it, and when its dream exceeds its reach, it settles for the occasional passing ship.

## A Kraken's Lair

A kraken lives in dark depths, usually a sunken rift or a cavern filled with detritus, treasure, and wrecked ships.

```statblock
"name": "Kraken"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "472"
"hit_dice": "27d20 + 189"
"stats":
- !!int "30"
- !!int "11"
- !!int "25"
- !!int "22"
- !!int "18"
- !!int "20"
"speed": "20 ft., swim 60 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "11"
  "Intelligence": !!int "13"
  "Strength": !!int "17"
  "Constitution": !!int "14"
"damage_immunities": "lightning; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "frightened, paralyzed"
"senses": "truesight 120 ft., passive Perception 14"
"languages": "Abyssal, Celestial, Infernal, Primordial, telepathy 120 ft. but can't\
  \ speak"
"cr": "23"
"traits":
- "desc": "The kraken can breathe air and water."
  "name": "Amphibious"
- "desc": "The kraken ignores difficult terrain, and magical effects can't reduce\
    \ its speed or cause it to be restrained. It can spend 5 feet of movement to escape\
    \ from nonmagical restraints or being grappled."
  "name": "Freedom of Movement"
- "desc": "The kraken deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The kraken makes three tentacle attacks, each of which it can replace with\
    \ one use of Fling."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 5 ft., one target. Hit: 23 (3d8\
    \ + 10) piercing damage. If the target is a Large or smaller creature grappled\
    \ by the kraken, that creature is swallowed, and the grapple ends. While swallowed,\
    \ the creature is blinded and restrained, it has total cover against attacks and\
    \ other effects outside the kraken, and it takes 42 (12d6) acid damage at the\
    \ start of each of the kraken's turns. If the kraken takes 50 damage or more on\
    \ a single turn from a creature inside it, the kraken must succeed on a DC 25\
    \ Constitution saving throw at the end of that turn or regurgitate all swallowed\
    \ creatures, which fall prone in a space within 10 feet of the kraken. If the\
    \ kraken dies, a swallowed creature is no longer restrained by it and can escape\
    \ from the corpse using 15 feet of movement, exiting prone."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +17 to hit, reach 30 ft., one target. Hit: 20\
    \ (3d6 + 10) bludgeoning damage, and the target is grappled (escape DC 18). Until\
    \ this grapple ends, the target is restrained. The kraken has ten tentacles, each\
    \ of which can grapple one target."
  "name": "Tentacle"
- "desc": "One Large or smaller object held or creature grappled by the kraken is\
    \ thrown up to 60 feet in a random direction and knocked prone. If a thrown target\
    \ strikes a solid surface, the target takes 3 (1d6) bludgeoning damage for every\
    \ 10 feet it was thrown. If the target is thrown at another creature, that creature\
    \ must succeed on a DC 18 Dexterity saving throw or take the same damage and be\
    \ knocked prone."
  "name": "Fling"
- "desc": "The kraken magically creates three bolts of lightning, each of which can\
    \ strike a target the kraken can see within 120 feet of it. A target must make\
    \ a DC 23 Dexterity saving throw, taking 22 (4d10) lightning damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Lightning Storm"
"legendary_actions":
- "desc": "The kraken makes one tentacle attack or uses its Fling."
  "name": "Tentacle Attack or Fling"
- "desc": "The kraken uses Lightning Storm."
  "name": "Lightning Storm (Costs 2 Actions)"
- "desc": "While underwater, the kraken expels an ink cloud in a 60-foot radius. The\
    \ cloud spreads around corners, and that area is heavily obscured to creatures\
    \ other than the kraken. Each creature other than the kraken that ends its turn\
    \ there must succeed on a DC 23 Constitution saving throw, taking 16 (3d10) poison\
    \ damage on a failed save, or half as much damage on a successful one. A strong\
    \ current disperses the cloud, which otherwise disappears at the end of the kraken's\
    \ next turn."
  "name": "Ink Cloud (Costs 3 Actions)"
"source":
- "MM"
- "EGW"
- "MOT"
- "BMT"
"image": "bestiary/tokens/MM/Kraken.webp"
```
^statblock

## Environment

underwater