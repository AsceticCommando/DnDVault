---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/kftgv
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/gnome
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kavoda"
---
# [Kavoda](3-Mechanics/CLI/bestiary/npc/kavoda-kftgv.md)
*Source: Keys from the Golden Vault p. 78*  

```statblock
"name": "Kavoda (KftGV)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Chaotic Good"
"ac": !!int "12"
"ac_class": "[robes](3-Mechanics/CLI/items/robe-xphb.md)"
"hp": !!int "16"
"hit_dice": "3d6 + 6"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "9"
"speed": "20 ft."
"skillsaves":
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"gear":
  - "[war pick](3-Mechanics/CLI/items/war-pick-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 12"
"languages": "Common, Gnomish, Terran, Undercommon"
"cr": "1/2"
"traits":
  - "desc": "Kavoda's innate spellcasting ability is Intelligence (spell save DC 11).\
      \ It can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [nondetection](3-Mechanics/CLI/spells/nondetection-xphb.md) (self\
      \ only)\n\n**1/day each:** [blindness/deafness](3-Mechanics/CLI/spells/blindness-deafness-xphb.md),\
      \ [blur](3-Mechanics/CLI/spells/blur-xphb.md), [disguise self](3-Mechanics/CLI/spells/disguise-self-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Kavoda carries a [spell scroll](3-Mechanics/CLI/items/spell-scroll-level-2-xdmg.md)\
      \ of [magic weapon](3-Mechanics/CLI/spells/magic-weapon-xphb.md) and a [potion\
      \ of giant strength (hill)](3-Mechanics/CLI/items/potion-of-hill-giant-strength-xdmg.md)."
    "name": "Special Equipment"
  - "desc": "Kavoda has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks made to hide in rocky terrain."
    "name": "Stone Camouflage"
  - "desc": "Kavoda has advantage on Intelligence, Wisdom, and Charisma saving throws\
      \ against magic."
    "name": "Gnome Cunning"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8\
      \ + 2) piercing damage."
    "name": "War Pick"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one creature. *Hit:*\
      \ 4 (1d4 + 2) piercing damage, and the target must succeed on a DC 12 Constitution\
      \ saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success"
    "name": "Poisoned Dart"
"source":
  - "KftGV"
"image": "file://bestiary/tokens/KftGV/Kavoda.webp"
```
^statblock