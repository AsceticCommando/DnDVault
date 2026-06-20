---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/gith
- ttrpg-cli/monster/type/humanoid/warlock
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Githyanki Star Seer"
---
# [Githyanki Star Seer](3-Mechanics/CLI/bestiary/humanoid/githyanki-star-seer-bam.md)
*Source: Boo's Astral Menagerie p. 27*  

Githyanki star seers believe that the stars are the eyes of the multiverse. They use their magic to contact ancient stellar entities such as Acamar, Caiphon, and Hadar, hoping to learn their secrets, then record these secrets in journals. They scour Wildspace in search of new entities as well, hoping to be the first to contact them.

Some of the secrets learned are so cryptic that they require years of research to decipher, but time is of little concern to a star seer, who resides mainly on the Astral Plane.

```statblock
"name": "Githyanki Star Seer (BAM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith, warlock"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"modifier": !!int "0"
"stats":
  - !!int "11"
  - !!int "11"
  - !!int "14"
  - !!int "19"
  - !!int "16"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+10"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+10"
"damage_resistances": "radiant"
"senses": "passive Perception 13"
"languages": "Common, Gith"
"cr": "7"
"actions":
  - "desc": "The githyanki makes three Astral Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range 60 ft.,\
      \ one target. *Hit:* 20 (3d10 + 4) radiant damage."
    "name": "Astral Bolt"
  - "desc": "The githyanki casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\n\
      **At will:** [light](3-Mechanics/CLI/spells/light-xphb.md), [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\
      \ (the hand is invisible)\n\n**2/day each:** [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md) (self only), [mage\
      \ armor](3-Mechanics/CLI/spells/mage-armor-xphb.md) (self only), [tongues](3-Mechanics/CLI/spells/tongues-xphb.md)\n\
      \n**1/day each:** [contact other plane](3-Mechanics/CLI/spells/contact-other-plane-xphb.md)\
      \ (as an action), [plane shift](3-Mechanics/CLI/spells/plane-shift-xphb.md),\
      \ [telekinesis](3-Mechanics/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The githyanki teleports, along with any equipment it is wearing or carrying,\
      \ up to 30 feet to an unoccupied space it can see."
    "name": "Astral Step (Recharge 4-6)"
"source":
  - "BAM"
"image": "file://bestiary/tokens/BAM/Githyanki%20Star%20Seer.webp"
```
^statblock