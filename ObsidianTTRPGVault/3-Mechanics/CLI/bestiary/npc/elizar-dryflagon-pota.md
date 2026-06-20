---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Elizar Dryflagon"
---
# [Elizar Dryflagon](3-Mechanics/CLI/bestiary/npc/elizar-dryflagon-pota.md)
*Source: Princes of the Apocalypse p. 202*  

Elizar was a druid who claims to be a member of the Circle of the Scarlet Moon. However, Elizar is really in service to Imix, maintaining some druidic power through a connection to the elements.

```statblock
"name": "Elizar Dryflagon (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "14"
  - !!int "11"
  - !!int "18"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+3"
"gear":
  - "[+1 dagger](3-Mechanics/CLI/items/1-weapon-xdmg.md)"
"senses": "passive Perception 14"
"languages": "Common, Druidic"
"cr": "5"
"traits":
  - "desc": "Elizar is a 7th-level spellcaster. His spellcasting ability is Wisdom\
      \ (spell save DC 15, +7 to hit with spell attacks). Elizar has the following\
      \ druid spells prepared:\n\n**Cantrips (at will):** [druidcraft](3-Mechanics/CLI/spells/druidcraft-xphb.md),\
      \ [guidance](3-Mechanics/CLI/spells/guidance-xphb.md), [poison spray](3-Mechanics/CLI/spells/poison-spray-xphb.md),\
      \ [produce flame](3-Mechanics/CLI/spells/produce-flame-xphb.md)\n\n**1st level\
      \ (4 slots):** [animal friendship](3-Mechanics/CLI/spells/animal-friendship-xphb.md),\
      \ [faerie fire](3-Mechanics/CLI/spells/faerie-fire-xphb.md), [healing word](3-Mechanics/CLI/spells/healing-word-xphb.md),\
      \ [jump](3-Mechanics/CLI/spells/jump-xphb.md), [thunderwave](3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\
      \n**2nd level (3 slots):** [flame blade](3-Mechanics/CLI/spells/flame-blade-xphb.md),\
      \ [spike growth](3-Mechanics/CLI/spells/spike-growth-xphb.md)\n\n**3rd level\
      \ (3 slots):** [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [stinking cloud](3-Mechanics/CLI/spells/stinking-cloud-xphb.md)\n\n**4th level\
      \ (2 slots):** [blight](3-Mechanics/CLI/spells/blight-xphb.md), [wall of fire](3-Mechanics/CLI/spells/wall-of-fire-xphb.md)"
    "name": "Spellcasting"
  - "desc": "By puffing on his pipe, Elizar can use an action to cast [conjure minor\
      \ elementals](3-Mechanics/CLI/spells/conjure-minor-elementals-xphb.md). If he\
      \ does so, he summons four smoke mephits."
    "name": "Summon Mephits (Recharges after a Long Rest)"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage."
    "name": "Dagger +1"
"source":
  - "PotA"
"image": "file://bestiary/tokens/PotA/Elizar%20Dryflagon.webp"
```
^statblock