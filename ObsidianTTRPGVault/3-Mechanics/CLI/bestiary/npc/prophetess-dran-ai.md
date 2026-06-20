---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Prophetess Dran"
---
# [Prophetess Dran](3-Mechanics/CLI/bestiary/npc/prophetess-dran-ai.md)
*Source: Acquisitions Incorporated p. 208*  

```statblock
"name": "Prophetess Dran (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Lawful Good"
"ac": !!int "14"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+5"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+3"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+5"
"gear":
  - "[maul](3-Mechanics/CLI/items/maul-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Common, Elvish"
"cr": "2"
"traits":
  - "desc": "Prophetess is a 5th-level spellcaster. Her spellcasting ability is Wisdom\
      \ (spell save DC 13, +5 to hit with spell attacks). Prophetess has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [sacred flame](3-Mechanics/CLI/spells/sacred-flame-xphb.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
      \n**1st level (4 slots):** [cure wounds](3-Mechanics/CLI/spells/cure-wounds-xphb.md),\
      \ [guiding bolt](3-Mechanics/CLI/spells/guiding-bolt-xphb.md), [sanctuary](3-Mechanics/CLI/spells/sanctuary-xphb.md)\n\
      \n**2nd level (3 slots):** [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration-xphb.md),\
      \ [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)\n\n**3rd\
      \ level (2 slots):** [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [spirit guardians](3-Mechanics/CLI/spells/spirit-guardians-xphb.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, Prophetess can expend a spell slot to cause her melee\
      \ weapon attacks to magically deal an extra 10 (3d6) radiant damage to a target\
      \ on a hit. This benefit lasts until the end of the turn. If Prophetess expends\
      \ a spell slot of 2nd level or higher, the extra damage increases by 1d6 for\
      \ each level above 1st."
    "name": "Divine Eminence"
  - "desc": "Prophetess has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put her to sleep."
    "name": "Fey Ancestry"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6\
      \ + 2) bludgeoning damage."
    "name": "Maul"
"source":
  - "AI"
"image": "file://bestiary/tokens/AI/Prophetess%20Dran.webp"
```
^statblock