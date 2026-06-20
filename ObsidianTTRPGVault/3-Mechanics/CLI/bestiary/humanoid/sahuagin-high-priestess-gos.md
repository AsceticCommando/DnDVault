---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/sahuagin
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sahuagin High Priestess"
---
# [Sahuagin High Priestess](3-Mechanics/CLI/bestiary/humanoid/sahuagin-high-priestess-gos.md)
*Source: Ghosts of Saltmarsh p. 251*  

A sahuagin high priestess is the most devout and ferocious of all Sekolah's worshipers. Armed with a staff studded with jagged shark's teeth, she can be seen leading dark rituals in The Final Enemy.

```statblock
"name": "Sahuagin High Priestess (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "12"
  - !!int "16"
  - !!int "10"
"speed": "30 ft., swim 40 ft."
"saves":
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 16"
"languages": "Sahuagin"
"cr": "5"
"traits":
  - "desc": "The high priestess is a 7th-level spellcaster. Her spellcasting ability\
      \ is Wisdom (spell save DC 14, +6 to hit with spell attacks). She has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [guidance](3-Mechanics/CLI/spells/guidance-xphb.md),\
      \ [mending](3-Mechanics/CLI/spells/mending-xphb.md), [resistance](3-Mechanics/CLI/spells/resistance-xphb.md),\
      \ [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\n**1st level (4\
      \ slots):** [bless](3-Mechanics/CLI/spells/bless-xphb.md), [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [guiding bolt](3-Mechanics/CLI/spells/guiding-bolt-xphb.md)\n\n**2nd level\
      \ (3 slots):** [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md), [spiritual\
      \ weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md) (trident)\n\n**3rd\
      \ level (3 slots):** [bestow curse](3-Mechanics/CLI/spells/bestow-curse-xphb.md),\
      \ [fear](3-Mechanics/CLI/spells/fear-xphb.md), [mass healing word](3-Mechanics/CLI/spells/mass-healing-word-xphb.md),\
      \ [tongues](3-Mechanics/CLI/spells/tongues-xphb.md)\n\n**4th level (1 slots):**\
      \ [banishment](3-Mechanics/CLI/spells/banishment-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The high priestess has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The high priestess can breathe air and water, but she needs to be submerged\
      \ at least once every 4 hours to avoid suffocating."
    "name": "Limited Amphibiousness"
  - "desc": "The high priestess can magically command any shark within 120 feet of\
      \ her, using a limited telepathy."
    "name": "Shark Telepathy"
"actions":
  - "desc": "The high priestess makes two attacks with her toothsome staff, or one\
      \ attack with her bite and one with her claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d8 + 2) piercing damage."
    "name": "Toothsome Staff"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) slashing damage."
    "name": "Claws"
"source":
  - "GoS"
"image": "file://bestiary/tokens/GoS/Sahuagin%20High%20Priestess.webp"
```
^statblock