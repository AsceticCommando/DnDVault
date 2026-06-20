---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lfl
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Merrow Haranguer"
---
# [Merrow Haranguer](3-Mechanics/CLI/bestiary/monstrosity/merrow-haranguer-lfl.md)
*Source: Lorwyn: First Light*  

Most Lorwyn merrow are Merrow Haranguers, who seek to overwhelm others with a glut of highly critical language to get their way.

## Merrow

Merrow are primarily water-dwelling people who exploit the realm of Lorwyn-Shadowmoor's land-dwelling species. They resemble large fish with humanoid torsos and arms, though their forms vary widely. Merrow are often capable warriors, but most prefer to duel with cutting words before resorting to physical violence.

```statblock
"name": "Merrow Haranguer (LFL)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "14"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "19"
"speed": "5 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+7"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+7"
"senses": "passive Perception 12"
"languages": "Common, Primordial (Aquan)"
"cr": "5"
"traits":
  - "desc": "The merrow can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The merrow makes three attacks, using Coral Scepter and Poisoned Longbow\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 14 (2d10 + 4) Bludgeoning\
      \ damage."
    "name": "Coral Scepter"
  - "desc": "*Ranged Attack Roll:* +7, range 150/600 ft. *Hit:* 8 (1d8 + 4) Piercing\
      \ damage plus 7 (2d6) Poison damage."
    "name": "Poisoned Longbow"
  - "desc": "*Wisdom Saving Throw:* DC 15, up to three creatures the merrow can see\
      \ within 60 feet. *Failure:* 14 (4d6) Psychic damage, and the creature has [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md)\
      \ on its next attack roll before the end of the merrow's next turn. *Success:*\
      \ Half damage only."
    "name": "Invective"
"source":
  - "LFL"
"image": "file://bestiary/tokens/LFL/Merrow%20Haranguer.webp"
```
^statblock

## Environment

planar, feywild