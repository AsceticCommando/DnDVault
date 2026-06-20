---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Iron Defender"
---
# [Iron Defender](3-Mechanics/CLI/bestiary/construct/iron-defender-erlw.md)
*Source: Eberron: Rising from the Last War p. 293*  

An iron defender fights for its creator. They come in many shapes and are often crafted in the form of animals. More creative artificers craft iron defenders in the shape of hybrid animals or other fantastical creatures.

## Constructed Nature

A homunculus doesn't require air, food, drink, or sleep.

A homunculus is a construct servant created for certain tasks. Artificers and wizards are responsible for most of the homunculi in existence.

Each kind of homunculus has a body constructed from different kinds of materials, including clay, iron, and bits of hair and feathers. The process that creates a homunculus sees those materials mixed with the creator's blood and animated through an extended magical ritual.

```statblock
"name": "Iron Defender (ERLW)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "16"
  - !!int "8"
  - !!int "11"
  - !!int "7"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "understands the languages of its creator but can't speak"
"cr": "1"
"traits":
  - "desc": "The defender has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks."
    "name": "Keen Senses"
  - "desc": "While the defender is on the same plane of existence as its master, it\
      \ can magically convey what it senses to its master, and the two can communicate\
      \ telepathically."
    "name": "Telepathic Bond"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) piercing damage. If the target is a creature, it must succeed on a DC\
      \ 13 Strength saving throw or take an extra 3 (1d6) piercing damage and be [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 13). The defender can have only one creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ in this way at a time."
    "name": "Bite"
"source":
  - "ERLW"
"image": "file://bestiary/tokens/ERLW/Iron%20Defender.webp"
```
^statblock