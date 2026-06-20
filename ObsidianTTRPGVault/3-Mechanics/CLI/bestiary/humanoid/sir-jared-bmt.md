---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bmt
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sir Jared"
---
# [Sir Jared](3-Mechanics/CLI/bestiary/humanoid/sir-jared-bmt.md)
*Source: The Book of Many Things p. 80*  

Jared is a wandering knight who makes an excellent contact for groups that have Solar Bastion patronage. A former mercenary, Jared credits Hilarion with helping him change his ways and use his skills for good instead of gold, but he feels unworthy of the organization and has grown lonely after so long away from the Solar Bastion.

```statblock
"name": "Sir Jared (BMT)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Good"
"ac": !!int "20"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor-xphb.md), [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "17"
  - !!int "13"
  - !!int "14"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[longsword](3-Mechanics/CLI/items/longsword-xphb.md)"
"senses": "passive Perception 12"
"languages": "Common, Halfling"
"cr": "5"
"actions":
  - "desc": "Jared makes three Longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) slashing damage plus 4 (1d8) radiant damage. On a roll of 19 or 20, Jared\
      \ scores a critical hit."
    "name": "Longsword"
"reactions":
  - "desc": "When a creature Jared can see attacks a target other than Jared that\
      \ is within 5 feet of him, Jared imposes disadvantage on the attack roll."
    "name": "Protect Ally"
"source":
  - "BMT"
"image": "file://bestiary/tokens/BMT/Sir%20Jared.webp"
```
^statblock