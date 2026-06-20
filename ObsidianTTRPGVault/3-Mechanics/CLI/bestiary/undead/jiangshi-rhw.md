---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Jiangshi"
---
# [Jiangshi](3-Mechanics/CLI/bestiary/undead/jiangshi-rhw.md)
*Source: RHW p. 251*  

*Vindictive, Vitality-Sapping Corpse*

When a soul becomes trapped within its corpse, its bitterness can reanimate its body, creating a jiangshi. These vengeful dead stalk their descendants, sowing terror and taking retribution for the slights or neglected burial rites that led to their cursed resurrections. Rigor mortis notoriously afflicts the limbs of jiangshi, causing them to hold their arms rigidly and to walk with a stiff gait. This, along with their flight, leads many to call them hopping vampires.

By day, jiangshi lurk within tombs or hidden ruins to avoid attention from the living. At night, they emerge to drain the life from those who dare wander in darkness. A Humanoid killed by a jiangshi rises as a life-hungry corpse that, if given the chance to slake its thirst, might also turn into jiangshi.

```statblock
"name": "Jiangshi (RHW)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "119"
"hit_dice": "14d8 + 56"
"modifier": !!int "-4"
"stats":
  - !!int "18"
  - !!int "3"
  - !!int "18"
  - !!int "17"
  - !!int "14"
  - !!int "12"
"speed": "20 ft., fly 5 ft. (hover)"
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
  - "charisma": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 16"
"languages": "Common plus three other languages"
"cr": "9"
"traits":
  - "desc": "The jiangshi has these weaknesses:\n\n- **Fear of Its Own Reflection.**\
      \ If the jiangshi sees its reflection, it immediately takes its [Reaction](3-Mechanics/CLI/rules/variant-rules/reaction-xphb.md),\
      \ if available, to move as far from the reflection as possible.  \n- **Susceptible\
      \ to Holy Symbols.** While the jiangshi is wearing or touching a [Holy Symbol](3-Mechanics/CLI/items/holy-symbol-xphb.md),\
      \ it loses its [Immunity](3-Mechanics/CLI/rules/variant-rules/immunity-xphb.md)\
      \ to the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) condition\
      \ and automatically fails saving throws to avoid or end the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition.  "
    "name": "Jiangshi Weaknesses"
"actions":
  - "desc": "The jiangshi makes three Slam attacks and uses Consume Energy."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 13 (2d8 + 4) Bludgeoning\
      \ damage."
    "name": "Slam"
  - "desc": "*Constitution Saving Throw:* DC 16, one creature the jiangshi can see\
      \ within 30 feet. *Failure:* 18 (4d8) Necrotic damage. *Success:* Half damage.\
      \ *Failure or Success:* The jiangshi regains [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ equal to the Necrotic damage taken, the jiangshi's [Fly Speed](3-Mechanics/CLI/rules/variant-rules/fly-speed-xphb.md)\
      \ increases to 20 feet until the end of its next turn, and it can take its Hungering\
      \ Stride [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md).\
      \ A Humanoid reduced to 0 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ by this damage rises at the end of the jiangshi's turn as a Wight under the\
      \ jiangshi's control. If this wight kills a Humanoid with its Life Drain action,\
      \ the wight transforms into an independent Jiangshi 5 days later."
    "name": "Consume Energy"
"bonus_actions":
  - "desc": "The jiangshi takes the [Dash](3-Mechanics/CLI/rules/actions.md#Dash)\
      \ action."
    "name": "Hungering Stride (Requires Consume Energy)"
  - "desc": "The jiangshi shape-shifts into a Medium or Small Beast, Humanoid, or\
      \ Undead creature, or it returns to its true form. Its game statistics, other\
      \ than its size, are the same in each form. Any equipment it is wearing or carrying\
      \ isn't transformed."
    "name": "Shape-Shift"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Jiangshi.webp"
```
^statblock

## Environment

any