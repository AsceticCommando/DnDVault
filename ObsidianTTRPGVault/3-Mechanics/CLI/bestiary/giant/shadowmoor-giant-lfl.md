---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lfl
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shadowmoor Giant"
---
# [Shadowmoor Giant](3-Mechanics/CLI/bestiary/giant/shadowmoor-giant-lfl.md)
*Source: Lorwyn: First Light*  

A giant in Shadowmoor takes great slumbers bordering on hibernation. These giants sleep for so long that they fuse with the surrounding earth, imbuing them with the land's ambient wild magic. The giants can mold and wield this wild magic to devastating effect.

## Giants

The giants of the realm of Lorwyn-Shadowmoor are wise, ancient beings wandering their homeland in search of wondrous things or simply a place to rest. They are deeply in tune with nature but care little for the smaller denizens around them. At best, this makes a giant aloof and disinterested in the squabbles of boggarts, kithkin, elves, and others. At worst, giants might be wrathful toward smaller folk, seeing them as invasive pests to be squashed.

When a giant in the realm of Lorwyn-Shadowmoor sleeps, it often has vivid, dramatic dreams. Giants see their dreams as powerful augurs or important messages that border on divine inspiration. These giants mark their resting spots with enormous stone archways to ensure their respites go uninterrupted.

Smart adventurers avoid these archways for fear of evoking the sleeping giant's ire. Treasure hunters might search for the archways in hopes of finding the place abandoned but still stocked with a giant's valuable relics. Such treasure hunters do well to tread carefully, for when angered, these giants can unleash the might of mountains and crush foes with the force of an avalanche.

```statblock
"name": "Shadowmoor Giant (LFL)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"modifier": !!int "2"
"stats":
  - !!int "22"
  - !!int "14"
  - !!int "20"
  - !!int "7"
  - !!int "19"
  - !!int "8"
"speed": "40 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "7"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 14"
"languages": "Giant"
"cr": "8"
"actions":
  - "desc": "The giant makes three attacks, using Tree Club or Boulder in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 15 ft. *Hit:* 17 (2d10 + 6) Bludgeoning\
      \ damage."
    "name": "Tree Club"
  - "desc": "*Ranged Attack Roll:* +9, range 60/240 ft. *Hit:* 13 (2d6 + 6) Bludgeoning\
      \ damage. If the target is a Large or smaller creature, it has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Boulder"
  - "desc": "*Dexterity Saving Throw:* DC 15, each creature in a 20-foot-radius [Sphere](3-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md)\
      \ centered on a point within 120 feet. *Failure:* 28 (8d6) damage (roll 1d4\
      \ to determine damage type: 1—Acid; 2—Fire; 3—Lightning; 4—Thunder). *Success:*\
      \ Half damage."
    "name": "Wild Magic Cataclysm (Recharge 5-6)"
"source":
  - "LFL"
"image": "file://bestiary/tokens/LFL/Shadowmoor%20Giant.webp"
```
^statblock

## Environment

planar, feywild