---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ekengarik"
---
# [Ekengarik](3-Mechanics/CLI/bestiary/npc/ekengarik-coa.md)
*Source: Chains of Asmodeus p. 141*  

```statblock
"name": "Ekengarik (CoA)"
"size": "Large"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "231"
"hit_dice": "22d10 + 110"
"modifier": !!int "3"
"stats":
  - !!int "23"
  - !!int "16"
  - !!int "21"
  - !!int "14"
  - !!int "17"
  - !!int "21"
"speed": "30 ft."
"saves":
  - "constitution": !!int "10"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+10"
"damage_resistances": "acid; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 13"
"languages": "Common, Formian, telepathy 120 ft."
"cr": "16"
"traits":
  - "desc": "All fiendish formians within 1 mile of Ekengarik can telepathically communicate\
      \ with each other and Ekengarik."
    "name": "Hive Mind"
  - "desc": "Ekengarik regenerates 10 hit points at the start of her turn, unless\
      \ she took radiant damage in the last round."
    "name": "Regeneration"
"actions":
  - "desc": "Ekengarik makes three Bite attacks. She can replace one of the attacks\
      \ with an Acid Spray (if available) attack or a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:* 15\
      \ (2d8 + 6) piercing damage and the target must make a DC 19 Constitution saving\
      \ throw. On a failed save, the target's Strength score is reduced by 2 (1d4).\
      \ The target dies if this reduces its Strength to 0. Otherwise, the reduction\
      \ lasts until the target finishes a short or long rest."
    "name": "Bite"
  - "desc": "Ekengarik spits acid at one creature within 60 feet of her, or two creatures\
      \ within 60 feet of her and 5 feet of each other. Targets must make a DC 18\
      \ Dexterity saving throw, taking 33 (6d10) acid damage on a failed saving throw,\
      \ or half as much on a successful one."
    "name": "Acid Spray (Recharge 5-6)"
  - "desc": "Ekengarik casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 18):\n\n**At\
      \ will:** [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Dispel\
      \ Magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [Heroism](3-Mechanics/CLI/spells/heroism-xphb.md),\
      \ [Magic Missile](3-Mechanics/CLI/spells/magic-missile-xphb.md)\n\n**1/day each:**\
      \ [Evard's Black Tentacles](3-Mechanics/CLI/spells/evards-black-tentacles-xphb.md),\
      \ [Cone of Cold](3-Mechanics/CLI/spells/cone-of-cold-xphb.md), [Confusion](3-Mechanics/CLI/spells/confusion-xphb.md),\
      \ [Dimension Door](3-Mechanics/CLI/spells/dimension-door-xphb.md), [Geas](3-Mechanics/CLI/spells/geas-xphb.md),\
      \ [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md), [Prismatic Wall](3-Mechanics/CLI/spells/prismatic-wall-xphb.md),\
      \ [Slow](3-Mechanics/CLI/spells/slow-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When hit with an attack, Ekengarik temporarily hardens her carapace,\
      \ reducing her speed to 0 and increasing her AC by 5 until the start of her\
      \ next turn."
    "name": "Hardened Carapace (Recharge 4-6)"
"source":
  - "CoA"
"image": "file://bestiary/tokens/CoA/Ekengarik.webp"
```
^statblock