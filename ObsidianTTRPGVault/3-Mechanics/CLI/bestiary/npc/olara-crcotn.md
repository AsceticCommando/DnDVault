---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Olara"
---
# [Olara](3-Mechanics/CLI/bestiary/npc/olara-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 129*  

Olara speaks an ancient dialect that formed the basis for both Elvish and Orc, and any character who speaks and understands either of those languages can converse with her. This is a trait she shares with some of the ghosts of her kinfolk that still haunt the ruins of Cael Morrow, but Olara is no ghost; she is one of the few mortals who survived Gruumsh's attack centuries ago. She subsists on the kelp growing throughout the Drowned City.

```statblock
"name": "Olara (CRCotN)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Good"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "13"
  - !!int "11"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"damage_resistances": "cold"
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow-xphb.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 15"
"languages": "Any one language (usually Common)"
"cr": "1/2"
"traits":
  - "desc": "Olara can breathe air and water."
    "name": "Amphibious"
  - "desc": "Olara has advantage on saving throws to end the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition on herself, and magic can't put her to sleep."
    "name": "Fey Ancestry"
  - "desc": "The scout has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing or sight."
    "name": "Keen Hearing and Sight"
"actions":
  - "desc": "Olara makes two melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, ranged 150/600 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"source":
  - "CRCotN"
"image": "file://bestiary/tokens/CRCotN/Olara.webp"
```
^statblock