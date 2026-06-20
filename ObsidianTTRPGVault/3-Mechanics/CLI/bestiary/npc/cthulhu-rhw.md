---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cthulhu"
---
# [Cthulhu](3-Mechanics/CLI/bestiary/npc/cthulhu-rhw.md)
*Source: RHW p. 106*  

Cthulhu was—and inevitably will be once more—a threat to the entire multiverse. For untold ages, the Dark Powers have bound this harbinger of doom. Unlike the other prisoners of the Domains of Dread, Cthulhu isn't plagued by ironic torments or thwarted ambitions. Rather, this ageless terror remains physically bound and can exert only a fraction of its terrible might. Nevertheless, Cthulhu's dreams slip beyond its prison, manipulating minds and orchestrating events to ensure its release and a new epoch of multiversal doom.

```statblock
"name": "Cthulhu (RHW)"
"size": "Gargantuan"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"hp": !!int "385"
"hit_dice": "22d20 + 154"
"modifier": !!int "9"
"stats":
  - !!int "29"
  - !!int "12"
  - !!int "25"
  - !!int "28"
  - !!int "18"
  - !!int "24"
"speed": "30 ft., climb 30 ft., swim 60 ft."
"saves":
  - "constitution": !!int "15"
  - "wisdom": !!int "12"
  - "charisma": !!int "15"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+12"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+15"
"damage_resistances": "acid, cold, lightning, psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 22"
"languages": "all; telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "Cthulhu can breathe air and water."
    "name": "Amphibious"
  - "desc": "If Cthulhu dies, it revives with all its [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ in 1d10 weeks inside the Vault of Cthulhu."
    "name": "Darklord Restoration"
  - "desc": "Ground, air, and water in a 10-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from Cthulhu is [Difficult Terrain](3-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md).\
      \ A creature that starts its turn in the [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ takes 7 (2d6) Bludgeoning damage."
    "name": "Impossible Geometry"
  - "desc": "If Cthulhu fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Domain)"
  - "desc": "Cthulhu has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Cthulhu makes three Eldritch Claw attacks and uses Spellcasting to cast\
      \ [Befuddlement](3-Mechanics/CLI/spells/befuddlement-xphb.md) if available or\
      \ [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md) (level 4 version).\
      \ It can replace one Eldritch Claw attack with a use of Tentacle."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +17, reach 10 ft. *Hit:* 18 (2d8 + 9) Slashing damage\
      \ plus 9 (2d8) Acid damage. If the target is a Large or smaller creature, it\
      \ has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition\
      \ (escape DC 19) from one of two limbs."
    "name": "Eldritch Claw"
  - "desc": "*Constitution Saving Throw:* DC 25, one creature [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by Cthulhu. *Failure:* 21 (6d6) Acid damage plus 13 (3d8) Psychic damage.\
      \ *Success:* Half damage. *Failure or Success:* The target's [Hit Point](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ maximum decreases by an amount equal to the Psychic damage taken, and Cthulhu\
      \ regains [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ equal to that amount."
    "name": "Tentacle"
  - "desc": "Cthulhu casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 25):\n\n\
      **At will:** [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md) (level\
      \ 4 version)\n\n**3/day each:** [Dream](3-Mechanics/CLI/spells/dream-xphb.md),\
      \ [Geas](3-Mechanics/CLI/spells/geas-xphb.md) (can target creatures through\
      \ dreams)\n\n**1/day each:** [Befuddlement](3-Mechanics/CLI/spells/befuddlement-xphb.md),\
      \ [Plane Shift](3-Mechanics/CLI/spells/plane-shift-xphb.md) (self only)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Cthulhu teleports to an unoccupied space it can see within 120 feet,\
      \ taking creatures it is grappling with it. Then each creature within 10 feet\
      \ of the space it left is subjected to the following effect. *Strength Saving\
      \ Throw:* DC 25. *Failure:* 7 (2d6) Bludgeoning damage plus 7 (2d6) Thunder\
      \ damage, and if the target is a Large or smaller creature, it has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition. *Success:* Half damage only."
    "name": "Warp"
"regional_effects":
  - "desc": "Innsmouth is altered by Cthulhu's presence, creating the following effects:\n\
      \n- **Choking Depths.** A creature can [hold its breath](3-Mechanics/CLI/traps-hazards/suffocation-xphb.md)\
      \ for only 30 seconds while in the domain.  \n- **Closing the Borders.** While\
      \ in its domain, Cthulhu can close or open the borders of Innsmouth at will.\
      \ While the borders are closed, those who enter the Mists surrounding Innsmouth\
      \ become lost at sea amid inky fog for 3d4 days before arriving once more at\
      \ Innsmouth.  \n- **Something in the Air.** Creatures other than Cthulhu and\
      \ its allies have [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md)\
      \ on saving throws to avoid or end the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition.  \n\nIf Cthulhu dies, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Cthulhu can expend a use to take one of the following actions. Cthulhu regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Cthulhu makes an Eldritch Claw attack."
    "name": "Clamp"
  - "desc": "*Charisma Saving Throw:* DC 25, each creature and object that isn't being\
      \ worn or carried in a 10-foot-radius [Sphere](3-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md)\
      \ centered on a point Cthulhu can see within 60 feet. *Failure:* 36 (8d8) Force\
      \ damage, and the target is teleported to an unoccupied space within 60 feet\
      \ of Cthulhu that is horizontal to it. *Success:* Half damage only. *Failure\
      \ or Success:* Cthulhu can't take this action again until the start of its next\
      \ turn."
    "name": "Fold Space"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Cthulhu.webp"
```
^statblock