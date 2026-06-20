---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aatm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Animated Coffin"
---
# [Animated Coffin](3-Mechanics/CLI/bestiary/construct/animated-coffin-aatm.md)
*Source: Adventure Atlas: The Mortuary*  

Animated coffins are heavy, macabre Constructs designed to ferry the dead to places of rest. They waddle the Mortuary's halls unbothered, scooping up corpses and carrying them to the next stage of the funerary process.

An animated coffin has an array of spidery metal legs it uses to skitter along steep inclines, walls, and ceilings, and the coffin's spacious interior bristles with retractable spikes. Like their inanimate counterparts, animated coffins range from plain wooden boxes with simple fittings to elaborate, gilded sarcophagi and reverent, fabric-lined caskets.

Beyond the City of Doors, animated coffins serve similar—albeit less industrial—roles. Natural ambushers and tireless sentries, animated coffins guard ancient necropolises, family crypts, and the lairs of powerful Undead. A cautious vampire might sleep in an animated coffin to evade hunters during the day, while a necromancer might enlist animated coffins to conscript corpses from faraway settlements into an Undead army.

Animated coffins are rarely empty. The Animated Coffin Contents table presents some contents an animated coffin might contain when encountered.

`dice: [](animated-coffin-aatm.md#^contents)`

| dice: d6 | Contents |
|----------|----------|
| 1 | `dice:1d4\|noform\|noparens\|avg` (`1d4`) swarm of bats |
| 2 | `dice:1d4\|noform\|noparens\|avg` (`1d4`) skeletons packed like sardines |
| 3 | A groaning mummy |
| 4 | A patch of [yellow mold](3-Mechanics/CLI/traps-hazards/yellow-mold-xdmg.md) (see the "Dungeon Master's Guide") |
| 5 | A slumbering vampire spawn |
| 6 | A portal to the Path of Graves (detailed in Adventure Atlas: The Mortuary) |
^contents

```statblock
"name": "Animated Coffin (AATM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d10 + 16"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "3"
  - !!int "11"
  - !!int "3"
"speed": "30 ft., climb 30 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (can't\
  \ see beyond this radius), passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "3"
"traits":
  - "desc": "If the animated coffin is motionless at the start of combat, it has advantage\
      \ on its initiative roll. Moreover, if a creature hasn't observed the coffin\
      \ move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation))\
      \ check to discern that the coffin is animate."
    "name": "False Appearance"
  - "desc": "The animated coffin can climb difficult surfaces, including upside down\
      \ on ceilings, without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The animated coffin makes two Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d8 + 3) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one Large or smaller creature.\
      \ *Hit:* The target has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 13). Until this grapple ends, if the target is not an\
      \ Undead, the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition and takes 14 (4d6) piercing damage at the start of each of its turns.\
      \ The animated coffin can grapple only one creature at a time."
    "name": "Entrap"
"source":
  - "AATM"
"image": "file://bestiary/tokens/AATM/Animated%20Coffin.webp"
```
^statblock