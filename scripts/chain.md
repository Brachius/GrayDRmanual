# Chain

Script name: `chain`

Runs steps one after another, separated by a pipe. A step whose first word is one of your scripts runs that script and waits for it to end; any other step is sent to the game and its roundtime waited out. A leading count like `3x` repeats the whole chain. Put `>` in front of a step to force it to the game when its first word is also a script name.

```
.chain sew hold sewing 4 "padded cloth hood" silk hood | sew seal hood
.chain 3x spin silk fine | weave-cloth
.chain >spin wheel | look
```

## How to start it

Type `.chain` followed by the words it takes.

Separate steps with |. Lead with a count like 3x to repeat the whole chain. Quotes work as usual.

Example:

```
.chain sew hold sewing 4 "padded cloth hood" silk hood | sew seal hood
```

In Master Train, pick **Chain** as the activity and put the same words in its Arguments box.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.
