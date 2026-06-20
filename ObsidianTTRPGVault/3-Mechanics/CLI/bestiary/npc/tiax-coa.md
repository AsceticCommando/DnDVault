---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tiax"
---
# [Tiax](3-Mechanics/CLI/bestiary/npc/tiax-coa.md)
*Source: Chains of Asmodeus p. 266*  

A long-serving cleric of Cyric, the god of lies, Tiax is absolutely certain of many things—most of them entirely untrue. After twenty years in Cyric's clergy, Tiax's mind has been twisted by the god's many tricks. Still, even so flavored by fantasy and deception, the favor of a god often proves a very powerful boon indeed. Whatever dire trouble Tiax finds himself in, even if it be the flames of the Nine Hells, his god will devise means of delivering him to safety—though often just by the skin of his teeth.

All of these near misses and improbable escapes have only solidified Tiax's delusions of grandeur. Though he is well aware that it is Cyric's divine interference which saves him, Tiax tells everyone he encounters that he is actually a powerful sorcerer and thus hides his piety to Cyric and the divine power he has been granted in return.

As one might expect, Tiax's foremost attributes are exaggeration and deceit. Unfortunately, for the unsuspecting, Tiax's unthreatening and absurd demeanor can grant the illusion of harmlessness. His many lies appear outlandish and easily dismissed, and his erratic behavior borders on complete buffoonery. Some might even find his colorful, chaotic personality to be charming. Certainly, Koh Tam seems to tolerate him for one reason or another. But make no mistake, Tiax is dangerous. The wise should be wary.

```statblock
"name": "Tiax (CoA)"
"size": "Small"
"type": "humanoid"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "16 with [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "110"
"hit_dice": "20d6 + 40"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "19"
  - !!int "18"
"speed": "25 ft."
"saves":
  - "wisdom": !!int "8"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+8"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+8"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Celestial, Common, Gnomish"
"cr": "9"
"traits":
  - "desc": "Tiax has advantage on Intelligence, Wisdom, and Charisma saving throws\
      \ against magic."
    "name": "Gnome Cunning"
  - "desc": "Tiax wears a [Ring of Resistance](3-Mechanics/CLI/items/ring-of-resistance-xdmg.md)\
      \ that grants him resistance to radiant damage."
    "name": "Special Equipment"
"actions":
  - "desc": "*Melee Spell Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 37 (6d10\
      \ + 4) necrotic damage."
    "name": "Touch of Decay"
  - "desc": "Tiax causes unholy fire to flare up in a creature's space within 60 feet\
      \ of him. The target must succeed on a DC 16 Dexterity saving throw or take\
      \ 18 (4d8) necrotic damage plus 18 (4d8) poison damage."
    "name": "Unholy Firebolt"
  - "desc": "Tiax casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 16):\n\n**At will:** [Bane](3-Mechanics/CLI/spells/bane-xphb.md),\
      \ [Disguise Self](3-Mechanics/CLI/spells/disguise-self-xphb.md), [Dispel Magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [Mage Armor](3-Mechanics/CLI/spells/mage-armor-xphb.md), [Mirror Image](3-Mechanics/CLI/spells/mirror-image-xphb.md),\
      \ [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\n**1/day each:**\
      \ [Bestow Curse](3-Mechanics/CLI/spells/bestow-curse-xphb.md), [Blindness/Deafness](3-Mechanics/CLI/spells/blindness-deafness-xphb.md),\
      \ [Blink](3-Mechanics/CLI/spells/blink-xphb.md), [Charm Person](3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [Contagion](3-Mechanics/CLI/spells/contagion-xphb.md), [Dimension Door](3-Mechanics/CLI/spells/dimension-door-xphb.md),\
      \ [Dominate Person](3-Mechanics/CLI/spells/dominate-person-xphb.md), [Hold Person](3-Mechanics/CLI/spells/hold-person-xphb.md),\
      \ [Pass Without Trace](3-Mechanics/CLI/spells/pass-without-trace-xphb.md), [Polymorph](3-Mechanics/CLI/spells/polymorph-xphb.md),\
      \ [Teleport](3-Mechanics/CLI/spells/teleport-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Tiax heals 70 hit points."
    "name": "Heal (2/Day)"
"source":
  - "CoA"
"image": "file://bestiary/tokens/CoA/Tiax.webp"
```
^statblock