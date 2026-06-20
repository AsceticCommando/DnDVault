---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/cos
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hungry Ghast"
---
# [Hungry Ghast](3-Mechanics/CLI/bestiary/undead/hungry-ghast-cos.md)
*Source: Curse of Strahd p. 192*  

```statblock
"name": "Hungry Ghast (CoS)"
"size": "Small"
"type": "undead"
"alignment": "Lawful Good"
"ac": !!int "13"
"hp": !!int "7"
"hit_dice": "2d6"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "17"
  - !!int "10"
  - !!int "11"
  - !!int "10"
  - !!int "8"
"speed": "30 ft."
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "Any creature that starts its turn within 5 feet of the ghast must succeed\
      \ on a DC 10 Constitution saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ until the start of its next turn. On a successful saving throw, the creature\
      \ is immune to the ghast's Stench for 24 hours."
    "name": "Stench"
  - "desc": "The ghast and any ghouls within 30 feet of it have advantage on saving\
      \ throws against effects that turn undead."
    "name": "Turn Defiance"
  - "desc": "The ghast can climb difficult surfaces, including upside down on ceilings,\
      \ without having to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:* 12\
      \ (2d8 + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage. If the target is a creature other than an undead,\
      \ it must succeed on a DC 10 Constitution saving throw or be [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Claws"
"source":
  - "CoS"
"image": "file://bestiary/tokens/CoS/Hungry%20Ghast.webp"
```
^statblock