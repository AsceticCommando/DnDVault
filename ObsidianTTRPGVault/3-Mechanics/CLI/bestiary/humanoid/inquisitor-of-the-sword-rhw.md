---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Inquisitor of the Sword"
---
# [Inquisitor of the Sword](3-Mechanics/CLI/bestiary/humanoid/inquisitor-of-the-sword-rhw.md)
*Source: RHW p. 273*  

Inquisitors in the Order of Ansel subject themselves to harsh asceticism so they can empower their bodies with psionic energy. They are the martial arm of the inquisition, represented by a sword.

## Ulmist Inquisitors

*Zealous Vanquishers of Evil Intent*

"Evil lurks everywhere. With our minds, we will unearth it, we will plumb its depths, and we will annihilate it." With those words, the psychically gifted priest Ulmed founded the Ulmist Inquisition, an order of psionic inquisitors that seeks to uncover and extinguish the wickedness lurking deep in people's hearts. From the depraved city of Malitain on the Material Plane, the inquisition sends its members throughout the multiverse seeking to thwart the work of malevolent cults, reality-defying horrors, and the evil inherent to mortals. Sects of the inquisition exist within the Domains of Dread, working either in hidden cabals or infiltrating other faiths, such as the Church of Ezra.

The Ulmist Inquisition is organized into three orders named for Ulmed's companions: the Order of Cosima, the Order of Ansel, and the Order of Tristian. Each order specializes in a different psionic power, and each bears a different symbol on its coat of arms. Some inquisitors entertain friendly rivalries with their fellows from other orders, but most put aside their grudges—at least temporarily—to work together against evil.

```statblock
"name": "Inquisitor of the Sword (RHW)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Lawful Neutral"
"ac": !!int "16"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "17"
  - !!int "15"
  - !!int "18"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "7"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[breastplate](3-Mechanics/CLI/items/breastplate-xphb.md)"
  - "[silvered longsword](3-Mechanics/CLI/items/silvered-weapon-xdmg.md)"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 30 ft., passive\
  \ Perception 17"
"languages": "Common plus two other languages"
"cr": "8"
"traits":
  - "desc": "At the start of each of its turns, if the inquisitor has at least 1 [Hit\
      \ Point](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), it regains\
      \ 10 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) and\
      \ can end one condition on itself."
    "name": "Metabolic Control"
"actions":
  - "desc": "The inquisitor makes three Silvered Longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage\
      \ plus 4 (1d8) Psychic damage. Critical *Hit:* If the target is a shape-shifted\
      \ creature, it takes an additional 4 (1d8) Slashing damage. *Hit or Miss:* The\
      \ inquisitor can teleport up to 60 feet to an unoccupied space it can see."
    "name": "Silvered Longsword"
  - "desc": "The inquisitor casts one of the following spells, requiring no spell\
      \ components and using Wisdom as the spellcasting ability (spell save DC 15):\n\
      \n**At will:** [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [Detect Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Dispel\
      \ Magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\
      \ (the hand is [Invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)),\
      \ [Sending](3-Mechanics/CLI/spells/sending-xphb.md)\n\n**1/day each:** [Dimension\
      \ Door](3-Mechanics/CLI/spells/dimension-door-xphb.md), [Fly](3-Mechanics/CLI/spells/fly-xphb.md),\
      \ [Greater Invisibility](3-Mechanics/CLI/spells/greater-invisibility-xphb.md)"
    "name": "Spellcasting"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Inquisitor%20of%20the%20Sword.webp"
```
^statblock

## Environment

any