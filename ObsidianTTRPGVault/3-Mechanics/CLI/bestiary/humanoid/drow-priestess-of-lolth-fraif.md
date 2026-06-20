---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drow Priestess of Lolth"
---
# [Drow Priestess of Lolth](3-Mechanics/CLI/bestiary/humanoid/drow-priestess-of-lolth-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 261*  

Lolth's worship is matriarchal, and only female drow can rise to become priestesses of the Spider Queen or rule a noble house.

## Drow of Lolth

*Elves Who Serve the Spider Queen*

Throughout the vast Underdark, in cities such as Menzoberranzan, many drow worship Lolth, the Spider Queen. Exiled from the surface world millennia ago, these drow now consider the Underdark to be their true home. Their insidious schemes include raiding the surface, plotting against each other, and preparing for ultimate war.

```statblock
"name": "Drow Priestess of Lolth (FRAiF)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "13"
  - !!int "18"
  - !!int "17"
"speed": "30 ft., fly 15 ft. (hover)"
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "7"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 17"
"languages": "Abyssal, Common, Elvish, Undercommon"
"cr": "8"
"traits":
  - "desc": "The drow has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws it makes to avoid or end the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition, and magic can't put the drow to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, the drow has [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md)\
      \ on attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The drow makes three Scourge attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 10 ft. *Hit:* 6 (1d6 + 3) Piercing damage\
      \ plus 17 (5d6) Poison damage."
    "name": "Scourge"
  - "desc": "*Constitution Saving Throw:* DC 15, each enemy in a 20-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the drow. *Failure:* 33 (6d10) Piercing damage, and the target\
      \ has the [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) condition\
      \ until the start of the drow's next turn. *Success:* Half damage only."
    "name": "Spider Vortex (Recharge 5-6)"
  - "desc": "The drow casts one of the following spells, requiring no Material components\
      \ and using Wisdom as the spellcasting ability:\n\n**At will:** [Dancing Lights](3-Mechanics/CLI/spells/dancing-lights-xphb.md),\
      \ [Guidance](3-Mechanics/CLI/spells/guidance-xphb.md), [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The drow casts [Cure Wounds](3-Mechanics/CLI/spells/cure-wounds-xphb.md),\
      \ [Darkness](3-Mechanics/CLI/spells/darkness-xphb.md), [Dispel Magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ or [Lesser Restoration](3-Mechanics/CLI/spells/lesser-restoration-xphb.md),\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Lolth's Blessing (3/Day)"
"source":
  - "FRAiF"
"image": "file://bestiary/tokens/FRAiF/Drow%20Priestess%20of%20Lolth.webp"
```
^statblock

## Environment

underdark, urban