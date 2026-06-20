---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Infesting Insects"
---
# [Swarm of Infesting Insects](3-Mechanics/CLI/bestiary/beast/swarm-of-infesting-insects-rhw.md)
*Source: RHW p. 271*  

Infesting insect swarms invade larger prey, burrowing into other creature's bodies with varied, gruesome results.

## Swarms of Insects

*Flesh-Eating Parasites*

Few fates are more gruesome than falling victim to the parasitic or skeletonizing insect swarms that lurk in haunted sites and cursed dungeons.

```statblock
"name": "Swarm of Infesting Insects (RHW)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "3"
  - !!int "14"
  - !!int "12"
  - !!int "1"
  - !!int "7"
  - !!int "1"
"speed": "20 ft., climb 20 ft., swim 20 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., passive\
  \ Perception 8"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The swarm can occupy another creature's space and vice versa, and it\
      \ can move through any opening large enough for a Tiny creature. The swarm can't\
      \ regain [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ or gain [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 12 (4d4 + 2) Poison damage,\
      \ or 7 (2d4 + 2) Poison damage if the swarm is [Bloodied](3-Mechanics/CLI/rules/conditions.md#Bloodied),\
      \ and the target has the [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition. If the target remains [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ in this way after 1 hour, it is subjected to the following effect. *Constitution\
      \ Saving Throw:* DC 11. *Failure:* Roll 1d6: on a 1-2, the target has the [Blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ condition; on a 3-4, the target's [Hit Point](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ maximum decreases by 5 (1d10); on a 5-6, the target gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion)\
      \ level. The effect lasts until the [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition ends. *Success:* The [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition ends."
    "name": "Infestation"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Swarm%20of%20Infesting%20Insects.webp"
```
^statblock

## Environment

coastal, forest, grassland, swamp, urban