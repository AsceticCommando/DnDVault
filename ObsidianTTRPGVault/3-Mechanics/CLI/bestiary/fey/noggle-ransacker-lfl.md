---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lfl
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Noggle Ransacker"
---
# [Noggle Ransacker](3-Mechanics/CLI/bestiary/fey/noggle-ransacker-lfl.md)
*Source: Lorwyn: First Light*  

Noggles don't burglarize—they ransack. Still, despite their indiscretion, many noggles choose to wear masks, bandannas, or flimsy disguises to obscure their identities.

## Noggles

Noggles are bipedal, donkey-like Fey that delight in thievery and mischief. They enjoy stealing from other creatures not out of necessity, but out of principle. This principle can be summarized by a common Sylvan expression that roughly translates to "that's mine!" Noggles are found only in Shadowmoor, where they roam and cause chaos.

```statblock
"name": "Noggle Ransacker (LFL)"
"size": "Small"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "15"
  - !!int "13"
  - !!int "8"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common, Sylvan"
"cr": "1/4"
"traits":
  - "desc": "The noggle deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing damage.\
      \ If the target is wearing armor, it is subjected to the following effect. *Dexterity\
      \ Saving Throw:* DC 12. *Failure:* The armor takes a -1 penalty to the AC it\
      \ offers. The target can take an action to remove the penalty from its armor."
    "name": "Sabotaging Swipe"
"bonus_actions":
  - "desc": "The noggle takes the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Nimble Escape"
"source":
  - "LFL"
"image": "file://bestiary/tokens/LFL/Noggle%20Ransacker.webp"
```
^statblock

## Environment

planar, feywild