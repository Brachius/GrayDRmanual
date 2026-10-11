# Enchanting

Script name: `enchant`

Makes one artificing piece: lays the sigils on the base item with the burin, uses the fount, and imbues with your wand or rod. The burin lives in your left hand and is stowed from there. A piece the game says is already enchanted is binned and the recipe starts over on a new base. A society brazier in the room is used when there is one.

```
.enchant 1 "radiant trinket" totem
.enchant 5 "gauge flow runestone" runestone
.enchant resume totem
```

Chapter, recipe in quotes, then the noun of the finished item, with the base item's noun after it when the two differ. `resume` scribes on after an imbue. You need the sigil scrolls the recipe asks for, the base item, a fount, and the burin, wand or rod on your belt or in the bag. Craft Training buys all of that for you; Work Orders artificing does too.

## How to start it

Type `.enchant` with the words shown above.

In Master Train, pick **Enchanting** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Crafting](/studio/crafting.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-enchanting-room"></span>**Enchanting room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |

