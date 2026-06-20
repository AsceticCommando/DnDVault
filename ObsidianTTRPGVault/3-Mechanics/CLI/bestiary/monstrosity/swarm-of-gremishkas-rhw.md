---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Gremishkas"
---
# [Swarm of Gremishkas](3-Mechanics/CLI/bestiary/monstrosity/swarm-of-gremishkas-rhw.md)
*Source: RHW p. 249*  

*Magic-Reactive Mage Killer*

Gremishkas are magically unstable creations of misguided magic-users. These wildly destructive menaces delight in tormenting spellcasters and seek to destroy anything associated with them, particularly spellbooks, spell components, and familiars. If exposed to magic, a lone gremishka explodes into a destructive swarm of duplicate gremishkas.

```statblock
"name": "Swarm of Gremishkas (RHW)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "31"
"hit_dice": "7d4 + 14"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "15"
  - !!int "11"
  - !!int "14"
  - !!int "4"
"speed": "30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 30 ft., passive\
  \ Perception 12"
"languages": "understands Common but can't speak"
"cr": "2"
"traits":
  - "desc": "The gremishka has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny creature. The swarm\
      \ can't regain [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ or gain [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)."
    "name": "Swarm (Swarm Form Only)"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 12 (3d6 + 2) Piercing damage,\
      \ or 9 (3d4 + 2) Piercing damage if the swarm is [Bloodied](3-Mechanics/CLI/rules/conditions.md#Bloodied),\
      \ plus 7 (2d6) Force damage. If the target is attuned to any magic items, its\
      \ [Attunement](3-Mechanics/CLI/rules/variant-rules/attunement-xphb.md) to one\
      \ item (DM's choice) ends."
    "name": "Swarming Bites (Swarm Form Only)"
"source":
  - "RHW"
"image": "file://bestiary/tokens/RHW/Swarm%20of%20Gremishkas.webp"
```
^statblock

## Environment

urban