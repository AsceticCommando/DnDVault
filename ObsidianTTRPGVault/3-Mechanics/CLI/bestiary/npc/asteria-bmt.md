---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bmt
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/paladin
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Asteria"
---
# [Asteria](3-Mechanics/CLI/bestiary/npc/asteria-bmt.md)
*Source: The Book of Many Things p. 188*  

Though she now travels alone, Asteria still draws much of her power from her bond with Euryale. Asteria is foremost a protector and warrior, traveling the multiverse to uproot injustice, defend innocents, and inspire hope. She believes everyone deserves a chance to write their own story on their own terms, and her deeds have inspired countless heroic tales.

Even after so many years, Asteria maintains a joyous wanderlust and passion for discovery. She's as likely to be found climbing trees or poring over arcane texts as she is brandishing her sword in battle. Anyone who engages Asteria in conversation about her interests finds her an overflowing font of information. But she also retains her stubborn streak and quickly repudiates anyone who tries to order her around.

Asteria hasn't aged since Istus drew her future from the first Deck of Many Things. She doesn't know why this is but surmises her life is tied to that deck; so long as it continues to exist, so will she. She has no way to prove this hypothesis, but she nevertheless opposes groups like the Grim Harrow (see chapter 19) that seek to destroy the *Deck of Many Things*.

```statblock
"name": "Asteria (BMT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, paladin"
"alignment": "Chaotic Good"
"ac": !!int "18"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate-xphb.md), [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "195"
"hit_dice": "26d8 + 78"
"modifier": !!int "5"
"stats":
  - !!int "12"
  - !!int "21"
  - !!int "17"
  - !!int "15"
  - !!int "11"
  - !!int "20"
"speed": "30 ft., fly 30 ft. (winged boots)"
"saves":
  - "dexterity": !!int "11"
  - "constitution": !!int "9"
  - "wisdom": !!int "6"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+11"
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+14"
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+11"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+6"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 22"
"languages": "Common, Druidic"
"cr": "18"
"traits":
  - "desc": "Whenever a creature of Asteria's choice within 30 feet of her makes a\
      \ saving throw, Asteria can give the creature advantage on the saving throw\
      \ (no action required). This trait doesn't function if Asteria has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Guardian Aura"
  - "desc": "If Asteria fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Asteria wears [Winged Boots](3-Mechanics/CLI/items/winged-boots-xdmg.md),\
      \ which grant her a flying speed (included in her statistics). She also carries\
      \ one half of a pair of [Sending Stones](3-Mechanics/CLI/items/sending-stones-xdmg.md);\
      \ the other half of the pair is held by Euryale."
    "name": "Special Equipment"
"actions":
  - "desc": "Asteria makes two Radiant Blade attacks and uses Bursting Benediction."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d8 + 5) slashing damage plus 13 (3d8) radiant damage."
    "name": "Radiant Blade"
  - "desc": "Asteria causes a burst of magical energy to envelop one creature she\
      \ can see within 60 feet of herself. The target must make a DC 19 Dexterity\
      \ saving throw, taking 40 (9d8) force damage on a failed save, or half as much\
      \ damage on a successful one. Asteria or another creature that she can see within\
      \ 60 feet of herself then regains 10 hit points."
    "name": "Bursting Benediction"
  - "desc": "Asteria casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 19):\n\n**At\
      \ will:** [Guidance](3-Mechanics/CLI/spells/guidance-xphb.md), [Light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\n**2/day each:**\
      \ [Bless](3-Mechanics/CLI/spells/bless-xphb.md), [Freedom of Movement](3-Mechanics/CLI/spells/freedom-of-movement-xphb.md),\
      \ [Greater Restoration](3-Mechanics/CLI/spells/greater-restoration-xphb.md),\
      \ [Plane Shift](3-Mechanics/CLI/spells/plane-shift-xphb.md) (self only), [Protection\
      \ from Evil and Good](3-Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md),\
      \ [Revivify](3-Mechanics/CLI/spells/revivify-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Asteria summons a spectral version of her shield, which orbits and bolsters\
      \ one creature of Asteria's choice that she can see within 60 feet of herself.\
      \ The spectral shield lasts until the start of Asteria's next turn. While the\
      \ shield is orbiting the creature, the creature has half cover, is immune to\
      \ the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) condition,\
      \ and makes weapon attack rolls with advantage."
    "name": "Empowering Aegis (Recharge 4-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Asteria can expend a use to take one of the following actions. Asteria regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Asteria makes one Radiant Blade attack."
    "name": "Brazen Strike"
  - "desc": "Asteria moves up to her speed. This movement doesn't provoke opportunity\
      \ attacks."
    "name": "Nimble Sprint"
  - "desc": "Asteria uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
"source":
  - "BMT"
"image": "file://bestiary/tokens/BMT/Asteria.webp"
```
^statblock