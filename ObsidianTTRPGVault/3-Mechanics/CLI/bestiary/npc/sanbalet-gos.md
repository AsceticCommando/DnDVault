---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sanbalet"
---
# [Sanbalet](3-Mechanics/CLI/bestiary/npc/sanbalet-gos.md)
*Source: Ghosts of Saltmarsh p. 252*  

In The Sinister Secret of Saltmarsh, Sanbalet is the leader of the land-based half of a smuggling ring. He is a cunning narcissist with an interest in illusion and mind control. He defends the contraband stored in the caves under the haunted house.

```statblock
"name": "Sanbalet (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "11"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "11"
  - !!int "16"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "1"
"traits":
  - "desc": "Sanbalet is a 3rd-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 13, +5 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** [dancing lights](3-Mechanics/CLI/spells/dancing-lights-xphb.md),\
      \ [minor illusion](3-Mechanics/CLI/spells/minor-illusion-xphb.md), [ray of frost](3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\
      \n**1st level (4 slots):** [charm person](3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [color spray](3-Mechanics/CLI/spells/color-spray-xphb.md), [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md),\
      \ [silent image](3-Mechanics/CLI/spells/silent-image-xphb.md)\n\n**2nd level\
      \ (2 slots):** [magic mouth](3-Mechanics/CLI/spells/magic-mouth-xphb.md), [scorching\
      \ ray](3-Mechanics/CLI/spells/scorching-ray-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 3 (1d4 + 1) piercing damage."
    "name": "Dagger"
"source":
  - "GoS"
"image": "file://bestiary/tokens/GoS/Sanbalet.webp"
```
^statblock