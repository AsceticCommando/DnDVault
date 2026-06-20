---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pendragon Beestinger"
---
# [Pendragon Beestinger](3-Mechanics/CLI/bestiary/npc/pendragon-beestinger-ai.md)
*Source: Acquisitions Incorporated p. 206*  

Able arcanist Pendragon Beestinger took over as "B" Team cartographer after Brahma Lutier left the group. In fact, his first assignment was to assist in the team's attempts to apprehend the wandering bard. An adopted child of the "C" Team's Rosie Beestinger, Pendragon is his mother's foil in almost every way-including his goal of wanting to mainstream some of the family's rumored criminal interests. Pendragon has, in fact, attempted to kill his mother-and been killed himself in the process. Despite his having been resurrected at Rosie's request, things remain cool between the two.

Pendragon was kicked out of wizarding school as a result of the dark rumors following the Beestinger clan. Now a self-taught mage, he specializes in making use of the dangerous spells and weird trinkets he often comes across in his role as a kind of arcane archaeologist. Seeking out the family feeling that an adventuring group provides keeps him in the "B" Team, even if that unfortunately comes with Oak Truestrike as a kind of father figure.

```statblock
"name": "Pendragon Beestinger (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+2"
"gear":
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "passive Perception 10"
"languages": "Common, Draconic, Elvish, Halfling"
"cr": "2"
"traits":
  - "desc": "Pendragon is a 4th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 13, +5 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** [acid splash](3-Mechanics/CLI/spells/acid-splash-xphb.md),\
      \ [light](3-Mechanics/CLI/spells/light-xphb.md), [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [poison spray](3-Mechanics/CLI/spells/poison-spray-xphb.md), [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp-xphb.md)\n\
      \n**1st level (4 slots):** [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md), [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md),\
      \ [sleep](3-Mechanics/CLI/spells/sleep-xphb.md)\n\n**2nd level (3 slots):**\
      \ [blindness/deafness](3-Mechanics/CLI/spells/blindness-deafness-xphb.md), [cloud\
      \ of daggers](3-Mechanics/CLI/spells/cloud-of-daggers-xphb.md), [scorching ray](3-Mechanics/CLI/spells/scorching-ray-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Pendragon can cast the spell he cast on his last turn, whose casting\
      \ time becomes 1 bonus action. This bonus casting uses a spell slot as normal."
    "name": "Echo Spell (1/Day)"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
"source":
  - "AI"
"image": "file://bestiary/tokens/AI/Pendragon%20Beestinger.webp"
```
^statblock