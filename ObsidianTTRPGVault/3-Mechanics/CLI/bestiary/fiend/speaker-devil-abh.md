---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/abh
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/nine-hells
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Speaker Devil"
---
# [Speaker Devil](3-Mechanics/CLI/bestiary/fiend/speaker-devil-abh.md)
*Source: Astarion's Book of Hungers p. 17*  

*Devil of Spoken Compulsion*

Speaker devils are hulking, four-armed devils who discover the secrets of creatures they then compel to perform wicked deeds. Despite their large tongues, speaker devils speak with clear and pleasing voices. Among the ranks of the Nine Hells, they are known as logokrons.

Many speaker devils are loyal to the archdevil Mephistopheles. These devils record the secrets they uncover in Mephistar, Mephistopheles's vast library in Cania. While greedy to uncover other creatures' secrets, speaker devils diligently redact any evidence of their own secrets, lest such knowledge be used against them.

> [!quote] A quote from Astarion on Speaker Devils  
> 
> I know what you're thinking, and it's simply a terrible idea. Yes, yes, I know. That enormous tongue! And four arms! Oh, the possibilities! But trust me when I say it'll only end in tears.


```statblock
"name": "Speaker Devil (ABH)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "189"
"hit_dice": "18d10 + 90"
"modifier": !!int "4"
"stats":
  - !!int "21"
  - !!int "19"
  - !!int "20"
  - !!int "22"
  - !!int "18"
  - !!int "17"
"speed": "30 ft., fly 30 ft."
"saves":
  - "constitution": !!int "9"
  - "intelligence": !!int "10"
  - "wisdom": !!int "8"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+10"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+10"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
"damage_resistances": "cold"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 18"
"languages": "Infernal; telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "If the devil dies outside the Nine Hells, its body disappears in sulfurous\
      \ smoke, and it gains a new body instantly, reviving with all its [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ somewhere in the Nine Hells."
    "name": "Diabolical Restoration"
  - "desc": "The devil has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The devil makes two Thundering Halberd attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 10 ft. *Hit:* 16 (2d10 + 5) Slashing damage\
      \ plus 14 (4d6) Thunder damage."
    "name": "Thundering Halberd"
  - "desc": "The devil casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 18):\n\n\
      **At will:** [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Detect\
      \ Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md)\n\n**2/day each:**\
      \ [Dimension Door](3-Mechanics/CLI/spells/dimension-door-xphb.md), [Modify Memory](3-Mechanics/CLI/spells/modify-memory-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "*Wisdom Saving Throw:* DC 18, each creature in a 20-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the devil. *Failure:* The target has the [Stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ condition until the end of the devil's next turn."
    "name": "Utterance of Pain"
  - "desc": "*Constitution Saving Throw:* DC 18, each creature in a 20-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the devil. *Failure:* 22 (4d10) Force damage. *Success:*\
      \ Half damage."
    "name": "Utterance of Unmaking"
"source":
  - "ABH"
"image": "file://bestiary/tokens/ABH/Speaker%20Devil.webp"
```
^statblock

## Environment

planar, nine hells