---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Knight of the Black Sword"
---
# [Knight of the Black Sword](3-Mechanics/CLI/bestiary/humanoid/knight-of-the-black-sword-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 259*  

The Knights of the Black Sword are a secret society of cultists devoted to Levistus, the archdevil who rules Stygia, the sixth layer of the Nine Hells, from the confines of an ice prison from which he cannot escape.

Most of the cultists are Icewind Dale natives who would have perished in the wilderness had Levistus not intervened on their behalf. The cultists' stories are all the same: the archdevil reached out to them in their minds as they were freezing to death, offering a second chance at life in exchange for their absolute devotion. After they agreed to follow Levistus, a pale glow caught their eye in the snow nearby, leading to the discovery of a sword-shaped amulet of chardalyn. Each of these amulets has an inner radiance that provides warmth and aid, protecting its wearer against the cold while guiding them safely back to civilization. Once its wearer reaches Ten-Towns, the talisman loses its inner radiance, yet the cultists keep their amulets as signs of their devotion to the archduke of Stygia (see the "Chardalyn Amulets" sidebar).

```statblock
"name": "Knight of the Black Sword (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+4"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "passive Perception 11"
"languages": "Common, Infernal"
"cr": "2"
"traits":
  - "desc": "The fanatic is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 11, +3 to hit with spell attacks). The fanatic has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [sacred flame](3-Mechanics/CLI/spells/sacred-flame-xphb.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
      \n**1st level (4 slots):** [command](3-Mechanics/CLI/spells/command-xphb.md),\
      \ [inflict wounds](3-Mechanics/CLI/spells/inflict-wounds-xphb.md), [shield of\
      \ faith](3-Mechanics/CLI/spells/shield-of-faith-xphb.md)\n\n**2nd level (3 slots):**\
      \ [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md), [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The fanatic has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dark Devotion"
  - "desc": "When the cultist dies, its corpse freezes for 9 days, during which time\
      \ it can't be thawed, harmed by fire, animated, or raised from the dead."
    "name": "Icy Doom"
"actions":
  - "desc": "The fanatic makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "IDRotF"
"image": "file://bestiary/tokens/IDRotF/Knight%20of%20the%20Black%20Sword.webp"
```
^statblock