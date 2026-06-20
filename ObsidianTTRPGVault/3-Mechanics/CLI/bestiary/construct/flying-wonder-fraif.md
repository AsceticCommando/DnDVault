---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Flying Wonder"
---
# [Flying Wonder](3-Mechanics/CLI/bestiary/construct/flying-wonder-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 246*  

```statblock
"name": "Flying Wonder (FRAiF)"
"size": "Tiny"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"modifier": !!int "2"
"stats":
  - !!int "2"
  - !!int "15"
  - !!int "10"
  - !!int "3"
  - !!int "10"
  - !!int "1"
"speed": "5 ft., fly 30 ft."
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 10"
"languages": "understands Common but can't speak"
"cr": "0"
"traits":
  - "desc": "The wonder can carry up to 100 pounds."
    "name": "Increased Carrying Capacity"
  - "desc": "The wonder has the [Unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ condition until another creature winds it with the wonder's unique key for\
      \ 1 minute. Once wound, the wonder operates for 24 hours or until a creature\
      \ touches the wonder with its key as a [Utilize](3-Mechanics/CLI/rules/actions.md#Utilize)\
      \ action to deactivate it, after which the wonder has the [Unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ condition until it is wound again."
    "name": "Wind-Up Operation"
"bonus_actions":
  - "desc": "The wonder chirps a merry, metronomic tune. The wonder chooses one ally\
      \ that it can see within 60 feet. Until the start of the wonder's next turn,\
      \ the target has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on the next ability check it makes with a Musical Instrument or Tinker's Tools."
    "name": "Chime"
  - "desc": "The wonder takes the [Dash](3-Mechanics/CLI/rules/actions.md#Dash) action."
    "name": "Sprint"
"source":
  - "FRAiF"
"image": "file://bestiary/tokens/FRAiF/Flying%20Wonder.webp"
```
^statblock