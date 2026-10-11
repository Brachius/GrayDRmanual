# Mix calculator

Script name: `mixcalc`

A calculator, nothing is sent to the game. It tells you how much pure metal and how much magic ingot (1% main metal, 99% mixing metal) to smelt together for a 67/33 ingot of the size you want. Pure and magic mix two to one, so the batch rounds up to a multiple of three.

```
.mixcalc 20        Pure: 14  Magic: 7   Total volume: 21
.mixcalc 4 1       Pure: 2   Magic: 1   Leftover 67/33: 1   Total: 4
```

The second number is 67/33 you already have; it counts straight toward the total.

## How to start it

Type `.mixcalc` followed by the words it takes.

First number is the volume you need. Second number, optional, is the volume of 67/33 you already have.

Example:

```
.mixcalc 20
```

In Master Train, pick **Mix calculator** as the activity and put the same words in its Arguments box.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.
