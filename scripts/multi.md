# Multi

Script name: `multi`

Repeats a list of game commands and scripts in order. Separate the entries with commas, or with semicolons when no entry has a comma in it. A script entry starts with a colon or semicolon and is waited for; anything else is sent to the game. Put the repeat count first or last.

```
.multi 2,cough,:wait 1,sneeze
.multi 5,:spin silk,:weave-cloth
```

Chain does the same job with a plainer shape; use whichever reads better to you.

## How to start it

Type `.multi` followed by the words it takes.

Put the repeat count first or last. Prefix child scripts with a colon or semicolon; separate entries with commas, or use semicolons when no commas are present.

Example:

```
.multi 2,cough,:wait 1,sneeze
```

In Master Train, pick **Multi** as the activity and put the same words in its Arguments box.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.
