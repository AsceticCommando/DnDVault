---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cultist of Bhaal"
---
# [Cultist of Bhaal](3-Mechanics/CLI/bestiary/humanoid/cultist-of-bhaal-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 255*  

Cultists of Bhaal revel in bloodshed. They enjoy the act of murder, particularly when they can use inventive methods that instill fear among witnesses. Cultists of Bhaal sometimes form cabals of assassins or mercenaries, but they perform their brutal slaughter for the perverse love of bloodshed and honor to their sinister god rather than for financial recompense. These cunning serial killers and mass murderers remain a step ahead of investigators, at least until the cultists' zealous bloodlust overwhelms their senses.

## Cultists

*Wicked Zealots of the Dead Three*

The adventurers Bane, Bhaal, and Myrkul seized divinity but were slain for their hubris. All three have been reborn and are now known as the Dead Three. Each of the Dead Three has inspired wicked cults that follow their paths of tyranny, murder, and necromancy.

More than any other gods, the Dead Three directly influence Faerûn—and particularly the city of Baldur's Gate—in malign ways. Cultists who receive orders from their patron god directly are often the most ambitious and most dangerous.

```statblock
"name": "Cultist of Bhaal (FRAiF)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"modifier": !!int "7"
"stats":
  - !!int "13"
  - !!int "19"
  - !!int "18"
  - !!int "15"
  - !!int "17"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "intelligence": !!int "5"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"gear":
  - "[holy symbol](3-Mechanics/CLI/items/holy-symbol-xphb.md)"
  - "[studded leather armor](3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 16"
"languages": "Common"
"cr": "7"
"traits":
  - "desc": "While [Bloodied](3-Mechanics/CLI/rules/conditions.md#Bloodied), the cultist\
      \ has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on\
      \ saving throws."
    "name": "Blood-Soaked Resolve"
"actions":
  - "desc": "The cultist makes three Cursed Blade attacks. It can replace one of these\
      \ attacks with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +7 (with [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ if the target doesn't have all its [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)),\
      \ reach 5 ft. or range 20/80 ft. *Hit:* 14 (3d6 + 4) Slashing damage. *Hit or\
      \ Miss:* The blade magically returns to the cultist's hand immediately after\
      \ a ranged attack."
    "name": "Cursed Blade"
  - "desc": "The cultist casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 14):\n\n**2/day:** [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)\n\
      \n**1/day each:** [Dimension Door](3-Mechanics/CLI/spells/dimension-door-xphb.md),\
      \ [Mislead](3-Mechanics/CLI/spells/mislead-xphb.md)"
    "name": "Spellcasting"
"source":
  - "FRAiF"
"image": "file://bestiary/tokens/FRAiF/Cultist%20of%20Bhaal.webp"
```
^statblock

## Environment

urban