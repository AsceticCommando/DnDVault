---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/water-genasi
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shoalar Quanderil"
---
# [Shoalar Quanderil](3-Mechanics/CLI/bestiary/npc/shoalar-quanderil-pota.md)
*Source: Princes of the Apocalypse p. 208*  

A plump water genasi armed with a jovial manner and biting sense of humor, Shoalar Quanderil seems like the last person one would expect to be a cruel member of a destructive cult. Nevertheless, Shoalar is the captain of a pirate ship that harries the Sword Coast, and a high-ranking Crushing Wave cultist. He sees Olhydra's power as a means to making himself as rich as possible.

```statblock
"name": "Shoalar Quanderil (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "Water genasi"
"alignment": "Lawful Evil"
"ac": !!int "10"
"ac_class": "13 with [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "16"
  - !!int "14"
  - !!int "10"
  - !!int "17"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+2"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+5"
"damage_resistances": "acid"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "passive Perception 10"
"languages": "Aquan, Common"
"cr": "4"
"traits":
  - "desc": "Shoalar is a 5th-level spellcaster. His spellcasting ability is Charisma\
      \ (spell save DC 13, +5 to hit with spell attacks). He knows the following sorcerer\
      \ spells:\n\n**Cantrips (at will):** [acid splash](3-Mechanics/CLI/spells/acid-splash-xphb.md),\
      \ [chill touch](3-Mechanics/CLI/spells/chill-touch-xphb.md), [friends](3-Mechanics/CLI/spells/friends-xphb.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md), [ray\
      \ of frost](3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\n**1st level (4 slots):**\
      \ [disguise self](3-Mechanics/CLI/spells/disguise-self-xphb.md), [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md),\
      \ [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md)\n\n**2nd level\
      \ (3 slots):** [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md), [misty\
      \ step](3-Mechanics/CLI/spells/misty-step-xphb.md)\n\n**3rd level (2 slots):**\
      \ [tidal wave](3-Mechanics/CLI/spells/tidal-wave-xge.md)"
    "name": "Spellcasting"
  - "desc": "Shoalar's innate spellcasting ability is Constitution (spell save DC\
      \ 13, +5 to hit with spell attacks). He can innately cast the following spells:\n\
      \n**At will:** [shape water](3-Mechanics/CLI/spells/shape-water-xge.md)\n\n\
      **1/day:** [create or destroy water](3-Mechanics/CLI/spells/create-or-destroy-water-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Shoalar can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or ranged 20/60\
      \ ft., one target. *Hit:* 3 (1d4 + 1) piercing damage."
    "name": "Dagger"
"source":
  - "PotA"
"image": "file://bestiary/tokens/PotA/Shoalar%20Quanderil.webp"
```
^statblock