---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Reanimated Companion"
---
# [Reanimated Companion](3-Mechanics/CLI/bestiary/undead/reanimated-companion-rhw.md)
*Source: RHW*  

```statblock
"name": "Reanimated Companion (RHW)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral"
"ac_class": "10 plus your Intelligence modifier"
"modifier": !!int "0"
"stats":
  - !!int "11"
  - !!int "10"
  - !!int "16"
  - !!int "4"
  - !!int "10"
  - !!int "6"
"speed": "30 ft."
"damage_resistances": "necrotic, poison"
"damage_immunities": "lightning"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 10"
"languages": "understands the languages you know"
"traits":
  - "desc": "The companion explodes when it dies. *Dexterity Saving Throw:* DC equals\
      \ your spell save DC, each creature in a 10-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the companion. *Failure:* 2d4 Necrotic damage. *Success:*\
      \ Half damage."
    "name": "Death Burst"
  - "desc": "Whenever the companion is subjected to Lightning damage, it regains a\
      \ number of [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ equal to the Lightning damage dealt."
    "name": "Lightning Absorption"
"actions":
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft. *Hit:* 1d4 plus your Intelligence modifier Necrotic damage, and the target\
      \ can't take [Opportunity Attacks](3-Mechanics/CLI/rules/actions.md#Opportunity%20Attack)\
      \ until the start of its next turn."
    "name": "Dreadful Swipe"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Reanimated%20Companion.webp"
```
^statblock