---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Omin Dran"
---
# [Omin Dran](3-Mechanics/CLI/bestiary/npc/omin-dran-ai.md)
*Source: Acquisitions Incorporated p. 196*  

> [!quote]  
> 
> My duty, first and foremost, is to my shareholders. And I am the only shareholder.

Ominifis Hereward Dran spent his formative years in the small way-stop of Red Larch, where his mother, Prophetess, ran a popular inn and restaurant. In the brief periods of respite afforded by working the family business, Omin and his sisters, Auspicia and Portentia, were wont to wander the hills and trails around town, dreaming of adventure. But adventure of the wrong kind came calling for the trio one day, when an underground ruin they had often explored-actually a creature called the Wandering Crypt-took Auspicia from the world.

Omin Dran built the organization called Acquisitions Incorporated to facilitate and expand his quest to find his true sister, at least in part. For despite his unprecedented success in establishing the market for franchised adventuring across the Sword Coast and beyond, Omin's full measure eludes most people. He is known to be a worshiper of Tymora, ruthless in matters of business, feckless in matters of love, and hopeless in games of chance. Omin is also often accused of being one of the Masked Lords of Waterdeep, though this bit of fancy earns little more than a chuckle in response. And even if the rumor were true, Omin would never leverage such a position for greater financial gain and power. Because that would be wrong...

```statblock
"name": "Omin Dran (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "14"
  - !!int "11"
  - !!int "18"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+4"
"gear":
  - "[maul](3-Mechanics/CLI/items/maul-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 17"
"languages": "Common, Dwarvish, Elvish, Goblin"
"cr": "5"
"traits":
  - "desc": "Omin is a 9th-level spellcaster. His spellcasting ability is Wisdom (spell\
      \ save DC 15, +7 to hit with spell attacks). He has the following cleric spells\
      \ prepared:\n\n**Cantrips (at will):** [guidance](3-Mechanics/CLI/spells/guidance-xphb.md),\
      \ [sacred flame](3-Mechanics/CLI/spells/sacred-flame-xphb.md), [spare the dying](3-Mechanics/CLI/spells/spare-the-dying-xphb.md),\
      \ [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\n**1st level (4\
      \ slots):** [bless](3-Mechanics/CLI/spells/bless-xphb.md), [command](3-Mechanics/CLI/spells/command-xphb.md),\
      \ [divine favor](3-Mechanics/CLI/spells/divine-favor-xphb.md), [shield of faith](3-Mechanics/CLI/spells/shield-of-faith-xphb.md)\n\
      \n**2nd level (3 slots):** [enhance ability](3-Mechanics/CLI/spells/enhance-ability-xphb.md),\
      \ [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md), [magic weapon](3-Mechanics/CLI/spells/magic-weapon-xphb.md),\
      \ [silence](3-Mechanics/CLI/spells/silence-xphb.md), [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)\n\
      \n**3rd level (3 slots):** [beacon of hope](3-Mechanics/CLI/spells/beacon-of-hope-xphb.md),\
      \ [crusader's mantle](3-Mechanics/CLI/spells/crusaders-mantle-xphb.md), [dispel\
      \ magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [mass healing word](3-Mechanics/CLI/spells/mass-healing-word-xphb.md),\
      \ [spirit guardians](3-Mechanics/CLI/spells/spirit-guardians-xphb.md)\n\n**4th\
      \ level (3 slots):** [death ward](3-Mechanics/CLI/spells/death-ward-xphb.md),\
      \ [freedom of movement](3-Mechanics/CLI/spells/freedom-of-movement-xphb.md),\
      \ [locate creature](3-Mechanics/CLI/spells/locate-creature-xphb.md), [stoneskin](3-Mechanics/CLI/spells/stoneskin-xphb.md)\n\
      \n**5th level (1 slots):** [dispel evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md),\
      \ [flame strike](3-Mechanics/CLI/spells/flame-strike-xphb.md), [hold monster](3-Mechanics/CLI/spells/hold-monster-xphb.md),\
      \ [greater restoration](3-Mechanics/CLI/spells/greater-restoration-xphb.md),\
      \ [legend lore](3-Mechanics/CLI/spells/legend-lore-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Once on each of his turns when he hits a creature with a weapon attack,\
      \ Omin can cause the attack to deal an extra 4 (1d8) damage of the same type\
      \ dealt by the weapon."
    "name": "Divine Strike"
  - "desc": "Omin has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put him to sleep."
    "name": "Fey Ancestry"
"actions":
  - "desc": "Omin makes two attacks with his maul."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) bludgeoning damage."
    "name": "Maul"
"reactions":
  - "desc": "When a creature within 30 feet of Omin makes an attack roll, but before\
      \ learning whether it hits or misses, Omin can grant the creature a +10 bonus\
      \ to that roll."
    "name": "War God's Blessing (Recharges after a Short or Long Rest)"
"source":
  - "AI"
"image": "file://bestiary/tokens/AI/Omin%20Dran.webp"
```
^statblock