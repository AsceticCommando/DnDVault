---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lfl
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lorwyn Giant"
---
# [Lorwyn Giant](3-Mechanics/CLI/bestiary/giant/lorwyn-giant-lfl.md)
*Source: Lorwyn: First Light*  

In Lorwyn, giants are curious colossi who roam vast plains, bathe in salty lagoons, and nap against mountains. They sometimes lend their brawn to smaller species who have something interesting to offer in return.

## Giants

The giants of the realm of Lorwyn-Shadowmoor are wise, ancient beings wandering their homeland in search of wondrous things or simply a place to rest. They are deeply in tune with nature but care little for the smaller denizens around them. At best, this makes a giant aloof and disinterested in the squabbles of boggarts, kithkin, elves, and others. At worst, giants might be wrathful toward smaller folk, seeing them as invasive pests to be squashed.

When a giant in the realm of Lorwyn-Shadowmoor sleeps, it often has vivid, dramatic dreams. Giants see their dreams as powerful augurs or important messages that border on divine inspiration. These giants mark their resting spots with enormous stone archways to ensure their respites go uninterrupted.

Smart adventurers avoid these archways for fear of evoking the sleeping giant's ire. Treasure hunters might search for the archways in hopes of finding the place abandoned but still stocked with a giant's valuable relics. Such treasure hunters do well to tread carefully, for when angered, these giants can unleash the might of mountains and crush foes with the force of an avalanche.

```statblock
"name": "Lorwyn Giant (LFL)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "115"
"hit_dice": "11d12 + 44"
"modifier": !!int "1"
"stats":
  - !!int "21"
  - !!int "13"
  - !!int "18"
  - !!int "9"
  - !!int "16"
  - !!int "8"
"speed": "40 ft."
"saves":
  - "constitution": !!int "7"
  - "wisdom": !!int "6"
"senses": "passive Perception 13"
"languages": "Common, Giant"
"cr": "6"
"actions":
  - "desc": "The giant makes two attacks, using Stone Sword or Boulder in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 15 ft. *Hit:* 21 (3d10 + 5) Slashing damage."
    "name": "Stone Sword"
  - "desc": "*Ranged Attack Roll:* +8, range 60/240 ft. *Hit:* 14 (2d8 + 5) Bludgeoning\
      \ damage. If the target is a Large or smaller creature, it has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Boulder"
"bonus_actions":
  - "desc": "The giant falls into a deep, restorative slumber. The giant gains 20\
      \ [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
      \ and has the [Unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ condition until it takes damage or the end of its next turn. The giant has\
      \ [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on ability\
      \ checks and saving throws for 1 minute."
    "name": "Name Sleep (Recharge 5-6)"
"source":
  - "LFL"
"image": "file://bestiary/tokens/LFL/Lorwyn%20Giant.webp"
```
^statblock

## Environment

planar, feywild