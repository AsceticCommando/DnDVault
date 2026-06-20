---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/abh
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/nine-hells
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Harvester Devil"
---
# [Harvester Devil](3-Mechanics/CLI/bestiary/fiend/harvester-devil-abh.md)
*Source: Astarion's Book of Hungers p. 15*  

*Devil of Guile and Temptation*

With a name that hints at their skill at gathering souls for the Nine Hells, harvester devils are smooth-talking creatures that resemble tieflings. Also known as falxugons among the ranks of the Nine Hells, harvester devils have short horns and expressive tails. Most harvester devils dress in flattering finery. They promise wealth or influence to corruptible mortals, often securing a deal with a contract they produce in a flash of brimstone. This contract binds the mortal signatory's soul to the Nine Hells.

Harvester devils' contracts are lengthy and convoluted, but these devils are quick to make deals and might leave loopholes that can save a signatory's soul. Roll on or choose a result from the Contract Loopholes table to inspire a loophole an astute reader might discover.

`dice: [](harvester-devil-abh.md#^1-the-contract-is-void-if-the-signatory)`

| dice: 1d6 | The Contract Is Void If the Signatory... |
|-----------|------------------------------------------|
| 1 | Delivers ninety nine other souls to Mephistopheles. |
| 2 | Stands under the light of a full moon and a half-moon simultaneously. |
| 3 | Renounces the contract while in the Abyss. |
| 4 | Is under the protection of another fiend. |
| 5 | Has an identical twin or clone. |
| 6 | Tricks the devil into signing any other contract. |
^1-the-contract-is-void-if-the-signatory

> [!quote] A quote from Astarion on Harvester Devils  
> 
> Unfortunately, finding these dandyish devils' contractual loopholes is not nearly as much fun as I had hoped.


```statblock
"name": "Harvester Devil (ABH)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "17"
  - !!int "14"
  - !!int "14"
  - !!int "13"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+8"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "cold"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft. (unimpeded\
  \ by magical [Darkness](3-Mechanics/CLI/rules/variant-rules/darkness-xphb.md)),\
  \ passive Perception 13"
"languages": "Common, Infernal; telepathy 120 ft."
"cr": "3"
"traits":
  - "desc": "Attack rolls against the devil have [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md).\
      \ If the devil makes an attack roll, this trait is suppressed until the start\
      \ of its next turn."
    "name": "Diabolic Ward"
  - "desc": "If the devil dies outside the Nine Hells, its body disappears in sulfurous\
      \ smoke, and it gains a new body instantly, reviving with all its [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ somewhere in the Nine Hells."
    "name": "Diabolical Restoration"
  - "desc": "The devil has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The devil makes two attacks, using Infernal Blade or Confounding Ray\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage\
      \ and 7 (2d6) Fire damage."
    "name": "Infernal Blade"
  - "desc": "*Ranged Attack Roll:* +5, range 120 ft. *Hit:* 13 (2d12) Psychic damage.\
      \ If the target is a creature, it can't make [Opportunity Attacks](3-Mechanics/CLI/rules/actions.md#Opportunity%20Attack)\
      \ until the start of the devil's next turn."
    "name": "Confounding Ray"
  - "desc": "*Charisma Saving Throw:* DC 14, one creature within 30 feet of the devil.\
      \ *Failure:* The target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition. While it is [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ it has the [Stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) condition,\
      \ except the target can speak. If the target agrees to the devil's contract,\
      \ the effect ends. Otherwise, the target repeats the save whenever it takes\
      \ damage and at the end of each of its turns, ending the effect on itself on\
      \ a success. After 1 minute, it succeeds automatically."
    "name": "Compelling Contract (1/Day)"
"source":
  - "ABH"
"image": "file://bestiary/tokens/ABH/Harvester%20Devil.webp"
```
^statblock

## Environment

planar, nine hells