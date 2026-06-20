---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mist Horror"
---
# [Mist Horror](3-Mechanics/CLI/bestiary/undead/mist-horror-rhw.md)
*Source: RHW p. 255*  

*Shapeless Stalker in the Mists*

The Mists separating the Domains of Dread are far from safe—or empty. Mist horrors are animate clouds of vapor, barely perceptible within the Mists. In the presence of creatures, these vaporous terrors take the shape of their viewers' greatest fears. Such appearances are subjective, and anyone who views a mist horror sees it in the way that terrifies them most. A mist horror outside the Mists swiftly loses cohesion and collapses into harmless vapor.

```statblock
"name": "Mist Horror (RHW)"
"size": "Large"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "45"
"hit_dice": "7d10 + 7"
"modifier": !!int "2"
"stats":
  - !!int "1"
  - !!int "15"
  - !!int "12"
  - !!int "6"
  - !!int "13"
  - !!int "16"
"speed": "25 ft., fly 25 ft. (hover)"
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 120 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The mist horror can enter an enemy's space and stop there. It can move\
      \ through a space as narrow as 1 inch without expending extra movement to do\
      \ so."
    "name": "Air Form"
  - "desc": "While the mist horror is in fog or mist, it has the [Invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ condition. The mist horror has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition while it is outside an area of fog or mist."
    "name": "One with the Mists"
"actions":
  - "desc": "The mist horror makes two Mind Rend attacks. It can replace one attack\
      \ with a use of Spellcasting to cast [Command](3-Mechanics/CLI/spells/command-xphb.md)\
      \ if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Psychic damage."
    "name": "Mind Rend"
  - "desc": "The mist horror casts one of the following spells, requiring no spell\
      \ components and using Charisma as the spellcasting ability (spell save DC 13):\n\
      \n**At will:** [Fog Cloud](3-Mechanics/CLI/spells/fog-cloud-xphb.md)\n\n**1/day:**\
      \ [Command](3-Mechanics/CLI/spells/command-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "*Wisdom Saving Throw:* DC 13, each creature in the mist horror's space.\
      \ *Failure:* The target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the start of the mist horror's next turn."
    "name": "Instill Dread (Recharge 4-6)"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Mist%20Horror.webp"
```
^statblock

## Environment

any