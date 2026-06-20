---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Neogi Hatchling Swarm"
---
# [Neogi Hatchling Swarm](3-Mechanics/CLI/bestiary/aberration/neogi-hatchling-swarm-bam.md)
*Source: Boo's Astral Menagerie p. 40*  

A neogi lives about a century. When an individual is rendered weak by advanced age, the other neogi in the group overpower it and inject it with a special poison. The toxin transforms the old neogi into a bloated mass of flesh. Younger neogi lay their eggs atop it, and when the hatchlings emerge, they devour the old neogi and one another until only a few of the strongest newborns are left. Sometimes the newborns, united by a singular evil purpose, coalesce into a skittering swarm instead.

```statblock
"name": "Neogi Hatchling Swarm (BAM)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "11"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "13"
  - !!int "14"
  - !!int "6"
  - !!int "10"
  - !!int "9"
"speed": "20 ft., climb 20 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The swarm can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny neogi hatchling.\
      \ The swarm can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:* 22\
      \ (6d6 + 1) poison damage, or 11 (3d6 + 1) poison damage if the swarm has half\
      \ of its hit points or fewer, and the target must succeed on a DC 12 Constitution\
      \ saving throw or become [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 minute. A target can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success."
    "name": "Swarm of Bites"
"source":
  - "BAM"
"image": "file://bestiary/tokens/BAM/Neogi%20Hatchling%20Swarm.webp"
```
^statblock