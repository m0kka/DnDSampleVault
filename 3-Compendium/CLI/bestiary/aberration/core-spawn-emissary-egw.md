---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Core Spawn Emissary"]
---
# [Core Spawn Emissary](3-Compendium\CLI\bestiary\aberration/core-spawn-emissary-egw.md)
*Source: Explorer's Guide to Wildemount p. 286*  

These airborne predators serve as assassins and sentinels for the core spawn. The terrible thrum of its insectoid wings and a chittering of mandibles announces an emissary's arrival.

The core spawn emissary can expel clouds of crystalline spores from tubes in its head. These spores act like a contact poison and can be deadly if inhaled.

The Elder Evils assault the multiverse in strange and calamitous ways. Sometimes they breach the Material Plane by exploiting the unfathomable energy and darkness found in the world's depths. These terrestrial manifestations of loathsome alien agendas are known as core spawn, and they are as varied in their physiology as they are horrific.

Their concentration in the desolate lands of Blightshore makes the core spawn a challenge to research, and many who have sought to observe or study these nightmarish entities rarely return. Those who do return are often shells of their former selves who speak of horrifying underground labyrinths of twisting caverns and malevolent nests where other denizens of the Miskath Strand are dragged below to some infernal purpose.

## Offspring of Calamity

The aberrant creatures known as core spawn are a subterranean breed of heralds, servants, foot soldiers, and lieutenants of the Elder Evils, awakened in the depths by the cataclysmic actions of the Betrayer Gods and their minions. They often appear on the surface world in the wake of seismic events, such as that which created the bottomless Miskath Pit of Eastern Wynandir. Warlocks and cultists sometimes gather together to hasten the arrival of core spawn to the Material Plane, focusing their arcane power on areas of natural seismic instability when the signs and stars are right.

```statblock
"name": "Core Spawn Emissary (EGW)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "102"
"hit_dice": "12d8 + 48"
"stats":
- !!int "17"
- !!int "15"
- !!int "18"
- !!int "8"
- !!int "13"
- !!int "8"
"speed": "40 ft., fly 60 ft. (hover)"
"saves":
  "Charisma": !!int "2"
  "Dexterity": !!int "5"
  "Wisdom": !!int "4"
"skillsaves":
  "Perception": !!int "4"
"damage_immunities": "psychic"
"condition_immunities": "blinded"
"senses": "blindsight 30 ft., tremorsense 60 ft., passive Perception 14"
"languages": "telepathy 120 ft., understands Deep Speech but can't speak"
"cr": "6"
"traits":
- "desc": "The emissary has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The emissary makes three talons attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 14\
    \ (2d10 + 3) slashing damage."
  "name": "Talons"
- "desc": "The emissary emits a dreadful yet alluring hum. Each creature within 20\
    \ feet of the emissary that can hear it and that isn't an aberration must succeed\
    \ on a DC 14 Constitution saving throw or be charmed for 1 minute. A creature\
    \ can repeat the saving throw at the end of each of its turns, ending the effect\
    \ on itself on a success."
  "name": "Alluring Thrum (Recharge 5-6)"
- "desc": "A 15-foot-radius cloud of toxic crystalline spores extends out from the\
    \ emissary. The spores spread around corners. Each creature in the area must succeed\
    \ on a DC 14 Constitution saving throw or become poisoned. While poisoned in this\
    \ way, a creature takes 11 (2d10) poison damage at the start of each of its turns.\
    \ A creature can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success."
  "name": "Crystal Spores (Recharge 6)"
"source":
- "EGW"
"image": "bestiary/tokens/EGW/Core Spawn Emissary.webp"
```
^statblock