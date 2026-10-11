# Shaping

Script name: `shape`

Engineering: shaping wood into lumber items and arrow shafts, the bow enhancements, and crafting from instructions. It buys the consumables for the chapter when they run low, trains crafting magic between steps when that is set, and finishes the piece the way you asked.

```
.shape log 7 "comb" maple comb
.shape hold 2 "arrow shafts" maple shafts skip
.shape hold instructions maple bow
.shape resume comb
.shape laminate bow           (also: lighten, cable)
```

The finish word comes first (`hold`, `log`, `stow`, `trash`), then the chapter, the recipe in quotes, the wood, and the noun. `skip` skips restocking. `resume` carries on with a piece already started.

## How to start it

Type `.shape` with the words shown above.

In Master Train, pick **Shaping (Shape)** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Crafting](/studio/crafting.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-engineering-room"></span>**Private engineering room (0 = public shaping rooms)** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |

