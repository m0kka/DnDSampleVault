---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/giant/titan
statblock: inline
aliases: ["Scion of Skoraeus"]
---
# [Scion of Skoraeus](3-Compendium\CLI\bestiary\giant/scion-of-skoraeus-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 169*  

A scion of Skoraeus typically slumbers deep in the heart of a towering mountain, almost becoming one with the earth. While the scion dreams, the mountain's minerals are transformed into fine carving stones and brilliant gems.

If a miner tunnels too close to the heart of the mountain, the cradle awakens as a bipedal mass of stone and crystals. It brings the weight of the mountain down on the intruder's head and unleashes an earsplitting roar that can collapse mine tunnels.

If the cradle is destroyed, the scion of Skoraeus inside it awakens. At nearly 70 feet tall, it towers over most other creatures and wields a mass of crystal as a club. Once awakened, the scion continues to pursue the art that ornamented its dreams, seeking to mold and shape stone into beautiful elegance. If it needs more raw materials, the scion can transform a living creature in its palm into stone.

> [!quote] A quote from Bigby  
> 
> One time Diancastra and I were exploring deep underground, and suddenly an eye opened in the wall of the cave and a rumbling voice said, "Auntie D, is that you?" I nearly... well, let's just say I was startled.

> [!quote] A quote from Diancastra  
> 
> Don't forget who I am, dear Bigby.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See " Giants of Myth " in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Scion of Skoraeus (BGG)"
"size": "Gargantuan"
"type": "giant"
"subtype": "titan"
"alignment": "typically  Neutral"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "444"
"hit_dice": "24d20 + 192"
"stats":
- !!int "29"
- !!int "20"
- !!int "26"
- !!int "19"
- !!int "24"
- !!int "14"
"speed": "60 ft."
"saves":
  "Dexterity": !!int "12"
  "Wisdom": !!int "14"
"skillsaves":
  "Perception": !!int "14"
  "Acrobatics": !!int "12"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid"
"condition_immunities": "charmed, frightened, paralyzed, petrified"
"senses": "truesight 120 ft., passive Perception 24"
"languages": "Giant, Primordial"
"cr": "23"
"traits":
- "desc": "If the scion fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (6/Day)"
- "desc": "The scion has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The scion deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The scion makes one Crystal Club attack and two Slam attacks, then uses\
    \ Entombing Grasp if available. Alternatively, the scion makes two Runic Boulder\
    \ attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +16 to hit, reach 30 ft., one target. Hit: 35\
    \ (4d12 + 9) bludgeoning damage. Hit or Miss: The scion can cause the club to\
    \ flare with bright light, and the target must succeed on a DC 22 Constitution\
    \ saving throw or take 18 (4d8) radiant damage and have the blinded condition\
    \ until the start of the scion's next turn."
  "name": "Crystal Club"
- "desc": "Melee Weapon Attack: +16 to hit, reach 20 ft., one target. Hit: 31\
    \ (4d10 + 9) force damage."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +16 to hit, range 120/480 ft., one target. Hit:\
    \ 27 (4d8 + 9) bludgeoning damage. Hit or Miss: The boulder explodes. The target\
    \ and each creature within 30 feet of it must make a DC 22 Dexterity saving throw.\
    \ On a failed save, a creature takes 19 (3d12) force damage and has the prone\
    \ condition. On a successful save, a creature takes half as much damage only."
  "name": "Runic Boulder"
- "desc": "The scion wreathes its hand in petrifying magic and touches one Huge or\
    \ smaller creature it can see within 20 feet of itself. The target must succeed\
    \ on a DC 24 Dexterity saving throw or take 28 (8d6) force damage and have the\
    \ grappled condition (escape DC 19). At the start of the scion's next turn, if\
    \ the target is still grappled, the target has the petrified condition."
  "name": "Entombing Grasp (Recharge 6)"
"bonus_actions":
- "desc": "The scion moves up to its speed and then sends a shock wave through the\
    \ ground in a 60-footradius circle centered on itself. Each creature on the ground\
    \ in that area that is concentrating must succeed on a DC 24 Constitution saving\
    \ throw or lose concentration."
  "name": "Earth-Shaking Movement"
"regional_effects":
- "desc": "The region surrounding a scion of Skoraeus is altered by the giant's magic,\
    \ creating one or more of the following effects:"
  "name": ""
- "desc": "- Abundant Stone and Minerals. Smooth stones and gems grow within 6\
    \ miles of the scion.  \n- Edible Moss. Carpets of golden moss that stone\
    \ giants find tasty grow on cavern walls within 6 miles of the scion.  \n- Empowered\
    \ Stone Giants. Stone giants within 1,000 feet of the scion gain a +7 bonus\
    \ to attack and damage rolls.  "
  "name": ""
- "desc": "If the scion dies, the Empowered Stone Giants effect ends immediately.\
    \ The other effects cease to produce new moss and minerals, and existing moss\
    \ dies within 1d10 days."
  "name": ""
"source":
- "BGG"
"image": "bestiary/tokens/BGG/Scion of Skoraeus.webp"
```
^statblock