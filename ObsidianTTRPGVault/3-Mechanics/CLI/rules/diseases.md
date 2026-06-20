---
obsidianUIMode: preview
cssclasses:
- json5e-note
tags:
- ttrpg-cli/compendium/src/5e/cm
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/compendium/src/5e/oow
- ttrpg-cli/compendium/src/5e/phb
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/compendium/src/5e/vrgr
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/compendium/src/5e/xdmg
aliases:
- "Diseases"
---
# Diseases

## Arcane Blight
_Source: Icewind Dale: Rime of the Frostmaiden p. 233_

Any humanoid that spends 12 hours in the necropolis must succeed on a DC 15 Constitution saving throw or contract an arcane blight. This magical disease transforms the humanoid into a [nothic](3-Mechanics/CLI/bestiary/aberration/nothic-xmm.md), but only after the victim experiences hallucinations and feelings of isolation and paranoia. Other symptoms include clammy skin, hair loss, and myopia (nearsightedness).

A player character infected with the arcane blight gains the following flaw: "I don't trust anyone." This flaw, which supersedes any conflicting flaw, is fed by delusions that are difficult for the character to distinguish from reality. Common delusions include the belief that that allies are conspiring to steal the victim's riches or otherwise turn against the victim.

Whenever it finishes a long rest, an infected humanoid must repeat the saving throw. On a successful save, the DC for future saves against the arcane blight drops by `dice:1d6|noform|noparens|avg` (`1d6`). If the saving throw DC drops to 0, the creature overcomes the arcane blight and becomes immune to the effect of further exposure. A creature that fails three of these saving throws transforms into a [nothic](3-Mechanics/CLI/bestiary/aberration/nothic-xmm.md) under the DM's control. Only a [wish](3-Mechanics/CLI/spells/wish-xphb.md) spell or divine intervention can undo this transformation.

A [greater restoration](3-Mechanics/CLI/spells/greater-restoration-xphb.md) spell or similar magic ends the infection on the target, removing the flaw and all other symptoms, but this magic doesn't protect the target against further exposure.

## Blinding Sickness
_Source: Player's Handbook p. 227_

Pain grips the creature's mind, and its eyes turn milky white. The creature has disadvantage on Wisdom checks and Wisdom saving throws and is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded).

> [!note]
> This disease can be inflicted with the [contagion](3-Mechanics/CLI/spells/contagion-xphb.md) spell.

## Blue Mist Fever
_Source: Tomb of Annihilation p. 40_

A magical mist creeps through the jungles of Chult. Contact with this thin, blue, odorless mist can infect giants and humanoids with blue mist fever. A [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md) spell destroys the mist in a 20-foot square starting at a point chosen by the caster within the spell's range. An encounter with this mist typically covers `dice:1d6|noform|noparens|avg` (`1d6`) such areas (400-2,400 square feet).

A giant or humanoid that comes into contact with the mist must succeed on a DC 13 Constitution saving throw or become infected with blue mist fever. An infected creature begins seeing vivid hallucinations of blue monkeys `dice:1d6|noform|noparens|avg` (`1d6`) hours after failing the save, and the hallucinations last until the disease ends on the creature. A creature can repeat the saving throw every 24 hours, ending the effect on itself on a success.

## Bluerot
_Source: Ghosts of Saltmarsh p. 234_

This disease targets humanoids. While afflicted with bluerot, a victim grows grotesque blue boils on their face and back. This disease is carried by undead (including the drowned ones in Tammeraut's Fate), and victims most often acquire it through wounds caused by infected creatures. The disease's boils manifest in `dice:1d4|noform|noparens|avg` (`1d4`) hours, causing the victim's Constitution and Charisma scores to decrease by `dice:1d4|noform|noparens|avg` (`1d4`) each, to a minimum of 3. This is quickly followed by a fever and tingling in the extremities. An infected creature is vulnerable to radiant damage and gains the ability to breathe underwater.

At the end of each long rest, an infected creature makes a DC 12 Constitution saving throw. On a success, the victim regains 1 point of Constitution and 1 point of Charisma lost to the disease. If the infected creature regains all the points lost to the disease, it is cured. Other effects that raise the victim's ability scores do not cure the disease. On a failed saving throw, the victim takes `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) necrotic damage as the boils burst and spread. A creature reduced to 0 hit points by this damage cannot regain hit points until the disease is cured, though it can be stabilized as normal.

## Cackle Fever
_Source: Dungeon Master's Guide (2024) p. 61. Available in the <span title='Systems Reference Document (5.2)'>SRD</span>_

Cheaply made potions and elixirs are sometimes tainted by Cackle Fever, which affects Humanoids only (gnomes are strangely immune). A creature suffers the following effects `dice:1d4|noform|noparens|avg` (`1d4`) days after infection:

- **Fever.** The creature gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level, which lasts until the contagion ends on the creature.  
- **Uncontrollable Laughter.** While the creature has the [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) condition, the creature makes a DC 13 Constitution saving throw each time it takes damage other than Psychic damage. On a failed save, the creature takes `dice:1d10|noform|noparens|avg|text(5)` (`1d10`) Psychic damage and has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition as it laughs uncontrollably. At the end of each of its turns, the creature repeats the save, ending the effect on itself on a success. After 1 minute, it succeeds automatically.  

**Fighting the Contagion.** At the end of each Long Rest, an infected creature makes a DC 13 Constitution saving throw. After the creature succeeds on three of these saves, the contagion ends on it, and the creature is immune to Cackle Fever for 1 year.

**Spreading the Contagion.** Any Humanoid (other than a gnome) that starts its turn within a 10-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from a creature infected with Cackle Fever must succeed on a DC 10 Constitution saving throw or also become infected with the contagion. On a successful save, the Humanoid can't catch the contagion from that particular infected creature for the next 24 hours.

## Filth Fever
_Source: Player's Handbook p. 227_

A raging fever sweeps through the creature's body. The creature has disadvantage on Strength checks, Strength saving throws, and attack rolls that use Strength.

> [!note]
> This disease can be inflicted with the [contagion](3-Mechanics/CLI/spells/contagion-xphb.md) spell.

## Flesh Rot
_Source: Player's Handbook p. 227_

The creature's flesh decays. The creature has disadvantage on Charisma checks and vulnerability to all damage.

> [!note]
> This disease can be inflicted with the [contagion](3-Mechanics/CLI/spells/contagion-xphb.md) spell.

## Frigid Woe
_Source: Explorer's Guide to Wildemount p. 125_

Frigid woe is a special disease developed by Aeor's mages that cannot be cured by conventional treatment or magic. The only way a creature infected with the disease can be cured is by finding and drinking the manufactured antidote, a milky liquid stored in gold vials found in Eiselcross's ruins. This disease was created to slow down the forces of the gods and get around the healing power of their clerics and angels.

The disease is transmitted by breathing in blue spores that Aeor's mages created long ago. When a creature comes into contact with these spores, it must succeed on a DC 11 Constitution saving throw or become infected with frigid woe. It takes `dice:1d4|noform|noparens|avg` (`1d4`) days for the symptoms to manifest in an infected creature. These symptoms include fatigue, chills, and visible blue veins that appear on the creature's body. The infected creature's speed is reduced by 5 feet as long as it remains infected. Every 10 days after symptoms appear, an infected creature must succeed on a DC 11 Constitution saving throw, or its speed is reduced by another 5 feet. If a creature's speed is reduced to 0 as a result of this disease, the creature dies and its body turns into a statue made of ice.

A creature can drink the antidote as an action, ending all symptoms and effects of the disease instantly.

## Ghoul Gut
_Source: The Orrery of the Wanderer p. 111_

Water polluted with ghoul parts carries ghoul gut. A creature drinking this tainted water must succeed on a DC 12 Constitution saving throw or contract the disease. Symptoms strike when a victim starts a long rest or next becomes excited, as during combat. A victim suffers severe cramps, and their bowels make sounds like two ghouls fighting. When the symptoms first strike, the victim takes `dice:2d4|noform|noparens|avg|text(5)` (`2d4`) necrotic damage. In addition, a diseased victim regains no hit points or Hit Dice from nonmagical sources, including resting or spending Hit Dice. A victim who finishes a long rest can attempt a DC 12 Constitution saving throw. On a successful save, the victim shakes off the disease. Failure deals the character another `dice:2d4|noform|noparens|avg|text(5)` (`2d4`) necrotic damage.

A character who succeeds on a DC 15 Wisdom ([Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)) check can also remove the disease from another creature. Doing so requires the character making the check to care for the sick individual during a long rest. The caregiver gains no benefit from that rest.

## Grackle-Lung
_Source: Out of the Abyss p. 54_

The constant smog in Gracklstugh causes grackle-lung in living, breathing creatures, resulting in persistent, wracking coughs and the spewing of thick, black phlegm. Whenever a living, breathing creature finishes a long rest in Gracklstugh, it must make a DC 11 Constitution saving throw. On each failed save, the creature gains one level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) as its airways become increasingly clogged. A creature that reaches level 6 [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) dies, as normal.

A creature with one or more levels of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) brought on by grackle-lung must succeed on a Constitution check to take the [Dash](3-Mechanics/CLI/rules/actions.md#Dash) action. If the check fails, the action cannot be attempted. If the creature attempts to cast a spell with a verbal component, it must succeed on a Constitution check or be unable to complete the spell, causing the spell to fail with no effect. The DC for each check is 10 + the creature's current [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level.

If a creature's [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level drops below 1, it no longer suffers the effects of grackle-lung and becomes immune to it for the next week. Duergar and derro are inured to grackle-lung, making Constitution checks against it with advantage. Any spell or effect that cures disease also cures grackle-lung, effectively removing all levels of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) brought on by the affliction.

## Lichen Plague
_Source: Forgotten Realms: Adventures in Faerûn p. 98_

A Beast, Giant, Humanoid, or Monstrosity that comes into contact with bile lichen spores is at risk of contracting a horrible disease as the lichen takes root on its body and grows into its brain. A creature suffers the following effects `dice:1d4|noform|noparens|avg` (`1d4`) days after infection:

- **Skinroot.** The contagion first appears as a patch of green-yellow lichen no larger than 1 square inch on a random area of the body. When it finishes a Long Rest, the infected creature must succeed on a DC 14 Constitution saving throw or gain 1 Exhaustion level as the lichen spreads toward the creature's head. This Exhaustion level lasts until the contagion ends on the creature.  
- **Mindroot.** A Humanoid that dies while infected with Lichen Plague rises immediately as a [Zombie](3-Mechanics/CLI/bestiary/undead/zombie-xmm.md) under the DM's control.  

**Fighting the Contagion.** When it finishes a Long Rest, an infected creature makes a DC 14 Constitution saving throw. If the creature succeeds on three of these saving throws, the contagion ends on the creature and the creature is immune to Lichen Plague forever. The successful saves don't need to be consecutive.

**Spreading the Contagion.** Any Beast, Giant, Humanoid, or Monstrosity that makes skin contact with the lichen on an infected creature must succeed on a DC 14 Constitution saving throw or be infected with Lichen Plague. On a successful save, the creature can't catch Lichen Plague for the next 24 hours.

## Mindfire
_Source: Player's Handbook p. 227_

The creature's mind becomes feverish. The creature has disadvantage on Intelligence checks and Intelligence saving throws, and the creature behaves as if under the effects of the [confusion](3-Mechanics/CLI/spells/confusion-xphb.md) spell during combat.

> [!note]
> This disease can be inflicted with the [contagion](3-Mechanics/CLI/spells/contagion-xphb.md) spell.

## Mudpox
_Source: Forgotten Realms: Adventures in Faerûn p. 98_

Contact with dead oozes from the Underdark mixed with snowmelt and mud has been making people sick. Any Beast or Humanoid that touches mud contaminated by Mudpox must succeed on a DC 12 Constitution saving throw or become infected, suffering the following effect:

- **Disrupted Digestion.** Daily at dawn, the creature must succeed on a DC 12 Constitution saving throw or vomit up the food it ate the previous day, gaining 1 Exhaustion level. If the creature succeeds on this saving throw three consecutive times, the contagion ends.  

**Fighting the Contagion.** A [Heal](3-Mechanics/CLI/spells/heal-xphb.md) or [Lesser Restoration](3-Mechanics/CLI/spells/lesser-restoration-xphb.md) spell ends the contagion immediately.

**Spreading the Contagion.** Any Humanoid that makes skin contact with a creature infected with Mudpox must succeed on a DC 12 Constitution saving throw or also become infected with the contagion. If the creature succeeds on this save, it can't catch the contagion from that particular infected creature for the next 24 hours.

## Redface
_Source: Ghosts of Saltmarsh p. 168_

The effects of redface are identical to those of [sight rot](3-Mechanics/CLI/rules/diseases.md#Sight%20Rot) (see ""Diseases"" in chapter 8 of the "Dungeon Master's Guide"), but it's caused by pollutants in the air rather than contaminated drinking water, making it difficult to avoid.

## Saprophytic Plague
_Source: Candlekeep Mysteries p. 253_

Xanthoria's research into lichdom and her creation of a living phylactery led to the emergence of the plague spreading across the Sword Coast. Any beast or humanoid that comes within 10 feet of a creature infected by the saprophytic plague must succeed on a DC 20 Constitution saving throw or become infected as well. On a successful save, a creature is immune to the plague for 24 hours, and any creature that is immune to disease succeeds on the save automatically.

After a failed save, a creature experiences the first symptoms—body aches, nausea, slurred speech, and uncontrollable drooling—`dice:1d4|noform|noparens|avg` (`1d4`) hours later and gains 1 level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion). Every 24 hours thereafter, the creature automatically gains another level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion). Any creature killed by the saprophytic plague transforms into a lifeless magenta ooze.

A creature infected by the saprophytic plague for at least 24 hours behaves like a zombie and seems barely aware of its surroundings, as fungal growths sprout from its head, body, and limbs. It feels an overriding urge to be around groups of uninfected creatures so that it can spread the contagion. This is the time when infected humanoids begin speaking the word "Xanthoria" over and over, with no understanding of what the word means. This behavior is the result of a mycelial network of spores that forms a tenuous connection between Xanthoria and humanoids that become infected by the plague.

Foodstuffs that are exposed to the plague's spores decay or go sour within `dice:2d12|noform|noparens|avg` (`2d12`) hours, leaving behind a lurid magenta mass of oozing fungi. Eating infected food requires a saving throw as above.

Any magic that cures a disease can rid a creature of the saprophytic plague. Casting [purify food and drink](3-Mechanics/CLI/spells/purify-food-and-drink-xphb.md) destroys the infection in foodstuffs.

## Seizure
_Source: Player's Handbook p. 227_

The creature is overcome with shaking. The creature has disadvantage on Dexterity checks, Dexterity saving throws, and attack rolls that use Dexterity.

> [!note]
> This disease can be inflicted with the [contagion](3-Mechanics/CLI/spells/contagion-xphb.md) spell.

## Sewer Plague
_Source: Dungeon Master's Guide (2024) p. 61. Available in the <span title='Systems Reference Document (5.2)'>SRD</span>_

Fouled potions and alchemical waste can give rise to Sewer Plague, which incubates in sewers and refuse heaps and is sometimes transmitted by creatures that dwell in such areas, including otyughs and rats. Any Humanoid that is wounded by a creature that carries the contagion or that comes into contact with contaminated filth or offal must succeed on a DC 11 Constitution saving throw or become infected with Sewer Plague. A creature suffers the following effects `dice:1d4|noform|noparens|avg` (`1d4`) days after infection:

- **Fatigue.** The creature gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level.  
- **Weakness.** While the creature has any Exhaustion levels, it regains only half the normal number of Hit Points from spending Hit Point Dice.  
- **Restlessness.** While the creature has any Exhaustion levels, finishing a Long Rest neither restores lost Hit Points nor reduces the creature's Exhaustion level.  

**Fighting the Contagion.** Daily at dawn, an infected creature makes a DC 11 Constitution saving throw. On a failed save, the creature gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level as its fatigue worsens. On a successful save, the creature's Exhaustion level decreases by 1. If the creature's Exhaustion level is reduced to 0, the contagion ends on the creature.

## Shaking Plague
_Source: Forgotten Realms: Adventures in Faerûn p. 70_

Magical experiments gone awry gave rise to Shaking Plague, which affects Humanoids. A creature suffers the following effects `dice:1d4|noform|noparens|avg` (`1d4`) days after infection:

- **Fatigue.** The creature gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level. While the creature has any [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) levels, finishing a [Long Rest](3-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md) doesn't reduce the creature's [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level.  
- **Pus Boils.** While the creature has any [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) levels, its skin is covered in pus-filled boils.  
- **Shaking.** While the creature has any [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) levels, magic-dampening tremors afflict it. The creature has [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on Dexterity checks and saving throws, and whenever the creature casts a spell with a Somatic component, it must succeed on a DC 11 Constitution saving throw, or the spell dissipates with no effect and the action, [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), or [Reaction](3-Mechanics/CLI/rules/variant-rules/reaction-xphb.md) used to cast it is wasted. If that spell was cast with a spell slot, that slot isn't expended.  

**Fighting the Contagion.** Daily at dawn, an infected creature makes a DC 11 Constitution saving throw. On a failed save, the creature gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level as its fatigue worsens. On a successful save, the creature's [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level decreases by 1. If the creature's [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level is reduced to 0, the contagion ends on the creature.

**Spreading the Contagion.** Any Humanoid that makes skin contact with a creature infected with Shaking Plague must succeed on a DC 11 Constitution saving throw or also become infected with the contagion. On a successful save, the Humanoid can't catch the contagion from that particular infected creature for the next 24 hours.

## Shivering Sickness
_Source: Tomb of Annihilation p. 40_

Insects native to the jungles and marshes of Chult carry this disease, shivering sickness. The easiest protection against it is a coating of insect-repelling salve on all exposed skin (for the cost of insect repellent, see "Buying a Special Item".

A giant or humanoid that takes damage from [insect swarms](3-Mechanics/CLI/bestiary/beast/swarm-of-insects-xmm.md) or from [giant centipedes](3-Mechanics/CLI/bestiary/beast/giant-centipede-xmm.md), [giant scorpions](3-Mechanics/CLI/bestiary/beast/giant-scorpion-xmm.md), or [giant wasps](3-Mechanics/CLI/bestiary/beast/giant-wasp-xmm.md) is exposed to the disease at the end of the encounter. Those who haven't applied insect repellent since their previous long rest are exposed to the disease when they finish a long rest.

A giant or humanoid exposed to the disease must succeed on a DC 11 Constitution saving throw or become infected. A creature with natural armor has advantage on the saving throw. It takes `dice:2d6|noform|noparens|avg` (`2d6`) hours for symptoms to manifest in an infected creature. Symptoms include blurred vision, disorientation, and a sudden drop in body temperature that causes uncontrollable shivering and chattering of the teeth.

Once symptoms begin, the infected creature regains only half the normal number of hit points from spending Hit Dice and no hit points from a long rest. The infected creature also has disadvantage on ability checks and attack rolls. At the end of a long rest, an infected creature repeats the saving throw, shaking off the disease on a successful save.

## Sight Rot
_Source: Dungeon Master's Guide (2024) p. 61. Available in the <span title='Systems Reference Document (5.2)'>SRD</span>_

Any Beast or Humanoid that drinks water tainted by Sight Rot must succeed on a DC 15 Constitution saving throw or have the [Blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) condition until the contagion ends.

**Fighting the Contagion.** Magic such as a [Heal](3-Mechanics/CLI/spells/heal-xphb.md) or [Lesser Restoration](3-Mechanics/CLI/spells/lesser-restoration-xphb.md) spell ends the contagion immediately. A character who is proficient with an [Herbalism Kit](3-Mechanics/CLI/items/herbalism-kit-xphb.md) can use it to create one dose of nonmagical ointment, which takes 1 hour. When applied to the eyes of a creature suffering from Sight Rot, the ointment suppresses the contagion on that creature for 24 hours. If the contagion is suppressed in this way for a total of 72 hours (requiring three doses and applications of the ointment), the contagion ends on the creature.

**Spreading the Contagion.** Any Humanoid that makes skin contact with a creature infected with Sight Rot must succeed on a DC 15 Constitution saving throw or also become infected with the contagion. On a successful save, the Humanoid can't catch the contagion from that particular infected creature for the next 24 hours.

## Slimy Doom
_Source: Player's Handbook p. 227_

The creature begins to bleed uncontrollably. The creature has disadvantage on Constitution checks and Constitution saving throws. In addition, whenever the creature takes damage, it is [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.

> [!note]
> This disease can be inflicted with the [contagion](3-Mechanics/CLI/spells/contagion-xphb.md) spell.

## Spider Eggs
_Source: Waterdeep: Dungeon of the Mad Mage p. 47_

If the party is defeated, stabilized characters awaken after `dice:1d4|noform|noparens|avg` (`1d4`) hours to find themselves cocooned in sticky webs and suspended 10 feet off the floor, with spider eggs implanted in their bodies. A cocooned character is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) and can use its action to try to escape by making a successful DC 15 Strength check.

Spider eggs implanted in a host hatch in `dice:2d12|noform|noparens|avg` (`2d12`) hours, killing the host as the baby spiders chew their way out. This infestation functions like a disease. A [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration-xphb.md) spell or similar magic cast upon the host kills the spider eggs, ending the threat.

## Super-Tetanus
_Source: Tales from the Yawning Portal p. 104_

A creature that contracts the disease of super-tetanus is wracked with pain as its heart races and its muscles spasm hard enough to break its bones. The creature takes `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) damage at the start of each of its turns. If a victim is not cured by other means, it can repeat the saving throw at the end of every minute after becoming exposed, ending the effect on itself with a successful save.

## The Gnawing Plague
_Source: Van Richten's Guide to Ravenloft p. 153_

The Gnawing Plague, also known as "the Gnaws," is known in every corner of Richemulot.

**Transmission.** The Gnaws is spread when a creature is bitten by a [rat](3-Mechanics/CLI/bestiary/beast/rat-xmm.md), [giant rat](3-Mechanics/CLI/bestiary/beast/giant-rat-xmm.md), [swarm of rats](3-Mechanics/CLI/bestiary/beast/swarm-of-rats-xmm.md), or [wererat](3-Mechanics/CLI/bestiary/monstrosity/wererat-xmm.md) that carries the disease, or by coming into physical contact with an infected creature.

**Infection.** Creatures exposed to the disease must succeed on a DC 10 Constitution saving throw or become infected. The DC of this saving throw can increase depending on the severity of the plague's spread (see ""Cycle of the Plague"" below).

**Symptoms.** It takes `dice:1d2|noform|noparens|avg` (`1d2`) days for the Gnawing Plague's symptoms to manifest in an infected creature. The infected creature then gains 1 level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion), regains only half the normal number of hit points from spending Hit Dice, and regains no hit points from finishing a long rest.

The plague's symptoms include buboes, fatigue, splotchy rashes, sweats, and shaking, particularly facial tremors. Locals liken these twitches to the sniffing of rats. Sufferers often have scraps of leather placed in their mouths to prevent their teeth from clattering, though they inevitably gnaw through these scraps.

**Recovery.** At the end of each long rest, an infected creature must make a DC 10 Constitution saving throw. On a failed save, the creature gains 1 level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion). On a successful save, the creature's [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level decreases by 1. If a successful saving throw reduces the infected creature's level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) below 1, the creature recovers from the disease.

**Immunity.** All forms of rats and wererats are immune to the Gnawing Plague.

## The Rusting
_Source: Forgotten Realms: Adventures in Faerûn p. 165_

The Rusting manifests as a thin, iron coating that grows over a victim's body. When exposed to moisture, this iron skin corrodes into a rust-colored plaque. As the Rusting covers the victim, the victim eventually transforms into a type of creature known as a Rusted (see "chapter 9").

Any creature that is wounded by a Rusted creature or spends 1 hour in an area where the Rusting has manifested makes a DC 10 Constitution saving throw. Constructs and Undead automatically succeed on this save. On a failed save, the creature is afflicted by the Rusting and suffers the following effects:

- **Curse.** The creature gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level and is cursed. While the creature is cursed, finishing a [Long Rest](3-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md) doesn't reduce the creature's [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level.  
- **Plated Joints.** The creature's [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md) is reduced by 5 feet.  
- **Rusted Fate.** When a cursed creature's [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level reaches 6, it doesn't die. Instead, the creature transforms into a Rusted version of its former self; its creature type becomes Construct, and it gains [Immunity](3-Mechanics/CLI/rules/variant-rules/immunity-xphb.md) to Poison damage and the [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion), [Petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), and [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) conditions. The curse then ends for that creature.  

**Fighting the Contagion.** Daily at dawn, an afflicted creature makes a DC 10 Constitution saving throw. On a failed save, the creature gains 1 [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level as more iron coats its skin. On a successful save, the creature's [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level decreases by 1. If the creature's [Exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) level is reduced to 0, the contagion ends on the creature.

Removing the curse immediately ends the contagion for a creature.

## Throat Leeches
_Source: Tomb of Annihilation p. 40_

Minuscule parasites known as throat leeches infect the water in Chult's forests, swamps, and rivers. Any giant or humanoid that swallows tainted water must succeed on a DC 12 Constitution saving throw or be infested with throat leeches. Immediate symptoms include throat inflammation and shortness of breath. After `dice:1d6|noform|noparens|avg` (`1d6`) hours, the infected character gains 1 level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) that can't be removed (except as described below) until the disease is cured. At the end of each long rest, the infected creature must repeat the saving throw. On a failed save, the creature's [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) increases by 1 level; on a successful save, the creature's [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) decreases by 1 level. If a successful saving throw reduces the infected creature's level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion) below 1, the creature recovers from the disease.

Explorers can avoid contracting throat leeches by drinking only rainwater or water that's been boiled or magically purified.