---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lfl
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Noggle Wild Mage"
---
# [Noggle Wild Mage](3-Mechanics/CLI/bestiary/fey/noggle-wild-mage-lfl.md)
*Source: Lorwyn: First Light*  

Some noggles have a powerful connection to the strange magic that suffuses the realm of Lorwyn-Shadowmoor. Such wild mages exist on the peripheries of noggle society as pariahs and vagabonds. Their innate magic becomes strongest when they are most desperate, such as in the heat of battle.

## Noggles

Noggles are bipedal, donkey-like Fey that delight in thievery and mischief. They enjoy stealing from other creatures not out of necessity, but out of principle. This principle can be summarized by a common Sylvan expression that roughly translates to "that's mine!" Noggles are found only in Shadowmoor, where they roam and cause chaos.

```statblock
"name": "Noggle Wild Mage (LFL)"
"size": "Small"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "4d6 + 8"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "charisma": !!int "5"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "Common, Sylvan"
"cr": "1"
"traits":
  - "desc": "While [Bloodied](3-Mechanics/CLI/rules/conditions.md#Bloodied), the noggle\
      \ has a [Fly Speed](3-Mechanics/CLI/rules/variant-rules/fly-speed-xphb.md) of\
      \ 30 feet and it can choose for any damage it deals to be Force damage."
    "name": "Bloodied Wild Magic"
"actions":
  - "desc": "The noggle makes two attacks, using Noggling Stick or Befuddling Ray\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Bludgeoning damage\
      \ plus 2 (1d4) Psychic damage."
    "name": "Noggling Stick"
  - "desc": "*Ranged Attack Roll:* +5, range 60 ft. *Hit:* 6 (1d6 + 3) Psychic damage,\
      \ and the target subtracts 1d4 from the next saving throw it makes before the\
      \ end of the noggle's next turn."
    "name": "Befuddling Ray"
"source":
  - "LFL"
"image": "file://bestiary/tokens/LFL/Noggle%20Wild%20Mage.webp"
```
^statblock

## Environment

planar, feywild