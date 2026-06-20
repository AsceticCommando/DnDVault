---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Karas Chembryl"
---
# [Karas Chembryl](3-Mechanics/CLI/bestiary/npc/karas-chembryl-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 263*  

## Karas Chembryl

*Assassin Heir to a Sinister Legacy*

After the death of patriarch Fzoul Chembryl, House Chembryl and its descendants were scattered across Faerûn. Some members have dutifully continued the family's dedication to Bane, while others have sought to free themselves from that god's malignant shadow. However, none have embraced the Chembryls' tyrannical legacy more than Karas Chembryl, a ruthless assassin whose devotion to the gods Bane, Bhaal, and Myrkul has earned her the title Auspice of the Dead Three.

## Karas Chembryl's Lair

Karas operates from a hideout deep beneath the city of Baldur's Gate. The hideout contains shrines to the Dead Three and her research about lore or Artifacts related to those gods. Only Karas's most trusted confidantes know her hideout's location.

```statblock
"name": "Karas Chembryl (FRAiF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "104"
"hit_dice": "19d8 + 19"
"modifier": !!int "11"
"stats":
  - !!int "11"
  - !!int "20"
  - !!int "12"
  - !!int "18"
  - !!int "15"
  - !!int "17"
"speed": "30 ft., climb 30 ft."
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "4"
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+11"
"damage_resistances": "poison, psychic"
"gear":
  - "[studded leather armor](3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., passive\
  \ Perception 18"
"languages": "Common, Elvish, Infernal, Thieves' cant"
"cr": "8"
"traits":
  - "desc": "If Karas is subjected to an effect that allows her to make a Dexterity\
      \ saving throw to take only half damage, Karas instead takes no damage if she\
      \ succeeds on the save and only half damage if she fails. She can't use this\
      \ trait if she has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Evasion"
  - "desc": "If Karas fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day or 4/Day in Lair)"
"actions":
  - "desc": "Karas makes two attacks using Dread Dagger or Tyrant's Blade in any combination."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +8, reach 5 ft. or range 20/60 ft. *Hit:*\
      \ 10 (2d4 + 5) Piercing damage plus 4 (1d8) Necrotic damage. *Hit or Miss:*\
      \ The dagger magically returns to Karas's hand immediately after a ranged attack."
    "name": "Dread Dagger"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 8 (1d6 + 5) Slashing damage,\
      \ and the target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the start of Karas's next turn. If the target is already [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
      \ it instead takes 10 (3d6) Psychic damage."
    "name": "Tyrant's Blade"
  - "desc": "Karas casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15, +7 to\
      \ hit with spell attacks):\n\n**At will:** [Friends](3-Mechanics/CLI/spells/friends-xphb.md),\
      \ [Silence](3-Mechanics/CLI/spells/silence-xphb.md), [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
      \n**2/day:** [Ray of Sickness](3-Mechanics/CLI/spells/ray-of-sickness-xphb.md)\
      \ (level 5 version)\n\n**1/day:** [Blight](3-Mechanics/CLI/spells/blight-xphb.md),\
      \ [Mislead](3-Mechanics/CLI/spells/mislead-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Karas moves up to half her [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
      \ without provoking [Opportunity Attack](3-Mechanics/CLI/rules/actions.md#Opportunity%20Attack)\
      \ action and takes the [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Withdraw"
"regional_effects":
  - "desc": "Karas extends her connection to the Dead Three into the region she inhabits,\
      \ creating the following effects:\n\n- **Creeping Dread.** Terror runs rampant\
      \ in Karas's domain. Within 1 mile of the lair, creatures other than members\
      \ of the Zhentarim and cultists of Bane, Bhaal, or Myrkul have Disadvantage\
      \ on saving throws to avoid or end the Frightened condition.  \n- **Death's\
      \ Lore.** When a Humanoid dies within 1 mile of the lair, Karas learns one secret\
      \ that the Humanoid knew.  \n\nIf Karas dies or moves her lair elsewhere, these\
      \ effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, Karas can expend a use to take one of the following actions.\
  \ Karas regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "*Wisdom Saving Throw:* DC 15, one creature Karas can see within 90 feet\
      \ of herself. *Failure:* 10 (3d6) Psychic damage, and the target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition for 1 minute. While [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
      \ the target's [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md) is\
      \ 0 feet, and it repeats the save at the end of each of its turns, ending the\
      \ effect on a success. *Failure or Success:* Karas can't take this action again\
      \ until the start of her next turn."
    "name": "Harrow"
  - "desc": "Karas makes one Dread Dagger attack and uses Withdraw."
    "name": "Stealth Attack"
"source":
  - "FRAiF"
"image": "file://bestiary/tokens/FRAiF/Karas%20Chembryl.webp"
```
^statblock