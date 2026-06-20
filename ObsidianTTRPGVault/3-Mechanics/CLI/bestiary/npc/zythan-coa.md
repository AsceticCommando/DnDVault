---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zythan"
---
# [Zythan](3-Mechanics/CLI/bestiary/npc/zythan-coa.md)
*Source: Chains of Asmodeus p. 26*  

Zythan, like many other Halruaans, spent his early years studying the arcane arts. His talent in Divination magic made him particularly useful to the Conclave, and they quickly sought him out. Under their tutelage, his skill flourished, and he became a powerful mage. Those that know him personally recount his matter-of-fact personality, his green hair, and his third eye that seems to open when he performs magic. He rarely speaks of himself, however, choosing instead to focus his attention on the future.

When he first received an official position within the Conclave, Zythan wanted to prove himself. He spent countless hours peering into the future and examining potential outcomes. One fateful night, he just barely caught sight of a forbidden ritual being prepared—a ritual that could cost the lives of many Halruaans. Because of his sight, the Conclave was able to intervene in time, and he was quickly promoted and showered with praise.

For the past few months, Zythan has felt like something was off: at first, he suspected another ritual within Halruaa. He requisitioned the help of the other diviners, as well as a powerful Crystal Ball, and together they were able to piece together a vision. The dark lord of the Nine Hells, Asmodeus, will unleash a great evil very soon. Though the Conclave often stays out of non-Halruaan affairs, they had no choice but to act. It is for this reason that the adventurers were called to Halruaa.

Zythan's skill in arcane magic, while particularly focused on Divination, extends to every school. While he lacks proficiency in martial combat, he can wield both offensive and defensive magic effectively. Outside of his magical talent, he is also known to be highly intelligent, though his social skills could use work. Much of his time is spent viewing alternate futures and preparing for potential dangers, leaving little for himself. He often goes without meals until he starts to feel weak, and if he had friends, they might be concerned about how much time he spends working.

```statblock
"name": "Zythan (CoA)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Neutral"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "10"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+15"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+15"
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+10"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+10"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks (from\
  \ Stoneskin); damage from spells"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "passive Perception 12"
"languages": "Celestial, Common, Draconic, Elvish, Infernal, Primordial"
"cr": "13"
"traits":
  - "desc": "Being within 5 feet of a hostile creature doesn't impose disadvantage\
      \ on Zythan's ranged attack rolls."
    "name": "Battlemage"
  - "desc": "Zythan has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Zythan makes three Dagger or Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "*Ranged Spell Attack:* +10 to hit, range 120 ft., one target. *Hit:*\
      \ 27 (4d10 + 5) radiant damage."
    "name": "Arcane Burst"
  - "desc": "Zythan causes a disruption in arcane energies in a 300-foot line that\
      \ is 5 feet wide. Each creature in the line must make a DC 18 Constitution saving\
      \ throw, taking 65 (10d12) radiant damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Spirit Fissure (Recharge 4-6)"
  - "desc": "Zythan casts one of the following spells, using Intelligence as the spellcasting\
      \ ability (spell save DC 18).\n\n**At will:** [Arcane Eye](3-Mechanics/CLI/spells/arcane-eye-xphb.md),\
      \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Detect Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [Fly](3-Mechanics/CLI/spells/fly-xphb.md), [Light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [Locate Object](3-Mechanics/CLI/spells/locate-object-xphb.md), [Mage Armor](3-Mechanics/CLI/spells/mage-armor-xphb.md),\
      \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [Message](3-Mechanics/CLI/spells/message-xphb.md),\
      \ [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n**1/day:**\
      \ [Cone of Cold](3-Mechanics/CLI/spells/cone-of-cold-xphb.md), [Foresight](3-Mechanics/CLI/spells/foresight-xphb.md),\
      \ [Stoneskin](3-Mechanics/CLI/spells/stoneskin-xphb.md), [Rary's telepathic\
      \ bond](3-Mechanics/CLI/spells/rarys-telepathic-bond-xphb.md), [True Seeing](3-Mechanics/CLI/spells/true-seeing-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "As a reaction to a creature Zythan can see making an attack roll, a saving\
      \ throw, or an ability check, Zythan rolls a d20 and chooses whether to use\
      \ that roll in place of the original roll."
    "name": "Portent (3/Day)"
"source":
  - "CoA"
"image": "file://bestiary/tokens/CoA/Zythan.webp"
```
^statblock