---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ancient Spirit Dragon"
---
# [Ancient Spirit Dragon](3-Mechanics/CLI/bestiary/dragon/ancient-spirit-dragon-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 279*  

Ancient spirit dragons have outgrown the petty concerns of the current age. After centuries of studying the culture and beliefs of an ancient empire, a spirit dragon's personality and outlook are often indistinguishable from that fallen realm's.

## Spirit Dragons

*Draconic Scions of an Ancient Empire*

Spirit dragons, sometimes called song dragons, are powerful dragons whose powers stem from the magic and history of fallen realms. They embody the spirit of a bygone age, and so as they grow and mature, they develop an erratic control over time.

A spirit dragon's primary motivation is to unearth and study the ruins of the ancient realm from which it arose. Spirit dragons share an innate intellectual curiosity, and many have a deep appreciation for the culture and art of humanoid societies.

Spirit dragons find even the most commonplace melodies moving. A song written in the time and region from which a spirit dragon hails can potentially overwhelm the dragon, driving it to either morose despondence or passionate rage.

No two spirit dragons are exactly alike; each individual bears features distinct to the empire from which it hails. Roll on or choose a result from the Spirit Dragon Origins table to determine which lost realm a spirit dragon is from.

`dice: [](ancient-spirit-dragon-fraif.md#^1-the-spirit-dragon-traces-its-origins-to)`

| dice: 1d6 | The Spirit Dragon Traces Its Origins to... |
|-----------|--------------------------------------------|
| 1 | Evermeet, a mythical realm of the elves. |
| 2 | Imaskar, a southern empire of artificers. |
| 3 | Jhaamdath, a prehistoric psiocracy. |
| 4 | Myth Drannor, a legendary city of magic. |
| 5 | Netheril, an empire of arcane secrets. |
| 6 | Ostoria, the first kingdom of the giants. |
^1-the-spirit-dragon-traces-its-origins-to

## Spirit Dragon Lairs

Spirit dragons haunt the ruined cities and buried monuments of ancient empires.

```statblock
"name": "Ancient Spirit Dragon (FRAiF)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Neutral"
"ac": !!int "21"
"hp": !!int "420"
"hit_dice": "24d20 + 168"
"modifier": !!int "9"
"stats":
  - !!int "26"
  - !!int "14"
  - !!int "25"
  - !!int "24"
  - !!int "18"
  - !!int "23"
"speed": "40 ft., burrow 30 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "9"
  - "constitution": !!int "14"
"skillsaves":
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+14"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+11"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "necrotic"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., [Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 21"
"languages": "Common, Draconic; telepathy 120 ft."
"cr": "22"
"traits":
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
"actions":
  - "desc": "The dragon makes three Rend attacks. It can replace one attack with a\
      \ use of (A) Time-Warping Breath or (B) Spellcasting to cast [Thunderwave](3-Mechanics/CLI/spells/thunderwave-xphb.md)\
      \ (level 2 version)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +15, reach 15 ft. *Hit:* 19 (2d10 + 8) Slashing\
      \ damage plus 9 (2d8) Necrotic damage."
    "name": "Rend"
  - "desc": "*Constitution Saving Throw:* DC 22, each creature in a 90-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
      \ *Failure:* 72 (16d8) Necrotic damage. *Success:* Half damage."
    "name": "Ruinous Breath (Recharge 5-6)"
  - "desc": "*Wisdom Saving Throw:* DC 22, each creature that isn't currently affected\
      \ by this breath in a 90-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
      \ *Failure:* The target's [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
      \ is halved, it can't take Reactions, and it can take either an action or a\
      \ [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md) on\
      \ its turn, not both. It repeats the save at the end of each of its turns, ending\
      \ the effect on itself on a success. After 1 minute, it succeeds automatically."
    "name": "Time-Warping Breath"
  - "desc": "The dragon casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 22):\n\n\
      **At will:** [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Shapechange](3-Mechanics/CLI/spells/shapechange-xphb.md)\
      \ (Beast or Humanoid form only, no [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
      \ gained from the spell, and no [Concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ or [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
      \ required to maintain the spell), [Thunderwave](3-Mechanics/CLI/spells/thunderwave-xphb.md)\
      \ (level 2 version)\n\n**1/day each:** [Legend Lore](3-Mechanics/CLI/spells/legend-lore-xphb.md)\
      \ (as an action), [Sequester](3-Mechanics/CLI/spells/sequester-xphb.md)"
    "name": "Spellcasting"
"regional_effects":
  - "desc": "The region containing an adult or ancient spirit dragon's lair is changed\
      \ by its presence, creating the following effects:\n\n- **Enchanted Acoustics.**\
      \ Creatures within 1 mile of the lair have Advantage on Charisma ([Performance](3-Mechanics/CLI/rules/skills.md#Performance))\
      \ checks that involve singing or playing music. Creatures other than the dragon\
      \ and its allies in that area have Disadvantage on saving throws to avoid or\
      \ end the Charmed condition.  \n- **Time Distortion.** While within 1 mile of\
      \ the lair, creatures age at one-tenth the usual rate.  \n\nIf the dragon dies\
      \ or moves its lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, the dragon can expend a use to take one of the following\
  \ actions. The dragon regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The dragon moves up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md),\
      \ and it makes one Rend attack."
    "name": "Pounce"
  - "desc": "The dragon uses Spellcasting to cast [Thunderwave](3-Mechanics/CLI/spells/thunderwave-xphb.md)\
      \ (level 2 version)."
    "name": "Shattering Wave"
  - "desc": "The dragon magically raises broken, ancient ruins in a 20-foot-radius,\
      \ 60-foot-high [Cylinder](3-Mechanics/CLI/rules/variant-rules/cylinder-area-of-effect-xphb.md)\
      \ centered on a point it can see within 120 feet. Ground in the [Cylinder](3-Mechanics/CLI/rules/variant-rules/cylinder-area-of-effect-xphb.md)\
      \ becomes [Difficult Terrain](3-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md).\
      \ Each creature in the [Cylinder](3-Mechanics/CLI/rules/variant-rules/cylinder-area-of-effect-xphb.md)\
      \ when it appears is subjected to the following effect. *Strength Saving Throw:*\
      \ DC 22. *Failure:* 13 (3d8) Bludgeoning damage, and the target has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition. *Failure or Success:* The dragon can't take this action again until\
      \ the start of its next turn."
    "name": "Unearth Ruins"
"source":
  - "FRAiF"
"image": "file://bestiary/tokens/FRAiF/Ancient%20Spirit%20Dragon.webp"
```
^statblock

## Environment

any