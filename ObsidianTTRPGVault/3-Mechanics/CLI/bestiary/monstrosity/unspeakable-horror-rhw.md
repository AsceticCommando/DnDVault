---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Unspeakable Horror"
---
# [Unspeakable Horror](3-Mechanics/CLI/bestiary/monstrosity/unspeakable-horror-rhw.md)
*Source: RHW p. 274*  

*Terrifying Monster of the Mists*

Unspeakable horrors are anathema to all other life in the multiverse. Their shapes change constantly in ways that defy and disrupt reality. Those who look on these beings instantly understand their absolute and awful wrongness. Such revelations are often the last witnesses have before they're dissolved by discordant, destructive forces.

```statblock
"name": "Unspeakable Horror (RHW)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "126"
"hit_dice": "12d12 + 48"
"modifier": !!int "4"
"stats":
  - !!int "21"
  - !!int "13"
  - !!int "19"
  - !!int "3"
  - !!int "14"
  - !!int "17"
"speed": "40 ft."
"saves":
  - "constitution": !!int "7"
  - "wisdom": !!int "5"
"damage_resistances": "acid, cold, necrotic, poison"
"condition_immunities": "[frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 60 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "8"
"traits":
  - "desc": "Attack rolls against the horror have [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md).\
      \ This trait is suppressed while the horror has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Incomprehensible Form"
  - "desc": "The horror regains 10 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ at the start of each of its turns if it has at least 1 [Hit Point](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)."
    "name": "Regeneration"
  - "desc": "The horror radiates an aura in a 15-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ while it doesn't have the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition. *Wisdom Saving Throw:* DC 15, any enemy that starts its turn in\
      \ the aura. *Failure:* The target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the start of its next turn. While [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ in this way, the target has the [Paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ condition. *Success:* The target is immune to this horror's aura for 24 hours."
    "name": "Terrifying Aura"
"actions":
  - "desc": "The horror makes three Phantasmic Assault attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +8, reach 5 ft. or range 60 ft. *Hit:*\
      \ 14 (4d6) Cold, Necrotic, Poison, or Psychic damage (horror's choice)."
    "name": "Phantasmic Assault"
"reactions":
  - "desc": "Trigger: A creature the horror can see within 120 feet of itself takes\
      \ the [Study](3-Mechanics/CLI/rules/actions.md#Study) action or makes a Constitution\
      \ saving throw to maintain [Concentration](3-Mechanics/CLI/rules/conditions.md#Concentration).\
      \ _Response—_*Wisdom Saving Throw:* DC 15, the triggering creature. *Failure:*\
      \ 7 (2d6) Psychic damage, and the target has the [Stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ condition until the end of its next turn."
    "name": "Warp Mind"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Unspeakable%20Horror.webp"
```
^statblock

## Environment

any