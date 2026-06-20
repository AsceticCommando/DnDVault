---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ez d'Avenir"
---
# [Ez d'Avenir](3-Mechanics/CLI/bestiary/npc/ez-davenir-rhw.md)
*Source: RHW p. 246*  

*Wandering Monster Hunter*

Ez d'Avenir first encountered monsters among her manipulative family, the Radanaviches, who posed as Vistani to prey on travelers. Among their foul deeds, the Radanavich family kidnapped Erasmus van Richten, the son of Rudolph van Richten and sold him to his death at the hands of the vampire Baron Metus. In the brief time Ez knew Erasmus, the youth spoke lovingly of a different sort of family than the one Ez knew. When Erasmus's father tracked down Ez's family and delivered her mother to justice, Ez didn't stop the determined doctor.

In the years that followed, Ez joined a true Vistani band and adopted the name d'Avenir. She traveled far but never found the sense of belonging Erasmus described. She sought out Rudolph van Richten and, after a wary introduction, came to study with the doctor. During that time, she reconnected with Erasmus, now a ghost. She learned priceless lessons from the van Richtens, but she eventually left their household to pursue her own destiny.

Ez's skillful slaying of monsters and her bravery in the face of supernatural perils have earned her a reputation as a folk hero and Mist wanderer of note. Although her adventures have cost her dearly—she has lost valuable bounties, dear companions, and her leg from the knee down—Ez works tirelessly to eradicate evil and protect innocents. Armed with wisdom from her mentor, encouragement from her departed friend, and hope forged in the depths of her heart, Ez aspires to someday create a place that feels safe enough to call home.

Whether she's hunting monsters or investigating mysteries, Ez carries Vistani music with her wherever she goes. She boasts a significant repertoire of songs from across the Land of the Mists, which she's happy to perform for anyone who travels alongside her.

```statblock
"name": "Ez d'Avenir (RHW)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Good"
"ac": !!int "14"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"modifier": !!int "7"
"stats":
  - !!int "14"
  - !!int "19"
  - !!int "16"
  - !!int "18"
  - !!int "11"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+3"
"gear":
  - "[light crossbow](3-Mechanics/CLI/items/light-crossbow-xphb.md)"
  - "[rapier](3-Mechanics/CLI/items/rapier-xphb.md)"
"senses": "passive Perception 13"
"languages": "Common, Elvish"
"cr": "8"
"actions":
  - "desc": "Ez makes three attacks, using Hunter's Blade or Fiery Bolt in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing damage\
      \ plus 11 (2d10) Radiant damage."
    "name": "Hunter's Blade"
  - "desc": "*Ranged Attack Roll:* +7, range 120 ft. *Hit:* 19 (3d10 + 3) Fire damage."
    "name": "Fiery Bolt"
  - "desc": "Ez casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\n\
      **At will:** [Light](3-Mechanics/CLI/spells/light-xphb.md), [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\n\
      \n**1/day each:** [Dispel Evil and Good](3-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md),\
      \ [Lightning Bolt](3-Mechanics/CLI/spells/lightning-bolt-xphb.md), [Magic Circle](3-Mechanics/CLI/spells/magic-circle-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Ez chooses up to six allies within 60 feet. Each target that can hear\
      \ her has Ez's choice of (A) [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on the next attack roll it makes before the end of its next turn or (B) [Resistance](3-Mechanics/CLI/rules/variant-rules/resistance-xphb.md)\
      \ to Acid, Necrotic, and Poison damage until the end of its next turn."
    "name": "Bolster Allies"
  - "desc": "Ez chooses a damage type. *Wisdom Saving Throw:* DC 15, one target within\
      \ 30 feet that Ez can see. *Failure:* The target is cursed. Until the curse\
      \ ends, the target has [Vulnerability](3-Mechanics/CLI/rules/variant-rules/vulnerability-xphb.md)\
      \ to the chosen damage type. The curse ends early if Ez uses this action again.\n\
      \nIf the target drops to 0 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ before the curse ends, Ez can take a [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md)\
      \ on a later turn to curse a new creature."
    "name": "Curse of the All-Seeing Eye (1/Day)"
  - "desc": "Ez chooses up to six allies within 60 feet. Each target that can hear\
      \ her can take a [Reaction](3-Mechanics/CLI/rules/variant-rules/reaction-xphb.md)\
      \ to move up to its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
      \ without provoking [Opportunity Attacks](3-Mechanics/CLI/rules/actions.md#Opportunity%20Attack)."
    "name": "Inspiring Rally"
"reactions":
  - "desc": "Ez casts [Shield](3-Mechanics/CLI/spells/shield-xphb.md) in response\
      \ to that spell's trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Shield (3/Day)"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Ez%20d%27Avenir.webp"
```
^statblock