---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Valindra Shadowmantle"
---
# [Valindra Shadowmantle](3-Mechanics/CLI/bestiary/npc/valindra-shadowmantle-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 283*  

## Valindra Shadowmantle

*Cold and Calculating Lich Wizard*

Valindra Shadowmantle was a selfish and ambitious high elf wizard who eschewed her community in search of arcane power in the wider world. Valindra has no compunctions about forming allies of convenience, and she's worked with Szass Tam and his Red Wizards of Thay, the Arcane Brotherhood of Luskan, devil cultists, and more.

Although Valindra has the sunken pallor common to liches, she prefers to maintain a magical disguise that allows her to appear as the high elf she was in life. Ever the schemer, Valindra doesn't use this disguise out of nostalgia or regret, but to hide the powers she has since gained as an Undead creature.

## Valindra Shadowmantle's Lair

Valindra lairs within a sprawling, ruined library in the Shadowfell. After several disastrous confrontations with enemies of her temporary allies, she's elected to keep her personal lair secret. Deep within her lair is a hidden reading room where she usually keeps her spirit gem.

The region containing Valindra's lair is warped by her presence, creating the following effects:

- **All-Seeing.** While in her lair, Valindra can cast Clairvoyance, requiring no spell components and using the same spellcasting ability as her Spellcasting action.  
- **Apathy.** Creatures within 1 mile of the lair that aren't Undead have Disadvantage on [Death Saving Throws](3-Mechanics/CLI/rules/variant-rules/death-saving-throw-xphb.md) and Initiative rolls.  
- **Thirst for Knowledge.** Within 1 mile of the lair, creatures have Advantage on Intelligence checks made when they take the Study action.  

If Valindra dies or moves her lair elsewhere, these effects end immediately. These effects resume if Valindra gains a new body (see her Spirit Gem trait).

```statblock
"name": "Valindra Shadowmantle (FRAiF)"
"size": "Medium"
"type": "undead"
"subtype": "wizard"
"alignment": "Neutral Evil"
"ac": !!int "20"
"hp": !!int "315"
"hit_dice": "42d8 + 126"
"modifier": !!int "17"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "21"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "10"
  - "constitution": !!int "10"
  - "intelligence": !!int "12"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+19"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+12"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold, lightning"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[component pouch](3-Mechanics/CLI/items/component-pouch-xphb.md)"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 19"
"languages": "all"
"cr": "21"
"traits":
  - "desc": "If Valindra fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (4/Day or 5/Day in Lair)"
  - "desc": "If destroyed, Valindra re-forms in 1d10 days if her spirit gem is intact,\
      \ reviving with all her [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).\
      \ The new body appears in an unoccupied space within her lair."
    "name": "Spirit Gem"
"actions":
  - "desc": "Valindra makes three attacks, using Eldritch Burst or Paralyzing Touch\
      \ in any combination. She can replace two attacks with a use of Spellcasting\
      \ to cast [Lightning Bolt](3-Mechanics/CLI/spells/lightning-bolt-xphb.md) (level\
      \ 5 version)."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +12, reach 5 ft. or range 120 ft. *Hit:*\
      \ 31 (4d12 + 5) Force damage."
    "name": "Eldritch Burst"
  - "desc": "*Melee Attack Roll:* +12, reach 5 ft. *Hit:* 14 (2d8 + 5) Cold damage,\
      \ and the target has the [Paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ condition until the start of Valindra's next turn."
    "name": "Paralyzing Touch"
  - "desc": "*Dexterity Saving Throw:* DC 20, each creature in a 30-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from Valindra. *1St Failure:* 39 (6d12) Force damage and the target\
      \ has the [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) condition\
      \ and repeats the save at the end of each of its turns, ending the effect on\
      \ itself on a success. After 1 minute, it succeeds automatically. Subsequent\
      \ Failures: 39 (6d12) Necrotic damage, and Valindra gains 20 [Temporary Hit\
      \ Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)."
    "name": "Deathly Grasp (Recharge 5-6)"
  - "desc": "Valindra casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (spell save DC 20):\n\n**At will:** [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [Detect Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Dispel\
      \ Magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [Fly](3-Mechanics/CLI/spells/fly-xphb.md),\
      \ [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md), [Lightning Bolt](3-Mechanics/CLI/spells/lightning-bolt-xphb.md)\
      \ (level 5 version), [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n**2/day\
      \ each:** [Animate Dead](3-Mechanics/CLI/spells/animate-dead-xphb.md), [Plane\
      \ Shift](3-Mechanics/CLI/spells/plane-shift-xphb.md)\n\n**1/day each:** [Cone\
      \ of Cold](3-Mechanics/CLI/spells/cone-of-cold-xphb.md) (level 8 version), [Finger\
      \ of Death](3-Mechanics/CLI/spells/finger-of-death-xphb.md), [Power Word Kill](3-Mechanics/CLI/spells/power-word-kill-xphb.md),\
      \ [Scrying](3-Mechanics/CLI/spells/scrying-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Valindra casts [Disguise Self](3-Mechanics/CLI/spells/disguise-self-xphb.md),\
      \ using the same spellcasting ability as Spellcasting. The spell lasts until\
      \ Valindra drops to 30 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ or fewer or uses her Life-Rending Gaze Legendary Action. Intelligence ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation))\
      \ checks made to discern her true appearance are made with [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md).\n"
    "name": "Illusory Disguise"
"reactions":
  - "desc": "Valindra casts [Counterspell](3-Mechanics/CLI/spells/counterspell-xphb.md)\
      \ or [Shield](3-Mechanics/CLI/spells/shield-xphb.md) in response to the spell's\
      \ trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic"
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, Valindra can expend a use to take one of the following\
  \ actions. Valindra regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "*Constitution Saving Throw:* DC 20, each creature that isn't Undead in\
      \ a 20-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from Valindra. *Failure:* 21 (6d6) Necrotic damage. *Success:*\
      \ Half damage. *Failure or Success:* Valindra can't take this action again until\
      \ the start of her next turn."
    "name": "Disrupt Life"
  - "desc": "Valindra makes one Eldritch Burst attack. Before or after the attack,\
      \ Valindra can teleport up to 20 feet to an unoccupied space she can see."
    "name": "Eldritch Jaunt"
  - "desc": "*Wisdom Saving Throw:* DC 20, one creature Valindra can see within 30\
      \ feet. *Failure:* 22 (4d10) Necrotic damage, and the target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the end of its next turn. *Success:* Half damage only."
    "name": "Life-Rending Gaze"
"source":
  - "FRAiF"
"image": "file://bestiary/tokens/FRAiF/Valindra%20Shadowmantle.webp"
```
^statblock