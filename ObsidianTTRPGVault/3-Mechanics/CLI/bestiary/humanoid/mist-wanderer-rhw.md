---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mist Wanderer"
---
# [Mist Wanderer](3-Mechanics/CLI/bestiary/humanoid/mist-wanderer-rhw.md)
*Source: RHW p. 256*  

*Traveler Between Domains*

Those who travel between the Domains of Dread develop traditions that hasten their travel and protect them from evil. Vistani, along with those who research their ways or the secrets of the Mists, are the most adept of such domain explorers.

```statblock
"name": "Mist Wanderer (RHW)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "12"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+5"
"gear":
  - "[orb](3-Mechanics/CLI/items/orb-xphb.md)"
  - "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"senses": "passive Perception 13"
"languages": "Common plus one other language"
"cr": "3"
"traits":
  - "desc": "*Charisma Saving Throw:* DC 13, each creature in a 5-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the wanderer when it dies. *Failure:* The target is cursed.\
      \ While cursed, the target has the [Blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [Deafened](3-Mechanics/CLI/rules/conditions.md#Deafened) conditions."
    "name": "Death Curse"
  - "desc": "The wanderer can travel safely through the Mists to reach a specific\
      \ domain it knows by name. The wanderer still can't bypass domain borders closed\
      \ by a Darklord's will."
    "name": "Mist Walker"
"actions":
  - "desc": "The wanderer makes two Radiant Burst attacks. It can replace one attack\
      \ with a use of Spellcasting to cast [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)\
      \ if available."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +5, reach 5 ft. or range 60 ft. *Hit:*\
      \ 14 (2d10 + 3) Radiant damage."
    "name": "Radiant Burst"
  - "desc": "The wanderer casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** [Light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\n\n**1/day each:** [Augury](3-Mechanics/CLI/spells/augury-xphb.md),\
      \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The wanderer casts [Hold Person](3-Mechanics/CLI/spells/hold-person-xphb.md),\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Evil Eye (1/Day)"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Mist%20Wanderer.webp"
```
^statblock

## Environment

any