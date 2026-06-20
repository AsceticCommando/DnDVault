---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Yithian"
---
# [Yithian](3-Mechanics/CLI/bestiary/aberration/yithian-rhw.md)
*Source: RHW p. 281*  

*Fungous Alien Body Swapper*

Yithians are cosmos-traveling scholars with distinctive, conical bodies and four limbs that end in pincers, sensory structures, and flute-like communication organs. They search for secrets to add to their vast libraries, conducting research by swapping minds with the inhabitants of other worlds—sometimes indefinitely. When a yithian swaps minds with a creature, it traps its victim's mind in the yithian's body, which it teleports to its unfathomable, alien home world.

```statblock
"name": "Yithian (RHW)"
"size": "Large"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "180"
"hit_dice": "19d10 + 76"
"modifier": !!int "5"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "21"
  - !!int "18"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "constitution": !!int "9"
  - "intelligence": !!int "10"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 60 ft., passive\
  \ Perception 14"
"languages": "Deep Speech; telepathy 120 ft."
"cr": "15"
"traits":
  - "desc": "The yithian has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The yithian's thoughts can't be read by any means, and other creatures\
      \ can communicate with it telepathically only if it allows them."
    "name": "Shielded Mind"
"actions":
  - "desc": "The yithian makes three Pincer attacks. It can replace one attack with\
      \ a use of Sup."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 10 ft. *Hit:* 18 (4d6 + 4) Piercing damage\
      \ and the creature has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 14)."
    "name": "Pincer"
  - "desc": "*Intelligence Saving Throw:* DC 18, one creature within 10 feet that\
      \ has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
      \ or [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) condition.\
      \ *Failure:* 15 (3d6 + 5) Psychic damage. The target's [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ maximum decreases by an amount equal to the damage taken, and the yithian\
      \ regains [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ equal to that amount."
    "name": "Sup"
"bonus_actions":
  - "desc": "*Intelligence Saving Throw:* DC 18, one Humanoid the yithian can see\
      \ within 5 feet. *Failure:* The target is possessed by the yithian; the yithian\
      \ disappears, and the target has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition and loses control of its body. The yithian now controls the body;\
      \ the target has no awareness of the yithian's actions. The yithian can't be\
      \ targeted by any attack, spell, or other effect. The yithian's game statistics\
      \ are the same, except it uses the possessed target's [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
      \ and Strength, Dexterity, and Constitution modifiers. It knows everything the\
      \ target knew.\n\nThe possession lasts until the body drops to 0 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ or the yithian leaves as a [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md).\
      \ When the possession ends, the yithian returns to its body, which appears within\
      \ 5 feet of the target. The target is [Stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ for 1 minute by alien memories, and it is immune to this yithian's Mind Swap\
      \ for 24 hours. *Success:* The target is immune to Mind Swap for 24 hours."
    "name": "Mind Swap (Recharge 6)"
  - "desc": "The yithian casts [Clairvoyance](3-Mechanics/CLI/spells/clairvoyance-xphb.md),\
      \ [Modify Memory](3-Mechanics/CLI/spells/modify-memory-xphb.md), [Phantasmal\
      \ Killer](3-Mechanics/CLI/spells/phantasmal-killer-xphb.md), or Transport via\
      \ Plants, requiring no spell components and using Intelligence as the spellcasting\
      \ ability (spell save DC 18).\n"
    "name": "Eldritch Magic (2/Day)"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Yithian.webp"
```
^statblock

## Environment

desert, underdark, urban