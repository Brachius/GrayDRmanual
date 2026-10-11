# Craft Training

Script name: `craft`

Rank-tier crafting training for one discipline: it picks the item that fits your ranks, buys the stock for it, walks to your training room (**Craft training rooms** on the Crafting page, or the safe room), makes the piece with the discipline's own script, and throws the result away. It stops when the skill is past **Skip crafting above this mindstate**.

```
.craft outfitting
.craft forging
.craft engineering
.craft alchemy
.craft enchanting
```

Outfitting knits up to 550 ranks and sews after; forging runs Smith with bronze; engineering shapes maple; alchemy forages and prepares the herbs then makes the remedy; enchanting buys the sigils, base and fount then enchants. **Craft overrides** on the Crafting page lets you name a different item per discipline. Add `debug` to see each step named.

## How to start it

Type `.craft` followed by the words it takes.

forging|outfitting|engineering|alchemy|enchanting [debug]

Example:

```
.craft outfitting
```

In Master Train, pick **Craft Training** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Crafting](/studio/crafting.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-training-rooms"></span>**Craft training rooms** | A list of room names. | (not set) | Global, or each character |
| <span id="setting-crafting-craft-max-mindstate"></span>**Maximum crafting mindstate** | A number, at least 0, at most 34. | 31 | Global, or each character |
| <span id="setting-crafting-craft-overrides"></span>**Rank-tier recipe overrides** |  |  | Global, or each character |

