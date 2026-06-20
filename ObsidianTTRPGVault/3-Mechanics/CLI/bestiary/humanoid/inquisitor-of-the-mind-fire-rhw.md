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
- "Inquisitor of the Mind Fire"
---
# [Inquisitor of the Mind Fire](3-Mechanics/CLI/bestiary/humanoid/inquisitor-of-the-mind-fire-rhw.md)
*Source: RHW p. 272*  

The Order of Cosima harnesses the Mind Fire—their name for the fire of thought that blazes within each person's mind. Inquisitors of this order use their psychic powers to read thoughts, reshape memories, and dominate the recalcitrant. They represent their order with the symbol of a burning eye.

## Ulmist Inquisitors

*Zealous Vanquishers of Evil Intent*

"Evil lurks everywhere. With our minds, we will unearth it, we will plumb its depths, and we will annihilate it." With those words, the psychically gifted priest Ulmed founded the Ulmist Inquisition, an order of psionic inquisitors that seeks to uncover and extinguish the wickedness lurking deep in people's hearts. From the depraved city of Malitain on the Material Plane, the inquisition sends its members throughout the multiverse seeking to thwart the work of malevolent cults, reality-defying horrors, and the evil inherent to mortals. Sects of the inquisition exist within the Domains of Dread, working either in hidden cabals or infiltrating other faiths, such as the Church of Ezra.

The Ulmist Inquisition is organized into three orders named for Ulmed's companions: the Order of Cosima, the Order of Ansel, and the Order of Tristian. Each order specializes in a different psionic power, and each bears a different symbol on its coat of arms. Some inquisitors entertain friendly rivalries with their fellows from other orders, but most put aside their grudges—at least temporarily—to work together against evil.

```statblock
"name": "Inquisitor of the Mind Fire (RHW)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Lawful Neutral"
"ac": !!int "16"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "15"
  - !!int "17"
  - !!int "16"
  - !!int "21"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[breastplate](3-Mechanics/CLI/items/breastplate-xphb.md)"
  - "[silvered longsword](3-Mechanics/CLI/items/silvered-weapon-xdmg.md)"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 30 ft., passive\
  \ Perception 16"
"languages": "Common plus two other languages"
"cr": "8"
"actions":
  - "desc": "The inquisitor makes three Silvered Longsword attacks or uses Mind Fire\
      \ three times. It can replace one attack or one use of Mind Fire with a use\
      \ of Spellcasting to cast [Hold Monster](3-Mechanics/CLI/spells/hold-monster-xphb.md)\
      \ if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 14 (2d8 + 5) Slashing damage\
      \ plus 4 (1d8) Psychic damage, and the target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the start of the inquisitor's next turn. Critical *Hit:* If\
      \ the target is a shape-shifted creature, it takes an additional 4 (1d8) Slashing\
      \ damage."
    "name": "Silvered Longsword"
  - "desc": "*Wisdom Saving Throw:* DC 16, each creature of the inquisitor's choice\
      \ that it can see within 60 feet. *Failure:* The target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition until the start of the inquisitor's next turn. On the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ target's turn, the inquisitor can telepathically control the target's move\
      \ and make the target take the [Attack](3-Mechanics/CLI/rules/actions.md#Attack)\
      \ action (the inquisitor chooses the target), the [Dash](3-Mechanics/CLI/rules/actions.md#Dash)\
      \ action, or no action."
    "name": "Inquisitor's Command (Recharge 5-6)"
  - "desc": "*Intelligence Saving Throw:* DC 16, one creature the inquisitor can see\
      \ within 120 feet. *Failure:* 9 (1d8 + 5) Psychic damage, and the target has\
      \ the [Stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) condition until\
      \ the start of the inquisitor's next turn."
    "name": "Mind Fire"
  - "desc": "The inquisitor casts one of the following spells, requiring no spell\
      \ components and using Charisma as the spellcasting ability (spell save DC 16):\n\
      \n**At will:** [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [Detect Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Dispel\
      \ Magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\
      \ (the hand is [Invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)),\
      \ [Sending](3-Mechanics/CLI/spells/sending-xphb.md)\n\n**1/day each:** [Hold\
      \ Monster](3-Mechanics/CLI/spells/hold-monster-xphb.md), [Modify Memory](3-Mechanics/CLI/spells/modify-memory-xphb.md)"
    "name": "Spellcasting"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Inquisitor%20of%20the%20Mind%20Fire.webp"
```
^statblock

## Environment

any