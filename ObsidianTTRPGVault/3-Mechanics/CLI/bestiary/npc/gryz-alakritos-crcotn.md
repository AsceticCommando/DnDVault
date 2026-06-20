---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gryz Alakritos"
---
# [Gryz Alakritos](3-Mechanics/CLI/bestiary/npc/gryz-alakritos-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 81*  

```statblock
"name": "Gryz Alakritos (CRCotN)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "goblin, wizard"
"alignment": "Neutral Good"
"ac": !!int "12"
"hp": !!int "82"
"hit_dice": "15d8 + 15"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "13"
  - !!int "18"
  - !!int "16"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+7"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 16"
"languages": "Common plus three other languages, Goblin"
"cr": "5"
"traits":
  - "desc": "Gryz"
    "name": "Nimble Escape"
"actions":
  - "desc": "Gryz makes two Arcane Shock or Dagger of the Poisoned Mind attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range 60 ft.,\
      \ one target. *Hit:* 26 (4d10 + 4) lightning damage. If the target is a creature,\
      \ it can't take reactions until the start of its next turn."
    "name": "Arcane Shock"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d4 + 4) piercing damage plus 10 (3d6) psychic\
      \ damage. If the target is a creature, it must succeed on a DC 15 Wisdom saving\
      \ throw or be [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) until\
      \ the end of its next turn."
    "name": "Dagger of the Poisoned Mind"
  - "desc": "Gryz casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\n\
      **At will:** [alter self](3-Mechanics/CLI/spells/alter-self-xphb.md), [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\n\n**1/day each:** [comprehend\
      \ languages](3-Mechanics/CLI/spells/comprehend-languages-xphb.md), [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md),\
      \ [zone of truth](3-Mechanics/CLI/spells/zone-of-truth-xphb.md)"
    "name": "Spellcasting"
"source":
  - "CRCotN"
"image": "file://bestiary/tokens/CRCotN/Gryz%20Alakritos.webp"
```
^statblock