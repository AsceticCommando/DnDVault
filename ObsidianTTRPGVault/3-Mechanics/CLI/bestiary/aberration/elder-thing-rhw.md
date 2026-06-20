---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Elder Thing"
---
# [Elder Thing](3-Mechanics/CLI/bestiary/aberration/elder-thing-rhw.md)
*Source: RHW p. 245*  

*Inscrutable Entity from Another Realm*

The aliens known as elder things have colonized countless worlds over unfathomable eons. Within hidden cyclopean cities, they collect mind-shattering secrets of the multiverse. Their empires have declined over the ages, suffering challenges by yithians and their creations, the shoggoths). Those elder things that remain guard the remnants of their power and seek to subjugate those they consider lesser beings.

```statblock
"name": "Elder Thing (RHW)"
"size": "Large"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "209"
"hit_dice": "22d10 + 88"
"modifier": !!int "0"
"stats":
  - !!int "21"
  - !!int "11"
  - !!int "18"
  - !!int "20"
  - !!int "17"
  - !!int "16"
"speed": "20 ft., fly 90 ft. (hover)"
"saves":
  - "constitution": !!int "9"
  - "intelligence": !!int "10"
"damage_resistances": "bludgeoning, piercing, psychic, slashing"
"damage_immunities": "lightning"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 13"
"languages": "Deep Speech; telepathy 120 ft."
"cr": "14"
"traits":
  - "desc": "The elder thing has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The elder thing makes two Soothing Tentacle attacks and uses Psychic\
      \ Skewer."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 10 ft. *Hit:* 14 (2d8 + 5) Psychic damage,\
      \ and the target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition until the start of the elder thing's next turn."
    "name": "Soothing Tentacle"
  - "desc": "*Intelligence Saving Throw:* DC 18, each creature in a 20-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the elder thing. *Failure:* 55 (10d10) Psychic damage. For\
      \ 1 minute, whenever the target takes the [Magic](3-Mechanics/CLI/rules/actions.md#Magic)\
      \ action, it takes 10 (3d6) Psychic damage. *Success:* Half damage only."
    "name": "Mind-Scouring Spores (Recharge 6)"
  - "desc": "*Wisdom Saving Throw:* DC 18, one creature within 60 feet. *Failure:*\
      \ 22 (4d10) Psychic damage. If the target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition, it gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion)\
      \ level and has the [Stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) condition\
      \ while [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)."
    "name": "Psychic Skewer"
"bonus_actions":
  - "desc": "The elder thing casts [Command](3-Mechanics/CLI/spells/command-xphb.md),\
      \ [Detect Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Gust of\
      \ Wind](3-Mechanics/CLI/spells/gust-of-wind-xphb.md), or [Nondetection](3-Mechanics/CLI/spells/nondetection-xphb.md),\
      \ requiring no spell components and using Intelligence as the spellcasting ability\
      \ (spell save DC 18).\n"
    "name": "Eldritch Magic (3/Day)"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Elder%20Thing.webp"
```
^statblock

## Environment

mountain, underdark