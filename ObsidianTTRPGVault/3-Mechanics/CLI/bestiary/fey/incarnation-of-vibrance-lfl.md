---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lfl
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Incarnation of Vibrance"
---
# [Incarnation of Vibrance](3-Mechanics/CLI/bestiary/fey/incarnation-of-vibrance-lfl.md)
*Source: Lorwyn: First Light*  

The incarnations of vibrance each resemble a titanic canine with a body of colorful foliage and horns like the branches of a blossoming cherry tree. When vibrance incarnations are in Lorwyn, meadows flourish and crop fields ripen in their presence, and kithkin rejoice when these incarnations pay their clachan a visit. In Shadowmoor, these same creatures are an ill omen—gruesome wolfhounds often accompanied by invasive plant species and frenzied wild beasts.

## Incarnations of Nature

Incarnations of nature embody abstract ideas such as curiosity, relief, or terror. Incarnations of nature are beyond the ken of most mortal beings—untamable, primal, and awe inspiring.

In the realm of Lorwyn-Shadowmoor, these beings take the forms of chimeric behemoths that combine the features of three or more creatures. In Lorwyn, incarnations of nature often embody positive, exhilarating emotions. In Shadowmoor, they often manifest dour, violent impulses.

An incarnation of nature that wanders from Lorwyn to Shadowmoor or vice versa retains its core identity but might transform physically. An incarnation of hope in Lorwyn, for example, might resemble a giant dove with a lizard's tail and leonine legs; in Shadowmoor, this same being might instead resemble a giant crow with a rattlesnake's tail, its leonine legs stained with blood.

```statblock
"name": "Incarnation of Vibrance (LFL)"
"size": "Huge"
"type": "fey"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"modifier": !!int "7"
"stats":
  - !!int "20"
  - !!int "17"
  - !!int "20"
  - !!int "10"
  - !!int "16"
  - !!int "21"
"speed": "40 ft."
"saves":
  - "constitution": !!int "9"
  - "charisma": !!int "9"
"damage_resistances": "radiant"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Sylvan; telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "The incarnation has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The incarnation makes two Vine attacks and uses Radiant Blast. It can\
      \ replace one vine attack with a use of Spellcasting to cast [Blindness/Deafness](3-Mechanics/CLI/spells/blindness-deafness-xphb.md)\
      \ if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 20 ft. *Hit:* 18 (3d8 + 5) Bludgeoning\
      \ damage. If the target is the incarnation's size or smaller, it has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 15) from one of two vines."
    "name": "Vine"
  - "desc": "*Constitution Saving Throw:* DC 17, each creature of the incarnation's\
      \ choice in a 20-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the incarnation. *Failure:* The creature takes 14 (2d8 +\
      \ 5) Radiant damage. *Success:* Half damage."
    "name": "Radiant Blast"
  - "desc": "The incarnation casts one of the following spells, requiring no spell\
      \ components and using Charisma as the spellcasting ability:\n\n**At will:**\
      \ [Daylight](3-Mechanics/CLI/spells/daylight-xphb.md), [Druidcraft](3-Mechanics/CLI/spells/druidcraft-xphb.md),\
      \ [Plant Growth](3-Mechanics/CLI/spells/plant-growth-xphb.md)\n\n**1/day:**\
      \ [Blindness/Deafness](3-Mechanics/CLI/spells/blindness-deafness-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The incarnation changes its size to Medium, Large, or Huge."
    "name": "Shape-Shift"
  - "desc": "The incarnation teleports up to 60 feet to an unoccupied space it can\
      \ see. The incarnation can't teleport while it has a creature [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)."
    "name": "Teleport"
"source":
  - "LFL"
"image": "file://bestiary/tokens/LFL/Incarnation%20of%20Vibrance.webp"
```
^statblock

## Environment

planar, feywild