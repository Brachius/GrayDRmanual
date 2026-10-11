# Make Steel

Script name: `makesteel`

Makes steel ingots. It draws the money from the bank, buys iron and coal nuggets at the blacksmithing stock room, loads an empty crucible (all the coal, then all the iron), runs Smelt until the metal is mixed, and puts the steel ingot away. With `refine` it then buys flux if needed and refines the ingot.

```
.makesteel 1
.makesteel 3 h refine
```

The number is how many ingots, 1 to 21. The letter is the carbon: `l` low (one coal per ingot), `m` medium (two), `h` high (three, the default). Each ingot costs 2000 copper.

## How to start it

Type `.makesteel` followed by the words it takes.

Number of ingots (1-21), then optionally l, m, or h for carbon content (default h), then optionally refine.

Example:

```
.makesteel 1 h refine
```

In Master Train, pick **Make Steel** as the activity and put the same words in its Arguments box.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.
