# Combat Quick Reference

These references are intended to be a quick look to get broad strokes, detailed rules are linked

## General

In order to determine the outcome of any non-trivial action, make an [Action Roll](Action Roll.md)

1. Take 1d20 and add any bonus dice granted by your character's [attributes](Attributes.md)
2. Roll all dice. Any die that lands on its maximum value "explodes" and is
   rolled again, adding the new result to the total.
3. Sum the results of all dice to get the action roll total.

## Combat

1. Roll [Speed](Speed.md) to determine initiative order
2. Each character gets a turn, on a turn you can do all of the above [Turn Actions](Turn Actions.md):
    1. Move up to your [Movement Speed](Speed.md) using a move action
    2. Take a Major action (Attack, Use a [Bane](Banes.md), Use a [Boon](Boons.md), Assist an Ally, or take an additional Move)
    3. Take any number of unique Minor actions
3. In lieu of the 3 action types available normally, you can take a single focus action:
    1. Superior Action: Make an action roll with advantage 1
    2. Charge: Move up to twice your speed and make one melee attack with disadvantage 1
4. On someone else's turn, you can do an Interrupt action at the cost of your major action on your next turn
    1. Defend: Make an active attribute roll to replace a defense score after a successful attack
    2. Improvise: React to a situation in an open-ended manner, with GM approval
    3. _using an interrupt action prevents you from using a focus action as well_

## Resting

You can take an uninterrupted hour of rest to recover from non-lethal damage.  Invoke the [Heal](Heal.md) boon using your [Recovery](Recovery.md) attribute.

The result of the roll and your recovery score will grant you this much healing:

| Min. Roll | Min. Recovery | Healing |
|-----------|---------------|---------|
| 12        | 1             | 1d4     |
| 14        | 2             | 1d6     |
| 16        | 3             | 1d8     |
| 18        | 4             | 1d10    |
| 20        | 5             | 2d6     |
| 22        | 6             | 2d8     |
| 24        | 7             | 2d10    |
| 26        | 8             | 3d8     |
| 28        | 9             | 3d10    |

To heal lethal damage, you must have a good night's rest and then recovery [Recovery](Recovery.md) + 1 points upon completion


## Calculations

* [Hit Points](Hit Points.md): 2 * ([Power](Power.md) + [Spirit](Spirit.md) + [Recovery](Recovery.md)) + 10
* Guard [Defense](Defenses.md): 10 + [Speed](Speed.md) + [Power](Power.md) + Armor
* Toughness [Defense](Defenses.md): 10 + [Power](Power.md) + [Recovery](Recovery.md)
* Resolve [Defense](Defenses.md): 10 + [Spirit](Spirit.md) + [Recovery](Recovery.md)

## Reach

Small and Medium characters have a [Reach](Reach.md) of 1 tile, large have a reach of 2 tiles, and huge have a reach of 3 tiles.
Larger creatures are represented by multiple tokens and have multiple places they can be hit.
