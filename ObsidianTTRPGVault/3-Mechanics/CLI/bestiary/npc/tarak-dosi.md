---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/dosi
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tarak"
---
# [Tarak](3-Mechanics\CLI\bestiary\npc/tarak-dosi.md)
*Source: Dragons of Stormwreck Isle p. 47*  

Before coming to Dragon's Rest, Tarak was a criminal, but he has since devoted himself to the study of herbs and medicine. He is usually unarmed, but he keeps several daggers hidden in his cell (in area A1 of Dragon's Rest).

```statblock
"name": "Tarak (DoSI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+3"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 12"
"languages": "Common, Draconic, Thieves' cant"
"cr": "1"
"actions":
  - "desc": "Tarak makes three Dagger attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
"bonus_actions":
  - "desc": "Tarak takes the [Dash](3-Mechanics/CLI/rules/actions.md#Dash), [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage),\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Cunning Action"
"source":
  - "DoSI"
"image": "3-Mechanics/CLI/bestiary/npc/token/tarak-dosi.webp"
```
^statblock