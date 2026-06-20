---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hol
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Disciple"
---
# [Disciple](3-Mechanics/CLI/bestiary/humanoid/disciple-hol.md)
*Source: The House of Lament p. 201*  

```statblock
"name": "Disciple (HoL)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "[shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "-1"
"stats":
  - !!int "12"
  - !!int "9"
  - !!int "10"
  - !!int "11"
  - !!int "13"
  - !!int "9"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[mace](3-Mechanics/CLI/items/mace-xphb.md)"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6\
      \ + 1) bludgeoning damage."
    "name": "Mace"
  - "desc": "You target one creature you can see within 60 feet of you. The target\
      \ must succeed on a DC 11 Dexterity saving throw or take 4 (1d8) radiant damage.\
      \ The target gains no benefit from cover for this saving throw."
    "name": "Sacred Flame (Cantrip)"
  - "desc": "You cast one the following cleric spells (spell save DC 11), using Wisdom\
      \ as the spellcasting ability:\n\n**At will:** [guidance](3-Mechanics/CLI/spells/guidance-xphb.md)\n\
      \n**2/day:** [cure wounds](3-Mechanics/CLI/spells/cure-wounds-xphb.md)"
    "name": "Spellcasting"
"source":
  - "HoL"
"image": "file://bestiary/tokens/HoL/Disciple.webp"
```
^statblock