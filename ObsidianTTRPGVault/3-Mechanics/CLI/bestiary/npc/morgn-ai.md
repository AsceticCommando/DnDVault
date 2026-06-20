---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Môrgæn"
---
# [Môrgæn](3-Mechanics/CLI/bestiary/npc/morgn-ai.md)
*Source: Acquisitions Incorporated p. 199*  

> [!quote]  
> 
> If I had wanted to kill, I would have killed.

The ranger Môrgæn is a renowned tracker and hunter, able to pinpoint-target foes at any range, then vanish into the woods with no one the wiser. Her legendary ability with the longbow and the custom arrows she crafts instills fear into the hearts of her many enemies-and more than a few of her coworkers. Famously, she is the only member of Acquisitions Incorporated known to be paid in advance, lest a missed invoice lead to dire repercussions.

A child of the forest, Môrgæn defends the natural world with singular ferocity and an impressive rate of sustained fire. Her core philosophy is that one should shoot first and then ask no questions later. Because what's the point of asking questions when the person you've shot first is already dead? Still, when the situation calls for it, this protector of the woodlands is equally at home on missions of subterfuge and social interaction in the big city, provided her well-known love of ale, wine, and other intoxicants doesn't get the better of her.

```statblock
"name": "Môrgæn (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "12"
  - !!int "12"
  - !!int "14"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "3"
  - "dexterity": !!int "6"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+3"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+4"
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Common, Draconic, Dwarvish, Giant, Goblin"
"cr": "4"
"traits":
  - "desc": "Môrgæn is a 9th-level spellcaster. Her spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). She has the following ranger\
      \ spells prepared:\n\n**1st level (4 slots):** [alarm](3-Mechanics/CLI/spells/alarm-xphb.md),\
      \ [animal friendship](3-Mechanics/CLI/spells/animal-friendship-xphb.md), [hunter's\
      \ mark](3-Mechanics/CLI/spells/hunters-mark-xphb.md)\n\n**2nd level (3 slots):**\
      \ [pass without trace](3-Mechanics/CLI/spells/pass-without-trace-xphb.md), [spike\
      \ growth](3-Mechanics/CLI/spells/spike-growth-xphb.md)\n\n**3rd level (2 slots):**\
      \ [conjure animals](3-Mechanics/CLI/spells/conjure-animals-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Môrgæn's spellcasting ability is Intelligence. She can innately cast\
      \ the following spells, requiring no material components:\n\n**At will:** [mage\
      \ hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Môrgæn has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put her to sleep."
    "name": "Fey Ancestry"
"actions":
  - "desc": "Môrgæn makes three attacks with her scimitars or her longbow."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) slashing damage."
    "name": "Scimitars"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 150/600 ft., one target. *Hit:*\
      \ 8 (1d8 + 4) piercing damage."
    "name": "Longbow"
"source":
  - "AI"
"image": "file://bestiary/tokens/AI/Morgaen.webp"
```
^statblock