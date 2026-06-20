---
obsidianUIMode: preview
cssclasses:
- json5e-feat
tags:
- ttrpg-cli/compendium/src/5e/rhw
- ttrpg-cli/feat
aliases:
- "Living Shadow"
---
# Living Shadow
*Source: RHW*  

**Prerequisite**: Ravenloft Campaign

The shadow you cast is animate and ever-present—sometimes it even acts according to its own will. You gain the following features.

**Grasping Shadow.** You learn the [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md) spell and can cast it without spell components. Intelligence, Wisdom, or Charisma is your spellcasting ability for this spell (choose when you select this feat).

**Lengthened Strike.** When you make a melee attack roll as part of the [Attack](3-Mechanics/CLI/rules/actions.md#Attack) or [Magic](3-Mechanics/CLI/rules/actions.md#Magic) action on your turn, you can increase your reach for that attack by 10 feet, as your shadow stretches to aid you. You can use this feature a number of times equal to your [Proficiency Bonus](3-Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), and you regain all expended uses when you finish a [Long Rest](3-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

**Ominous Will.** Immediately after you make a [D20 Test](3-Mechanics/CLI/rules/variant-rules/d20-test-xphb.md) and roll a 1 on the `dice:d20|noform|noparens|avg` (`d20`), your shadow attempts to exert its will. Make a Wisdom saving throw (DC 13 plus your [Proficiency Bonus](3-Mechanics/CLI/rules/variant-rules/proficiency-xphb.md)). On a failed save, you have the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition until the start of your next turn, at which point you must roll on the Shadow's Will table to determine what you do during that turn.

**Shadow's Will**

`dice: [](living-shadow-rhw.md#^shadows-will)`

| dice: 1d8 | Behavior |
|-----------|----------|
| 1 | You don't take an action or a [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), and you use all your movement to move. Roll `dice:1d4\|noform\|noparens\|avg` (`1d4`) for the direction: 1, north; 2, east; 3, south; or 4, west. |
| 2-6 | You don't move or take a [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), and you take the [Attack](3-Mechanics/CLI/rules/actions.md#Attack) action to make one melee attack against a random creature within reach. If none are within reach, you take no action. |
| 7-8 | You have the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition, and your turn ends. |
^shadows-will